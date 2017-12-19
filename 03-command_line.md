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
1. $ pwd, show current working directory 
2. $ mkdir, create a directory
3. $ rm -r, delete a directory and all of its child directories
4. $ touch, create a file

5. $ rm, remove a file
6. $ cp, rename or copy a file 
7. $ ls -a, list all files including hidden ones 
8. $ cp, copy a file from one folder to another
9. $ *, wildcard
10.$ grep, global regular expression print, it searches files for lines that match a pattern and returns the results 
---

### Q2.  List Files in Unix   

What do the following commands do:  
1. `ls` list all files in the current working directory  
2. `ls -a`  list all files including hidden files in the current working folder
3. `ls -l`  list all files in long forms 
4. `ls -lh` list all files in long formats with readable file sizes 
5. `ls -lah` list all files including hiddenfiles with readable file sizes  
6. `ls -t`  list contents sorted by time and date
7. `ls -Glp` list long format directories with / appended to the end without user group names


> > 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

1.ls -1, displays each entry on a line 
2.ls -c,displays files by file timestamp
3.ls -r, display files in reverse order 
4.ls -u, display files by the file access time
5.ls -x, display files as rows across the screen 
 

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.
xargs takes a standard input and converts it into an argument or command
> > $\ls | grep Cases | xargs touch


 

