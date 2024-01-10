# web
# pagina web de prueba para Docker 
# Vamos a automatizar la creación de imagenes de Docker con actios de github 
# Creamos el repositorio en github y luego nos vamos a nuestra maquina y lo clonamos solo con el README.
# Creamos nuestro Dockerfile, index.html y nuestra images (la que queramos que muestre nuestra web)
# Para ello tenemos que subir un Dockerfile y además crear el directorio .github/workflows en github, para hacer esto desde github nos vamos a [Actions] para crear uno
# Nos dará un fichero de ejemplo para crear images de Docker, lo creamos y nos lo volvemos a bajar a nuestro pc 
# Adaptamos nuestro fichero de action y lo subimos de nuevo a nuestro repo.  
# Además tendremos que configurar los parametros de nuestro Dockerhub
# Dentro de nuestro proyecto de git (web) tenemos ir a --> Setting --> Secrets and variables --> Actions y ahora New Repository Secrets 
# Creamos las secrets que hemos definido en nuestro yaml (DOCKER_PASSWORD and DOCKER_USER) con nuestras credenciales de Dockerhub 
# Ya podemos hacer algun cambio en nuestro código, como cambiar el texto de nuestro Index.html y se creará de forma automática la imagen en nnuestra cuenta de Dockerhub

