![TAR COMMAND 1](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/ea5ffce1-701f-4429-a206-2b19ece94efc)## LinuxProjectPractice Project 1

**What is Linux**?

A Linux is a program or utility that runs on the CLI-a console that interacts with the system via text and processes, it is similar to the command prompt application in Windows. In addition, it is executed on Terminal by pressing Enter at the end of the line, you can run commands to perform various tasks, from package installation to user management and file manipulation.

We would be testing some of the Linus Commands on this first Project.

**1. SUDO COMMAND**

It is the short form for SuperUser Do, Sudo is one of the most popular basic Linux commands that lets you perform tasks that require administrative or root permission.
![sudo command](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/6063043a-6ef9-455d-bde2-0821553a44ec)

You must make sure you have administrative privileges to perform this operation.

**2. PWD COMMAND**

The pwd command is used to print the current working directory in the terminal. Simply typing Enter, this will display the full path of the current directory you are in.
![PWD Command](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/2dc52458-5f96-4af6-81e6-20974fe3c373)


**3. CD COMMAND**

The cd command is used to change the current working directory in the terminal. Running this command without an option will take you to the home folder. keep in mind that only users with *SUDO privileges* can execute it.
![cd](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/fdf94ef6-95a9-4c52-b84b-f183ba7a0618)

Here are some shortcut to help you navigate:

cd ~ {Username} goes to another user's home directory

cd .. Moves one director upward

cd - moves you to your previous directory
![CD COMMAND 2](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/f4f2c347-1a7f-432b-b349-060a337f0f40)

**4. ls COMMAND**

This is an Ls command in the Ubuntu terminal that is used to list the files and directories in the current working directory, it provides a way of viewing the content of a directory. here are a few examples.

![LS COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/a932ca6e-e9a0-4f75-8216-1bfcb5922882)

other commands are :
ls -R

ls -a and ls -1h

![LS -R COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/46ed46e9-946e-4684-92c3-5615a80c3083)
![LS -a and LS -1h COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/3d6fd136-65e2-427a-8426-b21e0e5def1e)

**5. CAT COMMAND**

The cat command in the Ubuntu terminal is used to display the contents of text files. it's a short word for "concatenate", and its primary  use is to display the contents of one or more files. it's also commonly used to create new files, combine files and redirect content. for example:
![CAT COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/445a06cc-867c-45cd-92c3-4b4a2c1c6f5d)

TAC command display contents in a reverse order

![TAC COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/98d59aea-01db-4e44-8769-d3041acf27ae)

**6. CP COMMAND**

The cp command in the Ubuntu terminal is used to copy files or directories from one location to another. It stands for  "copy" and is followed by the source file/directory path and destination path to which you want to copy the files/directories to. for example:
![CP COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/98538682-7e4c-45ff-b155-360e81018503)

**7. MV COMMAND**
The mv command in Ubuntu (and other Linux-based systems) is used to move or rename files and directories. It stands for  "move" but it is also commonly used for renaming because the process involves changing the name and location of the specified directory. for example, you can use the mv command to move a file from one directory to another or rename a file by specifying a new name in the directory.
![MV COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/dd121550-75c1-4b9f-ac82-6771e533df90)

**8. MKDIR COMMAND**

The `mkdir` command in the Ubuntu terminal is used to create new directories (folders). You can use it to make a new directory within the current working directory or specify a full path to create a directory in a specific location. For example, typing `mkdir Ifyfolder` will create a new directory named "Ifyfolder" in the current directory.
![MKDIR COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/cf2d26a3-f556-4879-97f1-11e532a7a0c2)

**9. RMDIR COMMAND**

The `rmdir` command in the Ubuntu terminal is used to remove empty directories (folders). It deletes a directory only if it is empty; otherwise, it will show an error. For instance, if you have an empty directory named "Ifyfolder" and you want to remove it, you can use the command `rmdir Ifyfolder`. If the directory contains any files or subdirectories, you would need to use the `rm` command with the `-r` (recursive) option to remove them first before using `rmdir`.
![RMDIR COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/7e3d3df4-fe05-41ef-82bf-bc09ec30419f)

**10. RM COMMAND**

The rm command in the Ubuntu terminal is used to remove (delete) files or directories from the file system. Its primary function is to delete files, and it can also be used to remove empty directories. However, it's important to note that the rm command doesn't move deleted files to a trash or recycle bin; instead, it deletes them permanently from the system.

Here's the basic syntax of the rm command:
![RM COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/5c3f71e2-f38f-440e-9cd3-d97867202dfe)

**11. TOUCH COMMAND**

The touch command in the Ubuntu terminal is used to create new empty files or update the timestamp of existing files. Its primary function is to either create a new file if it doesn't exist or update the access and modification timestamps of an existing file.

The basic syntax of the touch command is:
![TOUCH COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/5eded162-34a3-4b3d-905a-0df08e0711c9)

**12. LOCATE COMMAND**

