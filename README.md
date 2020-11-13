# PRÁCTICA 3 - Arquitectura de una aplicación web LAMP en dos niveles

#### LO QUE VAMOS A HACER: 

- Instalar 2 máquinas Ubuntu Server (última versión)
- En una de ellas instalamos Apache y PHP
- En otra instalamos MySQL Server
- Hacer que entre ellas se conecten
- Configurar archivos de configuración en MySQl

### ESTRUCTURA DE LA RED

![](Imágenes/red.png);

> - Una capa de front-end, que será pública

> - Una capa de back-end, que será privada


 ################################################

## INSTALACIÓN

### Front-end:

Lo requisitos para esta máquina serían

- Abrir puerto SSH
- Abrir puerto HTTP
- Abrir puerto HTTPS
- Abrir puerto MySQL/Aurora

En ella creamos nuestra front-end.sh y haremos nuestros script escpedífico para esta máquina:

- Instalación de Apache
- Instalación de PHP
- Instalación de phpMyAdmin
- Instalación de GoAccess
- Instalación de Adminer 

:exclamation: Tendremos que configurar el archivo config.inc.conf 

:exclamation: Además de configurar el archivo config.php

Esto se hace para que entre las máquinas frond-end y back-end se vean entre ellas

### Back-end

Los requisitos para esta máquina serían

- Abrir puerto SSH
- Abrir puerto MySQL/Aurora

En ella crearemos nuestro back-end.sh y haremos nuestro script específico para esta máquina:

- Instalación de MySQL Server 

:exclamation: Configuramos el archivo mysqld.conf para que conecte con el front-end 

Creados nuestras máquinas y script para fornt-end y back-end ejecutamos. 

:smile_cat:
