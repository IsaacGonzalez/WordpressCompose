# Wordpress Compose

Proyecto de docker-compose para imagen de wordpress.
El proyecto tiene un archivo `uploads.ini` que permite personalizar el tamaño de subida para el wordpress.
y otras preferencias de PHP.


## Requerimientos

* Docker
* Docker Compose

## Comenzando

1. Clona este repositorio.
1. Posicionate en el folder creado.
1. Ejecuta `docker-compose up -d`
1. Accede a tu [sitio](http://localhost:8) 

## Imagenes

* [MySQL 5.7](https://hub.docker.com/_/mysql/) 
* [Wordpress](https://hub.docker.com/_/wordpress/)

## Persistencia 
Toda la información de la base de datos queda almacenada en un folder llamado `/data` 

