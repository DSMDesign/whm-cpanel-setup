# whm-cpanel-setup
Just some extra stuff to help setup on WHM/Cpanel Servers

### Firstly allow a few features in easyapache4 
    fileinfo
    intl
    pdo
    mssql
    mbstring

### Tweak the php.ini settings
    allow_url_fopen
    execution time 90
    max_input_time 120
    max_input_vars 2000
    memory_limit 256M
    post_max_size 128M
    upload_max_size 64M
    zlib Output On
    
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
