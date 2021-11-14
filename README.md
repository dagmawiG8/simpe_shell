# simpe_shell
Overview
This is a UNIX command line interpreter based on the simple shell(sh). It reads user input from the command line, interprets it, and executes commands.

# Getting Started
Clone this repository. Compile with GCC and use the following flags: gcc -Wall -Werror -Wextra -pedantic

Returns: 0 upon success or exit status upon error

# Usage
After compiling the program, you may use it in both interactive and non-interactive mode.

# Interactive Mode
From the command line, enter "./" , followed by the executable name (ex: "./a.out").
After the "$ " prompt appears, type in a command to be executed. Repeat as desired.
To exit the program, you can type in either crtl + d or "exit".

# Non-Interactive Mode
From the command line, use echo to pipe a command into the shell. Here's an example:
echo "pwd" | ./a.out

# Simple_Shell Built-ins
Command	| Description
env	    |   prints the environment
exit	  | exits out of our shell program

# Example Usage
ls -l lists directory contents using a long listing format
$ ls -l /tmp/
total 0
pwd prints the working directory
$ pwd
/home/vagrant/shelltesting
fakefile prints error because "fakefile" does not exist
$ fakefile
fakefile: No such file or directory

# About
Created on Ubuntu 14.04 LTS. Compiled with gcc 4.8.4, using flags: -Wall -Werror -Wextra and -pedantic

# Authors
Dagmawi Gebrewold <dagiwold@gmail.com>
