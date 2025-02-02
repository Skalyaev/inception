# <p align="center">inception</p>

> _Ce projet vise à élargir vos connaissances en administration système en utilisant Docker._
>
> _Vous allez virtualiser plusieurs images Docker, en les créant dans votre nouvelle machine virtuelle personnelle._

## Checklist

- [x] Docker setup
- [x] Nginx setup
- [x] Wordpress setup
- [x] PHP-fpm setup
- [x] MariaDB setup

## Usage

```bash
sudo apt update -y
sudo apt install -y make
sudo apt install -y docker.io
sudo apt install -y docker-compose
```

```bash
sudo vim /etc/hosts
# ajoute "127.0.0.1 anguinau.42.fr"
```

```bash
git clone https://github.com/Skalyaeve/inception.git
cd inception && sudo make
# ca va prendre du temps
# ensuite -> https://anguinau.42.fr/
```
