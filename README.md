# Docker Assignment - 2


Create a docker-compose.yaml file for the following Multi-container app (Drupal postgres)

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
