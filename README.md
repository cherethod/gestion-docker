# gestion-docker

## Instalación:

Construir contenedor : `docker compose build`  
Levantar contenedor : `docker compose up -d`  
Instalar dependecias de Symfony: `docker-compose exec php composer install`  

Al realizar las pruebas para verificar que al compartir el 'proyecto' todo fuera correcto en ocasiones he tenido problemas.   

![imagen](https://github.com/cherethod/gestion-docker/assets/9266765/7febd511-c330-40c8-8691-631a9bbb1b01)

Por ello adjunto la carpeta vendor mediante un enlace de Drive:  

https://drive.google.com/file/d/1Bmq5OzObMVnI2NhoQtB5MucGy1E_Q0Py/view?usp=sharing  



### Pruebas de funcionamiento:  

![imagen](https://github.com/cherethod/gestion-docker/assets/9266765/e7ca12c3-31a3-4d2a-9560-83cc4ec9848e)  

![imagen](https://github.com/cherethod/gestion-docker/assets/9266765/d01e3b42-9508-4718-bdb4-bb77ecd5c614)

![imagen](https://github.com/cherethod/gestion-docker/assets/9266765/84c2d3ca-2d7a-4f3a-add2-894c591687e3)



### Agregar base de datos:

Importar el archivo gestion.sql (servicio phpmyadmin en localhost:81)  *opcional* 

Si no se importa la BBDD de ejemplo realizar migración o forzar update (creo ;P)
