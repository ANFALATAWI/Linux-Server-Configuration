# Linux-Server-Configuration

This is Project 3 for Udacity’s Full-Stack Nanodegree, the objective is to configure a Linux server and deploy an app on it.

You can find the server running at http://3.121.110.122.xip.io 

The IP of the server: 3.121.110.122 

(It’s running   [Games’ Catalog](https://github.com/ANFALATAWI/Games_Catalog))

You can log in as user grader with the key provided in the instructor notes, using:
`ssh -i [PATH_TO_KEY] grader@3.121.110.122 -p 2200`

## Software Installed On Server
* [Apache](https://httpd.apache.org)
* [Git](https://git-scm.com)
* [mod_wsgi](https://en.wikipedia.org/wiki/Mod_wsgi)
* [Flask](http://flask.pocoo.org)
* [PostgreSQL](https://www.postgresql.org)
* [Google oAuth](https://developers.google.com/identity/protocols/OAuth2)
* [SQLalchemy](https://www.sqlalchemy.org)
and  a number of supporting modules to run the previous Udacity project [Games’ Catalog](https://github.com/ANFALATAWI/Games_Catalog).

## Configurations Made
* Remote login of root user disabled
* Grader user given sudo access
* UFW configured as per rubric
* users required to authenticate using RSA keys
* Configured cron scripts to automatically manage updates
* Virtual host
* Configured PSQL

## Resources & References
* [Udacity-Linux-Configuration](https://github.com/mulligan121/Udacity-Linux-Configuration/blob/master/README.md)
* [SSH: How to access a remote server and edit files](https://www.youtube.com/watch?v=HcwK8IWc-a8)  
