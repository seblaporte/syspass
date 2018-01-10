# Gestionnaire de mots de passes SysPass

> Ce projet contient le fichier docker-compose permettant la mise en place du serveur SysPass avec un reverse proxy Traefik

## Références

- [Site SysPass](https://syspass.org/index-en.html)
- [Projet Github](https://github.com/nuxsmin/sysPass)

## Informations sur le déploiement

Le fichier `.env.sample` doit être renommé en `.env` et valorisé

- __MYSQL_PASSWORD__ : Mot de passe root de la base de données
- __HOSTNAME_TO_REDIRECT__ : Nom de domaine associé à l'application pour la redirection Traefik