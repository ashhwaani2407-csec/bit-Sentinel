# Bandit Level 2 - Level 3

[↑ Up](README.md) | [← Previous](Bandit2.md) | [Next →](Bandit4.md)

### Level Goal
The password for the next level is stored in a file called `--spaces in this filename--` located in the home directory

### Commands needed to solve this

* `ssh`
* `ls`
* `cat`

### Use 
```bash
ls
```
This will give `spaces in this filename`.

But using simple `cat` command.
```bash
cat spaces in this filename
```
It will give - `No such file or directory` error.

We will have to use
```bash
cat "spaces in this filename"
```
It will return the required password for login into the next level.


[↑ Up](README.md) | [← Previous](Bandit2.md) | [Next →](Bandit4.md)
