# kubernetes-lab3

In this lab you are tasked with creating a running WordPress application.

[WordPress][wordpress] is a commonly used Blog and CMS engine that has multiple tiers.

The WordPress application we are going to deploy has two major components: A MySQL database that will be used to store persistent data and the actual WordPress container. The wordpress container uses an apache webserver, PHP, and other dependencies to run.

For this lab you should have multiple manifest files that fulfill the following requirements:

Requirements - 

- Deployment
- PVC
- DB Password as a Secret
- StatefulSet of the DB
- DB exposed as a service
- Wordpress exposed as a service


[wordpress]: https://wordpress.org/
