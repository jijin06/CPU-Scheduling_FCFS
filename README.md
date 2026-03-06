# CPU-Scheduling_FCFS
First-Come, First-Served (FCFS) is the simplest form of CPU scheduling. It manages processes based on their arrival order: the process that requests the CPU first is allocated the CPU first. It is a non-preemptive algorithm, meaning once a process starts executing, it will not leave the CPU until it finishes its burst time.
Key Characteristics:

    Simple Implementation: Managed using a FIFO (First-In-First-Out) queue logic.

    Fairness: Processes are treated in the exact order they arrive.

    Convoy Effect: A major drawback where short processes wait for a long time behind a single CPU-intensive process, leading to low CPU and device utilization.
