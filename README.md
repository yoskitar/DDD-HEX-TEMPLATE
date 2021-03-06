[![CI - Workflow](https://github.com/yoskitar/DDD-HEX-TEMPLATE/actions/workflows/ci-workflow.yml/badge.svg)](https://github.com/yoskitar/DDD-HEX-TEMPLATE/actions/workflows/ci-workflow.yml)

# You are using DDD-HEX-TEMPLATE
Plantilla realizada siguiendo la metodología Domain Driven Design. Se da por defecto el uso de varios protocolos de comunicación vía APIRest con HTTP, y Broker de mensajes mediante MQTT Y WebSockets. En caso de no tener que emplearse, tan solo será necesario eliminar la carpeta apropiada de la estructura del directorio.

Se ha presupuesto el uso del lenguaje Javascript para el desarrollo del microservicio en cuestión. En caso de emplear otro lenguaje, dirijirse a plantilla concreta, o adaptar esta para ello según sea necesario.

Para iniciar el proyecto, ejecutar la orden `npm init` en la ruta principal del repositorio de la siguientes forma, y con los siguientes argumentos:
```
$ npm init
```
```
Input:
{
  "name": "<nombre del microservicio>",
  "version": "1.0.0",
  "description": "<Breve descripción de no más de 2 líneas>",
  "main": "src/server.js",
  "scripts": {
    "test": "npx nyc --reporter=lcov nyc --reporter=lcov mocha src/test/ --exit"
  },
  "author": "smartfenix",
  "license": "ISC"
}
```