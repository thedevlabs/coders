Macs
======

Things you will need to code in an web stack

* [MAMP](http://www.mamp.info/en/) [easy mysql/web]
* [Homebrew](http://brew.sh/) Note: Homebrew will ask you to install Xcode. Go ahead and do this when prompted.


### Git Keys
* [ssh keys](https://confluence.atlassian.com/display/BITBUCKET/Set+up+SSH+for+Git)
* [ssh keys-github](https://help.github.com/articles/generating-ssh-keys/)


### Mac Workstation

- brew paths
- set paths for PATH, NODE_PATH  in ".bash_profile"
- reload or quit and restart Terminal
- alias the correct active php and mysql

```
export NODE_PATH="/usr/local/lib/node_modules"
export PATH="/usr/local/bin:/usr/local/sbin:/usr/local/mysql/bin:/usr/local/share/npm/bin:$PATH"

alias phpmamp="/Applications/MAMP/bin/php/php5.6.7/bin/php"
alias mysqlmamp='/Applications/MAMP/Library/bin/mysql'
```

###  Brews
* mysql
* elasticsearch
* geoip
* sqlite
* ssh-copy-id
* node
* redis
* mongodb


```
brew install mysql elasticsearch geoip sqlite ssh-copy-id node redis mongodb
```

### Central folder for all dev projects
Create a folder where all of your repositories will exists.

```
mkdir /Users/{your username}/dev
```

