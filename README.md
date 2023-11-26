# gestion-docker

## Instalación:

Construir contenedor : `docker compose build`  
Levantar contenedor : `docker compose up -d`  
Instalar dependecias de Symfony: `docker-compose exec php composer install`  

### Agregar base de datos:

Importar el archivo gestion.sql (servicio phpmyadmin en localhost:81)  *opcional* 

Si no se importa la BBDD de ejemplo realizar migración o forzar update
