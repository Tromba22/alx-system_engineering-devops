# Shell, init files, variables and expansions


### Resources

Read or watch:


* [Expansions](http://linuxcommand.org/lc3_lts0080.php)

* [Shell Arithmetic](https://www.gnu.org/software/bash/manual/html_node/Shell-Arithmetic.html)

* [Variables](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_02.html)

* [Shell initialization files](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html)

* [The alias Command](http://www.linfo.org/alias.html)

* [Technical Writing]


## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), without the help of Google:



### General

What happens when you type ```diff - $ ls -l *.txt in red ```

### Shell Initialization Files

What are the ### ```diff - /etc/profile in red ``` file and the ```diff - /etc/profile.d in red ``` directory

What is the ```diff - ~/.bashrc in red ``` file

### Variables

What is the difference between a local and a global variable

What is a reserved variable

How to create, update and delete shell variables

What are the roles of the following reserved variables: HOME, PATH, PS1

What are special parameters

What is the special parameter ```diff -$? in red ```?

### Expansions

What is expansion and how to use them

What is the difference between single and double quotes and how to use them properly

How to do command substitution with $() and backticks

### Shell Arithmetic

How to perform arithmetic operations with the shell

### The <span style="color: green"> alias </span> Command

How to create an alias

How to list aliases

How to temporarily disable an alias

Other help pages

How to execute commands from a file in the current shell

Copyright - Plagiarism

You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.

You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.

You are not allowed to publish any content of this project.

Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements

General

Allowed editors: vi, vim, emacs

All your scripts will be tested on Ubuntu 20.04 LTS

All your scripts should be exactly two lines long ($ wc -l file should print 2)

All your files should end with a new line (why?)

The first line of all your files should be exactly #!/bin/bash

A README.md file, at the root of the folder of the project, describing what each script is doing

You are not allowed to use &&, || or ;

You are not allowed to use bc, sed or awk

All your files must be executable
