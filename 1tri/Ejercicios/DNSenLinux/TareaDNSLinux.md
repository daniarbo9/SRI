## 1.Primero instalo el ubuntu en una maquina virtual
## 2. Instalar el bind en ubuntu

![Alt text](imagenes/Screenshot_20231106_175651.png)

## 3. Creo una carpeta compartida para para pasar las configuraciones

![Alt text](imagenes/2.png)

## 4.Configuro la carpeta /etc/bind para pasarle la configuracion previamente configurada con docker

![Alt text](imagenes/3.png)

## 5.Configura las zonas en la carpera /var/lib/bind

![Alt text](imagenes/5.png)

## 6.Enciendo el servicio de bind

![Alt text](imagenes/4.png)

## 7.Miro a que ip tengo que hacer el ping con netstat -putan

![Alt text](imagenes/7.png)

## 8.Compruebo con dig que todo funciona correctamente

![Alt text](imagenes/6.png)

## 9.Cambio la configuracion de ethernet a bridge,compruebo la ip de la puerta de bind y intento hacer consultas desde el anfitrion al bind de la maquina virtual

![Alt text](imagenes/9.png)

![Alt text](imagenes/10.png)

![Alt text](imagenes/8.png)