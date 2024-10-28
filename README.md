
1	Assignment No. 1	

A. Study of Basic Linux Commands: echo, ls, read, cat, touch, test, loops, arithmetic comparison,conditional loops, grep,sed etc.

B. Write a program to implement an address book with options given below:
    a) Create addressbook.
    b) View address book.
    c) Insert a record.
    d) Delete a record.
    e) Modify a record.
    f) Exit

2	Assignment No. 2	Process control system calls: The demonstration of FORK, EXECVE and WAITsystem calls along with zombie and orphan states.

A. Implement the C program in which main program accepts the integers to be sorted. Main programuses the FORK system call to create a new process called a child process. Parent process sorts the integers using sorting algorithm and waits for child process using WAIT system call to sort the integersusing any sorting algorithm. Also demonstrate zombie and orphan states.

B. Implement the C program in which main program accepts an array. Main program uses the FORK system call to create a new process called a child process. Parent process sorts an array and passes the sorted array to child process through the command line arguments of EXECVE system call. The child process uses EXECVE system call to load new program which display array in reverse order.

3	Assignment No. 3	Implement the C program for CPU Scheduling Algorithms: Shortest Job First (Preemptive) and Round Robin with different arrival time.

4	Assignment No. 4	

A. Thread synchronization using counting semaphores. Application to demonstrate: producer−consumer problem with counting semaphores and mutex.

B. Thread synchronization and mutual exclusion using mutex. Application to demonstrate: Reader−Writer problem with reader priority.

5	Assignment No. 5	Implement the C program for Deadlock Avoidance Algorithm: Bankers Algorithm.

6	Assignment No. 6	Implement the C program for Page Replacement Algorithms: FCFS, LRU, and Optimal for frame size as minimum three.

7	Assignment No. 7	Inter process communication in Linux using following.

A. FIFOS: Full duplex communication between two independent processes. First process accepts sentences and writes on one pipe to be read by second process and second process counts number of characters, number of words and number of lines in accepted sentences, writes this output in a text file and writes the contents of the file on second pipe to be read by first process and displays onstandard output.

B. Inter-process Communication using Shared Memory using System V. Application to demonstrate: Client and Server Programs in which server process creates a shared memory segment and writes the message to the shared memory segment. Client process reads the message from the shared memory segment and displays it to the screen.

8	Assignment No. 8	Implement the C program for Disk Scheduling Algorithms: SSTF, SCAN, C−Look considering the initial head position moving away from the spindle.

9	Study Assignment	: Implement a new system call in the kernel space, add this new system call in theLinux kernel by the compilation of this kernel (any kernel source, any architecture and any Linux kernel distribution) and demonstrate the use of this embedded system call using C program in user space.
