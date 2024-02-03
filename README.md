# Inception

*This project consists in having you set up a small infrastructure composed of different services under specific rules.*
*The whole project has to be done in a virtual machine. You have to use docker compose.*

## Checklist
- [x] Docker setup
- [x] Nginx setup
- [x] Wordpress setup
- [x] php-fpm setup
- [x] MariaDB setup

## Usage:
```sh
sudo nano /etc/hosts # add "127.0.0.1 anguinau.42.fr"
```
```sh
sudo apt install docker.io docker-compose
git clone git@github.com:Skalyaeve/inception.git
cd inception
sudo make
```
```sh
sudo make fclean
sudo nano /etc/hosts # remove "127.0.0.1 anguinau.42.fr"
```
