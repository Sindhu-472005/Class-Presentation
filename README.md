# Class-Presentation
**Topic - Linux Operating System**

**About Linux**

Linux is an operating system, created in 1991 by Linus Torvalds. Started as a hobby not as innovation.It is a open sourcee and free for everyone to use.


**Why Linux?**

It is an engine, that powers the basic functions of a computer. Since its free and open source users don't have to pay for customize it anyone can view and modify it to meet their specific needs and can distribute it. Linus is a community driven operating systeem so it provides regular updates and assistance and evolves continuously.


**Key difference between Linux and windows**

**Linux**

* Free open source don't have to pay
* Community developed
* Full user control
* Better privacy options
* Have higher learning curve but more powerful once mastered

 **Windows**

 * Its paid
 * Developed by microsoft
 * Microsoft controls software
 * Limited privacy
 * Beginner friendly. 


**Linus architecture**

User -- Shell -- Kernel -- Hardware

Kernel understands only 1,and 0 so shell converts our commands to computer language and tranfer it to kernel 

Kernel is a mediator between shell and hardware. It is responsible to communicate with hardware components [RAM, CPU, GPU, Hard disk]

In a General-Purpose Computer running many processes simultaneously, we need a middle layer to manage the distribution of the computer’s hardware resources efficiently and fairly among all the various processes running on the computer. This middle layer is referred to as the kernel

The kernel virtualizes the computer’s common hardware resources to provide each process with its own virtual resources. This makes the process seem as if it is the sole process running on the machine. The kernel is also responsible for preventing and mitigating conflicts between different processes. 

The kernel, if implemented properly, is invisible to the user, working in its own little world known as kernel space, where it allocates memory and keeps track of where everything is stored. What the user sees—like web browsers and files—are known as the user space. These applications interact with the kernel through a system call interface (SCI).

**The kernel has 4 jobs:**

1. Memory management -- tracking how much memory is consumed to stre what and where its stored.

2. Process management -- determine which should use the CPU, when and how long it should use central processor

3. Device drivers -- mediator between the hardware and processes

4. System security -- it receives requests for services from the processes.


