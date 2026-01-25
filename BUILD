=================== For building ISO on Unix systems (Linux) ====================

In the project root, where these files are, and also in the Makefile, write:

make clean && make

Or if separately, then:
First: make clean
Then: make

===================== For building ISO on Windows ======================

Same as on Unix systems, but separately:
First: make clean
Then: make

--------- Why do I need make clean? ---------

make clean cleans all old .o, .bin, and other files created during compilation
If you leave them and recompile with make without make clean, it will not overwrite existing .o and .bin files
It will instead create an ISO based on the current .o and .bin files, and any changes will not be applied
Using make clean removes these changes, so when you run make, it builds and creates all the files new, using the changes, not the existing ones.
