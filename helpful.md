# whm-cpanel-setup
Just some extra stuff to help setup on WHM/Cpanel Servers

### Composer now comes pre-installed but may need an update
    composer self-update
    
### Add Ruby
    sudo yum install ruby
    sudo yum install rubygems
    sudo yum install ruby-devel
    sudo gem update --system
    
### Add Compass (SASS)
    sudo gem install compass

### Add Node And NPM
    sudo yum install nodejs
    
### Check for versions
    npm -v
    ruby -v
    sass -v etc..
    
## Install some nice plugins to whm

ConfigServer do some nice additional plugins over at
https://www.configserver.com/cp/csf.html

Also NCDHost have a couple
https://www.ndchost.com/
