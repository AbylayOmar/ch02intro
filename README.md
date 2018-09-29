# ch02intro
Introduction to OS, Chapter 02

Read [Introduction to OS](http://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf) and answer the following review questions.

1. **What is an operating system? What does it do?** Operating system is stack of programs which are necessary for computer control. 
2. **What is virtualization?** This is a program that provides isolation between processes
3. **How does an OS provide access to its features?** By use programs. Ex. libriries, modules
4. **What illusion does a virtualized CPU provide?** Illision is system has a very large number of virtual CPUs.
    - **How does this affect the user experience?** No way. Can only because of the speed of work 
    - **How does this affect the developer experience?** The developer can speed up the speed of his work. 
    - **What if the CPU were not virtualized?** He could not use all his potential 
5. **What is a memory address?** Memory address is like link to the part of memory
6. **What is memory virtualization?** Each programm has own virtual space in memory
    - **Why would we want this?** We can run programs even if there is not enough memory for this
8. **What happens if you write a C/C++ program that writes past the end of an array?**  Anything. It depends on the architecture of the computer and depends on the values that were written
      - **Can this affect other programs?** It can happen anything you like, but usually it does not affect the work of other programs 
9. **What is a thread?** We can break the power of the processor for certain tasks. The task working on these resources is called a thread.
10. **Why would we ever write a multi-threaded program?** To increase the speed of the program
11. **What is atomicity?** A program that can not bring down another thread
    - **Is a C/C++ statement atomic?** No, it isnt
    - **Is a Java statement atomic?** Yes
    - **Is an assembler statement atomic?** No 

13. **What does persistence mean?** This software for permanent data storage

14. **How does OS hard drive virtualization differ from CPU & memory virtualization?** The OS does not create a separate piece of memory for applications
15. **How does running multiple programs at the same time increase CPU efficiency?** The OS will load many tasks into memory and switch between them 
16. **What is multiprogramming?** This is when the processor performs several programs at the same time
