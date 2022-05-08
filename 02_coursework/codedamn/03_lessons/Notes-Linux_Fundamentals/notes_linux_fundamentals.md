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

## pwd Command

The **pwd** command is used to display the location of the current working directory.

## echo Command

The **echo** command in Linux simply displaysaline of text/string which is passed in
as an argument. It is commonly used for debugging shell programs inside the
terminal.

## mkdir Command

The **mkdir** command is used to create a new directory under any directory.

## rmdir Command

The **rmdir** command is used to delete a directory.

## ls Command

The **ls** command is used to display a list of content of a directory.

## cd Command

The **cd** command is used to change the current directory.

## tree Command

The **tree** command in Linux can be used to list out the contents of directories ina
tree-like fashion.

## **FILE COMMANDS**

## touch Command

The **touch** command is used to create empty files. We can create multiple empty files by executing it once.

## cat Command

The **cat** command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

## rm Command

The **rm** command is used to remove a file.

## cp Command

The **cp** command is used to copy a file or directory.

## mv Command

The **mv** command is used to move a file or a directory form one location to another location.

## rename Command

The **rename** command is used to rename files. It is useful for renaming a large group of files.

## grep Command

The **grep** command in Linux searches throughaspecified file and prints all lines
that matchagiven pattern.

## **USER COMMANDS**

## su Command

The **su** command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

## useradd Command

The **useradd** command is used to add or remove a user on a Linux server.

## passwd Command

The **passwd** command is used to create and change the password for a user.

## **UTILITY COMMANDS**

## find Command

The **find** command is used to find a particular file within a directory. It also supports various options to find a file such as byname, by type, by date, and more.

The following symbols are used after the find command:

(.) : For current directory name

(/) : For root

## locate Command

The **locate** command is used to search a file by file name. It is quite similar to find command; the difference is that it is a background process. It searches the file in the database, whereas the find command searches in the file system. It is faster than the find command.

## cal Command

The **cal** command is used to display the current month's calendar with the current date highlighted.

## sleep Command

The **sleep** command is used to hold the terminal by the specified amount of time. By default, it takes time in seconds.

## time Command

The **time** command is used to display the time to execute a command.

## zcat Command

The **zcat** command is used to display the compressed files.

## df command

The **df** command is used to get a report on the system’s disk space usage, shown in percentage and KBs.

## exit Command

The **exit** command is used to exit from the current shell. It takes a parameter as a number and exits the shell with a return of status number.

## clear Command

The **clear** command is used to clear the terminal screen.

## kill Command

In case of an unresponsive program, one can terminate it manually by using the **kill** command. It will send a certain signal to the misbehaving app and instructs the app to terminate itself.

There is a total of 64 signals but people usually only use two signals:

**_SIGTERM_** (15) — requests a program to stop running and gives it some time to save all of its progress. If you don’t specify the signal when entering the kill command, this signal will be used.

**_SIGKILL_** (9) — forces programs to stop immediately. Unsaved progress will be lost.

## wget Command

The **_wget_** command in Linux isautility tool to download applications/web pages
directly from the web. It allows file downloads with HTTP, HTTPS, and FTP
protocols.
