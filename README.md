# stack-symfony
Base project with Docker Symfony, PHP 7.4, NGINX Alpine and MySQL 8

Goal<br>
Develop projects without the need to install frameworks.<br>

Requirements<br>
Docker<br>
Composer<br>

Instructions<br>
1-Download the project;
2-Enter the folder, run the command docker-composer up -d, wait for the images to download;
3-Enter the ss-php74 container with the command docker exec -it ss-php74, run the command create composer-project symfony/skeleton;

Database configuration<br>
I change localhost to mysql8-service, port 3306, default username and password or change it as preferred.
