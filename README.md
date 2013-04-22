REA site performance pre-interview task
=============


Provision a new application server and deploy the following application
-------
write configuration as code recipes in chef / puppet / ansible / babushka  / shell scripts to
- deploy this application onto a vanilla OS image (Centos/Fedora/Ubuntu/Debian/RHEL)
- use apache modpassenger  / unicorn nginx or whatever you like to serve up the application on port 80
- provision a web server with ruby to deploy the packaged Sinatra application
- ensure that the server is locked down and secure
- deploy the hello world application


Expected output
-------------
- chef / puppet  / ansible / babushka  / shell scripts that we can use to deploy the following application

 


To get this application working locally
=============

    git clone git://github.com/tnh/simple-sinatra-app.git
    shell $ bundle install
    shell $ bundle exec rackup

Mod passenger:
http://www.modrails.com/documentation/Users%20guide%20Apache.html

Unicorn nginx:
http://sirupsen.com/setting-up-unicorn-with-nginx/