The locate command in the Ubuntu terminal is used to quickly search for files and directories on the system by utilizing a pre-built index of file and directory names. It's a fast and efficient way to locate files, especially when compared to using commands like find that search the file system in real-time.

The locate command is based on a database called the "locatedb" or "slocate" database. This database is typically updated regularly (often daily) by a background process called updatedb. This process scans the entire file system and creates a database of file and directory names. When you use the locate command, it searches this database rather than directly searching the file system, which makes it much faster.

The basic syntax of the locate command is:
![LOCATE COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/1cd544ed-628c-42d0-ac4b-19310b9b32ba)

**13. FIND COMMAND**
The find command in the Ubuntu terminal is used to search for files and directories within a specified directory hierarchy based on various criteria such as file names, types, sizes, permissions, and more. It's a versatile tool that allows you to search for files using a wide range of conditions.

The basic syntax of the find command is:
![FIND COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/aae56ac5-df23-4846-97b7-7c86856cd4c6)

**14. GREP COMMAND**

The grep command in the Ubuntu terminal is used to search for specific patterns or text strings within files or the output of other commands. It's a powerful utility that allows you to filter and extract lines from text files based on a specified pattern, making it useful for text processing, searching, and data extraction.

The basic syntax of the grep command is:
![GREP COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/45c854cb-5a59-407f-a173-ec3398ca1604)

**15. DF COMMAND**

The df command in the Ubuntu terminal is used to display information about the disk space usage on your system's file systems (partitions). It provides information about the total, used, available, and percentage of disk space used for each mounted file system. This information is helpful for monitoring disk usage, understanding storage capacity, and identifying potential issues with disk space availability.

The basic syntax of the df command is:
![DF COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/108ff90b-ed32-4275-8771-97ae2cbc6e3a)

**16. DU COMMAND**

The du command in the Ubuntu terminal is used to estimate and display the disk space usage of files and directories. Unlike the df command, which provides information about disk space usage at the file system level, the du command focuses on specific files and directories, allowing you to see how much space individual files and directories are occupying.

The basic syntax of the du command is:
![DU COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/abd437ef-434d-4506-98f0-a4a7f299b6b9)

**17. HEAD COMMAND**

The head command in the Ubuntu terminal is used to display the beginning (top) portion of a text file or the output of a command. By default, it shows the first 10 lines of a file or command output, but you can specify a different number of lines if needed.

The basic syntax of the head command is:
![HEAD COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/e0ab19e5-74d6-4bdf-9b2d-3b547da46e31)

**18. TAIL COMMAND**

The tail command in the Ubuntu terminal is used to display the end (tail) portion of a text file or the output of a command. It is the counterpart to the head command, which displays the beginning of a file or command output. By default, tail shows the last 10 lines of a file or command output, but you can specify a different number of lines if needed.

The basic syntax of the tail command is:
![TAIL COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/19dbe710-8837-4e71-948b-24876344ed46)

**19. DIFF COMMAND**

The diff command in Ubuntu's terminal is used to compare the contents of two files or directories and highlight the differences between them. It's often used to find out what changes have been made between two versions of a file or to compare the contents of two directories.

Here's the basic syntax of the diff command:
![DIFF COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/293bb8e1-1148-4fce-ae59-30c1ac0d19c0)

**20. TAR COMMAND**

The tar command in Ubuntu's terminal is used for creating and manipulating archive files, often referred to as "tarballs." Tarballs are typically used to store and compress multiple files and directories into a single archive file, making it easier to transfer or back up a group of files while maintaining their directory structure and permissions.

The name "tar" stands for "tape archive," as the command was originally designed for archiving files onto magnetic tape drives. However, nowadays, it's commonly used for creating and extracting archive files on various storage mediums.

The basic syntax of the tar command is as follows:
![TAR COMMAND 1](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/a9438cd2-b80f-4f9e-87bd-cc188441988d)
![TAR COMMAND2 TO EXTRACT](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/f615ecf2-aa2d-435a-b714-e334b2933c73)

**21. CHMOD COMMAND**

The chmod command is a common command that modifies a file or directory's read, write and execution permission. in Linux, each file is associated with three user classes an owner, group members, and others. 

Here are the examples:

![CHMOD COMMAND1](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/3306333f-a042-4bcd-8a41-c1b7071a99f6)
![CHMOD COMMAND2](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/1bd0034b-0572-42b7-9a73-528df8da6876)

**22. CHOWN COMMAND**

The chmod command in Ubuntu (and other Unix-like systems) is used to change the permissions of files and directories. Here are some examples:

![CHOWN COMMAND1](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/3f13bdd7-fdf3-4a1d-9edc-9c146fb87e9b)

**23. JOBS COMMAND**

The jobs command is used to display the status of jobs running in the background or suspended, remember this command is only available in CSH, BASH, TCSH AND KSH shells:

The syntax below is:
job [options] jobID

Here are some of the options you can use:

