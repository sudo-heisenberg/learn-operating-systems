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

The job of the operating system is to create good abstractions and then implement and manage the abstract objects thus created. For e.g - FILES




#### In Linux, a desktop environment provides a graphical interface to interact with the system, including window management, system controls, and user applications. 
- The **X Window System ( x11 )** provides the foundational framework for graphical interfaces on Linux, though it is being gradually replaced by Wayland.
- **GNOME ( GNU Network Object Model Environment )** is perfect for users who prefer a minimalistic, easy-to-use desktop environment with a focus on productivity.
- **KDE Plasma** offers a rich, customizable environment, ideal for those who want a traditional desktop feel with the ability to tweak every aspect of the UI.




The first true digital computer was designed by the English mathematician
Charles Babbage (1792–1871). Although Babbage spent most of his life and fortune trying to build his ‘‘analytical engine,’’ he nev er got it working properly because it was purely mechanical, and the technology of his day could not produce
the required wheels, gears, and cogs to the high precision that he needed. Needless
to say, the analytical engine did not have an operating system.

As an interesting historical aside, Babbage realized that he would need software for his analytical engine, so he hired a young woman named Ada Lovelace,
who was the daughter of the famed British poet Lord Byron, as the world’s first
programmer. The programming language **Ada**® is named after her.
