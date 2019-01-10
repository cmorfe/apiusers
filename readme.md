# API de Usuarios

Se utilizó Lumen, el microframework de Laravel, pues se trata sólo de una API.

## Instalación

- Es necesario PHP v7.1 y Composer.
- Clonar el repositorio (https://github.com/cmorfe/apiusers.git).
- Abrir el directorio.
- Renombrar el archivo .env.example a .env.
- Crear la base de datos y configurar los parámetros de conexión a la misma en el archivo .env.
- Ejecutar el comando "composer install" en la terminal.
- Ejecutar el comando "php artisan migrate --seed" en la terminal.
- Para probar las solicitudes a la API se puede utilizar un programa como Postman o cualquiera de su preferencia.