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


### Permissions & Changing permissions
Linux is a multi-user system.

Files and directories have a permission assigned differently to owner / group / others.

Value "777" means no restrictions on permissions.

Value "755" means the file's owner may read, write, and execute the file. All others may read and execute the file. All others may read and execute the file.

Value "700" means the file's owner may read, write, and execute the file. Nobody else has any rights.

Value "666" means all users may read and write the file.

Value "644" means the owner may read and write a file, while all others may only read the file.

Value "600" means the owner may read and write a file. All others have no rights.

Change the permission of a file “word.txt” that only the owner (you) can read and write,
but all the others (including others in the group) can only read it. No execution is needed
for all users.
