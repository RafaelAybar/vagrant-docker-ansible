# Ejercicios con Docker y Docker Compose
1. Crea un Dockerfile con PHP para ejecutar Wordpress con distintas imágenes base. (php:X.Y , php:X.Y y compara las diferencias)
2. Utiliza una plantilla de Docker compose para exponer Wordpress. Debe tener:
    1. Gestión de perfiles. No siempre queremos probar todas las partes al mismo tiempo.
    2. Una base de datos que no puede ser expuesta salvo a localhost.
    3. Nginx como servidor web.
    4. Debes especificar el orden de cada servicio, puesto que no tiene sentido servir contenido cuando la base de datos no está activa.