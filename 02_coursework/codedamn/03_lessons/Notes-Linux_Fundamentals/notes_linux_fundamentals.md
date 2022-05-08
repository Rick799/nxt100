# Introduction

**_Linux_** is a family of free and open-source Unix-like operating systems based on the Linux kernel. Linux is typically packaged in a Linux distribution. Operating systems based on Linux are known as Linux distributions or distros. Examples include Debian, Ubuntu, Fedora, CentOS, Gentoo, Arch Linux, and many others.

## The Terminal

A **_terminal_** is an input and output environment that presents a text-only window running a shell.

## A Shell

A **_shell_** is a program that exposes the computer’s operating system to a user or program. In Linux systems, the shell presented in a terminal is a command line interpreter.

## Command Line Interface

A **_command line interface_** is a user interface (managed by a command line interpreter program) which processes commands to a computer program and outputs the results. <br><br>

# LINUX COMMANDS

## **DIRECTORY COMMANDS**

- ## pwd Command

The **pwd** command is used to display the location of the current working directory.

- ## echo Command

The **echo** command in Linux simply displaysaline of text/string which is passed in
as an argument. It is commonly used for debugging shell programs inside the
terminal.

- ## mkdir Command

The **mkdir** command is used to create a new directory under any directory.

- ## rmdir Command

The **rmdir** command is used to delete a directory.

- ## ls Command

The **ls** command is used to display a list of content of a directory.

- ## cd Command

The **cd** command is used to change the current directory.

- ## tree Command

The **tree** command in Linux can be used to list out the contents of directories ina
tree-like fashion.

## **FILE COMMANDS**

- ## touch Command

The **touch** command is used to create empty files. We can create multiple empty files by executing it once.

- ## cat Command

The **cat** command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

- ## rm Command

The **rm** command is used to remove a file.

- ## cp Command

The **cp** command is used to copy a file or directory.

- ## mv Command

The **mv** command is used to move a file or a directory form one location to another location.

- ## rename Command

The **rename** command is used to rename files. It is useful for renaming a large group of files.

- ## grep Command

The **grep** command in Linux searches throughaspecified file and prints all lines
that matchagiven pattern.

## **USER COMMANDS**

- ## su Command

The **su** command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

- ## useradd Command

The **useradd** command is used to add or remove a user on a Linux server.

- ## passwd Command

The **passwd** command is used to create and change the password for a user.

## **UTILITY COMMANDS**

- ## find Command

The **find** command is used to find a particular file within a directory. It also supports various options to find a file such as byname, by type, by date, and more.

The following symbols are used after the find command:

(.) : For current directory name

(/) : For root

- ## locate Command

The **locate** command is used to search a file by file name. It is quite similar to find command; the difference is that it is a background process. It searches the file in the database, whereas the find command searches in the file system. It is faster than the find command.

- ## cal Command

The **cal** command is used to display the current month's calendar with the current date highlighted.

- ## sleep Command

The **sleep** command is used to hold the terminal by the specified amount of time. By default, it takes time in seconds.

- ## time Command

The **time** command is used to display the time to execute a command.

- ## zcat Command

The **zcat** command is used to display the compressed files.

- ## df command

The **df** command is used to get a report on the system’s disk space usage, shown in percentage and KBs.

- ## exit Command

The **exit** command is used to exit from the current shell. It takes a parameter as a number and exits the shell with a return of status number.

- ## clear Command

The **clear** command is used to clear the terminal screen.

## kill Command

In case of an unresponsive program, one can terminate it manually by using the **kill** command. It will send a certain signal to the misbehaving app and instructs the app to terminate itself.

There is a total of 64 signals but people usually only use two signals:

**_SIGTERM_** (15) — requests a program to stop running and gives it some time to save all of its progress. If you don’t specify the signal when entering the kill command, this signal will be used.

**_SIGKILL_** (9) — forces programs to stop immediately. Unsaved progress will be lost.

## wget Command

The **_wget_** command in Linux isautility tool to download applications/web pages
directly from the web. It allows file downloads with HTTP, HTTPS, and FTP
protocols. <br><br>

# NANO TEXT EDITOR

**_GNU nano_** is an easy to use command line text editor for Unix and Linux operating systems. It includes all the basic functionality you’d expect from a regular text editor, like syntax highlighting, multiple buffers, search and replace with regular expression support, spellchecking, UTF-8 encoding, and more.

Install Nano on Ubuntu and Debian

- `sudo apt install nano`

To open an existing file or to create a new file, type nano followed by the file name:

- `nano filename`

All commands are prefixed with either ^ or M character. The caret symbol **(^)** represents the Ctrl key. For example, the ^J commands mean to press the Ctrl and J keys at the same time. The letter **M** represents the **_Alt_** key. <br> <br>

## Searching and replacing

To search for a text, press **_Ctrl+w_**, type in the search term, and press Enter. The cursor will move to the first match. To move to the next match, press Alt+w.

If you want to search and replace, press **\_Ctrl+\_**. Enter the search term and the text to be replaced with. The editor will move to the first match and ask you whether to replace it. After hitting **_Y_** or **_N_** it will move to the next match. <br>
Pressing **_A_** will replace all matches.

## Copping, cutting, and pasting

To select text, move the cursor to the beginning of the text and press **_Alt+a_**. This will set a selection mark. <br>
Move the cursor to the end of the text you want to select using the arrow keys. The selected text will be highlighted.<br>
If you want to cancel the selection press **_Ctrl+6_**

Copy the selected text to the clipboard using the **_Alt+6_** command.
**_Ctrl+k_** will cut the selected text.

If you want to cut whole lines, simply move the cursor to the line and press **_Ctrl+k_**. You can cut multiple lines by hitting **_Ctrl+k_** several times.

To paste the text move the cursor to where you want to put the text and press **_Ctrl+u_**.

## Saving and Exiting

To save the changes you’ve made to the file, press **_Ctrl+o_**. <br>
To exit nano press **_Ctrl+x_**. <br> <br>

# SHELL SCRIPTING BASICS

## BASH SCRIPT

A **_bash script_** is a series of commands written in a file. These are read and executed by the bash program. The program executes line by line.

## Define variables

A variable can be defined by using the syntax **_variable_name=value_**. To get the value of the variable, add **_$_** before the variable.

Numerical expressions can also be calculated and stored in a variable using the syntax below:

`var=$((expression))`

## read user input

In bash, we can take user input using the **_read_** command.To prompt the user with a custom message, use the **_-p_** flag.

## Conditional Statements

**_Conditions_** are expressions that evaluate to a boolean expression (true or false). To check conditions, we can use if, if-else, if-elif-else and nested conditionals.

The structure of conditional statements is as follows:

- if...then...fi statements <br>
- if...then...else...fi statements <br>
- if..elif..else..fi <br>
- if..then..else..if..then..fi..fi.. (Nested Conditionals) <br>

## Looping and skipping

**_For loops_**
For loops allow you to execute statements a specific number of times.

**_While loop_**

While loops check for a condition and loop until the condition remains true. We need to provide a counter statement that increments the counter to control loop execution.
