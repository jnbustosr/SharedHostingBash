# To could use symfony commands in the shared hosting, with Ionos, use
`php7.4 bin/console cache:clear --env=prod`

# To install composer
To could use the commands in a Symfony project, you should install it inside the folder of the project.
```
@~/my-project
curl -sS https://getcomposer.org/installer | php7.4
```
Then you can do 
```
@~/my-project
php7.4 composer.phar install
```

# To install symfony. Nevertheless, I haven't found it useful.
curl -sS https://get.symfony.com/cli/installer | bash


# The file to setup PATHs is ~/.bash_profile
