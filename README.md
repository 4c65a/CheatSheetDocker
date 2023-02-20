# CheatSheetDocker


# Comandos básicos

**docker run**: Ejecuta un contenedor. Ejemplo: docker run nginx

**docker start**: Inicia un contenedor previamente creado. Ejemplo: docker start my_container

**docker stop**: Detiene un contenedor en ejecución. Ejemplo: docker stop my_container

**docker rm**: Elimina un contenedor. Ejemplo: docker rm my_container

**docker ps**: Muestra los contenedores en ejecución. Ejemplo: docker ps

**docker images**: Muestra las imágenes disponibles en el host. Ejemplo: docker images

**docker pull**: Descarga una imagen de un repositorio. Ejemplo: docker pull ubuntu



# Trabajo con imágenes

**docker build**: Crea una imagen a partir de un archivo Dockerfile. Ejemplo: docker build -t my_image

**docker tag**: Etiqueta una imagen con un nombre personalizado. Ejemplo: docker tag my_image my_registry/my_image:1.0

**docker push**: Envía una imagen a un repositorio. Ejemplo: docker push my_registry/my_image:1.0

**docker rmi**: Elimina una imagen. Ejemplo: docker rmi my_image


# Redes y volúmenes

**docker network create**: Crea una red personalizada. Ejemplo: docker network create my_network

**docker network connect**: Conecta un contenedor a una red existente. Ejemplo: docker network connect my_network my_container

**docker volume create**: Crea un volumen personalizado. Ejemplo: docker volume create my_volume

**docker volume ls**: Muestra los volúmenes disponibles. Ejemplo: docker volume ls

**docker volume rm**: Elimina un volumen. Ejemplo: docker volume rm my_volume


# Comandos avanzados

**docker exec**: Ejecuta un comando en un contenedor en ejecución. Ejemplo: docker exec my_container ls /

**docker logs**: Muestra los registros de un contenedor en ejecución. Ejemplo: docker logs my_container

**docker inspect**: Muestra información detallada sobre un contenedor o imagen. Ejemplo: docker inspect my_container

**docker commit**: Crea una nueva imagen a partir de los cambios en un contenedor en ejecución. Ejemplo: docker commit my_container my_image

**docker-compose**: Herramienta para definir y ejecutar aplicaciones Docker multi-contenedor. Ejemplo: docker-compose up -d
