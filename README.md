Typescript and Express.js 
=========================

An Express.js project implemented using Typescript with strongly typed objects:

# Installation

Clone the repository

```
npm install 
```

For development:
```
npm run dev
```

To serve:
```
npm run serve
```

To debug in visual studio code:
```
npm run debug
```

Then run the `launch.json` configuration or inside visual studio code.  You should now be able to set breakpoints in your typescript.

Test
```
npm run test
```

Test Watch
```
npm run test:watch
```

Browse to http://localhost:3000


# Start in watch mode

`npm run nodemon`

# Folder structure

```
|-- Dockerfile 
|-- README.md 
|-- package.json
|-- spec
|   -- index.spec.ts
|-- src
|   |-- config
|   |   -- config.ts
|   |   -- express.ts
|   |-- controllers
|   |   -- index.server.controller.ts
|   |-- index.ts
|   |-- public
|   |   -- stylesheets
|   |       -- style.css
|   |-- routes
|   |   -- index.server.route.ts
|   |-- tsconfig.json
|   -- views
|       -- error.jade
|       -- index.jade
|       -- layout.jade
-- tsconfig.json
```

# Typescript

Typescript will output the compiled code to the `dist` folder.

# Docker

Build the image `sudo docker build -t rjmacarthy/express-typescript-starter .`

Run the image `docker-compose up`

Open `http://localhost:8080`

```
# Removes all other docker images and containers #

docker rmi $(docker images -q)
docker rm $(docker ps -a -q)
```



# License

MIT - Do with as you like.

