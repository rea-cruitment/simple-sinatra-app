REA site performance pre-interview task
=============





Package up and deploy this simple hello world application
-------
- package up the following application within this repo 
- deploy this application onto a vanilla OS image (Centos/Fedora/Ubuntu/Debian/RHEL)
- use apache modpassenger  / unicorn nginx or whatever you like to serve up the application on port 80


Provision a new application server
-------
- write configuration as code recipes in Chef / puppet / ansible / babushka  / shell scripts to
-- provision a web server with ruby to deploy the packaged Sinatra application
-- ensure that the server is locked down and secure
