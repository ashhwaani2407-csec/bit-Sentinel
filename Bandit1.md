# Bandit Level 0 → Level 1

[↑ Up](README.md) | [← Previous](Bandit0.md) | [Next →](Bandit2.md)

### Level Goal 
The password for the next level is stored in a file called `readme` located in the home directory.
Use this password to log into `bandit1` using SSH. Whenever you find a password for a level, use SSH (on port `2220`) to log into that level and continue the game.

### Commands needed to solve this

* `ssh`
* `ls`
* `cat`

As mentioned, the password for next level is stored in the file called `readme`, we need to read it using `cat`.
So, use 
```bash
ls
```

This will list all the files present in the directory in which we are present.

Then use,
```bash
cat readme
```

You will get the password for the next level. 
So, save it as we will use it as password for login to next level.

[↑ Up](README.md) | [← Previous](Bandit0.md) | [Next →](Bandit2.md)
