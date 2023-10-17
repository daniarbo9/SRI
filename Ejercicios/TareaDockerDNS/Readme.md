# Tarea DNS
### Primero hay que crear el docker compose y los archivos de configuracion que ves a continuacion:

![Alt text](imagenes/c1.png)

### Para empezar vamos a configurar:
## -docker-compose.yml
A continuacion imagen de un archivo de docker-compose.yml 

![Alt text](imagenes/c2.png)
##
### Una vez tengamos el .yml con los servicios que necesitemos tenemos que configurar los archivos que están el la carpeta conf

![Alt text](imagenes/c3.png)

##### Estas son las zonas por defecto

![Alt text](imagenes/c4.png)

#### Esta es la zona que voy a crear

![Alt text](imagenes/c5.png)

#### Esta es la configuracion del servidor DNS

![Alt text](imagenes/c6.png)

#### Y ahora seleccionamos que archivos usamos para la configuración de nuestro servidor DNS

#
### Creamos la carpeta lib que se usa en el archivo de configuración

![Alt text](imagenes/c8.png)
##
### Creamos la carpeta zonas y la configuramos

![Alt text](imagenes/c9.png)
##
### Y ahora por ultimo encendemos nuestro servidor DNS

![Alt text](imagenes/c7.png)
##
### Docker compose en funcionamiento

![Alt text](imagenes/c10.png)

![Alt text](imagenes/c11.png)

