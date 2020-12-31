# Docker Assignment - 2

Create a docker-compose.yaml file for the following multi-container app (Drupal and Postgres)

  Container-1 (front-end):

      front-end image - drupal:8-apache

      container port - 80

      volumes

              - /var/www/html/modules

              - /var/www/html/profiles

              - /var/www/html/themes

              - /var/www/html/sites

  Container-2 (database):

      back-end image - postgres:10

      environment variable - POSTGRES_PASSWORD: example
      
      
# Screenshots

![1](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/Before%20'sudo%20docker-compose%20up%20-d'.png)

![2](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/sudo%20docker-compose%20up%20-d.png)

![3](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/After%20'docker-compose%20up%20-d'.png)

![4](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/Drupal%20set-up%20page.png)

![5](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/Drupal%20installation.png)

![6](https://github.com/venkatsatish468/docker_assignment/blob/main/Images/Drupal%20landing%20page.png)
