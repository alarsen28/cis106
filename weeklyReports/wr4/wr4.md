---
Name: Angel Larsen
Semester: Fall 22
Course: CIS 106 - Linux fund
---
## Practice
[w4](wr4./prac1.png)
[w4](wr4./prac2.png)
[w4](wr4./prac3.png)
[w4](wr4./prac4.png)
[w4](wr4./prac5.png)
[w4](wr4./prac6.png)
[w4](wr4./prac7.png)
[w4](wr4./prac8.png)
[w4](wr4./prac9.png)
[w4](wr4./prac10.png)

## The Filesystem
| Directory | Data Stored In Directory                                                                                                                       |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| bin       | Essential Commands                                                                                                                             |
| dev       | Device File                                                                                                                                    |
| etc       | System configuration files                                                                                                                     |
| home      | User home directories                                                                                                                          |
| media     | Mount point for removable media, such as DVDs and floppy disks                                                                                 |
| opt       | Add-on software packages                                                                                                                       |
| proc      | Kernal information, process control, system hardware information                                                                               |
| srv       | Information relating to services that run on the system                                                                                        |
| usr       | Software not essential for system operation, such as applications                                                                              |
| var       | Dedicated to variables data, such as logs, databases, websites, and temporary spool(e-mail etc.) files that persist from one boot to the next. |


## Navigating the file system

| Command | What it does                                      | Syntax                          | Example        |
| ------- | ------------------------------------------------- | ------------------------------- | -------------- |
| pwd     | prints current working directory                  | `pwd`                           | `pwd`          |
| cd      | changing the current working directory            | cd + destination                | cd /usr/share/ |
| ls      | displaying all the files inside a given directory | ls + option + directory to list | ls -a          |

## Key terms

*Definition of the following terms*

File system: The way files are stored and organized to simplify access to data
Current directory: The directory in which the user is currently working in
parent directory:Always working inside a particular directory and you can move forward to a subdirectory or backwards to the previous directory
the difference between YOUR HOME directory and THE HOME directory: The difference is that your home directory contains a particular user's data and the home directory is that everything comes under the root directory. 
pathname: Indication the location of the file in the filesystem
relative path: The location of a file starting from the current working directory or a directory that is located inside the current working directory.
absolute path: the location of a file startin ga the root of the file system
the commands are used for navigating the filesystem
    pwd
    cd
    ls

