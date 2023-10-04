<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar repositorio

2. Ejecutar
```bash
$ npm install
```
3. Tener Nest CLI instaladdo
```bash
$ npm i -g @nestjs/cli
```
4. Levantar la base de datos
```bash
$ docker-compose up -d 
```
5. Clonar el archivo env.template y renombar a .env

6. llenar las variables de entorno definiddas .env

7. Ejecutar la app con
```bash
$ npm run start
```
8. recontruir la base de datos mongo con los datos de la semilla
```
localhost:3000/api/v2/seed
```
## Stack usado
* MongoDB
* NestJS