
**Just a bunch of shortcuts from my `~/.bashrc` file to jumpstart after installing an unix distro**


# Environmental Commands

### Open up with default editor to modify
`alias bashrc='sudo subl ~/.bashrc'`

### Add an "new host" `alias for new project
`alias editvh='sudo subl /etc/apache2/sites-available/workspace.tech.conf;sudo subl /etc/hosts'`

### restart apache server
`alias resapa='sudo systemctl restart apache2'`

### give permission 777 to all phperana subfolder
`alias php777='sudo chmod 777 -R /var/www/phparena'`

### give permission 755 to all phperana subfolder
`alias php755='sudo chmod 755 -R /var/www/phparena'`

### activate v 2.7 env python
`alias v27='source /home/shakeel/workspace/pyarena/envs/env27/bin/activate'`

### activate v 3.5 env python
`alias v35='source /home/shakeel/workspace/pyarena/envs/env35/bin/activate'`

### activate v 3.5 env python
`alias sele35='source /home/shakeel/workspace/pyarena/envs/sele35/bin/activate'`

### deactivate venv python
`alias da='deactivate'`

### composer dump-autoload
`alias comda='composer dump-autoload'`

### update the repository
`alias update='sudo apt-get update'`

### run pycharm professional
`alias pycharm='sh /opt/pycharm-2020.1/bin/pycharm.sh'`

### access to aws shaks.pem
`alias shaksaws='ssh -i ~/.pem/shaks.pem ubuntu@ec2-3-87-48-202.compute-1.amazonaws.com'`

### using valet run project in Virtual
`alias valet='~/.composer/vendor/bin/valet'`

# Workspaces Root Commands

### navigate to workspace/python directory

`alias phparena='cd /var/www/phparena/'`

`alias pyarena='cd /home/shakeel/workspace/pyarena/'`

`alias nodearena='cd /var/www/nodearena/'`

`alias railsarena='cd /var/www/railsarena/'`

### start artisan server of offerGenie
`alias offer='php /var/www/phparena/offergenie/artisan serve'`



# Laravel Commands 

### using lumen engine to create new laravel/lumen project
`alias lumen='~/.composer/vendor/bin/lumen'`

### using lumen engine to create new laravel/laravel project
`alias laravel='~/.composer/vendor/bin/laravel'`

### php artisan to upload data to db from CSV
`alias laraup='php artisan db:update'`

### php artisan to upload data from db to CSV
`alias laradown='php artisan db:generate --csv'`

### php artisan to upload data from db to CSV & to db from CSV
`alias larasync='php artisan db:generate --csv;php artisan db:update'`

### clear cache from all angle of laravel
`alias laracache='php artisan config:clear;php artisan cache:clear;`
`php artisan route:clear;php artisan view:clear'`

### clear cache from all angle of laravel
`alias larawash='php artisan config:clear;php artisan cache:clear;php artisan route:clear;php artisan view:clear;composer dump-autoload'`

### php artisan serve
`alias lserve='php artisan serve'`

### php artisan serve
`alias lmigrate='php artisan migrate'`



# Django Commands

### migrate django
`alias dmigrate='python manage.py migrate'`

### serve django
`alias dserve='python manage.py runserver'`

### create super user
`alias dsuper='python manage.py createsuperuser'`

### open shell
`alias dshell='python manage.py shell'`

### update static
`alias dstatic='python manage.py collectstatic'`

### test django
`alias dtest='python manage.py test'`

### create new app
`alias dapp='python manage.py startapp'`


# NodeJS Commands 

### npm run dev
`alias rund='npm run dev'`

### npm run production
`alias runp='npm run production'`

### npm run watch
`alias runw='npm run watch'`



# Project Based Shortcut Commands

### cd to TURN_FAST_WEB directory
`alias turn='cd /var/www/phparena/TURN_FAST_WEB'`

### run the server TURN_FAST_WEB
`alias turnfast='cd /var/www/phparena/TURN_FAST_WEB;php artisan serve'`

### cd to the server ForeTravel
`alias fore='cd /var/www/phparena/foretravel;php artisan serve'`

### cd to the server MHSRV
`alias mhsrv='cd /var/www/phparena/mhsrv'`

### run the socket server TURN_FAST_WEB
`alias socket='node socket_app/socket.js'`

### Jumpstart to donation project
`alias donation='v27;pyarena;cd donation_django_angular/donation;python manage.py runserver'`

