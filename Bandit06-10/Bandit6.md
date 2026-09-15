[↑ Up](README.md) | [← Previous](Bandit5.md) | [Next →](Bandit7.md)

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
But the catch is that the required file is hidden file( as it is suffixed with `.` i.e., filename is `.file2`).
So, first check using `ls`,

```bash
cd maybehere07
ls -a
```
This will list all the files including hidden files.

Now, we will verify that whether it satisfies the conditions as listed in the Level Goal.
First, human-readable

```bash
file .file2
```

This will return the file type as `ASCII Text, with very long lines`.
Now, Second i.e., non-executable

```bash
ls -al
```

This will return file and directories with with root, group and user and their permissions to read, write and execute the files and directories.
Now, after confirming, Use the `cat` to read that file

```bash
cat .file2
```

This will return the contents of the file. Save the retrieved password to login into next level.

[↑ Up](README.md) | [← Previous](Bandit5.md) | [Next →](Bandit7.md)
