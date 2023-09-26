**Github**

`Crear repositorio`

git init/git config --global init.defaultBranch main/git branch -m main/git remote add origin https://github.com/daniarbo9/SRI.git(Con los datos de la web)

`Subir o bajar archivos del repositorio`

`git add "name".md`

`git commit -m "first commit"`

`git push -u origin main`

**docker-compose**

`se usa para crear un contenedor`

services: 
  asir_web1:
    image: httpd:2.4
    ports: 
     - "8080:80"
    volumes:
     - ./paginas:/usr/local/apache2/htdocs
    container_name: asir_web1
