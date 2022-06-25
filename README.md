# CPU Scheduling of Process in C++-


**Introduction:**
CPU Scheduling is a process of determining which process will own CPU for execution while another process is on hold. The main task of CPU scheduling is to make sure that whenever the CPU remains idle, the OS at least select one of the processes available in the ready queue for execution. The selection process will be carried out by the CPU scheduler. It selects one of the processes in memory that are ready for execution. 

**Methodology:**
There are mainly six types of process scheduling algorithms which we covered in our OS Project.
1.	First Come First Serve (FCFS):
In this type of algorithm, the process which requests the CPU gets the CPU allocation first. This scheduling method can be managed with a FIFO queue.
2.	Shortest-Job-First (SJF) Scheduling:
The process with the shortest execution time should be selected for execution next. This scheduling method can be pre-emptive or non-pre-emptive. It significantly reduces the average waiting time for other processes awaiting execution.
3.	Shortest Remaining Time
The process will be allocated to the task, which is closest to its completion. This method prevents a newer ready state process from holding the completion of an older process.
4.	Priority Scheduling
The processes with higher priority should be carried out first, whereas jobs with equal priorities are carried out on a round-robin or FCFS basis. Priority can be decided based on memory requirements, time requirements, etc.
5.	Round Robin Scheduling
The name of this algorithm comes from the round-robin principle, where each person gets an equal share of something in turn. It is mostly used for scheduling algorithms in multitasking. This algorithm method helps for starvation free execution of processes.
