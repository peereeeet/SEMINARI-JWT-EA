# Ejercicio Seminario 7 - JWT

- register: crear usuari i et retorna un token 

- login: et loggeja i et retorna un token 

- profile: si li dones el teu id d'usuaari + token i comprova que ets propietari del token i et mostre les teves

- funcionalitat encrypted password enabled

- Delete user: comprova que el token que has introduit es d'un usuari administrador i deixa borrar el usuari introduit en la ruta

- Fer que un usuari introduint el seu ID i el seu token pugui fer canvis sobre les seves dades.

- Fer que només puguin veure el llistat d'usuaris, aquells usuaris que tinguin rol d'administrador.

# Commands to execute

Instal·lar jwt
- npm install jsonwebtoken 
- npm install @types/jsonwebtoken -D

Instal·lar dotenv
- npm i dotenv
- npm i @types/dotenv -D


Instal·lar bcrypt
- npm i bcryptjs
- npm i @types/bcryptjs -D

