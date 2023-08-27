# Docker Boilerplate

Setup and run docker for laravel webapp

## Docker Cmd

- `docker-compose build` , build and pull necessary images
- `docker-compose build --no-cache --force-rm` , scrape and rebuild image
- `docker-compose up -d` , live up container in detached mode
- `docker-compose stop` , stop container
- `docker-composer down -v` , remove container and remove created volumes
- to run command in container bash
- `docker exec -it {network_name} bash`
- in this case
- `docker exec -it php bash`
- to run cli command outside of container
- `docker exec {network_name} bash -c "php artisan migrate"`
- `docker exec {network_name} bash -c "php artisan db:seed"`

## Reference

- https://www.youtube.com/watch?v=IvDya1PibV4
