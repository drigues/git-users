## Using multiple accounts with git 

### to start git on root
    $ git init


### to list all variables
    $ git config --list


### to REMOVE the user/email
    $ git config --global --unset-all user.name
    $ git config --global --unset-all user.email
 
    $ git config --global --unset-all user.useConfigOnly


### useConfigOnly as TRUE
    $ git config --global --add user.useConfigOnly true


### to SET the user/email
    $ git config --global user.email "you@example.com"
    $ git config --global user.name "Your Name"


### to ADD the user/email
    $ git config --global --add user.name "you@example.com"
    $ git config --global --add user.email "Your Name"


### git config file on the root
/.git/config

### set a new url origin
    $ git remote set-url --add origin [URL]

### set a delete url origin
    $ git remote set-url --delete origin [URL]