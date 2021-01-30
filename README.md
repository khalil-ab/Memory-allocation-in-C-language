
Memory is the place where programs and data are located when the processor runs them. The term "memory" refers mainly to the main memory, i.e. RAM, and its management must be carried out in an optimal and careful way, because despite its high availability, it is usually never sufficient. This is due to the continuously increasing size of the programs. The person who takes care of the management task is called the memory manager.
The memory manager is a subset of the operating system that allows a number of tasks to be performed, including allocating free space to user processes using an allocation algorithm such as First-Fit and Best-Fit.
My goal is to create a memory allocation application. To achieve this goal, i used our C programming skills and I designed "A2M BF-FF".

A2M BF-FF is an easy-to-use computer program for managing the memory allocation of any process.

This program can be used by programmers, students or computer science enthusiasts, to find out how the processes of a program will be managed with the help of well-presented states with explanatory comments.
Very easy to master, A2M BF-FF allows you to instantly follow the evolution of a program by responding very easily to the needs of users.

The project instructions :
This project talks about creating a memory allocation application using two types of allocation algorithms and two types of scheduling algorithms, knowing that the system we are studying has a single processor.
The two types of allocation algorithms are :

1.FF (First-Fit): The first block large enough to contain our process is the one that we are going to allocate to the process so that it has to run.

2.BF (Best-Fit): The smallest block large enough to contain our process is the one we are going to allocate to the process to execute.
The two types of scheduling algorithms : 
- FIFO (First In First Out): Also called FCFS (First Come First Served), this is one of the simplest algorithms there is. The idea is to add each process in a queue and execute each process in order of arrival.
- SJF (Short Job First): The SJF algorithm (shorter job first) is similar to FIFO but instead of executing in order of arrival, we choose to execute the one with the shortest execution time.
So, in front of a waiting list of arriving processes, our program will have to choose the next process to be stored in RAM using the FIFO algorithm, and before allocating free memory space to it, if possible, we look for the appropriate block using one of the two allocation algorithms chosen: BF or FF. Once the process is allocated, the one that will be executed soon is the one with the shortest execution time: SJF. It should also be noted that each process is characterized by information loaded by the program from a TXT type file. Each line of the latter is composed of the following data separated by a semicolon : 
- The code that uniquely identifies the process
- The arrival date of the process
- The requested memory space size
- Process execution time
When the program is running, the user loads the TXT file containing the BCP of each process, chooses the type of memory allocation algorithm, specifies the RAM size, and then receives a presentation of all new instantaneous RAM states with the start and end address of each block, the size of each, pending processes and comments.

Attention !!
Before using this application you must make sure that you have configured the console as follows:
<p align="center">
  <img src="/important.JPG">
</p>

then you can start the app 

<p align="center">
  <img src="/0.png">
</p>
<p align="center">
  <img src="/1.png">
</p>
<p align="center">
  <img src="/2.png">
</p>
<p align="center">
  <img src="/3.png">
</p>
<p align="center">
  <img src="/4.png">
</p>
<p align="center">
  <img src="/5.png">
</p>

Here the link of the video simulation : 

Here is my email if anyone would like to contact me : abouabdelmajidkhalil@gmail.com
