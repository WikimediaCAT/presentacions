# presentacions

Requisits: nodejs >= v.16

Instal·lar:
```
$ cd reveal.js && npm install
$ npm start
```
Canviar a gulpfile.js:
````
const port = yargs.argv.port || 4000
const host = yargs.argv.host || '165.227.136.10'
````
per:
````
const port = yargs.argv.port || 8000
const host = yargs.argv.host || 'localhost'
````
Després podeu anar a http://localhost:8000 per veure les presentacions