-l lists process IDS along with their information, -n lists jobs whose statuses have changed since last the last notification, -p lists process IDs only.

**24. KILL COMMAND**

The kill command is used to send signals to processes. These signals instruct processes to perform various actions, such as terminating gracefully, reloading configurations, or responding to specific events. The primary function of the kill command is to manage and control processes running on the system. 

Here are some common signals and their functions:

1. TERM (15) - Terminate:
The default signal sent by kill is TERM, which asks the process to terminate gracefully. The process is given a chance to clean up before exiting.

2. INT (2) - Interrupt:
The INT signal is typically sent when you press Ctrl+C in the terminal. It interrupts the process, asking it to terminate immediately.

3. HUP (1) - Hang Up:
The HUP signal is often used to instruct a process to reload its configuration files without restarting. It's commonly used for daemons and servers to apply changes without stopping the service.

4. KILL (9) - Forceful Termination:
The KILL signal is used to forcefully terminate a process. It doesn't give the process a chance to clean up or react; the process is immediately terminated. This should be used cautiously, as it can lead to data corruption or incomplete cleanup.

5. USR1 (10) and USR2 (12) - User-defined Signals:
These signals can be used for custom actions defined by the process. Processes can handle these signals in their code to perform specific tasks.

6. STOP (19) and CONT (18) - Stop and Continue:
The STOP signal suspends a process, while the CONT signal resumes it. This is often used to pause and resume processes, allowing them to be temporarily halted without termination.

7. QUIT (3) - Quit:
The QUIT signal is similar to the TERM signal but is often used to trigger a graceful exit that produces a core dump. It's useful for debugging purposes.

8. TSTP (20) - Terminal Stop:
The TSTP signal is sent when you press Ctrl+Z in the terminal. It suspends the process and moves it to the background. You can resume the process later with the fg command.

The kill command can be used to send any of these signals to processes by specifying the signal number or its name. The typical syntax is kill -<signal> PID, where <signal> is the signal number or name, and PID is the Process ID of the target process.

Remember that different processes may respond differently to signals, and some signals might not have any effect on certain processes. Always use signals carefully and considerately to avoid disrupting the system's stability.

**25. PING COMMAND**

he ping command in the Ubuntu terminal is used to test the reachability and latency of a network host, typically using the Internet Control Message Protocol (ICMP). It sends ICMP echo request packets to the target host and waits for ICMP echo reply packets to come back. The primary function of the ping command is to check the connectivity and response time of a networked device, such as a server or another computer, on a local network or the internet.

Here's how the ping command works and what it's used for:

1. Checking Network Connectivity:
When you use the ping command followed by a hostname or IP address, the command sends a series of ICMP packets to the specified host. If the host is reachable and responsive, it sends back ICMP echo reply packets, indicating that the communication is successful.

2. Measuring Round-Trip Time (Latency):
The ping command also provides information about the round-trip time (latency) it takes for a packet to travel from your computer to the target host and back. The output displays the time in milliseconds for each packet's round-trip journey.

3. Troubleshooting Network Issues:
ping is commonly used to diagnose network problems. If a host doesn't respond to ping requests, it might indicate network congestion, connectivity issues, or firewall restrictions. It can help system administrators identify where a network communication problem might be occurring.

4. Checking Network Stability:
Running a continuous ping to a host over time can help monitor the stability of the network connection. If you notice fluctuations in response times or intermittent loss of connectivity, it could signal problems with the network.

Use example: 

![PING COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/ba50b358-68b4-4bce-84c7-21724d14ef1d)

**26. WGET COMMAND**

The wget command in the Ubuntu terminal is used for downloading files from the internet. It stands for "web get" and is a command-line utility that retrieves files using various protocols, such as HTTP, HTTPS, FTP, and more. The primary function of the wget command is to retrieve files from remote servers and save them to your local system.

Here's how the wget command works and what it's used for:

![WGET COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/29389fd8-a849-4c68-b92b-b99ec45f9101)

**27. UNAME COMMAND**

The uname command in Ubuntu (and other Unix-like operating systems) is used to display system information related to the system's kernel and operating system. It provides various options that allow you to retrieve specific information about the system. When you run the uname command without any options, it typically displays the kernel name, node (hostname), kernel release, kernel version, machine hardware architecture, and operating system.

Here are some common options and what they display:

1. -a or --all: Displays all available information about the system.
2. -s or --kernel-name: Displays the kernel name.
3. -n or --nodename: Displays the node (hostname).
4. -r or --kernel-release: Displays the kernel release.
5. -v or --kernel-version: Displays the kernel version.
6. -m or --machine: Displays the machine hardware architecture.
7. -p or --processor: Displays the processor type.
8. -i or --hardware-platform: Displays the hardware platform.
9. -o or --operating-system: Displays the operating system.
10. -h or --help: Displays the help message for uname command options.

![UNAME COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/32101ff5-f069-4e69-9369-9a89e5b8a152)































































   

