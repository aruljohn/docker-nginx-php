# Skeleton setup for Nginx and PHP on Docker

To run a bare minimum setup of Nginx and PHP on Docker, first install Docker Compose.

To start Docker, run this command:

    docker-compose up -d

You will be able to access index.php by going to http://localhost:8080

The HTML and PHP files will be stored in `html`.

To stop Docker, run this command:

    docker-compose down
