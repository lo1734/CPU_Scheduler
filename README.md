# PROCESS-Scheduler
## Scheduling Algorithms
In computing, scheduling is the method by which work is assigned to resources that complete the work. The work may be virtual computation elements such as threads, processes or data flows, which are in turn scheduled onto hardware resources such as processors, network links or expansion cards. A scheduler is what carries out the scheduling activity. Schedulers are often implemented so they keep all computer resources busy (as in load balancing), allow multiple users to share system resources effectively, or to achieve a target quality of service. Scheduling is fundamental to computation itself, and an intrinsic part of the execution model of a computer system; the concept of scheduling makes it possible to have computer multitasking with a single central processing unit (CPU). Given below are the description about 8 implemented algorithms

## First Come First Serve (FCFS)
First Come First Serve is an operating system scheduling algorithm that automatically executes queued requests and processes in order of their arrival. It is the easiest and simplest CPU scheduling algorithm. In this type of algorithm, processes which requests the CPU first get the CPU allocation first. This is managed with a FIFO queue.

## Shortest Job First (SJF)
Shortest Job First is a scheduling policy that selects the waiting process with the smallest execution time to execute next. It is a non-preemptive and Greedy algorithm. Shortest Job first has the advantage of having a minimum average waiting time among all scheduling algorithms. It may cause starvation if shorter processes keep coming.

## Shortest Remaining Time First (SRTF)
This Algorithm is the preemptive version of SJF scheduling. In SRTF, the execution of the process can be stopped after certain amount of time. At the arrival of every process, the short term scheduler schedules the process with the least remaining burst time among the list of available processes and the running process.

## Priority Scheduling
Priority Scheduling is a method of scheduling processes that is based on priority. Hence, the scheduler selects the tasks to work as per the priority. The processes with higher priority should be carried out first, whereas jobs with equal priorities are carried out on a round-robin or FCFS basis. Priority depends upon memory requirements, time requirements, etc.

## Round Robin Scheduling
Round Robin is the preemptive process scheduling algorithm. Each process is provided a fix time to execute, it is called a quantum. Once a process is executed for a given time period, it is preempted and other process executes for a given time period. Context switching is used to save states of preempted processes.

## Team Members


G Akshay Reddy : 2021BCS0010
N Lohitaksha : 2021BCS0110
