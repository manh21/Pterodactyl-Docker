# Pterodactyl Docker

This is template and short guide for setting up Pterodactyl Panel and Wings using Docker. Each server will be running on separate docker-compose file. The panel setup is tailored for traefik reverse proxy.

![Visitor](https://visitor-badge.laobi.icu/badge?page_id=manh21.pterodactyl-docker)

## Usage

### Initalize Panel

- ```bash docker-compose up -d```

- ```bash docker-compose run --rm panel php artisan p:user:make```

### Intialize Wings

- Copy confuguration file from panel to wings

- Generate SSL Certificate using CertBot or Cloudflare. [Guide for Creating SSL](https://pterodactyl.io/tutorials/creating_ssl_certificates.html)

- ```bash docker-compose up -d```

## Credit

Thanks for the amazing tutorial video from Techno Tim [Dockerized Pterodactyl Panel](https://www.youtube.com/watch?v=6Z4PnHTywmM)