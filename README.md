## tinyshell

# What is it?
Tinyhshell is a program written in C/C++ that tries to replicate a real shell. 
1. It processes all shell commands along with three other commands, namely history,            history -sbu and exit, which have been explained below. 
2. The code tries to inculcate Object Oriented Programming, STL and the concept of parent and child procceses into it.

# Additional Commands
The commands implemented for this project are:
1. history       : Displays the last five commands along with their executiong times.
2. history - sbu : Displays the last five commands in the descending order of their execution times.
3. exit          : exits the program


# How to set it up
To run the program and other functionalities, clone the repository and give the following make commands:
1. make tinyshell - Compiles the code (generating object code and linking the necesaary files together).
2. make run - runs the ./tinyshell executable file
3. make clean - cleans all the .o files in the directory along with the executable as well.
4. make tar - Creates an archive of the all the files into a single .tar file called tinyshell.tgvz




