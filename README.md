### My first command creating an app

    $ rails new simple_cms -d mysql
    
### To install gemfile
    
    $ bundle install
    
### To run Rails Server

    $ rails server
        or
    $ rails s
    
### To fix the error no database

    $rake db:create db:migrate

### To put password in MySQL

    mysql>update mysql.user set password = password('your password') where user ="root"; (ENTER)
    
    mysql>FLUSH PRIVILEGES; (ENTER)
    
    mysql>quit (ENTER)