# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- JSP
- Tomcat
- MySQL
- Memcached
- RabbitMQ

## Database Configuration

This project uses MySQL as the backend database to store application data.

A pre-configured SQL dump file is included in the project to simplify setup:
src/main/resources/db_backup.sql

To initialize the database, import the dump file using the following command:

mysql -u <username> -p accounts < db_backup.sql


# VProfile-Multi-Tier-Web-Application-Deployment
Deployed a Java-based multi-tier web application across multiple VMs using Vagrant and VirtualBox, implementing services like Nginx, Tomcat, MySQL, Memcached, and RabbitMQ. Automated setup using Infrastructure as Code to simulate a scalable and production-like environment.


## Architecture

This project follows a multi-tier architecture:

- Web Layer: Nginx
- Application Layer: Tomcat
- Cache Layer: Memcached
- Messaging Layer: RabbitMQ
- Database Layer: MySQL
