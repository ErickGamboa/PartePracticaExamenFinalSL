# Examen Final ISW811 - Erick Josué Gamboa Rodríguez
# Pasos para  para probar localmente la aplicación
- Tomando encuenta que ya tienes instalado XAMPP
- con el comando `git clone` debes de clonar en /htdocs el repositorio `https://github.com/ErickGamboa/PartePracticaExamenFinalSL`
- Teniendo el repositorio clonado debes de ejecutar el siguiente comando en la consola `php composer install`
- Posteriormente ejecustas el comando `npm install`
- De igual forma debes de crear un archivo .env con las variables que se relacionen a su ambiente, por ejemplo: 
```
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:1nDm/ctFHyKTiO+JzEQoUgQpvYoCQmZzI0kRgNPOFbA=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=containers-us-west-97.railway.app
DB_PORT=7144
DB_DATABASE=railway
DB_USERNAME=root
DB_PASSWORD=fhTutUQIG55Ti5VDTsHY

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailhog
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"
```

- Después de configurar su base de datos en estas variables debes de correr el comando `php artisan migrate`

- No olvides presionar el boton de start en apache y MySQL en la aplicación de XAMPP

- Entre los últimos pasos debe de ejecuitar el comando `npm run dev`

- Posteriormente en otra consola ejecutas `php artisan serve`

- Copias el url que te da este comando, lo pegas en el brawser y pruebas el funcionamiento del sistema

# URL del sitio hosteado 

- `https://partepracticaexamenfinalsl-production.up.railway.app/`