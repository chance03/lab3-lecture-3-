# Lab5 : Lecture Note on Shell Commands
***Note:*** This document is a note of fifth week lecture.

### I/O Redirection : Standard Output
---

Standard ouput is screen.

Redirect output using ">" after a command to create and save the output in a file

Using ">>" appends output to an extising file or create and write to a new file if it doesn't exist.

Command "cat" displays the content of a text file.

---

### I/O Redirection : Standard Output
---

Standard input is from keyboard

You can redirecct input from a file using “<”.

You can mix “<“ and “>” together in a single line.

---

### Pipelines “|"
Pipeline feeds output of previous command to input of next command such as command1 | command2 | command3 | …


### Expansion
Special characters expand its meaning when given to shell commands.


### Backslash
Backslah can be used to ignore line change in command (“enter”), to enter a long command in multiple lines.


### Permissions
Linux is a multi-user system.

Files and directories have a permission assigned differently to owner / group / others.

