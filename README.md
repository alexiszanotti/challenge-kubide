
## Back-end Challenge-kubide

Con esta API, mediante peticiones HTTP  podemos realizar distintas acciones con sus validaciones correspondientes.

## Features

- Registrame como usuario 
- Loguearme como usuario (JWT)
- Ver mis datos personales.
- Modificar mis datos personales.
- Obtener todos los usuarios.
- Ver usuarios activos.


## Collections

[Endpoints ](https://www.getpostman.com/collections/10ace6d22993eda5aafc)


## Installation

Clonamos el repositorio a nuestro entorno local, y una vez dentro del proyecto (verificar en la consola que estemos en la ruta correcta),
instalamos todas las dependencias necesarias mediante el siguiente comando.
```bash
  npm install o yarn (dependiendo el manejador de paquetes que tengamos) 
```

Tambien necesitaremos crear un contenedor (Docker) con una instancia de mysql con el siguiente comando.

```bash
  docker run --name mysql-nestjs-challenge -p 5000:3306 -e MYSQL_ROOT_PASSWORD=challenge -e MYSQL_DATABASE=database -d mysql:8.0.26 
```  

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
## Author

- [@AlexisZanotti](https://www.github.com/alexiszanotti)

