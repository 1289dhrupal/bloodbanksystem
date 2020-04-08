# bloodbanksystem
'''
$y cd htdocs/Projects/bloodbanksystem-master
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
'''
