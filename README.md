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

For example, if you run the following command:

![UNAME COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/32101ff5-f069-4e69-9369-9a89e5b8a152)

**28. top command**

The top command on Ubuntu (and other Unix-like operating systems) is used to monitor the system's real-time performance and resource utilization. It provides a dynamic, interactive view of various system statistics, including CPU usage, memory usage, running processes, and more. It is a powerful tool for system administrators and users to keep an eye on system health and performance.

When you run the top command, it displays a live updating list of processes, along with information about CPU usage, memory usage, system uptime, and other relevant metrics. The default view provides a snapshot of the most resource-intensive processes at the top, helping you quickly identify which processes are consuming the most resources.

Here's a brief overview of the information displayed by the top command:

Header Information: The top of the top display shows information about system uptime, load averages, number of running processes, etc.

Process List: The main part of the display lists all active processes. It includes details such as process ID (PID), user running the process, CPU usage percentage, memory usage percentage, process status, and more.

Summary Information: The bottom section of the top display provides summary information about CPU usage, memory usage, swap space usage, and other system-wide statistics.

Interactive Controls: top is interactive, which means you can use various keyboard commands to sort the process list, change the way processes are displayed, and more. For example, you can press "k" to send a signal to a process, "r" to renice a process, and "q" to quit the top command.

By default, top updates the displayed information in real-time. You can also configure the refresh interval and customize the information shown using various command-line options. The top command is commonly used for troubleshooting performance issues, identifying resource-hungry processes, and monitoring system behavior over time.

Keep in mind that top might have a learning curve due to its interactive nature and the wealth of information it provides, but it's a valuable tool for system monitoring and analysis.

![TOP COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/26c3a6a9-97c2-4431-8407-5f2f09e60ea7)

**29. HISTORY COMMAND**

The history command in Ubuntu (and other Unix-like operating systems) is used to display a list of commands that have been executed in the past in the current shell session. It provides a history of the commands you have entered in the terminal, allowing you to review and reuse them without having to retype them.

When you run the history command, it displays a numbered list of commands along with their command numbers. By default, it shows the most recent commands at the bottom of the list.

Here are a few ways the history command can be useful:

Command Recall: You can quickly recall and reuse previously executed commands by typing their command numbers and using the ! notation. For example, to rerun the command number 42, you can type !42.

Search: You can search through your command history for specific commands using the grep command. For instance, to search for all commands containing the word "sudo," you can use history | grep sudo.

Analyzing Activity: The history command allows you to review your recent terminal activity, which can be useful for troubleshooting or keeping track of what you've done.

Scripting and Automation: You can extract specific commands from your history to create scripts or automate certain tasks. This is particularly useful when you want to create a script to replicate a series of commands you've previously executed.

By default, the history list has a limited size, typically around 1000 commands, depending on the configuration. You can customize the history settings by modifying the shell's configuration file (e.g., ~/.bashrc for the Bash shell). You can control parameters like the maximum number of commands stored, the format of timestamps, and more.

Here are a few commonly used history command options:

1. history: Displays the list of previously executed commands.
2. !!: Repeats the last executed command.
3. !n: Repeats the nth command in history (replace "n" with the command number).
4. !string: Repeats the most recent command that starts with "string."
5. history -c: Clears the history list.
6. history -d n: Deletes the command with number "n" from the history.
7. history -a: Appends new history entries to the history file.
8. history -w: Writes the current history to the history file.
   
Remember that the history command shows commands from the current shell session only. Once you close the terminal or start a new session, the command history will not be retained unless you've configured your shell to save it to a history file.

![HISTORY COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/4436ff26-064d-4e42-a89f-cedd6e21a247)

**30. MAN COMMAND**

The man command in Ubuntu (and other Unix-like operating systems) is used to display the manual pages (or documentation) for various commands, functions, system calls, and configuration files. It provides detailed information about how to use specific commands and utilities available on your system. The manual pages are a crucial resource for learning about the functionality and usage of different commands and tools.

When you run the man command followed by the name of a command, it opens up the corresponding manual page in your terminal. Manual pages are organized into sections, and the man command allows you to specify the section if a command name exists in multiple sections. For example, you can use man 1 ls to view the manual page for the ls command in section 1 (general commands), and man 3 printf to view the manual page for the printf function in section 3 (library calls).

The manual page for a command typically includes the following information:

1. Name: The name of the command or function.
2. Synopsis: The syntax and usage of the command or function, including its options and arguments.
3. Description: Detailed information about what the command does and how it works.
4. Options: Explanation of the available command-line options and their meanings.
5. Examples: Usage examples that demonstrate how to use the command effectively.
6. See Also: References to related commands or functions that might be helpful.

Here's how you use the man command:

