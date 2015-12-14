REA Site Performance & Availability Engineer pre-interview task
=============

Provision a new application server and deploy the application in this Git repository
-------
- write configuration-as-code recipes (using your preferred orchestration software) to:
  - configure an OS image (your choice) appropriately.
  - deploy the provided application.
  - make the application available on port 80.
  - ensure that the server is locked down and secure.
- provide documentation.

Expected output
-------------
- scripts and/or configuration that we can use to deploy the application.
- documentation.

To get the provided application working locally
=============

    git clone git://github.com/tnh/simple-sinatra-app.git
    shell $ bundle install
    shell $ bundle exec rackup
