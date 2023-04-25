## **Comands inside of folder**

docker-compose build<br>
docker-compose up<br>
docker-compose down<br>

## **Rebuild**
docker compose build --no-cache && docker compose up --force-recreate -d

## **Stop Service**

docker ps <br>
docker stop **the-container-id**<br>
docker rm **the-container-id**<br>

## **Show Logs**

 docker-compose logs -f<br>
 

## **Entrar em bash do container**
docker exec -it **nome do container no compose.yml** bash

## **install make on windows install**

make Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('[https://community.chocolatey.org/install.ps1](https://community.chocolatey.org/install.ps1)')) <br>
choco install make

## LARAVEL

### JWT User
composer require tymon/jwt-auth
php artisan vendor:publish  - selecione o jwt - gera o config
