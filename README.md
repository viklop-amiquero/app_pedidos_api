                                  APP PEDIDOS API
                               -----------------------

Proyecto creado con la versión de laravel "^11.31"

Herramientas instaladas localmente:
-------------------------------------------------
> Composer version 2.7.4
> PHP version 8.3.6 
> mysql


Pasos para correr el proyecto
--------------------------------------------

1. Clonar el proyecto
2. Instalar las dependencias "composer install" 
2. Crear una conexión desde cualquier DBMS (DataGrip, Mysql Workbench), asegurarse que este corriendo localmente "mysql".
4. Crear el archivo ".env" y copiar todo de .env-example, reescribir lo siguiente:

                    ####ojo: 127.0.0.1 ó "localhost"
                    el user y password, es el usuario y contraseña de "mysql". 

                    DB_CONNECTION=mysql
                    DB_HOST=127.0.0.1 
                    DB_PORT=3306
                    DB_DATABASE=app_pedidos
                    DB_USERNAME=root
                    DB_PASSWORD=root

5. En caso haya un error que no encuentre la base de datos "app_pedidos", crear el "schema" de nombre "app_pedidos" en el DBMS.
