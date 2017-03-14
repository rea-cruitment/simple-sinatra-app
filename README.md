REA Systems Engineer practical task
===================================

Provision a new application server and deploy the application in this Git repository
------------------------------------------------------------------------------------
- Write configuration-as-code recipes (using your preferred orchestration software) to:
  - Create the server (can be local VM or AWS based)
  - Configure an OS image (your choice) appropriately.
  - Deploy the provided application.
  - Make the application available on port 80.
  - Ensure that the server is locked down and secure.
- Provide documentation:
  - Instructions for the reviewer which explain how your code should be executed
  - Requirements for running. (AWS account? Base images? Other tooling pre-installed?)
  - Explanation of assumptions and design choices.

Expected output
---------------
- Scripts and/or configuration that we can use to deploy the application.
- Documentation.

Submission format
-----------------
Preferred option is a link to public git repository with your solution. We understand you may not want the solution associated with your public profile, feel free to create a new github account for the submission. Alternatively a [git-bundle](https://www.kernel.org/pub/software/scm/git/docs/git-bundle.html) or zip archive are acceptable.


To get the provided application working locally
===============================================

    git clone git@github.com:rea-cruitment/simple-sinatra-app.git
    shell $ bundle install
    shell $ bundle exec rackup


How we review the submission
============================
We rate the solution and documentation against all the following categories:

- Simplicity
- Code / documentation layout
- Ease of deployment
- Idempotency
- Security
- Anti-fragility

The documentation is as important as the scripts. We are looking to understand why you chose a certain solution and what trade offs it has.

Documenting any known short comings of a solution and the reasons why will be seen as more positive than unmentioned issues. 

