This is a program for implementing CPU Scheduling Simulator in C/C++. This program will simulate following scehduling algorithms and will print all the statistics in the txt file processes_stat.txt.

	1. FCFS		(First Come Fisrt Server)
	2. SRTF		(Shortest Remaining Time First)
	3. SJF		(Shortest Job Fisrt) 
	4. RR 		(Round Robin)

This code uses makes use of following system calls and concepts
	1. fork()
	2. exec()
	3. dup()/dup2()
	4. Named/Unnamed pipes
	5. Threading concepts
	
The program will read the data from the txt file which should be written in the following way
	Algorithem Name
	Proc1			(Name of Proc so that we can identify different Processes)
	Quantum 		(In case of RR algo) 
	Arrival time
	Burst Time 

All the statistics like turn around time, waiting time etc. will be written in processes_stat.txt file attched. 


									Running the code
To run the code type following commands at the terminal of any Linux OS.
	1. g++ new.cpp -o new
	2. g++ -pthread ready.cpp -o ready
	3. g++ -pthread blocked.cpp -o blocked
	4. g++ -pthread running.cpp -o running
	5. g++ -pthread exit.cpp -o exit
	6. g++ main.cpp
	7. ./a.out
On succesfull compilation of all the cpp files you will be able to see the program running 
				
		
