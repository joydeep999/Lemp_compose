# Introduction

* Contains a basic docker compose file for lemp stack.

* Pulls latest images of PHP, MySql, Nginx from the docker hub and runs them as containers on executing **docker-compose -f lemp_stack.yaml up**


# How it works

* Runs all the containers inside a same network so that they could communicate with each other using their names.

* Enviornment variables for the MySql are defined such as user name and password.

* Named voulume for MySql is configured which is best practice for the Prod Enviornments.

* For the nginx.conf configuration you can refer the Nginx_configuration repository which consists of a nginx.conf file and and a commands.txt which consists of the commands which should be applied for the changes to reflect on Nginx.


# Notes

* Please note that this is not only it, I am working on making the compose file more robust.
