# Inception
Ce projet vise à élargir vos connaissances en administration système en utilisant Docker. Vous allez virtualiser plusieurs images Docker, en les créant dans votre nouvelle machine virtuelle personnelle.

## Checklist
- [x] Docker setup
- [x] Nginx setup
- [x] Wordpress setup
- [x] php-fpm setup
- [x] MariaDB setup

## Install
```bash
sudo apt update -y
sudo apt install -y make
sudo apt install -y docker.io
sudo apt install -y docker-compose
```
```bash
sudo vim /etc/hosts
# add "127.0.0.1 anguinau.42.fr"
```
```bash
link=Skalyaeve/inception
name=inception

git clone https://github.com/$link.git $name
cd $name && sudo make
```
> https://anguinau.42.fr/

## Uninstall
```bash
name=inception

cd $name && sudo make fclean
rm -r $name
```
```bash
sudo vim /etc/hosts
# remove "127.0.0.1 anguinau.42.fr"
```
