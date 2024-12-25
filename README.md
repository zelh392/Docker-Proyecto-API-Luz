
# PROYECTO API-PRECIO-LUZ

### Pasos para ejecutar el proyecto:

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tuusuario/proyecto-api-precio-luz.git
   cd proyecto-api-precio-luz


### Explicación:

- **`docker-compose up`** descargará las imágenes del contenedor desde tu Docker Hub y las levantará automáticamente.
- Si hay actualizaciones de la imagen en Docker Hub, con **`docker-compose pull`** los usuarios pueden actualizar las imágenes antes de levantar los contenedores con **`docker-compose up`**.

### Ventajas de este enfoque:

- **Simplicidad**: Solo tienes un archivo `docker-compose.yml` en el repositorio.
- **No duplicación de configuraciones**: Al descargar las imágenes desde Docker Hub, evitas tener que mantener diferentes archivos Docker Compose o duplicar configuraciones.
- **Facilidad de uso**: Los usuarios simplemente ejecutan `docker-compose up` y todo se configura automáticamente.

### Consideraciones adicionales:

Este enfoque centraliza todo el proceso de despliegue y hace que sea muy fácil para cualquier persona probar el proyecto sin tener que construir las imágenes manualmente.
