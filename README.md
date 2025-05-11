# CSCI-340-Project-3-CPU-Scheduling-Algorithms

Third project that involves utilizing different process scheduling algorithms to optimize performance and ensure fair CPU time among concurrent processes (no starvation). The executable was implemented using Python. 

## Features
Notable process scheduling algorithms that was used.
1. First Come First Serve (FCFS **Non-preemptive**)
2. Shortest Remaining Time First (SRTF **Preemptive**)
3. Priority Scheduling (Pri **Preemptive**)
4. Round Robin (RR **Non-preemptive**)

## Instructions
1. Clone the repo
```bash
git clone <name-of-repo>
cd <name-of-repo> 
```
2. Make the script an executable
```bash 
chmod +x schedule
```

3. Run using the file test0.txt, test1.txt OR your own input file. 
- **NOTE**: The input to your program will be a test file, where each line contains information about one process in a comma separated values (CSV) format as follows: 
- Process ID,Arrival Time,Burst Time,Priority 
- For more clarification, refer to the **'Project3.pdf'** in the repo
```bash
./schedule <file path> <scheduling algorithm> <time quantum if rr is being used> 
```

**NOTE**: Running the command above will output to the screen, enter the following command to redirect the output and save it to a file
```bash
./schedule test_files/test0.txt fcfs > output.txt
```

