Contient l'application App1 de la boite DM.

1 Nginx
1 php7.0-fpm
1 base de donnée mariaDB (avec persistance busybox - linked to app 2)

Pour recuperrer le projet en local:

git clone https://github.com/cnerot/docker1.git
docker-compose up -d

Port d'acces: 8081
