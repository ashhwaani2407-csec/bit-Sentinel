# Bandit Level 1 → Level 2
[↑ Up](README.md) | [← Previous](Bandit2.md) | [Next →](Bandit3.md)


# Level Goal
The password for the next level is stored in a file called `-` located in the home directory.

### Commands needed to solve this
* `ls`
* `cat`

### Use 
```bash
ls
```
lists all the files in the directory in which we are present.

```bash
cat -
```
Using this command we will not get the desired output as it takes input and gives the same input text as output in the cli.

### So use this
```bash
cat ./-
```
This will give the desired password as output. Copy it and save it, to login into the next level.


[↑ Up](README.md) | [← Previous](Bandit2.md) | [Next →](Bandit3.md)
