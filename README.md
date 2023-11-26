# Actividad-4-

Si desea ejecutar el backend:
  Dentro de la carpeta backend ingrese el siguiente comando:
  npm install
  Este se encarga de instalar todas las dependencias definidas dentro del packaje.json
  Para correr el servidor ingrese:
  node index.js

Si desea ejecutar el Frontend:
  Dentro de la carpeta Frontend ingrese el siguiente comando:
  npm install
  Este se encarga de instalar todas las dependencias definidas dentro del packaje.json
  Para correr el servidor ingrese:
  npm run dev

Codigo de la base de datos:
CREATE DATABASE empleados

use empleados;

-- Table: empleados
CREATE TABLE empleados (
  id int(0) NOT NULL AUTO_INCREMENT,
    nombre varchar(100) NOT NULL DEFAULT '',
    edad int(100) NOT NULL DEFAULT 0,
    pais VARCHAR(100) NOT NULL DEFAULT '',
    cargo VARCHAR(100) NOT NULL DEFAULT '',
    anios int DEFAULT 0,
  PRIMARY KEY (id)
) 
