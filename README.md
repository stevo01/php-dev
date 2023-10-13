# environment for php development / with debugging

this projekt allows you to debug php 8.1 projects 
with vscode

## build and start container
docker compose build
docker compose up -d

## build and stop container
docker compose down

## build image and restart container
docker compose down && docker compose up -d --build

## start shell in php container
docker compose exec php8 bash 

## set valid owner for files in gtml directory
sudo chown stevo:stevo volumes/joomla -R

# Bookmarks
* https://github.com/thecodeholic/php-mvc-framework
* https://youtu.be/it7JQKPfWTU?si=Dn2FUbsCge_q110V