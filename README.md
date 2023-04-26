## Simple Shell > In this project, we coded from scratch a simple Unix shell. A shell is an interactive > command-line interpreter. We created a shell that would utilize the command line > interface (CLI). It allows users to type in a defined set of > commands (e.g. "rm" to remove files, "cat" to combine word documents, etc) and have the > operating system run the appropriate function. It is slightly different from a graphical user > interface (GUI). For instance, instead of using a mouse to click to open folders and delete files, a user > can type in a command (i.e. "ls" or "rm") and have the files be displayed or > modified in a list on the command line. GUI and CLI both have the same purpose to interact > with the operating system but their input methods are different and some developers > prefer the CLI to interact with the shell because their typing is quicker than > clicking and dragging. There are a few > versions of Unix shells, from the very first (Ken Thompson's) shell that can > be activated by typing ```sh``` in the terminal to today's most popular Bash > (Bourne Again Shell). Later versions of the shell handle memory leaks better and > have more functionality. Our shell is a simple version that handles memory leaks > very well and has basic functionality. You can create/write/read/open/remove > folders, print things to the terminal, change directories, print where you are > in the system, etc.

Synopsis

This repository holds all the code necessary for our custom simple shell to run. Our shell currently handles the executions of executables found in the environmental variable PATH, with or without their full paths. Sample commands that our shell supports include ls (/bin/ls), pwd, echo, which, whereis, etc. We've also created the following builtins.

Builtins

exit exits shell (Usage: exit [status])
env prints environmental variables (Usage: env)
setenv creates or modifies an environmental variable (Usage: setenv name value)
unsetenv removes an envrionmental variable (Usage: unsetenv name value)
cd changes directories (Usage: cd [-][~][path])

Functions and system calls used

read, signal, malloc, free, getcwd, chdir, access, execve, wait, write, exit

Description of what each file shows:

man_3_shell ------------------------ custom manpage for our simple shell
