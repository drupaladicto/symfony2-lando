# symfony2-lando
Symfony 2 Demo Application with Lando

Descripción
----------------
Proyecto Symfony 2 Standard Edition de Ejemplo, ideal para comenzar a trabajar utilizando Lando.

#Archivos:

.lando.yml - Modificado para funcionar con Composer 1, evitando errores de compatibilidad con Symfony.

Symfony 2 - Estructura Standard descargada utilizando Composer.


Instalación
----------------
1.- Clonar el repositorio

2.- Arrancar el lando, con el comando

    lando start

3.- Descargar las dependencias conel Composer

    lando composer update
	
4.- Una vez terminado el proceso acceder a la página de bienvenida, añadiendo a la url app_dev.php:

http://symfony2-app.lndo.site/app_dev.php
	
## Para corregir posibles fallos, ejecutar el comando:

	lando rebuild