**CPU Scheduling Simulator Project**

**Project Description:**
Our CPU Scheduling Simulator aims to model and analyze various CPU scheduling and page replacement algorithms. The simulator allows users to interactively explore and compare algorithms such as First-Come-First-Served (FCFS), Shortest Job First (SJF), Priority Scheduling, Round Robin (RR), and Multilevel Feedback Queue (MFQ) for CPU scheduling. For page replacement, it supports First-Come-First-Served (FCFS), Shortest Job First (SJF), Least Recently Used (LRU), Optimal, and Second Chance algorithms.

**Objective:**
To create a user-friendly tool that simulates CPU scheduling and page replacement processes, visualizes these processes, and calculates key performance metrics like average turnaround time, waiting time, and CPU utilization.
![image](https://github.com/user-attachments/assets/7260c37c-b346-4d92-8023-1f02e6dbfed0)


**Project Modules:**
1. **CPU Scheduling Algorithms:**
   ![image](https://github.com/user-attachments/assets/e1373578-8edd-4977-9e71-9e884c748c16)
![image](https://github.com/user-attachments/assets/27b2d0d6-5b59-4b83-bf3e-2204504a6ea2)

   - FCFS: Executes processes in the order of arrival.
   - SJF: Chooses the process with the shortest burst time.
   - Priority Scheduling: Allocates CPU based on process priority.
   - RR: Distributes CPU time in fixed intervals.
   - MFQ: Uses multiple queues with dynamic priority adjustments.

3. **Page Replacement Algorithms:**
   ![image](https://github.com/user-attachments/assets/383be0da-9d3e-41b8-a82f-de92cd85d46d)
   ![image](https://github.com/user-attachments/assets/777564e4-b82b-480a-ade7-ae735bdcb09d)


   - FCFS: Replaces the oldest page in memory.
   - SJF: Replaces the page with the shortest future use time.
   - LRU: Replaces the least recently used page.
   - Optimal: Replaces the page that will not be used for the longest period.
   - Second Chance: Gives pages a second chance before replacement.

**Implementation:**
Developed in [Programming Language], the simulator features process creation, simulation runs, performance metrics calculation, and visualization of scheduling processes.

**Functionalities:**
- **Process Creation:** Input process attributes such as ID, arrival time, burst time, and priority.
- **Simulation Run:** Execute simulations based on selected algorithms.
- **Performance Metrics:** Calculate and display metrics like average turnaround time, waiting time, and CPU utilization.
- **Visualization:** Graphical representation of scheduling and page replacement processes.

**Reporting:**
Includes algorithm implementations, comparisons, performance metrics analysis, and program code explanations.
