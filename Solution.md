Solution:-
e know how to find an effective access time (EAT) for a given page-fault rate (p). 
Here, we have to find 'p' for given 'EAT' so we set up the following equation and solve for 'p':
(Note: 1 millisecond = 1,000,000 nanoseconds = 1e6 nanoseconds)
Time taken to service page Fault for empty page or unmodified page = 8ms.
Time taken to service page Fault for modified page = 20ms
Memory access time = 100ns
Effective Access time = 200ns
      EAT = (1-p)*(100) + (p)*(100 + (1-.7)*(8msec) + (.7)*(20msec))   
	  = 100 - 100p + 100p + (2.4e6)*p + (14e6)*p
	  = 100 + (16.4e6)*p
      200 = 100 + (16.4e6)*p
      p = 100/16.4e6 = 6.0975609756097560975609756097561e-6 ~ 6.01e-6
      p-->page Fault Rate
