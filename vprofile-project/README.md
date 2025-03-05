# Prerequisites
#
- Vagrant (with hostmanager plugin) for host name to ip mapping
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch

# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

# TODO:
# VM Setup
- Test if all the services are able to conect,
```ping app01 -c 4
- Check if all the vms are running

# SQL SETUP
- First ssh to the db vm
- login as root user
- update all the packages ```dnf update -y
- set the epel release repo ```dnf install epel-release -y
- install mariadb package ```dnf install mariadb-server -y
