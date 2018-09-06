# Udacity Web FullStack Project 5
    Fifth project at Udacity Nanodegree Web FullStack.
    This project is a Linux server setup

#Host
    Amazon Lightsail

#IP
    18.215.208.255

#URL
    http://18.215.208.255/ 
    (Did not find a default url for the instance)

#User
    grader
    
#Softwares
    Ubuntu                 18.04.1
    Python                 2.7.12
    PostgreSQL             9.5.14
    Apache                 2.14.18
    Git                    1:2.7.4
    Nmap                   last version
    Finger                 last version
    Libapache2-mod-wsgi    last_version

#Ubuntu
    Commands to update the packages:
        apt-get update
        apt-get upgrade
    
#Python modules
    Flask
    Psycopg2
    Sqlalchemy
    Datetime 
    Flask_oauth 
    Oauth2client

#Application Catalog
    Deployed at:
        /var/www/html

#Settings Changed Files
    Ubuntu:
        sshd_config: 
            Authorized Key Files : uncomment
            Connect with Password: No
    
    Apache:
        000-default.conf:
            define the wsgi path

#PostgreSQL
    Commands used:
        CREATE USER catalog;
        ALTER USER catalog PASSWORD *****;
        CREATE DATABASE catalog OWNER catalog;
    
