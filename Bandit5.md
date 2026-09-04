[↑ Up](README.md) | [← Previous](Bandit4.md) | [Next →](Bandit6.md)

# Bandit Level 4 - Level 5

### Level Goal

The password for the next level is stored in the only human-readable file in the inhere directory.
Tip: if your terminal is messed up, try the “reset” command.

### Commands used to solve this 
* `cd`
* `ls`
* `cat`
* `file`
* `find`


### Use 
First go to the `inhere` directory.
```bash
cd inhere
```
Then Using `ls` will give all the files and directories in the `inhere` directory.
As mentioned earlier, there is only human-readable file. So, reading each file one-by-one will be not optimal.
Instead we will use `file` command and determine the file type and then retrieve the password for the next level.
Here's how to use :

```bash
file ./-file*
```
Here, `*` will ensure that all file types are determined with filename starting with `-file`. Here all filenames are starting with `-file` 
and also the names `-file00`, `-file01` and so on.
Now, one of the file will be of type ASCII Text, this we have to read to retrieve the password.

```bash
cat ./-file07
```
Now, we got the password. Save it to use it for login to next level.


[↑ Up](README.md) | [← Previous](Bandit4.md) | [Next →](Bandit6.md)
