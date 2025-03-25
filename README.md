<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>


# 🚀 Haki-Back (Backend con NestJS, PostgreSQL y Docker)

Este proyecto es una API backend desarrollada con **NestJS**, utilizando **PostgreSQL** como base de datos y **Docker** para la gestión de entornos.

---

## 📌 Tecnologías utilizadas

- 🏗 **NestJS** (Framework de Node.js)
- 🐘 **PostgreSQL** (Base de datos relacional)
- 🐳 **Docker** y **Docker Compose** (Contenedores)
- 📜 **TypeORM** (ORM para gestionar PostgreSQL)
- 🛠 **dotenv** (Manejo de variables de entorno)

---

## 🚀 Instalación y ejecución

### 🔹 **1. Clonar el repositorio**
```sh
git clone https://github.com/tu-usuario/haki-back.git
cd haki-back
```
2. ``npm install``
3. Clonar el archivo ``.env.template`` y renombrarlo a ``.env``
4. Cambiar las variables de entorno, por defecto son las siguientes:
```
DATABASE_PASSWORD=postgres
DATABASE_USERNAME=postgres
DATABASE_PORT=5432
DATABASE_NAME=postgres_db
DATABASE_HOST=localhost
```
5. Levantar la base de datos
```
docker-compose up -d
```
6. Levantar el proyecto
```sh
npm run start:dev
```