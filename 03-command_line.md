# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 
* show current working directory path: pwd
* creating a directory: mkdir directory_name
* deleting a directory: rmdir directory_name
* creating a file using `touch` command: touch filename
* deleting a file: rm filename
* renaming a file: mv filename1 filename2
* listing hidden files: ls -a
* copying a file from one directory to another: cp directory1/filename directory2
* moving file: mv filename directory/
* Find(search) words in files: grep word filename
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 
* ls : list all the files and directories in working directory  
* ls -a  : lists all contents including hidden files and directories
* ls -l  : lists all contents of a directory in long format
* ls -lh : lists files in human readable format
* ls -lah: lists all the files in human readable format including hidden files.
* ls -t  : orders the files and directories based on time they were last modified
* ls -Glp : lists the files in long format but exclude owner name,and display directories with /.

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -a,ls -t,ls -g,ls -r,ls -l

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 'xargs' reads data from standard input and execute the commands one or more times based on the standard input. xargs can be used to find different types of file in a directory like ".txt",".log",".tmp" files.

 

