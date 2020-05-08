## Using multiple accounts on git 

### to start git on root
    $ git init

### to list all variables
on config list you all variables from repository and user

    $ git config --list

### to REMOVE the user/email
    $ git config --global --unset-all user.name
    $ git config --global --unset-all user.email
 
    $ git config --global --unset-all user.useConfigOnly

### useConfigOnly as TRUE
    $ git config --global --add user.useConfigOnly true

### to SET the user/email
    $ git config --global user.name "Your Name"
    $ git config --global user.email "you@example.com"

### to ADD the user/email
    $ git config --global --add user.name "Your Name"
    $ git config --global --add user.email "you@example.com"

### git config file on the root
/.git/config

### to ADD a new url origin repository
first you need to add the new url repository to delete the previous one

    $ git remote set-url --add origin [URL]

### to DELETE url origin repository
    $ git remote set-url --delete origin [URL]
