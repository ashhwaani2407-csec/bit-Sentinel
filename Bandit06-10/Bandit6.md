[↑ Up](README.md) | [← Previous](Bandit4.md) | [Next →](Bandit6.md)

# Bandit Level 5 → Level 6

### Level Goal

The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

* human-readable
* 1033 bytes in size
* not executable

### Commands used to solve this 
* `cd`
* `ls`
* `cat`
* `file`
* `find`


### Use 
First go to the `inhere` directory using `cd` command.
Then, using `ls` we found that there number of directories and nested directories, making it difficult to find out the desired file manually.
So, we will use commands to find it easily.
here we will use,

```bash
find -size 1033c
```
This will return us the required file. Now we will have to read it and retrieve the password for the next level to login.

```bash
cd maybehere07
cat file2
```



[↑ Up](README.md) | [← Previous](Bandit4.md) | [Next →](Bandit6.md)
