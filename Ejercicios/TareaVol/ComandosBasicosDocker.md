Tarea: Docker - Comandos básicos
1. Descarga la imagen 'ubuntu y comprueba que está en tu equipo
Para descargar la imagen y ver que imágenes tengo uso estos comandos.
docker run hello-world
docker search ubuntu
docker pull ubuntu:latest
docker run ubuntu
docker images
2. Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre
Para crear el contenedor uso el comando “docker run -it ubuntu bash” y como no
declaro el nombre se lo pone automáticamente docker en mi caso le puso
silly_robinson.
3. Crea un contenedor con el nombre 'ubu1'. ¿Como puedes acceder a él?
Para crearlo uso el comando docker run -it –name ubi1 ubuntu bash.
Después de crearlo accedo a el mediante el comando docker exec -it ubi1 bash.
4. Comprueba que ip tiene y si puedes hacer un ping a google.com
Para comprobar que ip tengo descargo net-tools y después utilizo el comando
“ifconfig”.
Y después de instalar con un comando el paquete para hacer ping si que me deja
usar el ping con google.5. Crea un contenedor con el nombre 'ubu2'. ¿Puedes hacer ping entre los
contenedores?
Si que puedo hacer ping entre los contenedores.
6. Sal del terminal, ¿que ocurrió con el contenedor?
Nada,el contenedor continua encendido.
7. ¿Cuanta memoria en el disco duro ocupaste? ¿Hay alguna herramienta de docker
para calcularlo?
Si.Con el comando docker stats se puede ver el uso de cada contenedor activo.
226,4mb es el tamaño de los contenedores
8. ¿Cuanta RAM ocupan los contenedores? Crea cuantos contenedores necesites para
calcularlo.
ubi 1mb ubi2 4,5