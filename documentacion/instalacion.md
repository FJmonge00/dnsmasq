<img src="../imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

# 2.- Instalación
![logo portainer](../imagenes/portainer.png)
## Instalación del contenedor
Al bajarnos la imagen de DockerHub tendremos que especificar tambien el usuario ya que no es una imagen oficial de docker...

![pull de la imagen](../imagenes/poolDeLaImagen.png)

`docker pull portainer/portainer`

Levantamos la imagen con docker run...

`docker run -d --name portainer -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer`

![pull de la imagen](../imagenes/poolDeLaImagen.png)

Comprobamos que esta corriendo la imagen...

`docker ps`

![docker ps](../imagenes/dockerps.png)

________________________________________
*[Volver al indice...](../README.md)*