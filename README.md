
## Comandos docker

```bash
# crear imagen a partir de dockerfile
docker build -t name:of:image .

# crear contenedor a partir de una imagen
# -d para hacer un proceso en background
# -p para esteblecer los puertos puertolocal:puertointernodelcontenedor 
docker run -d -p 80:3000 nombre:de:la:imagen

#subir imagen a docker hub crear previanteme un repositorio

# iniciar sesión
docker login
#comando para crear tag
docker tag imagen:local nombre:del:repositorio:version
#comando para pusear
docker push nombre:del:repositorio:version
```


## Stay in touch

- Author - [Rafael Falconí](rfalconi@unibe.edu.ec)
