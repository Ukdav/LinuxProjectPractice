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

The tar command in Ubuntu's terminal is used for creating and manipulating archive files, often referred to as "tarballs." Tarballs are typically used to store and compress multiple files and directories into a single archive file, making it easier to transfer or backup a group of files while maintaining their directory structure and permissions.

The name "tar" stands for "tape archive," as the command was originally designed for archiving files onto magnetic tape drives. However, nowadays, it's commonly used for creating and extracting archive files on various storage mediums.

The basic syntax of the tar command is as follows:
![TAR COMMAND 1](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/a9438cd2-b80f-4f9e-87bd-cc188441988d)
![TAR COMMAND2 TO EXTRACT](https://github.com/Ukdav/LinuxProjectPractice/assets/139593350/f615ecf2-aa2d-435a-b714-e334b2933c73)



















































   

