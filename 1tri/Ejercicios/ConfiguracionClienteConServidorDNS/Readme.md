# Configuracion cliente + servidor DNS

## Primero configuramos el docker-compose.yml de manera que cree el servidor DNS y un cliente

![Alt text](imagenes/c1.png)
![Alt text](imagenes/c1.2.png)
#
### Una vez que cliente y servidor estén en funcionamiento accedemos al cliente y descargamos bind-tools para hacer las comprobaciones

![Alt text](imagenes/c2.png)
#
### Buscamos y modificamos el archivo resolv.conf en el cliente

![Alt text](imagenes/c3.png)

![Alt text](imagenes/c4.png)
#
### Y por ultimo comprobamos con dig que la nueva dirección nos resuelva correctamente

![Alt text](imagenes/c5.png)