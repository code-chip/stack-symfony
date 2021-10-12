# stack-symfony
Base project with Docker Symfony, PHP, Apache and MySQL

Requirements
Docker
Composer

Instructions
1-Download the project;
2-Enter the folder, run the command docker-composer up -d, wait for the images to download;
3-Enter the ss-php74 container with the command docker exec -it ss-php74, run the command create composer-project symfony/skeleton;

Database configuration
I change localhost to mysql-service, port 3306, default username and password or change it as preferred.