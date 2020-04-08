# bloodbanksystem
```
$ cd htdocs/Projects/bloodbanksystem-master
$ heroku login
$ git init
$ git add .
$ git commit -am"first commit"
$ heroku create
$ git push heroku master
$ heroku addons:add cleardb:ignite
$ mysql -u b8cc36236ace06 -h us-cdbr-iron-east-01.cleardb.net -p heroku_923e2c6e4de1689 < users.sql
Enter password: ********
$ composer update
$ git add .
$ git commit -am "sql commit"
$ git push heroku master
```
## Steps for setup
Install Xampp


1. Open Xampp Control Centre and start Apache and MySQL


2. Download this file in C:\xampp\htdocs folder and "extract here"


3. goto localhost\bloodbanksystem-master to open the php files


4. goto localhost\phpmyadmin to import sql file
  4.1. on the left side there is list of database select "New"
  4.2. name the database "users" and scroll down and click "go" (creates a database named users)
  4.3. seltec your database from the list.
  4.4. on the navigation bar above find "Import"
  4.5. locate your database (for me its C:\xampp\htdocs\bloodbank-master\users.sql) and execute.
  4.6  now your database is linked


5. goto localhost\bloodbanksystem-master to access the site


6. to host the site on cloud follow the links below


## Steps for cloud hosting 
https://scotch.io/@phalconVee/deploying-a-php-and-mysql-web-app-with-heroku



## steps to find clearDB host, password, user and DBname
https://scotch.io/@phalconVee/using-mysql-on-heroku

## Working app can be found at
https://powerful-ridge-48280.herokuapp.com/index.php
