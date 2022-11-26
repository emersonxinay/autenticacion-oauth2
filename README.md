# Autenticación con OAuth 2.0

1 - Clone del repo: https://github.com/emersonxinay/autenticacion-oauth2
En el repo estan los dos directorios admin y blog. Para cada directorio cambiar al branch de la clase:
2 - git checkout configuracion-inicial-de-los-proyectos
```bash
git checkout configuracion-inicial-de-los-proyectos
```

3 - En el directorio blog: npm install nodemon@latest -D luego npm install
```bash
npm install nodemon@latest -D 
```
instalar global
```bash
npm install -g nodemon
```
```bash
npm install
````

4 - En el directorio blog: npm start
```bash
npm start
```
5 - En el directorio admin: npm install
```bash
npm install
````

6 - En el directorio admin: npm run dev
```bash
npm audit fix
```
por si te sale error 
```bash
sudo npm install first
```
recuerda crear tu archivo .env a nivel de raiz de la carpeta admin y debe tener la siguientes variables: 
```.env 
// SPOTIFY
SPOTIFY_CLIENT_ID=
SPOTIFY_REDIRECT_URI=

// AUTH0
AUTH0_DOMAIN=
AUTH0_CLIENT_ID=
AUTH0_API_AUDIENCE=
AUTH0_REDIRECT_URI=
```
ejecuta para ver que todo anda corrirendo bien
```bash
npm run dev
```


recuerda que tienes que pasar de una carpeta otra es decir a la carpeta admin, api y blog
para ingresar a la carpeta admin:
```bash
cd admin
```
para regresar
```bash
cd ..
````
para ingresar a la carpeta blog:
```bash
cd blog
```
para regresar
```bash
cd ..
````
para ingresar a la carpeta api:
```bash
cd api
```
para regresar
```bash
cd ..
````

