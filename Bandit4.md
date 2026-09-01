# Bandit Level 3 - Level 4

[↑ Up](README.md) | [← Previous](Bandit32.md) | [Next →](Bandit5.md)

### Level Goal

The password for the next level is stored in a hidden file in the inhere directory.

### Commands used to solve this 
* `cat`
* `file`
* `find`

### Use 
```bash
file inhere
```
determines file type.

```bash
ls -a
```
lists all hidden files in the directory. You will encounter a hidden file named `.hidden`(This is the required file) .

```bash
file .hidden
```
Gives the type of `.hidden` i.e., ASCII Text.

Then read that hidden file.
```bash
cat .hidden
```
This will give the required password for the next level to login.


[↑ Up](README.md) | [← Previous](Bandit3.md) | [Next →](Bandit5.md)
