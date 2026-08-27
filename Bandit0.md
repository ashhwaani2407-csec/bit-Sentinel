[↑ Up]() | [← Previous]() | [Next →]()

### 
Goal - The goal of this level is for you to log into the game using SSH. 
       The host to which you need to connect is `bandit.labs.overthewire.org`, on port `2220`. 
       The username is `bandit0` and the password is `bandit0`. Once logged in, go to the Level 1 page to find out how to beat Level 1.

### Commands needed to solve this 
* `ssh`

```bash 
man ssh
```

It opens manual page for `man` containing descriptions for different flags.

For Login 
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

This will ask for the password which is `bandit0`. And allow you get logged in for that level.

### Note 
Always save the password which you get in each level as it will be used to login into the next level each time.

[↑ Up]() | [← Previous]() | [Next →]()
