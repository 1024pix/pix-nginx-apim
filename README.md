# Pix Gravitee APIM deployment

Ce dépot contient le code poussé sur Scalingo pour déployer l'instance APIM de Pix.

Il utilise le buildpack nginx de Scalingo.

[buildpack-nginx]: https://github.com/Scalingo/nginx-buildpack

# Usage

Variables d'environement :
 * Choisir la version de nginx `NGINX_VERSION=1.8.0`
 * Définir le host cible `PIX_API_HOSTNAME=api.recette.pix.fr`

Le fichier à configurer est le fichier `nginx.conf.erb`
