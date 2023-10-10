# lecture summary
---

It’s essential to use a version control system for software development 
and other documentation works.
So we make copies, and we need a systematic management system for version control and collaboration.

### I/O Redirection: Standard Input
- Using “>>” appends output to an extising file (if it already exitsts), or create and write to a new file if it doesn’t exist
- You can redirecct input from a file using “<”

*You can mix “<“ and “>” together in a single line.*

### Pipelines |
- Pipeline feeds output of previous command to input of next command
*ex) command1 | command2 | command3 | …*

### Expansion
- Special characters expand its meaning when given to shell commands

---
### Permissions

- Linux is a multi-user system.
- Files and directories have a permission assigned differently to owner / group / others

*changing permissions*
```sh
$ 777
$ 755
$ 700
$ 666
$ 644
$ 600
```
Superuser
- A superuser has all system administation authority.
- Some commands need superuser’s privilleges.
- Put “sudo” before the command if you are a superuser.
- Type “exit” to get out of a superuser session.
