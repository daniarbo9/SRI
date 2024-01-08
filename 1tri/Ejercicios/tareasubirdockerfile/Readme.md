'Para crear la imagen'
docker build -t tareasubirdockerfile":opcionaltag" /home/asir2/Documentos/SRI/Ejercicios/tareasubirdockerfile
'Para subir la imagen'
docker login    
docker tag      load-image":tagname si se puso en el build"  mi_repositorio_en_docker.hub:tagname    
docker push     mi_repositorio_en_docker.hub:tagname
