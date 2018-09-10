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

> > 1. show current working directory path: pwd
2. creating a directory: mkdir
3. deleting a directory: rmdir 
4. creating a file using touch command: touch [filename]
5. deleting a file: rm [filename]
6. renaming a file: mv [filename_old] [filename_new]
7. listing hidden files: ls -ld.?*
8. copying a file from one directory to another: cp dir1/[filename] dir2
9. change file permissions: chmod options permissions [filename]
10. show contents of file: cat [filename] 

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`: lists directory contents of files and other directories   
`ls -a`  : lists all files including hidden files 
`ls -l`  : lists all files with long format and shows permissions
`ls -lh`  : lists long format with readable file size
`ls -lah`  : lists using long listing format, all entries starting with., and human readable files 
`ls -t`  : sorts the list by time and date
`ls -Glp`: don't print group names, use long format, append to directories∑


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 'ls -d': displays only directories
'ls -r': displays in reverse order
'ls -x': displays in rows across screen
'ls -1': displays each entry on a line
'ls -p': displays directories with / 

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command line utility for building an execution pipeline from standard input. e.g. 
echo 'one two three' | xargs mkdir

creates 3 directories: one, two, three
