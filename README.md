# Lightning Shell 

A simple shell

## Synopsis

A Unix shell is both a command interpreter and a programming language. As a
command interpreter, the shell provides the user interface to the rich set of
GNU utilities. The programming language features allow these utilities to be
combined. Files containing commands can be created, and become commands
themselves. These new commands have the same status as system commands in
directories such as /bin, allowing users or groups to establish custom
environments to automate their common tasks.

On this project, this program is a simple implementation of a shell.

## Description
This program runs and mimics like a simple UNIX command interpreter. 

Rundown of the program
- Gets user input
- Tokenize input
- Check builtins
- Check Environment and use PATH
- Use fork(), execve(), and wait()

## Requirements

-   Compiled on Ubuntu 20.04 LTS
-   Your programs and functions will be compiled with gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
-Wextra and -pedantic
-   Follows the Betty style
-   Prototypes of the functions are in the shell.h header file
-   No more than 5 functions per file
