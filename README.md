# Stop Bad Bots Docker Image

Supported architecture: amd64

Built width: PHP 7.3, Apache, MySQL

The Stop Bad Bots is a Free App to block Bad Bots, Crawlers, and Spiders and protect your website.

An Internet Bot, also known as web robot, WWW robot or simply bot, the spider is a software application that runs automated tasks (scripts) over the Internet. Bad bots consume bandwidth, slow down your server, steal your content, and look for vulnerability to compromise your server. Be proactive and Block Bad Bots right away from accessing your server. You can protect any .php site with our app.

For details, visit http://StopBadBots.com

### Getting Started:
1) Download the Docker Compose file link: http://StopBadBots.com/files/docker-compose.zip

2) Download the PHP file stopbadbots.zip link: http://StopBadBots.com/files/stopbadbots-docker.zip

3) Unzip both files on your computer.

4) Upload the file stopbadbots.php to your site root folder

5) Upload the file docker-compose.yml to your server

6) To install, execute docker-compose up -d on the same folder of docker-compose.yml

### Usage:
Include the line below at the top of your index.php file

include_once('stopbadbots.php');

No page limits.

http://YourDomain.com:8080

Login:


- User: admin

- Password: password

(change that asap, look below)

To PHPmyAdmin: http://YourDomain.com:30002

(use to manage the table users and change the password)

- user: db_user

- password: sweetpwd

You can change the port number on the file docker-compose.yml

### Support Site:
http://BillMinozzi.com/support/
