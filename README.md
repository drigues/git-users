* $ git init

* $ git config

* to list all variables
$ git config --list

* to reset the user/email
$ git config --global --add user.useConfigOnly true
$ git config --global --unset-all user.name
$ git config --global --unset-all user.email

* to set the user/email
$ git config --global --add user.name ""
$ git config --global --add user.email

* git config file on the root
/.git/config