* Thank you for downloading Open Source Jeb OS v7.8!

You now have the complete OS structure. All files are important except for the LICENSE and this README file. To build the .iso, enter make clean && make in the terminal, or if on Windows, each one separately: make clean and then make. Files like this will appear:

kernel.o - The system itself with logic
boot.o - CPU information on what to do
jeeb.bin - The system kernel (all files in compiled assembly)

You can delete them all or do whatever you like with them, but they are created for building the ISO and are no longer needed once the .iso has been built. Once JebOS.iso appears next to this file in the root directory, you can use utilities like Rufus and others to create a bootable disk with this OS.

All files can be modified, custom commands can be added, or the OS can be executed now. Version 7.8 of the OS supports 6 commands, such as:

---

help - Help menu for commands

---

clear - Clears the entire command line, leaving only the REPL (Jeb#) at the top.

---

info - More about Jeb OS
jeeb - More aboud Jeeb shell

---

reboot - Restarts the PC.

---

off - Terminates all processes and only then shuts down the PC. (Simply shutting down may not save saved commands and other important files.)

---

There is also support for arrow controls, for example, to move through text, use the left and right arrows, and to move through commands, like history, use the up and down arrows (the command history is saved to a file, and even rebooting and shutting down save the history)

================ Thank you for using and installing Jeb OS 1.0! ================

We appreciate users sharing their projects and modifying these projects. Everything is openly available on Github, and ready-to-use releases are available without the need to build them yourself using a Makefile. You can follow the links below if needed, or download the finished .zip file or .iso file of this project from SourceForge. The MIT license was used and continues to be used until the 2027 license update. (You can modify and share your projects, but please provide attribution to: Mavox-ID and NeedYOU4.)

Github Mavox-ID: https://github.com/Mavox-ID
Website Mavox-ID: https://ye-a.pp.ua
Github Repo: https://github.com/Mavox-ID/JebOS
