 ## Using multiple accounts with git 

    $ git init

    $ git config

* to list all variables
    $ git config --list

### to reset the user/email
    $ git config --global --unset-all user.useConfigOnly
    $ git config --global --unset-all user.name
    $ git config --global --unset-all user.email

* useConfigOnly as TRUE
    $ git config --global --add user.useConfigOnly true

* to set the user/email
    $ git config --global user.email "you@example.com"
    $ git config --global user.name "Your Name"

* to add the user/email
    $ git config --global --add user.name "you@example.com"
    $ git config --global --add user.email "Your Name"

### git config file on the root
/.git/config

### set a new url origin
    $ git remote set-url --add origin [URL]