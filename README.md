# OS-ASSIGNMENT
Question Assigned:

  CPU schedules N processes which arrives at different time intervals and each processes is allocated the CPU for a specific user input time unit, processers are scheduled using a preemptive round robin scheduling algorithm. Each process must be assigned a numerical priority, with a higher number indicating a higher relative priority. In addition to the processes one task has priority 0. The length of a time quantum is T units, where T is the custom time considered as time quantum for processing. If a process is preempted by a higher-priority process, the preempted process is placed at the end of the queue. Design a scheduler so that the task with priority 0 doesn’t starve for resources and gets the CPU at some time unit to execute. Also compute waiting time and turn around time. 

