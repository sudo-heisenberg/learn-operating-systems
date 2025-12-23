[Books by Andrew S. Tanenbaum](https://csc-knu.github.io/sys-prog/books/)

[MINIX3](www.minix3.org)

botnets & malwares

- The program that users interact with, usually called as **shell** when it is text based, or **GUI (Graphical User Interface)** when it uses icons, is actually not part of the operating system, although it uses the operating system to get its work done.


- Most computers have two modes
  - User mode ( The rest of the softwares run in user mode where they have access to a certain subset of machine instructions - any instruction that caffect the control of the machine i.e. I/O is forbidded to the user mode )
  - Kernel mode ( The OS runs in **kernel mode or supervisor mode** where it has complete access to all the hardware and can execute any instruction the machine is capable of executing )

<img width="754" height="459" alt="Screenshot 2025-12-23 at 10 41 58 AM" src="https://github.com/user-attachments/assets/a3e951ab-a588-4eba-911f-1a43b05790da" />

<br>
<br>
<br>

Some interesting facts about OS
- Linux or Windows is of the order of 5 million lines of code. ( Which is only for the part that runs in the kernel )
- When essential shared libraries are included, windows is over 70 million lines of code. ( this excludes basic application softwares like windows explorer, windows media player )


Operating systems
1. Windows 95/98/Me
2. Windows NT/2000/XP/Vista/Windows 7
3. System V
4. Solaris
5. FreeBSD
6. Linux - closely modeled on UNIX & highly compatible with it
7. OS X - modeled on UNIX
8. MINIX - modeled on UNIX



The architecture of a computer ( instruction set, memory organization, I/O, and bus structure ) at the machine language level is primitive and awkward to program, specially I/O.

SATA Hard disks - Serial ATA


The job of the operating system is to create good abstractions and then implement
and manage the abstract objects thus created. For e.g - FILES