![MAN COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/e58862fb-b85a-4a69-b95e-9796f1d3e8bf

**31. ECHO COMMAND**

The echo command in Ubuntu (and other Unix-like operating systems) is used to display text or messages on the terminal. It is a simple and commonly used command that allows you to print information to the screen. The primary function of the echo command is to output its arguments (text strings) to the terminal window.

Here's how you use the echo command:

![ECHO COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/7ffd69a4-532a-45e5-99cc-bdee817fe0ea)

**32. ZIP, UNZIP COMMAND**

The zip and unzip commands on Ubuntu (and other Unix-like operating systems) are used for compressing and decompressing files and directories into the ZIP file format. ZIP is a popular archive file format that allows you to group multiple files and directories into a single compressed package, making it easier to store and transfer data while saving disk space.

Here's an overview of the functions of these commands:

zip Command:
The zip command is used to create compressed ZIP archives from one or more files or directories. It offers various options to customize the compression process, such as setting compression levels, including/excluding specific files, and more.

unzip Command:
The unzip command is used to extract files from ZIP archives. It can extract individual files or entire directories from a ZIP archive, and it provides options to control the extraction process, such as extracting files to a specific directory.

![ZIP, UNZIP COMMANMD](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/215ee188-a5f8-4851-9f2a-c22ca83b16ab)

**33. USERADD, USERDEL COMMANDS**

On Ubuntu (and other Unix-like operating systems), the useradd and userdel commands are used to manage user accounts on the system. They allow you to add and delete user accounts, respectively. Here's an overview of their functions:

useradd Command:
The useradd command is used to create a new user account on the system. When you create a user using this command, it initializes the user's home directory, sets a default shell, and performs other necessary setup tasks.

Here are the syntax examples

![USERADD, USERDEL COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/390ed652-6fb8-4060-adef-7218fa94dfca)

**34. HOSTNAME COMMAND**

The hostname command on Ubuntu (and other Unix-like operating systems) is used to display or set the system's hostname. The hostname is a label or identifier that is assigned to a system and is used to identify the system on a network or within a local environment. It's a human-readable name that helps in identifying and distinguishing different systems.

Here's how the hostname command can be used:

1. Display the Hostname:
Running the hostname command without any options will display the current hostname of the system.

2. Set the Hostname:
You can also use the hostname command to set a new hostname for the system. To do this, you typically need superuser privileges (root access) because changing the hostname can affect network configuration and system identification.

![HOSTNAME COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/8f62c601-7154-43ce-8321-76e2887cd765)

**35. APT-GET COMMAND**

The apt-get command on Ubuntu is used to manage software packages on the system. It is a powerful command-line tool that helps you install, upgrade, remove, and manage software packages from Ubuntu's software repositories. apt-get is part of the Advanced Package Tool (APT) suite, which is the package management system used in Ubuntu and other Debian-based distributions.

Here are some of the main functions of the apt-get command:

1. Install Packages:
You can use apt-get to install software packages from the Ubuntu repositories. For example, to install the Firefox web browser.

2. Upgrade Packages:
apt-get can upgrade installed packages to their latest available versions. This helps keep your system up to date with the latest security patches and bug fixes. Use the following command to update all installed packages:

3. Remove Packages:
You can use apt-get to uninstall or remove packages from your system. For example, to remove the Firefox package.

4. Search for Packages:
apt-get can be used to search for packages based on keywords. This can be helpful when you want to find a specific package to install. For example, to search for packages related to "text editor," 

5. Clean Package Cache:
The package cache can consume disk space over time. To clean up old package files that are no longer needed.

6. Upgrade Distribution (Release Upgrade):
To upgrade your Ubuntu distribution to a new release, you can use the dist-upgrade option:

![APT-GET INSTALL COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/6e523968-c77b-4454-b569-08c99d6a08d7)

![APT-GET UPGRADE COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/97085f12-02da-4226-a394-d3c7d81b9742)

**36. NANO, VI, JED COMMANDS**

The nano, vi, and jed commands are all text editors available on Ubuntu (and other Unix-like systems) that allow you to create, edit, and modify text files directly from the command line. Each of these editors has its own features and usage patterns:

1. nano Command:
nano is a user-friendly, beginner-friendly text editor. It's designed to be easy to use and provides an intuitive interface for editing text files. It offers basic editing functionalities and keyboard shortcuts that are similar to those found in other common applications. nano is particularly suitable for users who are not familiar with more advanced text editors like vi.

2. vi Command:
vi is a powerful and widely used text editor that comes with most Unix-like operating systems. However, it has a steeper learning curve compared to nano. vi operates in different modes: command mode (for navigating and performing operations) and insert mode (for inserting text).

3. jed Command:
jed is another text editor that provides an environment suitable for both novice and experienced users. It offers features similar to nano and vi but also includes support for scripting and customization. jed is known for its extensibility through the use of macros.

![NANO COMMNAD](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/b81321f9-e96c-4eb1-a585-5d677482944a)

![VI COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/60cc51ca-2ab7-4174-8cce-d8996b1929ef)

**37. ALIAS, UNALIAS COMMAND**

The alias and unalias commands on Ubuntu (and other Unix-like operating systems) are used to create and remove aliases, respectively. Aliases are custom shortcuts that allow you to create new, shorter names for longer or frequently used commands. These aliases can save you time and typing by allowing you to execute complex or lengthy commands with just a few keystrokes.

![ALIAS COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/45df4c67-873e-400f-8750-623f62e6d6a0)

![UNALIAS COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/527ae108-05bc-47d3-8978-ebc32bd7152b)

**38. SU COMMAND**

The su (short for "substitute user") command on Ubuntu (and other Unix-like operating systems) is used to switch to a different user account from within a terminal session. It allows you to run commands and perform tasks as if you were logged in as that user, provided you have the necessary permissions. The primary purpose of the su command is to execute commands with elevated privileges, usually as the root (superuser) user.

Here's how the su command works and its main functions:

Switch to Another User:
The basic usage of the su command is as follows:

![SU COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/5247cc4e-c0bf-4ecf-a645-53a934c81681)

**39. HTOP COMMAND**

The htop command on Ubuntu is a terminal-based process viewer and system monitoring tool. It provides an interactive and more feature-rich alternative to the traditional top command. htop allows you to monitor the system's resources, view and manage running processes, and perform various actions on them.

Here's an overview of the functions and features of the htop command:

1. Real-Time System Monitoring:
htop displays real-time information about system resources such as CPU usage, memory usage, swap usage, and more. It provides graphical representations of these resources, making it easier to understand their current state.

2. Process Listing and Management:
htop lists all running processes on the system, similar to the top command. It displays information about each process, including its process ID (PID), owner, CPU usage, memory usage, and more. The list is updated in real-time.

3. Interactive Interface:
Unlike the traditional top command, htop features an interactive and colorful interface. You can use keyboard shortcuts to sort the process list based on different criteria (e.g., CPU usage, memory usage), search for specific processes, and perform various actions on processes.

4. Process Actions:
htop allows you to perform actions on processes directly from its interface. You can send signals to processes (e.g., terminate, stop, continue), change the priority of processes, and even kill processes if necessary.

5. Resource Bars:
htop uses colored bars to represent resource usage, making it easier to visualize the distribution of resources among different processes.

6. Customization:
You can customize the htop display to suit your preferences. You can change colors, adjust columns, and configure various settings to tailor the view to your needs.

7. Tree View:
htop can display processes in a hierarchical tree structure, allowing you to see parent-child relationships between processes.

Please note that while htop provides a more intuitive and interactive interface compared to top, it might not be installed by default on all systems. You can install it using your package manager, such as **sudo apt-get install htop on Ubuntu**. It's a valuable tool for system administrators and users who want a more detailed and interactive view of their system's resource usage and process management.

To use htop, simply enter the following command in your terminal:

![HTOP INSTALLATION COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/d9b13390-c5c6-4664-b561-28c6dc838ad0)

![HTOP COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/5ceae297-431d-435a-8fbc-edbc4bb34d91)

**40. PS COMMAND**
The ps command on Ubuntu (and other Unix-like operating systems) is used to display information about currently running processes on the system. It provides insight into the active processes, including their process IDs (PIDs), resource usage, and other attributes. The ps command is a powerful tool for monitoring and managing processes on the command line.

![PS COMMAND](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/414bb113-78e8-4eb4-b5a0-8401e2eed362)

Learning Linux commands is a fundamental skill for anyone seeking to navigate and manage a Unix-like operating system effectively. With a diverse range of commands at your disposal, you can efficiently perform tasks, monitor system health, and interact with your system at a low level. Understanding commands like ls, cd, cp, mv, rm, ps, and many more empowers you to manipulate files and directories, manage processes, and navigate through the terminal.

Beyond these basics, you can delve into more advanced commands like grep, sed, and awk to manipulate text and data, top and htop for system monitoring, and sudo for executing commands with elevated privileges. Learning how to use package management tools such as apt or yum enables seamless software installation and maintenance.

Command-line skills also extend to file permissions and user management with chmod, chown, useradd, and userdel, allowing you to secure your system and create user accounts efficiently.

Throughout the learning process, it's important to understand that each command serves a specific purpose, and practice is key to mastery. Familiarity with the commands' options, flags, and arguments enhances your ability to adapt them to different scenarios. Combining commands with pipes and redirections unlocks even more powerful capabilities.

In conclusion, mastering Linux commands empowers you to efficiently manage and navigate your system, troubleshoot issues, automate tasks, and become a proficient Linux user. As you continue to explore, experiment, and build on your knowledge, you'll find that the command line is an indispensable tool for unleashing the full potential of your Linux experience.














































































































   

