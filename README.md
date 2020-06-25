# English:

# Boilerplate for API with Node, typescript and express

### Docker commands:

##### docker build - .t *container name*

Builds the container

##### docker run -p 3000:3000 *container name*

Runs an instance of the container

### npm commands:

##### npm run dev

Runs an instance of the app directly from /src/index.ts with nodemon (it uses ts-node so it automatically transpiles to js)

##### npm run build

Takes all there is in the folder /src, compiles it to javascript and saves it inside /dist. In order to use a watcher so that every time changes are saved the code is compiled you sould add  the -w flag to the build script: "tsc -w"

##### npm start
Runs the app from /dist. (npm run build first)

# Español

# Api genérica con node, typescript y express

### Docker commands:

##### docker build . -t *container name*

"Buildea" el container.

##### docker run -p 3000:3000 *container name*

Corre una instancia del container

### npm commands:

##### npm run dev

Corre una instancia de la aplicación directamente desde /src/index.ts con nodemon (como usa ts-node, transpila automáticamente a js)

##### npm run build

Toma todo lo que está en la carpeta /src, lo convierte a js y lo guarda dentro de /dist. Si se quiere agregar un watcher para que el compilador quede escuchando se debe agregar el flag -w (quedaría "tsc -w").

##### npm start

Ejecuta la aplicacion con node a partir de /dist. Tener en cuenta que para que funcione, hay que previamente haber corrido npm run build.
