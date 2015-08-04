### My first command creating an app

    $ rails new simple_cms -d mysql
    
### To install gemfile
    
    $ bundle install

#### Open gemfile

    You can edit the gemfile comment some of the packages
    then run bundle install 

### To run Rails Server (WebServer)

    $ rails server
        or
    $ rails s

##### **localhost:3000**
    
### To fix the error no database

    $rake db:create db:migrate

### To put password in MySQL

    mysql>update mysql.user set password = password('your password') where user ="root"; (ENTER)
    
    mysql>FLUSH PRIVILEGES; (ENTER)
    
    mysql>quit (ENTER)
    
### Generate Controller

    $ rails generate controller demo index
    
### To view the list
    
    $ rails generate