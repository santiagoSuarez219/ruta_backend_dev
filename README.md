- [Modulo 1: Backend con Node JS: API REST con Express.js](#modulo-1-backend-con-node-js-api-rest-con-expressjs)
  - [¿Que es Express.js?](#que-es-expressjs)
    - [ESLint](#eslint)
  - [Instalacion de Express.js y tu primer servidor HTTP](#instalacion-de-expressjs-y-tu-primer-servidor-http)
  - [Routing con Express.js](#routing-con-expressjs)
  - [Operaciones CRUD](#operaciones-crud)
    - [¿Que es una RESTful API?](#que-es-una-restful-api)
  - [GET: recibir parametros](#get-recibir-parametros)
  - [GET: parámetros query](#get-parámetros-query)
  - [Separacion de responsabilidades con express.Router](#separacion-de-responsabilidades-con-expressrouter)
    - [Buenas practicas para rutas](#buenas-practicas-para-rutas)
  - [POST: metodo para crear](#post-metodo-para-crear)
  - [PUT, PATCH y DELETE](#put-patch-y-delete)
  - [Codigos de estado o HTTP response status codes](#codigos-de-estado-o-http-response-status-codes)
  - [Servicios](#servicios)
  - [Crear, editar y eliminar](#crear-editar-y-eliminar)
  - [Async, await y captura de errores](#async-await-y-captura-de-errores)
  - [Middlewares](#middlewares)
  - [Middleware para HttpErrors](#middleware-para-httperrors)
  - [Manejo de errores con Boom](#manejo-de-errores-con-boom)
  - [Validacion de datos con Joi](#validacion-de-datos-con-joi)
  - [Probando nuestros endpoints](#probando-nuestros-endpoints)
- [Modulo 2: Express con bases de datos SQL](#modulo-2-express-con-bases-de-datos-sql)
  - [Enlaces de interes](#enlaces-de-interes)
  - [Explorando Postgres: interfaces graficas y terminal](#explorando-postgres-interfaces-graficas-y-terminal)
  - [Integracion de nodejs con postgres](#integracion-de-nodejs-con-postgres)
  - [Manejo un Pool de conexiones](#manejo-un-pool-de-conexiones)
  - [Variables de ambiente en Node.js](#variables-de-ambiente-en-nodejs)
  - [ORM: Instalacion y configuracion de Sequelize](#orm-instalacion-y-configuracion-de-sequelize)
    - [Tu primer modelo en Sequelize](#tu-primer-modelo-en-sequelize)
    - [Crear, actualizar y eliminar](#crear-actualizar-y-eliminar)
    - [Middleware para errores de Sequelize](#middleware-para-errores-de-sequelize)
  - [Cambiando a la base de datos a MySQL](#cambiando-a-la-base-de-datos-a-mysql)
  - [Migraciones](#migraciones)
    - [Configurando y correindo migraciones con npm scripts](#configurando-y-correindo-migraciones-con-npm-scripts)
    - [Modificando una entidad con migraciones](#modificando-una-entidad-con-migraciones)
  - [Relaciones](#relaciones)
    - [Relaciones uno a uno](#relaciones-uno-a-uno)
  - [Relaciones 1 a muchos](#relaciones-1-a-muchos)
  - [Relaciones muchos a muchos](#relaciones-muchos-a-muchos)
  - [Paginacion](#paginacion)
  - [Filtrando precios con operadores](#filtrando-precios-con-operadores)
  - [Consideraciones al hacer migraciones en produccion](#consideraciones-al-hacer-migraciones-en-produccion)
- [Modulo 3: Autenticacion y autorizacion](#modulo-3-autenticacion-y-autorizacion)
  - [Middlerae de verificacion](#middlerae-de-verificacion)
    - [Utilizando variables de entorno](#utilizando-variables-de-entorno)
  - [Hashing de contraseñas](#hashing-de-contraseñas)
  - [Login con passport.js](#login-con-passportjs)
  - [Jason Web Tokens (JWT)](#jason-web-tokens-jwt)
  - [Firmar y verificar tokens](#firmar-y-verificar-tokens)
    - [Generar JWT en el servicio](#generar-jwt-en-el-servicio)
- [Falta terminar modulo verificacion](#falta-terminar-modulo-verificacion)
- [Modulo 4: Nest.js](#modulo-4-nestjs)
  - [Crea tu primer proyecto con NestJS](#crea-tu-primer-proyecto-con-nestjs)
  - [Estructura de un proyecto NestJS](#estructura-de-un-proyecto-nestjs)
  - [Repaso a TS: tipos y POO](#repaso-a-ts-tipos-y-poo)
    - [Qué es TypeScript](#qué-es-typescript)
    - [Tipado de Datos con TypeScript](#tipado-de-datos-con-typescript)
    - [Programación Orientada a Objetos con TypeScript](#programación-orientada-a-objetos-con-typescript)
  - [REST API con NestJS](#rest-api-con-nestjs)
  - [Controladores](#controladores)
  - [Estructura de un controlador](#estructura-de-un-controlador)
  - [GET: como recibir parametros](#get-como-recibir-parametros)
  - [Parametros query](#parametros-query)
  - [Separacion de responsabilidades](#separacion-de-responsabilidades)
  - [Responsabilidades en NestJS](#responsabilidades-en-nestjs)
  - [Metodo POST](#metodo-post)
  - [Metodo PUT y DELETE](#metodo-put-y-delete)
  - [Eliminar datos con Delete](#eliminar-datos-con-delete)
  - [Codigos de estado HTTP](#codigos-de-estado-http)
  - [Status Codes en Nest JS](#status-codes-en-nest-js)
  - [Integridad de datos](#integridad-de-datos)
  - [Servicios](#servicios-1)
  - [Creando un servicio](#creando-un-servicio)
  - [Servicios en NestJS](#servicios-en-nestjs)
  - [Implementando servicios en tu controlador](#implementando-servicios-en-tu-controlador)
  - [Inyeccion de dependencias](#inyeccion-de-dependencias)
  - [Controladores y servicios](#controladores-y-servicios)
  - [Controllers](#controllers)
  - [Manejo de errores con throw y NotFoundException](#manejo-de-errores-con-throw-y-notfoundexception)
  - [Manejo de errores](#manejo-de-errores)
  - [Pipes](#pipes)
    - [Implementación de PIPES](#implementación-de-pipes)
  - [Crea tu propio Pipe](#crea-tu-propio-pipe)
  - [Generar un pipe con nest g pi common/parse-int](#generar-un-pipe-con-nest-g-pi-commonparse-int)
  - [Creando Data Transfer Objects (DTOs)](#creando-data-transfer-objects-dtos)
    - [¿Qué es un DTO?](#qué-es-un-dto)
    - [Creando un DTO](#creando-un-dto)
    - [Importando un DTO](#importando-un-dto)
      - [SRC:DTOS](#srcdtos)
  - [Validando parametros con class-validator y mapped-types](#validando-parametros-con-class-validator-y-mapped-types)
    - [Validacion de datos con DTO](#validacion-de-datos-con-dto)
    - [Como reutilizar los DTO](#como-reutilizar-los-dto)
  - [Como evitar parametros incorrectos](#como-evitar-parametros-incorrectos)
    - [Como hacer la prohibicion de datos](#como-hacer-la-prohibicion-de-datos)
- [Modulo 5: Programacion modular](#modulo-5-programacion-modular)
  - [Encapsular logica en modulos](#encapsular-logica-en-modulos)
  - [Interaccion entre modulos](#interaccion-entre-modulos)
  - [Entendiendo la inyeccion de dependencias](#entendiendo-la-inyeccion-de-dependencias)
  - [Precaucion utilizando servicios](#precaucion-utilizando-servicios)
  - [useClass](#useclass)
  - [useValue](#usevalue)
  - [Use Factory](#use-factory)
  - [Global Module](#global-module)
  - [Módulo de configuración](#módulo-de-configuración)
    - [Consejos sobre las variables de entorno](#consejos-sobre-las-variables-de-entorno)
  - [Configuracion por ambiente](#configuracion-por-ambiente)
  - [Tipado en config](#tipado-en-config)
  - [Validacion de esquemas en .envs con Joi](#validacion-de-esquemas-en-envs-con-joi)
- [Modulo 6: Documentacion con Swagger](#modulo-6-documentacion-con-swagger)
  - [Tipado de la documentación](#tipado-de-la-documentación)
  - [Extendiendo la documentación](#extendiendo-la-documentación)
- [Modulo 7: Deploy en Heroku](#modulo-7-deploy-en-heroku)
  - [Configuración del proyecto al usar Heroku](#configuración-del-proyecto-al-usar-heroku)
  - [Configuración versión de NodeJS](#configuración-versión-de-nodejs)
  - [Configuración de Heroku](#configuración-de-heroku)
  - [Variables de entorno en Heroku](#variables-de-entorno-en-heroku)
- [Modulo 8: Nest con MongoDB](#modulo-8-nest-con-mongodb)
  - [Instalacion de Docker](#instalacion-de-docker)
  - [Configuracion de Docker para MongoDB](#configuracion-de-docker-para-mongodb)
    - [Cuáles son los beneficios de Docker](#cuáles-son-los-beneficios-de-docker)
  - [Exploración de la base de datos con Mongo Compass](#exploración-de-la-base-de-datos-con-mongo-compass)
  - [Instalando y conectando MongoDB Driver](#instalando-y-conectando-mongodb-driver)
  - [Conexion como inyectable](#conexion-como-inyectable)
    - [Código de ejemplo de: conexión como inyectable](#código-de-ejemplo-de-conexión-como-inyectable)
  - [Ejecutando un query](#ejecutando-un-query)
  - [Usando varibales de ambiente en Mongo](#usando-varibales-de-ambiente-en-mongo)
  - [Mongoose](#mongoose)
  - [Instalación y configuración de Mongoose](#instalación-y-configuración-de-mongoose)
  - [Esquemas con Mongoose](#esquemas-con-mongoose)
  - [Conectando Mongo a los servicios](#conectando-mongo-a-los-servicios)
  - [Create, update y delete](#create-update-y-delete)
  - [Pipe para mongoid](#pipe-para-mongoid)
  - [Agregando paginacion](#agregando-paginacion)
  - [Agregando un filtro de rango para precios](#agregando-un-filtro-de-rango-para-precios)
  - [Agregando indexadores](#agregando-indexadores)
  - [Relaciones uno a uno referenciadas](#relaciones-uno-a-uno-referenciadas)
  - [Relaciones uno a muchos referenciadas](#relaciones-uno-a-muchos-referenciadas)
  - [Manipulacion de arrays en MongoDB](#manipulacion-de-arrays-en-mongodb)
    - [Agregar y quitar elementos en un array](#agregar-y-quitar-elementos-en-un-array)
  - [Operadores especiales de MongoDB](#operadores-especiales-de-mongodb)
- [Modulo 9: Autenticacion con Passport y JWT](#modulo-9-autenticacion-con-passport-y-jwt)
  - [Enlaces de interes](#enlaces-de-interes-1)
  - [Introduccion a Guards](#introduccion-a-guards)
  - [Usando un decorador](#usando-un-decorador)
  - [Guardianes con variables de entorno](#guardianes-con-variables-de-entorno)
  - [Hashing de contraseñas en Mongo](#hashing-de-contraseñas-en-mongo)
  - [Autenticacion con Passport.js](#autenticacion-con-passportjs)
  - [Ruta de login](#ruta-de-login)
  - [Conectando Passport con JWT](#conectando-passport-con-jwt)
  - [Implementando JWT Guard](#implementando-jwt-guard)
  - [Extendiendo JWT Guard](#extendiendo-jwt-guard)
  - [Control de roles en NestJS](#control-de-roles-en-nestjs)
  - [Obteniendo ordenes del perfil](#obteniendo-ordenes-del-perfil)
- [Modulo 10: Deploy de Mongo](#modulo-10-deploy-de-mongo)
  - [Configurando Mongo Atlas](#configurando-mongo-atlas)
  - [Desplegando en Heroku](#desplegando-en-heroku)

# Modulo 1: Backend con Node JS: API REST con Express.js

## ¿Que es Express.js?

Express es un framework de Node.js utilizado para construir aplicaciones web del lado del servidor. Es rápido, minimalista y cuenta con un conjunto de características robustas y de alto rendimiento para aplicaciones web y móviles. Express proporciona una capa de abstracción sobre la API HTTP en Node.js, lo que facilita la creación de aplicaciones y servicios web altamente escalables y mantenibles.

### ESLint

ESLint es una herramienta de linting de JavaScript que identifica y reporta patrones en el código JavaScript. Un linter es una herramienta que analiza el código fuente para señalar errores de sintaxis, detectar posibles problemas, y aplicar ciertas reglas de programación para mejorar la calidad del código, aumentar la eficiencia en la escritura y el mantenimiento del código, y evitar posibles errores de programación. En términos sencillos, un linter funciona como un corrector ortográfico para el código, identificando errores de escritura y sugiriendo cómo corregirlos.

## Instalacion de Express.js y tu primer servidor HTTP

```javascript
const express = require("express");
const app = express();
const port = 3000;

app.get("/", (req, res) => {
  res.send("Hello World");
});

app.listen(port, () => {
  console.log("Mi port" + port);
});
```

1. [Documentacion de Express JS](https://expressjs.com/)

## Routing con Express.js

```javascript
app.get("/nueva-ruta", (req, res) => {
  res.send("Hola, soy una nueva ruta");
});

app.get("/productos", (req, res) => {
  res.json({
    name: "Producto 1",
    price: 1000,
  });
});
```

## Operaciones CRUD

### ¿Que es una RESTful API?

Un RESTful API (Application Programming Interface) es un modelo de arquitectura para sistemas de comunicación entre diferentes aplicaciones. Este tipo de API utiliza el protocolo HTTP para realizar operaciones con los recursos disponibles en un servidor. Una API RESTful está formada por recursos, que son objetos o datos que se almacenan en el servidor y se pueden consultar, crear, modificar o borrar. Cada recurso tiene una URL única que permite acceder a él mediante los métodos de HTTP correspondientes (GET, POST, PUT, DELETE, etc.). También se utiliza el formato JSON para el intercambio de datos entre el servidor y la aplicación que consume la API.

GET, PUT, DELETE, y POST son los principales métodos utilizados en una API RESTful para realizar operaciones en los recursos disponibles en un servidor. Aquí te explico brevemente para qué sirve cada uno:

- GET: Es utilizado para solicitar una representación del recurso especificado en la URL. Normalmente se utiliza para leer información.

- POST: Sirve para crear un nuevo recurso en el servidor. Por ejemplo, se puede utilizar para enviar información de un formulario a un servidor que luego crea un nuevo objeto.

- PUT: Se utiliza para actualizar un recurso existente en el servidor. Por ejemplo, si un usuario quiere cambiar algún dato de un perfil, se puede realizar una solicitud PUT para actualizar la información.
- DELETE: Sirve para eliminar un recurso existente en el servidor. Por ejemplo, si un usuario quiere eliminar su perfil, se puede utilizar una solicitud DELETE para que el servidor elimine los datos correspondientes.

Es importante mencionar que estos métodos no son los únicos que se pueden utilizar en una API RESTful, pero son los más comunes y recomendados por convención.

![Image](https://static.platzi.com/media/user_upload/REST-65e4240f-662b-406e-91c9-57d8b0dd56f4.jpg)

## GET: recibir parametros

```javascript
app.get("/products", (req, res) => {
  res.json([
    {
      name: "Producto 1",
      price: 1000,
    },
    {
      name: "Producto 2",
      price: 2000,
    },
  ]);
});

app.get("/products/:id", (req, res) => {
  const { id } = req.params;
  res.json({
    id,
    name: "Producto 1",
    price: 1000,
  });
});

app.get("/categories/:category_id/products/:product_id", (req, res) => {
  const { category_id, product_id } = req.params;
  res.json({
    category_id,
    product_id,
  });
});
```

## GET: parámetros query

Los query parameters, también conocidos como parámetros de consulta, son una forma de agregar información adicional a una solicitud GET. Estos parámetros se agregan a la URL de la solicitud después del signo de interrogación (?), y consisten en una clave y un valor separados por el signo igual (=), por ejemplo:

`https://api.example.com/customers?sortBy=name&limit=10.`

Los query parameters permiten a los clientes de la API RESTful solicitar datos más específicos y detallados del recurso que se está solicitando. Por ejemplo, un cliente puede utilizar los parámetros de consulta para ordenar los resultados de una búsqueda, filtrar información o paginar los resultados. En general, los parámetros de consulta son una buena forma de optimizar la experiencia del usuario final, proporcionándole solo la información que necesita y reduciendo el tiempo de procesamiento del servidor.

Hay varios query parameters comúnmente utilizados en las solicitudes GET de una API RESTful. Algunos de los más populares son:

- **sort**: ordena los resultados de la búsqueda por un campo determinado (por ejemplo, sort=name ordena los resultados por el nombre)

- **filter**: filtra los resultados por un criterio específico (por ejemplo, filter=category:books muestra solo los resultados de la categoría de libros)

- **page**: permite la paginación de los resultados para mostrar una cantidad específica de resultados en una página (por ejemplo, page=2&limit=10 muestra los resultados de la página 2 con un límite de 10 resultados por página)

- **limit**: limita la cantidad de resultados que se muestran en una sola solicitud (por ejemplo, limit=25 muestra solo los primeros 25 resultados)

- **fields**: muestra solo los campos específicos de un recurso determinado (por ejemplo, fields=name,age muestra solo los campos de nombre y edad)

En general, estos parámetros de consulta son útiles para personalizar las solicitudes GET y obtener información más específica y útil de la API RESTful.

```javascript
app.get("/products", (req, res) => {
  const products = [];
  const { size } = req.query;
  const limit = size || 10;
  for (let i = 0; i < limit; i++) {
    products.push({
      name: faker.commerce.productName(),
      price: parseInt(faker.commerce.price(), 10),
      image: faker.image.imageUrl(),
    });
  }
  res.json(products);
});
```

**Nota**
Cuando tengo ENDPoints similares como estos, debe ir primero los fijos y luego los dinamicos.

```javascript
app.get("/products/filter", (req, res) => {
  res.send("Filtrando productos");
});

app.get("/products/:id", (req, res) => {
  const { id } = req.params;
  res.json({
    id,
    name: "Producto 1",
    price: 1000,
  });
});
```

## Separacion de responsabilidades con express.Router

El principio de responsabilidad única (Single Responsibility Principle) es un principio dentro del desarrollo de software que establece que una clase o módulo debe tener solo una responsabilidad o motivo para cambiar. Esto significa que una clase debe tener una y solo una razón para cambiar, lo que la hace más fácil de mantener y entender. Si una clase asume varias responsabilidades, puede volverse difícil de mantener a medida que evoluciona el software y puede ser difícil de reutilizar.

En resumen, el principio de responsabilidad única se enfoca en que un componente de software debe tener un solo propósito o función de manera que pueda ser fácilmente entendido, modificado y mantenido sin afectar otros componentes.

1. Se crea una carperta Router: alli iran las diferentes rutas

```javascript
const express = require("express");
const { faker } = require("@faker-js/faker");

const router = express.Router();

router.get("/", (req, res) => {
  const products = [];
  const { size } = req.query;
  const limit = size || 10;
  for (let i = 0; i < limit; i++) {
    products.push({
      name: faker.commerce.productName(),
      price: parseInt(faker.commerce.price(), 10),
      image: faker.image.imageUrl(),
    });
  }
  res.json(products);
});

router.get("/filter", (req, res) => {
  res.send("Filtrando productos");
});

router.get("/:id", (req, res) => {
  const { id } = req.params;
  res.json({
    id,
    name: "Producto 1",
    price: 1000,
  });
});

module.exports = router;
```

2. Se crea el archivo index de las rutas

```javascript
const productsRouter = require("./productsRouter");
// const usersRouter = require('./usersRouter');

function routerApi(app) {
  app.use("/products", productsRouter);
  // app.use('/users', usersRouter')
}

module.exports = routerApi;
```

3. Se actualiza el index

```javascript
const express = require("express");
const routerApi = require("./routes");

const app = express();
const port = 3000;

routerApi(app);

app.listen(port, () => {
  console.log("Mi port" + port);
});
```

### Buenas practicas para rutas

```javascript
const express = require("express");

const productsRouter = require("./products.router");
const categoriesRouter = require("./categories.router");
const usersRouter = require("./users.router");

function routerApi(app) {
  const router = express.Router();
  app.use("/api/v1", router);
  router.use("/products", productsRouter);
  router.use("/categories", categoriesRouter);
  router.use("/users", usersRouter);
}

module.exports = routerApi;
```

## POST: metodo para crear

1. Crear un metodo POST

```javascript
router.post("/", (req, res) => {
  const body = req.body;
  res.json({
    message: "created",
    data: body,
  });
});
```

2. Actualizar index.js para que permita verificar los JSON

```javascript
const app = express();
const port = 3000;

app.use(express.json());
```

## PUT, PATCH y DELETE

```javascript
router.post("/", (req, res) => {
  const body = req.body;
  res.json({
    message: "created",
    data: body,
  });
});

router.patch("/:id", (req, res) => {
  const { id } = req.params;
  const body = req.body;
  res.json({
    message: "update",
    data: body,
    id,
  });
});

router.delete("/:id", (req, res) => {
  const { id } = req.params;
  res.json({
    message: "deleted",
    id,
  });
});
```

## Codigos de estado o HTTP response status codes

Los status code o códigos de estado son números de tres dígitos que se utilizan en las respuestas de las solicitudes HTTP y que indican el resultado de dicha operación. Estos códigos se dividen en cinco clases principales, y cada una de ellas tiene un rango de valores asociado:

- Clase 1xx: indica una respuesta informativa.
- Clase 2xx: indica una respuesta satisfactoria.
- Clase 3xx: indica una redirección.
- Clase 4xx: indica un error del cliente.
- Clase 5xx: indica un error del servidor.

Algunos ejemplos comunes de códigos de estado son:

- 200 OK: indica que la solicitud se ha procesado correctamente.
- 400 Bad Request: indica que la solicitud es inválida o está mal formada.
- 401 Unauthorized: indica que el usuario no está autorizado para acceder al recurso solicitado.
- 404 Not Found: indica que el recurso solicitado no se ha encontrado en el servidor.
- 500 Internal Server Error: indica un error interno del servidor.

Los códigos de estado son útiles para la depuración y el monitoreo de una API, ya que permiten identificar rápidamente qué ha pasado en cada solicitud y cómo se ha comportado el servidor.

2. [Http Cats](https://http.cat/)

```javascript
router.get("/:id", (req, res) => {
  const { id } = req.params;
  if (id === "999") {
    res.status(404).json({
      message: "Product not found",
    });
  } else {
    res.json({
      id,
      name: "Producto 1",
      price: 1000,
    });
  }
});

router.post("/", (req, res) => {
  const body = req.body;
  res.status(201).json({
    message: "created",
    data: body,
  });
});
```

## Servicios

1. Crear carpeta services
2. Crear archivo product.service.js

```javascript
const { faker } = require("@faker-js/faker");

class ProductServices {
  constructor() {
    this.products = [];
    this.generate();
  }

  generate() {
    const limit = 100;
    for (let i = 0; i < limit; i++) {
      this.products.push({
        id: faker.datatype.uuid(),
        name: faker.commerce.productName(),
        price: parseInt(faker.commerce.price(), 10),
        image: faker.image.imageUrl(),
      });
    }
  }

  create() {}

  find() {
    return this.products;
  }

  findOne(id) {
    return this.products.find((item) => item.id === id);
  }

  update() {}

  delete() {}
}

module.exports = ProductServices;
```

3. Actualizar el archivo products.router.js

```javascript
const express = require('express');

const ProductServices = require('../services/product.service');

const router = express.Router();
const service =  new ProductServices();

router.get('/',(req,res) =>{
  const products = service.find();
  res.json(products);
});

router.get('/filter',(req,res) =>{
  res.send('Filtrando productos');
});

router.get('/:id',(req,res) =>{
  const { id } = req.params;
  const product = service.findOne(id);
  res.json(product);
});

...
```

## Crear, editar y eliminar

1. Actualizar el archivo product.service.js

```javascript

    update(id, changes){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw new Error('Product not found');
        }
        const product = this.products[index];
        this.products[index] = {
            ...product,
            ...changes
        };
        return this.products[index];
    }

    delete(id){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw new Error('Product not found');
        }
        this.products.splice(index,1);
        return {id};
    }

```

2. Actualizar el archivo products.router.js

```javascript
router.post("/", (req, res) => {
  const body = req.body;
  const newProduct = service.create(body);
  res.status(201).json(newProduct);
});

router.patch("/:id", (req, res) => {
  const { id } = req.params;
  const body = req.body;
  const product = service.update(id, body);
  res.json(product);
});

router.delete("/:id", (req, res) => {
  const { id } = req.params;
  const rta = service.delete(id);
  res.json(rta);
});
```

## Async, await y captura de errores

1. Actualizar product services (Async y await)

```javascript
const {faker} = require('@faker-js/faker');

class ProductServices {

    constructor(){
        this.products = [];
        this.generate();

    }

    generate(){
        const limit = 100;
        for (let i = 0; i < limit; i++) {
          this.products.push({
            id: faker.datatype.uuid(),
            name: faker.commerce.productName(),
            price: parseInt(faker.commerce.price(),10),
            image: faker.image.imageUrl()
          });
        }
    }

    async create(data){
        const newProduct = {
            id: faker.datatype.uuid(),
            ...data
        }
        this.products.push(newProduct);
        return newProduct;
    }

    async find(){
        return new Promise((resolve,reject) =>{
            setTimeout(() =>{
                resolve(this.products);
                }, 5000);
        });
    }

    async findOne(id){
        return this.products.find(item => item.id === id);
    }

    async update(id, changes){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw new Error('Product not found');
        }
        const product = this.products[index];
        this.products[index] = {
            ...product,
            ...changes
        };
        return this.products[index];
    }

    async delete(id){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw new Error('Product not found');
        }
        this.products.splice(index,1);
        return {id};
    }
}
...
```

2. Actualizar products.router.js (Async y await)

```javascript
const express = require('express');

const ProductServices = require('../services/product.service');

const router = express.Router();
const service =  new ProductServices();

router.get('/', async (req,res) =>{
  const products = await service.find();
  res.json(products);
});

router.get('/:id', async (req,res) =>{
  const { id } = req.params;
  const product = await service.findOne(id);
  res.json(product);
});

router.post('/',async (req,res) =>{
  const body = req.body;
  const newProduct = await service.create(body);
  res.status(201).json(newProduct);
});

router.patch('/:id',async (req,res) =>{
  try {
    const { id } = req.params;
    const body = req.body;
    const product = await service.update(id,body);
    res.json(product);
  } catch (error) {
    res.status(404).json({
      message: error.message
    });
  }
});

router.delete('/:id',async (req,res) =>{
  const { id } = req.params;
  const rta = await service.delete(id);
  res.json(rta);
});
...
```

## Middlewares

En el contexto de la programación de software, un middleware es un software que actúa como intermediario entre diferentes aplicaciones o componentes de una misma aplicación. Los middlewares se utilizan para facilitar la comunicación y el intercambio de información entre diferentes sistemas, ya que proporcionan una capa de abstracción que oculta las complejidades de los sistemas subyacentes.

Los middlewares pueden tener diversas funcionalidades, como por ejemplo:

- Transformar los datos de un formato a otro para que puedan ser procesados por diferentes sistemas.
- Proporcionar una capa de seguridad adicional para proteger los datos en tránsito entre diferentes sistemas.
- Controlar y gestionar el flujo de información entre diferentes sistemas para evitar congestiones o cuellos de botella.
- Realizar tareas de autenticación y autorización para garantizar que solo los usuarios autorizados puedan acceder a los datos o servicios ofrecidos por una aplicación.

En resumen, los middlewares son una herramienta muy útil para facilitar la integración y la interoperabilidad entre diferentes sistemas y aplicaciones en el desarrollo de software.

## Middleware para HttpErrors

1. Crear carpeta middlewares
2. crear archivo error.handler.js

```javascript
function logErrors(err, req, res, next) {
  console.error(err);
  next(err);
}

function errorHandler(err, req, res, next) {
  res.status(500).json({
    message: err.message,
    stack: err.stack,
  });
}

module.exports = { logErrors };
```

3. Actualizar index.js

```javascript
const express = require("express");
const routerApi = require("./routes");

const { logErrors, errorHandler } = require("./middlewares/error.handler");

const app = express();
const port = 3000;

app.use(express.json());

app.get("/", (req, res) => {
  res.send("Hello World");
});

routerApi(app);
app.use(logErrors);
app.use(errorHandler);

app.listen(port, () => {
  console.log("Mi port" + port);
});
```

4. Actualizar products.router.js

```javascript
router.get("/:id", async (req, res, next) => {
  try {
    const { id } = req.params;
    const product = await service.findOne(id);
    res.json(product);
  } catch (error) {
    next(error);
  }
});
```

## Manejo de errores con Boom

1. Instalar boom

```bash
 sudo npm i @hapi/boom
```

2. Actualizar error.handler.js

```javascript
function boomErrorHandler(err, req, res, next) {
  if (err.isBoom) {
    const {
      output: { statusCode, payload },
    } = err;
    res.status(statusCode).json(payload);
  } else {
    next(err);
  }
}

module.exports = { logErrors, errorHandler, boomErrorHandler };
```

3. Actualizar index.js

```javascript
...

const {logErrors, errorHandler, boomErrorHandler} = require('./middlewares/error.handler');

...

routerApi(app);
app.use(logErrors);
app.use(boomErrorHandler);
app.use(errorHandler);

...
```

4. Actualizar products.router.js

```javascript
router.post("/", async (req, res) => {
  const body = req.body;
  const newProduct = await service.create(body);
  res.status(201).json(newProduct);
});

router.patch("/:id", async (req, res, next) => {
  try {
    const { id } = req.params;
    const body = req.body;
    const product = await service.update(id, body);
    res.json(product);
  } catch (error) {
    next(error);
  }
});
```

5. Actualizar products.service.js

```javascript
...
const boom = require('@hapi/boom');

class ProductServices {

...

    generate() {
        const limit = 100;
        for (let index = 0; index < limit; index++) {
          this.products.push({
            id: faker.datatype.uuid(),
            name: faker.commerce.productName(),
            price: parseInt(faker.commerce.price(), 10),
            image: faker.image.imageUrl(),
            isBlock: faker.datatype.boolean(),
          });
        }
      }

...

    async findOne(id) {
        const product = this.products.find(item => item.id === id);
        if (!product) {
          throw boom.notFound('product not found');
        }
        if (product.isBlock) {
          throw boom.conflict('product is block');
        }
        return product;
      }

    async update(id, changes){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw boom.notFound('Product not found')
        }
        const product = this.products[index];
        this.products[index] = {
            ...product,
            ...changes
        };
        return this.products[index];
    }

    async delete(id){
        const index = this.products.findIndex(item => item.id === id);
        if (index === -1) {
            throw boom.notFound('Product not found')
        }
        this.products.splice(index,1);
        return {id};
    }
}

...
```

## Validacion de datos con Joi

1. Instalar libreria

```bash
npm i joi
```

2. crear carpeta shemas/products.shema.js

```javascript
const Joi = require("joi");

const id = Joi.string().uuid();
const name = Joi.string().alphanum().min(3).max(15);
const price = Joi.number().integer().min(10);

const createProductSchema = Joi.object({
  name: name.required(),
  price: price.required(),
});

const updateProductSchema = Joi.object({
  name: name,
  price: price,
});

const getProductSchema = Joi.object({
  id: id.required(),
});

module.exports = { createProductSchema, updateProductSchema, getProductSchema };
```

3. Crear Middlewares

```javascript
const boom = require("@hapi/boom");

function validatorHandler(schema, property) {
  return (req, res, next) => {
    const data = req[property];
    const { error } = schema.validate(data);
    error ? next(boom.badRequest(error)) : next();
  };
}

module.exports = validatorHandler;
```

## Probando nuestros endpoints

1. Actualizar products.router.js

```javascript
const express = require('express');

const ProductServices = require('../services/product.service');
const validationHandler = require('../middlewares/validator.handler');
const {createProductSchema, updateProductSchema, getProductSchema} = require('../schemas/product.schema');

...

router.get('/:id',
  validationHandler(getProductSchema, 'params'),
  async (req,res, next) =>{
    try {
      const { id } = req.params;
      const product = await service.findOne(id);
      res.json(product);
    } catch (error) {
      next(error);
    }
  });

router.post('/',
  validationHandler(createProductSchema, 'body'),
  async (req,res) =>{
    const body = req.body;
    const newProduct = await service.create(body);
    res.status(201).json(newProduct);
  });

router.patch('/:id',
  validationHandler(getProductSchema, 'params'),
  validationHandler(updateProductSchema, 'body'),
  async (req, res, next) => {
    try {
      const { id } = req.params;
      const body = req.body;
      const product = await service.update(id, body);
      res.json(product);
    } catch (error) {
      next(error);
    }
  });
...

```

2. Actualizar products.schema.js

```javascript
const Joi = require("joi");

const id = Joi.string().uuid();
const name = Joi.string().min(3).max(15);
const price = Joi.number().integer().min(10);
const image = Joi.string().uri();

const createProductSchema = Joi.object({
  name: name.required(),
  price: price.required(),
  image: image.required(),
});

const updateProductSchema = Joi.object({
  name: name,
  price: price,
});

const getProductSchema = Joi.object({
  id: id.required(),
});

module.exports = { createProductSchema, updateProductSchema, getProductSchema };
```

3. Actualizar validator.handler.js

```javascript
const boom = require("@hapi/boom");

function validatorHandler(schema, property) {
  return (req, res, next) => {
    const data = req[property];
    const { error } = schema.validate(data, { abortEarly: false });
    error ? next(boom.badRequest(error)) : next();
  };
}

module.exports = validatorHandler;
```

# Modulo 2: Express con bases de datos SQL

## Enlaces de interes

1. [Repositorio](https://github.com/platzi/curso-nodejs-postgres)

**Nota: Para este modulo es necesario tener docker instalado en el pc**

_Archivo docker-compose.yml_

```yml
version: "3.3"

services:
  postgres:
    image: postgres:13
    environment:
      - POSTGRES_DB=my_store
      - POSTGRES_USER=nico
      - POSTGRES_PASSWORD=admin123
    ports:
      - 5432:5432
    volumes:
      - ./postgres_data:/var/lib/postgresql/data
```

Para lanzar el contenedor de postgres ejecutar el siguiente comando

```bash
docker-compose up -d postgres
```

## Explorando Postgres: interfaces graficas y terminal

Para acceder a la base de datos desde la terminal ejecutar el siguiente comando

```bash
docker-compose exec postgres bash
```

Para acceder a la base de datos desde la terminal ejecutar el siguiente comando

```bash
psql -h localhost -U nico -d my_store
```

Para salir de la base de datos ejecutar el siguiente comando

```bash
\q
```

Para salir de la terminal ejecutar el siguiente comando

```bash
exit
```

Para acceder mediante una interfaz grafica, se puede utilizar pgAdmin

_En el archivo docker-compose.yml_

```yml
---
pgadmin:
image: dpage/pgadmin4
environment:
  - PGADMIN_DEFAULT_EMAIL=admin@mail.com
  - PGADMIN_DEFAULT_PASSWORD=root
ports:
  - 5050:80
# volumes:
#   - ./pgadmin_data:/var/lib/pgadmin
```

Debes crear un nuevo servidor en la opcion Object -> Create -> Server

Para saber la ip del contenedor de la base de datos ejecutar el siguiente comando

```bash
docker inspect id_contenedor
```

Dentro de la interfaz grafica puedes correr consultas SQL, por ejemplo.

```sql
CREATE TABLE task (
	id serial PRIMARY KEY,
	title VARCHAR ( 250 ) NOT NULL,
	completed boolean DEFAULT false
);
```

El ejemplo anterior te permite crear una tabla llamada task con los campos id, title y completed.

## Integracion de nodejs con postgres

Para instalar la libreria de postgres ejecutar el siguiente comando

```bash
npm i pg
```

[Documentacion](https://node-postgres.com/)

En una carpeta llamada libs crear un archivo llamado postgres.js

```javascript
const { Client } = require("pg");

async function getConnection() {
  const client = new Client({
    host: "localhost",
    port: 5432,
    user: "nico",
    password: "admin123",
    database: "my_store",
  });
  await client.connect();
  return client;
}

module.exports = getConnection;
```

Para conectar un servicio con la base de datos puede tener el siguiente codigo

```javascript
....

const getConnection = require('../libs/postgres');

class UserService {
  constructor() {}

  ....

  async find() {
    const client = await getConnection();
    const rta = await client.query('SELECT * FROM tasks');
    return rta.rows;
  }

  ....
}

module.exports = UserService;
```

## Manejo un Pool de conexiones

No es recomendable crear una conexion cada vez que se necesite una consulta, por lo tanto, es mejor crear un pool de conexiones.

_en el archivo postgres.pool.js_

```javascript
const { Pool } = require("pg");

const pool = new Pool({
  host: "localhost",
  port: 5432,
  user: "nico",
  password: "admin123",
  database: "my_store",
});

module.exports = pool;
```

Para utilizar el pool en cualquier servicio se puede utilizar el siguiente codigo

```javascript
....
const pool = require('../libs/postgres.pool');

class ProductsService {

  constructor(){
    this.products = [];
    this.generate();
    this.pool = pool;
    this.pool.on('error', (err) => console.error(err));
  }

  ....

  async find() {
    const query = 'SELECT * FROM tasks';
    const rta = await this.pool.query(query);
    return rta.rows;
  }
  ....
}

module.exports = ProductsService;
```

[Documentacion](https://node-postgres.com/features/pooling)

## Variables de ambiente en Node.js

Debes instalar la libreria dotenv

```bash
npm i dotenv
```

_En una carpeta llamada config, en un archivo llamado config.js_

```javascript
require("dotenv").config();

const config = {
  env: process.env.NODE_ENV || "dev",
  port: process.env.PORT || 3000,
  dbUser: process.env.DB_USER,
  dbPassword: process.env.DB_PASSWORD,
  dbHost: process.env.DB_HOST,
  dbName: process.env.DB_NAME,
  dbPort: process.env.DB_PORT,
};

module.exports = { config };
```

_En postgress.pool.js_

```javascript
const { Pool } = require("pg");

const { config } = require("./../config/config");

const USER = encodeURIComponent(config.dbUser);
const PASSWORD = encodeURIComponent(config.dbPassword);
const URI = `postgres://${USER}:${PASSWORD}@${config.dbHost}:${config.dbPort}/${config.dbName}`;

const pool = new Pool({ connectionString: URI });

module.exports = pool;
```

_En el archivo .env_

```bash
DB_USER=nico
DB_PASSWORD=admin123
DB_HOST=localhost
DB_NAME=my_store
DB_PORT=5432
```

Tambien puedes tener un archivo env.example para que otras personas puedan saber que variables de entorno deben tener. Este archivo puede ser subido al repositorio y tiene la siguiente estructura.

```bash
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_NAME=
DB_PORT='3000'
```

## ORM: Instalacion y configuracion de Sequelize

Un ORM es una herramienta de programación que permite a los desarrolladores manipular datos a través de un lenguaje de programación orientado a objetos. Los ORM se utilizan para facilitar el desarrollo de aplicaciones que interactúan con una base de datos, ya que permiten a los desarrolladores utilizar objetos en lugar de sentencias SQL para manipular los datos.

[Documentacion](https://sequelize.org/docs/v6/getting-started/)

Para instalar sequelize ejecutar el siguiente comando

```bash
npm i sequelize
```

Para instalar el driver de postgres ejecutar el siguiente comando

```bash
npm i pg pg-hstore
```

_En una archivo sequelize.js_

```javascript
const { Sequelize } = require("sequelize");

const { config } = require("./../config/config");

const USER = encodeURIComponent(config.dbUser);
const PASSWORD = encodeURIComponent(config.dbPassword);
const URI = `postgres://${USER}:${PASSWORD}@${config.dbHost}:${config.dbPort}/${config.dbName}`;

const sequelize = new Sequelize(URI, {
  dialect: "postgres",
  logging: true,
});

module.exports = sequelize;
```

Para utilizar sequelize en cualquier servicio se puede utilizar el siguiente codigo

```javascript
....
const sequelize = require('../libs/sequelize');

class ProductsService {
  constructor(){
    this.products = [];
    this.generate();
  }

  ....

  async find() {
    const query = 'SELECT * FROM tasks';
    const [data] = await sequelize.query(query);
    return data;
  }
  ....
}

module.exports = ProductsService;
```

### Tu primer modelo en Sequelize

Crear una carpeta llamada db/models y dentro de ella crear un archivo llamado user.model.js

```javascript
const { Model, DataTypes, Sequelize } = require("sequelize");

const USER_TABLE = "users";

const UserSchema = {
  id: {
    allowNull: false, // Permite nulos
    autoIncrement: true, // Autoincrementable
    primaryKey: true, // Es llave primaria
    type: DataTypes.INTEGER, // Tipo de dato
  },
  email: {
    allowNull: false,
    type: DataTypes.STRING,
    unique: true, // Es unico
  },
  password: {
    allowNull: false,
    type: DataTypes.STRING,
  },
  createdAt: {
    allowNull: false,
    type: DataTypes.DATE,
    field: "create_at", // Nombre de la columna
    defaultValue: Sequelize.NOW, // Valor por defecto
  },
};

class User extends Model {
  static associate() {
    // associate
  }

  static config(sequelize) {
    return {
      sequelize,
      tableName: USER_TABLE, // Nombre de la tabla
      modelName: "User", // Nombre del modelo
      timestamps: false, // Evita la creacion de los campos createdAt y updatedAt
    };
  }
}

module.exports = { USER_TABLE, UserSchema, User };
```

En el archivo db/models/index.js

```javascript
const { User, UserSchema } = require("./user.model");

function setupModels(sequelize) {
  User.init(UserSchema, User.config(sequelize));
}

module.exports = setupModels;
```

En el archivo lib/sequalize.js

```javascript
....
const setupModels = require('./../db/models');

....

setupModels(sequelize);

sequelize.sync();

module.exports = sequelize;
```

En el archivo users.service.js

```javascript
....
const { models } = require('./../libs/sequelize');

class UserService {
  ....

  async find() {
    const rta = await models.User.findAll();
    return rta;
  }
  ....
}

module.exports = UserService;
```

### Crear, actualizar y eliminar

En el archivo users.service.js

```javascript
const boom = require("@hapi/boom");

const { models } = require("./../libs/sequelize");

class UserService {
  constructor() {}

  async create(data) {
    const newUser = await models.User.create(data);
    return newUser;
  }

  async find() {
    const rta = await models.User.findAll();
    return rta;
  }

  async findOne(id) {
    const user = await models.User.findByPk(id);
    if (!user) {
      throw boom.notFound("user not found");
    }
    return user;
  }

  async update(id, changes) {
    const user = await this.findOne(id);
    const rta = await user.update(changes);
    return rta;
  }

  async delete(id) {
    const user = await this.findOne(id);
    await user.destroy();
    return { id };
  }
}

module.exports = UserService;
```

### Middleware para errores de Sequelize

```js
const { ValidationError } = require('sequelize');
const boom = require('@hapi/boom');

....

function ormErrorHandler(err, req, res, next) {
  if (err instanceof ValidationError) {
    res.status(409).json({
      statusCode: 409,
      message: err.name,
      errors: err.errors
    });
  }
  next(err);
}


module.exports = { logErrors, errorHandler, boomErrorHandler, ormErrorHandler }
```

En el archivo index.js

```javascript
....
const { logErrors, errorHandler, boomErrorHandler, ormErrorHandler } = require('./middlewares/error.handler');

....

app.use(logErrors);
app.use(boomErrorHandler);
app.use(ormErrorHandler);
app.use(errorHandler);
```

## Cambiando a la base de datos a MySQL

En el archivo docker-compose.yml

```yml
version: '3.3'

services:
  ....

  mysql:
    image: mysql:5
    environment:
      - MYSQL_DATABASE=my_store
      - MYSQL_USER=root
      - MYSQL_ROOT_PASSWORD=admin123
      - MYSQL_PORT=3306
    ports:
      - 3306:3306
    volumes:
      - ./mysql_data:/var/lib/mysql

  # Entorno grafico
  phpmyadmin:
    image: phpmyadmin/phpmyadmin
    environment:
      - MYSQL_ROOT_PASSWORD=admin123
      - PMA_HOST=mysql # Nombre del servicio
    ports:
      - 8080:80
```

**Debes instalar el driver de Sequelize para MySQL, tambien debes modificar el archivo .env en el puerto y en sequalize.js debes cambiar el dialect a mysql**

## Migraciones

Las migraciones son una forma de mantener actualizada la estructura de la base de datos a medida que evoluciona una aplicación. Las migraciones se utilizan para crear tablas, modificar tablas existentes y realizar otras operaciones relacionadas con la estructura de la base de datos.

la linea `sequealize.sync()` solo se utiliza para desarrollo. En produccion se debe utilizar migraciones.

Para instalar la libreria de migraciones ejecutar el siguiente comando

```bash
npm i sequelize-cli --save-dev
```

crear un archivo .sequelizerc

```javascript
module.exports = {
  config: "./db/config.js",
  "models-path": "./db/models/",
  "seeders-path": "./db/seeders/",
  "migrations-path": "./db/migrations/",
};
```

la estructura de la carpeta db debe ser la siguiente

```bash
db
├── config.js
├── migrations
├── models
└── seeders
```

dentro de config.js

```javascript
const { config } = require("./../config/config");

const USER = encodeURIComponent(config.dbUser);
const PASSWORD = encodeURIComponent(config.dbPassword);
const URI = `postgres://${USER}:${PASSWORD}@${config.dbHost}:${config.dbPort}/${config.dbName}`;

module.exports = {
  development: {
    url: URI,
    dialect: "postgres",
  },
  production: {
    url: URI,
    dialect: "postgres",
  },
};
```

### Configurando y correindo migraciones con npm scripts

En el archivo package.json configurar un nuevo script

```json
{
  ....
  "scripts": {
    "dev": "nodemon index.js",
    "start": "node index.js",
    "lint": "eslint",
    "migrations:generate": "sequelize-cli migration:generate --name",
    "migrations:run": "sequelize-cli db:migrate",
    "migrations:revert": "sequelize-cli db:migrate:undo",
    "migrations:delete": "sequelize-cli db:migrate:undo:all"
  },
  ....
}
```

Para crear una migracion ejecutar el siguiente comando

```bash
npm run migrations:generate create-users-table
```

Lo primero que debes hacer es dejar de sincronizar la base de datos con el codigo, para eso debes comentar la linea `sequelize.sync()` en el archivo lib/sequelize.js

En el archivo db/migrations/20210904185910-create-users-table.js

```javascript
"use strict";

const { USER_TABLE, UserSchema } = require("./../models/user.model");

module.exports = {
  up: async (queryInterface, Sequelize) => {
    await queryInterface.createTable(USER_TABLE, UserSchema);
  },

  down: async (queryInterface, Sequelize) => {
    await queryInterface.dropTable(USER_TABLE);
  },
};
```

Para correr las migraciones ejecutar el siguiente comando

```bash
npm run migrations:run
```

Para revertir una migracion ejecutar el siguiente comando

```bash
npm run migrations:revert
```

Para revertir todas las migraciones ejecutar el siguiente comando

```bash
npm run migrations:delete
```

### Modificando una entidad con migraciones

1. en user.model.js vamos a incluir el campo role

```javascript
....

const UserSchema = {
  ....
  role: {
    allowNull: false,
    type: DataTypes.STRING,
    defaultValue: 'customer'
  },
  ....
}

....
module.exports = { USER_TABLE, UserSchema, User }
```

2. Crear una nueva migracion

```bash
npm run migrations:generate add-role-to-users
```

3. En el archivo db/migrations/20210904191210-add-role-to-users.js

```javascript
"use strict";

const { USER_TABLE, UserSchema } = require("./../models/user.model");

module.exports = {
  up: async (queryInterface) => {
    await queryInterface.addColumn(USER_TABLE, "role", UserSchema.role);
  },

  down: async (queryInterface) => {
    await queryInterface.removeColumn(USER_TABLE, "role");
  },
};
```

4. Correr la migracion

```bash
npm run migrations:run
```

## Relaciones

### Relaciones uno a uno

En este caso, vamos a implementar la relacion de que un cliente tiene un usuario.

1. Crear un nuevo modelo llamado customer.model.js

```javascript
const { Model, DataTypes, Sequelize } = require('sequelize');

const { USER_TABLE } = require('./user.model')

const CUSTOMER_TABLE = 'customers';

const CustomerSchema =  {
  ....
  userId: {
    field: 'user_id',
    allowNull: false,
    type: DataTypes.INTEGER,
    unique: true,
    references: {
      model: USER_TABLE,
      key: 'id'
    },
    onUpdate: 'CASCADE',
    onDelete: 'SET NULL'
  }
}

class Customer extends Model {

  static associate(models) {
    this.belongsTo(models.User, {as: 'user'}); // La FK esta en este modelo
  }
  ....
}

module.exports = { Customer, CustomerSchema, CUSTOMER_TABLE };
```

En el archivo db/models/index.js

```javascript
const { User, UserSchema } = require("./user.model");
const { Customer, CustomerSchema } = require("./customer.model");

function setupModels(sequelize) {
  User.init(UserSchema, User.config(sequelize));
  Customer.init(CustomerSchema, Customer.config(sequelize));

  User.associate(sequelize.models);
  Customer.associate(sequelize.models);
}

module.exports = setupModels;
```

En el archivo db/migrations/20210904200010-create-customers-table.js

```javascript
"use strict";

const {
  CUSTOMER_TABLE,
  CustomerSchema,
} = require("./../models/customer.model");

module.exports = {
  up: async (queryInterface, Sequelize) => {
    await queryInterface.createTable(CUSTOMER_TABLE, CustomerSchema);
    // await queryInterface.changeColumn(CUSTOMER_TABLE, 'user_id', {
    //   field: 'user_id',
    //   type: Sequelize.INTEGER,
    //   allowNull: false,
    //   unique: true
    // }); // Para cambiar una columna
  },

  down: async (queryInterface, Sequelize) => {
    await queryInterface.dropTable(CUSTOMER_TABLE);
  },
};
```

En el archivo customers.service.js en el metodo create y en el metodo find

```javascript
async find() {
  const rta = await models.Customer.findAll({
    include: ['user'] // Trae los datos del usuario
  });
  return rta;
}


async create(data) {
  const newUser = await models.User.create(data);
  const newCustomer = await models.Customer.create({ userId: newUser.id });
  return newCustomer;
}
```

En user.model.js

```javascript
class User extends Model {
  static associate(models) {
    this.hasOne(models.Customer, {as: 'customer',
    foreignKey: 'userId'}); // La FK esta en el otro modelo
  }
  ....
}
```

Debes modificar en el servicio de usuarios el metodo findAll de igual manera al anterior

_Como puedo crear el usuario en el mismo EndPoint?_

1. En customer.schmema.js debes modificar createCustomerSchema en el campo user

```js
user: Joi.object({
  email: email.required(),
  password: password.required(),
});
```

2. En el archivo customers.service.js debes modificar el metodo create

```js
async create(data) {
  const newCustomer = await models.Customer.create(data, {
    include: ['user']
  });
}
```

## Relaciones 1 a muchos

En este caso, vamos a implementar la relacion de que muchos productos pertenecen a una categoria y un producto pertenece a una categoria.

[Repositorio](https://github.com/platzi/curso-nodejs-postgres/tree/18-step)

en el archivo product.model.js

```js
categoryId: {
  field: 'category_id',
  type: DataTypes.INTEGER,
  allowNull: false,
  references: {
    model: CATEGORY_TABLE,
    key: 'id'
  },
}

class Product extends Model {
  static associate(models) {
    this.belongsTo(models.Category, {as: 'category'});
  }
  ....
}
```

en el archivo category.model.js

```js
class Category extends Model {
  static associate(models) {
    this.hasMany(models.Product, {as: 'products',
    foreignKey: 'categoryId'});
  }
  ....
}
```

en products.service.js

```js
async create(data) {
  const newProduct = await models.Product.create(data);
  return newProduct;
}

async find() {
  const products = await models.Product.findAll({
    include: ['category']
  });
  return products;
}
```

en categories.service.js

```js
async find() {
  const categories = await models.Category.findAll();
  return categories;
}

async findOne(id) {
  const category = await models.Category.findByPk(id, {
    include: ['products']
  });
  return category;
}
```

_Nota:_

Para anidar relaciones se debe utilizar el siguiente codigo

```js
await models.Order.findByPk(id, {
  include: [
    "user",
    {
      association: "products",
      include: ["images"],
    },
  ],
});
```

## Relaciones muchos a muchos

Cuando se tiene relaciones muchos a muchos, se debe crear una tabla intermedia.

En este caso, vamos a implementar la relacion entre orders y products.

[Repositorio](https://github.com/platzi/curso-nodejs-postgres/tree/19-step)

1. Debes crear la tabla intermedia order_products.js. La estructura de la tabla debe ser la siguiente

```js
const { Model, DataTypes, Sequelize } = require("sequelize");

const { ORDER_TABLE } = require("./order.model");
const { PRODUCT_TABLE } = require("./product.model");

const ORDER_PRODUCT_TABLE = "orders_products";

const OrderProductSchema = {
  id: {
    allowNull: false,
    autoIncrement: true,
    primaryKey: true,
    type: DataTypes.INTEGER,
  },
  createdAt: {
    allowNull: false,
    type: DataTypes.DATE,
    field: "created_at",
    defaultValue: Sequelize.NOW,
  },
  amount: {
    allowNull: false,
    type: DataTypes.INTEGER,
  },
  orderId: {
    field: "order_id",
    allowNull: false,
    type: DataTypes.INTEGER,
    references: {
      model: ORDER_TABLE,
      key: "id",
    },
    onUpdate: "CASCADE",
    onDelete: "SET NULL",
  },
  productId: {
    field: "product_id",
    allowNull: false,
    type: DataTypes.INTEGER,
    references: {
      model: PRODUCT_TABLE,
      key: "id",
    },
    onUpdate: "CASCADE",
    onDelete: "SET NULL",
  },
};

class OrderProduct extends Model {
  static associate(models) {
    //
  }

  static config(sequelize) {
    return {
      sequelize,
      tableName: ORDER_PRODUCT_TABLE,
      modelName: "OrderProduct",
      timestamps: false,
    };
  }
}

module.exports = { OrderProduct, OrderProductSchema, ORDER_PRODUCT_TABLE };
```

2. En order.model.js

```js
class Order extends Model {
  static associate(models) {
    this.belongsTo(models.Customer, {as: 'customer'});
    this.belongsToMany(models.Product, {as: 'products', through: models.OrderProduct, foreignKey: 'orderId', otherKey: 'productId'});
  }
  ....
}
```

[Repositorio](https://github.com/platzi/curso-nodejs-postgres/blob/20-step/db/models/order-product.model.js)

_Revisar archivos orden.schema.js, orders.router.js, order.service.js/addItem order.servive.js/findOne, order.model.js_

## Paginacion

en product.service

```js
async find(query) {
  const options = {
    include: ['category'],
  };
  const { limit, offset } = query;
  if (limit && offset) {
    options.limit = limit;
    options.offset = offset;
  }
  const products = await models.Product.findAll(options);
}
```

en product.schema.js

```js
const limit = Joi.number().integer().min(1).max(100);
const offset = Joi.number().integer().min(0);

const queryProductSchema = Joi.object({
  limit: limit,
  offset: offset,
});

module.exports = {
  createProductSchema,
  updateProductSchema,
  getProductSchema,
  queryProductSchema,
};
```

en products.router.js

```js
router.get(
  "/",
  validationHandler(queryProductSchema, "query"),
  async (req, res, next) => {
    try {
      const products = await service.find(req.query);
      res.json(products);
    } catch (error) {
      next(error);
    }
  }
);
```

## Filtrando precios con operadores

[Documentacion](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/#applying-where-clauses)

[Repositorio](https://github.com/platzi/curso-nodejs-postgres/blob/22-step/db/models/order-product.model.js)

_Revisar: product.schema.js_

en product.service.js

```js
async find(query) {
  const options = {
    include: ['category'],
    where: {}
  };
  const { limit, offset, minPrice, maxPrice, price } = query;
  if (limit && offset) {
    options.limit = limit;
    options.offset = offset;
  }
  if (price) {
    options.where.price = price;
  }
  if (minPrice && maxPrice) {
    options.where = {
      price: {
        [Op.gte]: minPrice,
        [Op.lte]: maxPrice
      }
    }
  }
  const products = await models.Product.findAll(options);
  return products;
}
```

## Consideraciones al hacer migraciones en produccion

1. Normalmente, se tiene un esquema inicial con toda la estructura de la base de datos, este esquema se debe crear en produccion con una sola migracion.
2. Es buena practica que las migraciones no dependan de los esquemas. Es mejor tener un codigo largo en las migraciones a que se rompa el codigo.

# Modulo 3: Autenticacion y autorizacion

## Middlerae de verificacion

En la carpeta middlewares crear un archivo llamado auth.handler.js

```js
const boom = require("@hapi/boom");

const checkApiKey = (req, res, next) => {
  const apiKey = req.headers["api"];
  if (apiKey === "123") {
    next();
  } else {
    next(boom.unauthorized());
  }
};

module.exports = checkApiKey;
```

Para utilizar el middleware en una ruta se debe utilizar el siguiente codigo

```js
app.get("/", checkApiKey, (req, res) => {
  res.send("Hello World");
});
```

### Utilizando variables de entorno

En el archivo .env

```bash
API_KEY=123
```

En config.js

```js
const config = {
  ....
  apiKeyToken: process.env.API_KEY
}
```

En auth.handler.js

```js
const { config } = require("./../config/config");

const checkApiKey = (req, res, next) => {
  const apiKey = req.headers["api"];
  if (apiKey === config.apiKey) {
    next();
  } else {
    next(boom.unauthorized());
  }
};
```

## Hashing de contraseñas

Instalar la libreria bcrypt

```bash
npm i bcrypt
```

Para utilizar la libreria en el archivo users.service.js

```js
const bcrypt = require('bcrypt');

async create(data) {
  const hash = await bcrypt.hash(data.password, 10);
  const newUser = await models.User.create({ ...data, password: hash });
  return newUser;
}
```

Es una buena practica devolver el usuario sin la contraseña, para eso se puede utilizar el siguiente codigo

```js
async create(data) {
  const hash = await bcrypt.hash(data.password, 10);
  const newUser = await models.User.create({ ...data, password: hash });
  delete newUser.dataValues.password;
  return newUser;
}
```

En customer.service.js

```js
async create(data) {
  const hash = await bcrypt.hash(data.user.password, 10);
  const newData = {
    ...data,
    user: {
      ...data.user,
      password: hash
    }
  };
  const newCustomer = await models.Customer.create(newCustomer, {
    include: ['user']
  });
  delete newCustomer.dataValues.user.dataValues.password;
  return newCustomer;
}
```

## Login con passport.js

[Documentacion](https://www.passportjs.org/)

Instalar la libreria passport

```bash
npm i passport passport-local
```

En una carpeta utils con la siguiente estructura

```bash
utils
└── auth
    └── strategies
        └── local.strategy.js
    └── index.js
```

En local.strategy.js

```js
const { Strategy } = require("passport-local");
const boom = require("@hapi/boom");
const bcrypt = require("bcrypt");

const UserService = require("./../../services/user.service");
const service = new UserService();

const LocalStrategy = new Strategy(
  {
    usernameField: "email",
    passwordField: "password",
  },
  async (email, password, done) => {
    try {
      const user = await service.findByEmail(email);
      if (!user) {
        return done(boom.unauthorized(), false);
      }
      const isMatch = await bcrypt.compare(password, user.password);
      if (!isMatch) {
        return done(boom.unauthorized(), false);
      }
      delete user.dataValues.password;
      done(null, user);
    } catch (error) {
      done(error, false);
    }
  }
);

module.exports = LocalStrategy;
```

En index.js

```js
const passport = require("passport");

const LocalStrategy = require("./strategies/local.strategy");

passport.use(LocalStrategy);
```

En user.service.js

```js
async findByEmail(email) {
  const user = await models.User.findOne({ where: { email } });
  return user;
}
```

En auth.router.js

```js
const express = require("express");
const passport = require("passport");

const router = express.Router();

router.post(
  "/login",
  passport.authenticate("local", { session: false }),
  async (req, res, next) => {
    try {
      res.json(req.user);
    } catch (error) {
      next(error);
    }
  }
);

module.exports = router;
```

Recuerda incorpotar el router en el archivo router/index.js y modificar el archivo principal de index.js para utilizar la autenticacion.

```js
// index.js
app.use(cors(options));

require("./utils/auth");
```

[Repositorio](https://github.com/platzi/curso-nodejs-auth/tree/5-step)

## Jason Web Tokens (JWT)

JWT es un estándar abierto basado en JSON propuesto por IETF para la creación de tokens de acceso que permiten la propagación de identidad y privilegios entre dos partes en forma de objetos JSON. El token es emitido por un servidor de confianza y se valida en un servidor de recursos, que puede ser el mismo servidor que lo emitió o uno diferente.

[Documentacion](https://jwt.io/)

## Firmar y verificar tokens

Instalar la libreria jsonwebtoken

```bash
npm i jsonwebtoken
```

[Ejemplo en archivos toker.sign y token.verify](https://github.com/platzi/curso-nodejs-auth/tree/6-step)

### Generar JWT en el servicio

en auth.router.js

```js
const express = require('express');
const passport = require('passport');
const jwt = require('jsonwebtoken');

....

router.post('/login',
  passport.authenticate('local', {session: false}),
  async (req, res, next) => {
    try {
      const user = req.user;
      const payload = {
        sub: user.id,
        role: user.role
      }
      const token = jwt.sign(payload, config.jwtSecret);
      res.json({
        user,
        token
      });
    } catch (error) {
      next(error);
    }
  }
);

module.exports = router;
```

El secret debe estar en una variable de entorno.

[Pagina para crear secretos](https://keygen.io/)

Vamos a utilizar el algoritmo WEP 256-bit Key

```bash
JWT_SECRET='NakKxrw14WEQJIhnzyVseoqMfUpl9v36'
```

# Falta terminar modulo verificacion

# Modulo 4: Nest.js

NestJS es un potente framework de NodeJS para la construcción de aplicaciones del lado del servidor. NestJS ha crecido mucho en los últimos años y se ha convertido en una de las principales opciones que los desarrolladores eligen para la programación de APIs con NodeJS. Gracias a la utilización de TypeScript y la Programación Orientada a Objetos, es un framework ideal para iniciar en el desarrollo backend.

## Crea tu primer proyecto con NestJS

Cuando se inicia con una nueva tecnología, el primer paso es el ya conocido “Hola Mundo”. Realizar la instalación por primera vez del framework o lenguaje para asegurar que este esté funcionando. Asegúrate de tener instalado en tu ordenador tanto NodeJS como NPM. Se recomienda al menos NodeJS versión 10 u 12.

Puedes verificar la versión de Node con el comando

```bash
node --version
```

y de NPM con el comando

```bash
npm --version
```

Una vez los hayas instalado, es hora de instalar el CLI de NestJS de forma global con el comando

```bash
npm install -g @nestjs/cli
```

Una vez instalado el CLI, verifica que el proceso es correcto con el comando

```bash
nest --version
```

Para crear tu primer proyecto con este framework basta con utilizar el comando

```bash
nest new <project-name>
cd <project-name>
```

El CLI te realizará una pregunta sobre qué gestor de dependencias quieres utilizar, para este ejemplo, escojeremos NPM. Luego de algunos segundos, tu primer proyecto estará listo.

Ahora, utiliza el comando

```bash
npm run start
```

para levantar el servidor de pruebas básico que trae consigo NestJS y finalmente, ingresa a http://localhost:3000/ para visualizar tu primer “Hola Mundo” con esta tecnología.

## Estructura de un proyecto NestJS

NestJS es un framework que utiliza la arquitectura MVC (Modelo-Vista-Controlador) para la construcción de aplicaciones del lado del servidor. NestJS posee desde el inicio de un proyecto varios directorios y archivos que se generan por defecto al crearlo. Veamos para que te sirve cada uno.

1. Node_modules:
   Todo proyecto de Javascript posee este directorio donde se almacenan las librerías y dependencias que se descarguen con NPM.

2. SRC:
   Directorio principal del proyecto donde encontramos:

- app.controller.spec.ts: archivo de pruebas unitarias del controlador con el mismo nombre.
- app.controller.ts: controlador que contiene endpoints a diferentes recursos.
- app.module.ts: módulo principal de toda la aplicación NestJS.
- app.service.ts: servicio consumido por los controladores para determinados propósitos.
- main.ts: archivo Core de la aplicación NestJS donde se realizan configuraciones e imports básicos para su funcionamiento

3. Test:
   Directorio de pruebas unitarias y de integración. NestJS utiliza por defecto Jest para escribir las pruebas.

- .editorconfig: este archivo no viene por defecto, pero se recomienda crearlo e instalar el plugin con el mismo nombre en el editor. Permite autoformatear los archivos, espacios, indentación, etc.
- .eslintrc.js: permite la configuración de un analizador de código para detectar tempranamente errores y resolverlos. Requiere instalación de un plugin en el editor.
- .gitignore: indicarle a GIT qué archivos/directorios ignorar.
- .prettierrc: archivo de configuración para el autoformateo de código. Requiere instalación de un plugin en el editor.
- nest-cli.json: archivo con configuraciones de NestJS. Algunos plugins del framework requieren de configuraciones adicionales en este archivo.
- package-lock.json: describe las dependencias exactas que se generaron en la instalación del proyecto.
- package.json: archivo para el manejo de dependencias, scripts y metadatos relevantes para el proyecto.
- README.md: archivo markdown para la documentación del proyecto.
- tsconfig.build.json: archivo principal para la configuración de TypeScript
- tsconfig.json: extensión con más configuraciones de TypeScript.

_Archivo ./editorconfig_

```bash
# ./editorconfig
# Editor configuration, see https://editorconfig.org
root = true

[*]
charset = utf-8
indent_style = space
indent_size = 2
insert_final_newline = true
trim_trailing_whitespace = true

[*.ts]
quote_type = single

[*.md]
max_line_length = off
trim_trailing_whitespace = false
```

## Repaso a TS: tipos y POO

NestJS utiliza TypeScript como lenguaje de programación y conocer sus características y qué le adiciona a Javascript te convertirá en un profesional más completo de esta tecnología.

### Qué es TypeScript

TypeScript es un lenguaje de programación mantenido por Microsoft. En otras palabras, es un “superconjunto” de Javascript que le agrega tipado de datos y programación orientada a objetos.

El código fuente escrito en TypeScript, se “transpila” a código Javascript que es el que finalmente entienden los intérpretes de Javascript como los navegadores web o NodeJS.

### Tipado de Datos con TypeScript

Con Javascript puedes crear una variable del tipo String y posteriormente asignarle un valor del tipo Entero o Boolean. Esto es propenso a tener errores en tiempo de ejecución.
TypeScript permite tipar los datos para que estos no cambien de tipo.

```ts
// Tipado de datos con TypeScript
const text: string;
const num: number;
const bool: boolean:
const arr: Array<number>[];

// Safe type
let name: string;
const age = 19;
const suma = (a: number, b:number) => {
   return a + b;
}

// Clases
class Person {
   constructor(private age: number, private name: string) {}

   getSummary() {
      return `I'm ${this.name} and I'm ${this.age}`;
   }
}
```

### Programación Orientada a Objetos con TypeScript

TypeScript es un lenguaje de programación orientado a objetos. Esto quiere decir que puedes crear clases, interfaces, herencia, etc.

```ts
// Programación Orientada a Objetos con TypeScript
class Alumno {
  private nombre: string;
  private apellido: string;

  constructor(nombre: string, apellido: string) {
    this.nombre = nombre;
    this.apellido = apellido;
  }

  getNombre() {
    return this.nombre;
  }
  setNombre(nuevoNombre: string) {
    this.nombre = nuevoNombre;
  }
}
const alumno = new Alumno("Freddy", "Vega");
alumno.setNombre("Freddy Vega");
console.log(alumno.getNombre());
```

## REST API con NestJS

## Controladores

El concepto más básico para desarrollar una aplicación con NestJS son los Controladores. Los Controladores manejarán las rutas o endpoints que la aplicación necesite, además de validar los permisos del usuario, filtro y manipulación de datos

## Estructura de un controlador

La aplicación de NestJS creada por defecto con el CLI trae consigo un controlador básico con el nombre app.controller.ts. Verás que dicho archivo contiene una clase que a su vez posee un decorador llamado @Controller().

Dicho decorador le indica al compilador de NestJS que esta clase tendrá el comportamiento de un controlador.

```ts
// app.controller.ts
import { Controller, Get } from "@nestjs/common";
import { AppService } from "./app.service";

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get()
  getHello(): string {
    return this.appService.getHello();
  }
}
```

Los controladores deben ser importados en un módulo para que sean reconocidos los endpoints.

```ts
// app.module.ts
import { Module } from "@nestjs/common";
import { AppController } from "./app.controller";

@Module({
  imports: [],
  controllers: [
    // Imports de Controladores
    AppController,
  ],
})
export class AppModule {}
```

El controlador importa un servicio que son los responsables de la lógica y obtención de datos desde una BBDD que el controlador requiere.

```ts
// app.service.ts
import { Injectable } from "@nestjs/common";

@Injectable()
export class AppService {
  getHello(): string {
    return "Hello World!";
  }
}
```

Puedes correr el servidor de NestJS con el comando `npm run start:dev` e ingresar a la ruta localhost:3000/ para visualizar el contenido que el controlador envía.

Si quieres crear una nueva ruta, basta con crear un método en la clase del controlador y colocarle el decorador @Get() con un nombre para el nuevo endpoint.

```ts
// app.controller.ts
@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get()
  getHello(): string {
    return this.appService.getHello();
  }

  @Get("new-endpoint")
  newEndpoint(): string {
    return "New endpoint";
  }
}
```

Ingresa a esta nueva ruta desde localhost:3000/new-endpoint para visualizar su respuesta y así crear los endpoints que necesites.

## GET: como recibir parametros

Existen diferentes tipos de endpoints que se identifican a través de los Verbos HTTP. Cada uno con un propósito determinado siguiendo el protocolo.

En particular, el verbo GET suele utilizarse para endpoints que permiten la obtención de datos como un producto o una lista de productos.

Es frecuente la necesidad de que este tipo de endpoints también reciban información dinámica en las URL como el identificador de un producto.

Para capturar estos datos en NestJS, tienes que importar el decorador Param desde @nestjs/common y emplearlo de la siguiente manera en tus endpoints.

```ts
import { Controller, Get, Param } from "@nestjs/common";
import { AppService } from "./app.service";

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get("product/:idProduct")
  getProduct2(@Param("idProduct") idProduct: string): string {
    return `Producto id: ${idProduct}`;
  }

  @Get("categories/:id/products/:productId")
  getCategory(@Param("productId") productId: string, @Param("id") id: string) {
    return `product ${productId} and ${id}`;
  }
}
```

## Parametros query

Hay varias maneras de enviar información a un endpoint del tipo GET, cada una con sus ventajas y desventajas. Profundicemos acerca de ellas.

Los parámetros de ruta son aquellos que forman parte del propio endpoint y suelen ser parámetros obligatorios. Por otro lado, están los parámetros de consulta o query en las URL como por ejemplo example.com/products?limit=10&offset=20 que se capturan con el decorador @Query() importado desde @nestjs/common.

```ts
@Get('products')
getProducts(@Query('limit') limit = 10, @Query('offset') offset = 0): string {
    return `Lista de productos limit=${limit} offset=${offset}`;
}
```

Su principal diferencia es que los parámetros de consulta suelen ser opcionales; el comportamiento del endpoint tiene que contemplar que estos datos pueden no existir con un valor por defecto.

Los parámetros de ruta se utilizan para IDs u otros identificadores obligatorios, mientras que los parámetros de consulta se utilizan para aplicar filtros opcionales a una consulta. Utilízalos apropiadamente en tus endpoints según tengas la necesidad.

**Evitando el bloqueo de rutas**
Un importante consejo a tener en cuenta para construir aplicaciones con NestJS es asegurar que un endpoint no esté bloqueando a otro.
Por ejemplo:

```ts
/* Ejemplo Bloqueo de Endpoints */
@Get('products/:idProduct')
endpoint1() {
    // ...
}
@Get('products/filter')
endpoint2() {
    // ...
}
```

El endpoint1 bloquea al \*\*endpoint2, ya que este está esperando un parámetro :idProduct y si llamamos a localhost:3000/products/filter NestJS entenderá que la palabra filter es el ID que espera el primer endpoint ocasionando que no sea posible acceder al segundo endpoint.

Se soluciona de forma muy sencilla invirtiendo el orden de los mismos. Coloca los endpoints dinámicos en segundo lugar para que no ocasionen problemas.

```ts
/* Solución Bloqueo de Endpoints */
@Get('products/filter')
endpoint2() {
    // ...
}
@Get('products/:idProduct')
endpoint1() {
    // ...
}
```

Este es un inconveniente común que suele suceder en NestJS y es importante que lo conozcas para evitar dolores de cabeza.

## Separacion de responsabilidades

NestJS le da mucha importancia a los Principios SOLID en el desarrollo de software para mantener las buenas prácticas de codificación. Una de ellas es la responsabilidad única

La S de SOLID hace referencia a “Single Responsibility” y recomienda que cada pieza de software debe tener una única función. Por ejemplo, un controlador de productos no debería encargarse de categorías o de usuarios. Se debe crear un controlador para cada entidad que la aplicación necesite.

Lo mismo ocurre con los métodos. Un método para la obtención de datos solo debe realizar dicha acción y no estar actualizando o manipulando los datos de otra manera.

## Responsabilidades en NestJS

En NestJS, una buena práctica es crear un directorio llamado controllers donde se agruparán todos los controladores que tu aplicación necesite. Ese ya es un buen paso para mantener el orden en tu proyecto.

Apóyate del CLI de NestJS para autogenerar código rápidamente con el comando

```bash
nest generate controller <controller-name> <controller-name>.
```

o en su forma corta

```bash
nest g co <controller-name>.
```

Es una buena forma de comenzar a seguir las buenas prácticas a la hora de escribir código y estructurar una aplicación.

```bash
nest g cor controllers/categories --flat
```

src/controllers/categories.controller.ts

```ts
import { Controller, Get, Param } from "@nestjs/common";

@Controller("categories") // 👈 Route
export class CategoriesController {
  @Get(":id/products/:productId")
  getCategory(@Param("productId") productId: string, @Param("id") id: string) {
    return `product ${productId} and ${id}`;
  }
}
```

```bash
nest g co controllers/products --flat
```

src/controllers/products.controller.ts

```ts
import { Controller, Get, Query, Param } from "@nestjs/common";

@Controller("products") // 👈 Route
export class ProductsController {
  @Get()
  getProducts(
    @Query("limit") limit = 100,
    @Query("offset") offset = 0,
    @Query("brand") brand: string
  ) {
    return `products limit=> ${limit} offset=> ${offset} brand=> ${brand}`;
  }

  @Get("filter")
  getProductFilter() {
    return `yo soy un filter`;
  }

  @Get(":productId")
  getProduct(@Param("productId") productId: string) {
    return `product ${productId}`;
  }
}
```

src/app.module.ts

```ts
import { Module } from "@nestjs/common";
import { AppController } from "./app.controller";
import { AppService } from "./app.service";
import { ProductsController } from "./controllers/products.controller";
import { CategoriesController } from "./controllers/categories.controller";

@Module({
  imports: [],
  controllers: [
    AppController,
    ProductsController, // 👈 New controller
    CategoriesController, // 👈 New controller
  ],
  providers: [AppService],
})
export class AppModule {}
```

## Metodo POST

Así como el verbo HTTP GET se utiliza para la obtención de datos, el verbo HTTP Post se utiliza para la creación de los mismos previamente.

El metodo post se utiliza para crear un recurso en el servidor, por ejemplo, crear un usuario, crear un producto, crear una categoria, etc.

En tu proyecto NestJS, tienes que importar los decoradores Post y Body desde @nestjs/common. El primero para indicar que el endpoint es del tipo POST y el segundo para capturar los datos provenientes del front-end en el cuerpo del mensaje.

```ts
import { Controller, Post, Body } from "@nestjs/common";

@Controller()
export class AppController {
  @Post("product")
  createProducto(@Body() body: any): any {
    return {
      name: body.name,
      price: body.price,
    };
  }
}
```

Un buen endpoint del tipo POST tiene que devolver el registro completo recientemente insertado en la BBDD para que el front-end pueda actualizarse inmediatamente y no tener que realizar una consulta por el mismo.

Recuerda también que, al tratarse de un endpoint POST, no puedes realizar la solicitud desde el navegador al igual que con los endpoints GET. Para probar tu aplicación, tienes que utilizar una plataforma de APIs como Postman.

```ts
import { ..., Post, Body } from '@nestjs/common';

@Controller('products')
export class ProductsController {
  ...

  @Post() // 👈 New decorator
  create(@Body() payload: any) {
    return {
      message: 'accion de crear',
      payload,
    };
  }
}
```

## Metodo PUT y DELETE

El verbo HTTP GET se utiliza para la obtención de datos y el verbo POST para la creación de estos. También existe el verbo PUT y DELETE para la actualización y borrado de datos respectivamente.

El verbo PUT se usa para la actualización de un registro en la BBDD. Suele recibir un Body con los datos a actualizar, pero también es importante que reciba el ID del registro para buscar al mismo.

```ts
import { Controller, Put, Param, Body } from "@nestjs/common";
import { AppService } from "./app.service";

@Controller()
export class AppController {
  @Put("product/:idProduct")
  updateProducto(
    @Param("idProduct") idProduct: string,
    @Body() body: any
  ): any {
    return {
      idProduct: idProduct,
      name: body.newName,
      price: body.newPrice,
    };
  }
}
```

El ID suele recibirse por parámetros de URL para que sea obligatorio, mientras que reservamos el cuerpo del mensaje para los datos actualizados. Finalmente, retornamos el registro completo luego de ser actualizado.

## Eliminar datos con Delete

Eliminar un registro es sencillo. Basta con decorar el endpoint con DELETE. Suele recibir el ID del registro a borrar únicamente.

```ts
import { Controller, Delete, Param } from "@nestjs/common";
import { AppService } from "./app.service";

@Controller()
export class AppController {
  @Delete("product")
  deleteProducto(@Param("idProduct") idProduct: string): any {
    return {
      idProduct: idProduct,
      delete: true,
      count: 1,
    };
  }
}
```

Una buena práctica para este tipo de endpoints es retornar un booleano que indique si el registro fue eliminado o no. Además de incluir un count que indique cuántos registros fueron eliminados.

src/controllers/products.controller.ts

```ts
import {..., Put, Delete } from '@nestjs/common';

@Controller('products')
export class ProductsController {
  ...
  @Put(':id')
  update(@Param('id') id: number, @Body() payload: any) {
    return {
      id,
      payload,
    };
  }

  @Delete(':id')
  delete(@Param('id') id: number) {
    return id;
  }
}
```

## Codigos de estado HTTP

El protocolo HTTP tiene estandarizado una lista de códigos de estado que indican los tipos de respuesta que las API deben enviar dependiendo la situación. Como profesional en el desarrollo de software, debes conocerlos y diferenciarlos. Hay cinco familias de códigos de estado HTTP que tienes que utilizar apropiadamente para que tus APIs informen correctamente la situación de la solicitud.

- Estados informativos (100–199)
- Estados de éxito (200–299)
- Estados de redirección (300–399)
- Estados de error del cliente (400–499)
- Estados de error del servidor (500–599)

## Status Codes en Nest JS

En NestJS, puedes manejar los códigos de estado HTTP importando el decorador HttpCode y el enumerado HttpStatus desde @nestjs/common.

El primero te servirá para indicar cuál será el código de estado HTTP que un endpoint tiene que devolver; el segundo para ayudarte por si no recuerdas qué código pertenece a cada tipo de respuesta.

```ts
import { Controller, HttpCode, HttpStatus } from '@nestjs/common';

@Get('product/:idProduct')
@HttpCode(HttpStatus.OK)
getProduct2(@Param('idProduct') idProduct: string): string {
    return `Producto id: ${idProduct}`;
}

@Post('product')
@HttpCode(HttpStatus.CREATED)
createProducto(@Body() body: any): any {
    return {
      name: body.name,
      price: body.price
    };
}
```

El enumerado HttpStatus.OK indica código de estado 200 que es el que suele devolver por defecto todos los endpoints cuando la operación sale exitosamente. Los endpoints POST suelen devolver HttpStatus.CREATED o código 201 para indicar la creación exitosa del registro.

src/controllers/products.controller.ts

```ts
import { ..., HttpStatus, HttpCode, Res } from '@nestjs/common';
import { Response } from 'express';

@Controller('products')
export class ProductsController {
  ...
  @Get(':productId')
  @HttpCode(HttpStatus.ACCEPTED) // 👈 Using decorator
  getOne(
    @Res() response: Response,
    @Param('productId') productId: string
  ) {
    response.status(200).send({...}); // 👈 Using express directly
  }
}
```

## Integridad de datos

## Servicios

Los servicios en NestJS son los que suelen tener la lógica del negocio y la conexión con la base de datos.

Los servicios son una pieza esencial de las aplicaciones realizadas con el framework NestJS. Están pensados para proporcionar una capa de acceso a los datos que necesitan las aplicaciones para funcionar.

Un servicio tiene la responsabilidad de gestionar el trabajo con los datos de la aplicación, de modo que realiza las operaciones para obtener esos datos, modificarlos, etc.

## Creando un servicio

Para crear un servicio puedes utilizar el comando

```bash
nest generate service <service-name>
```

o su forma corta

```bash
nest g s <service-name>
```

```ts
// app.service.ts
import { Injectable } from "@nestjs/common";

@Injectable()
export class AppService {
  getHello(): string {
    return "Hello World!";
  }
}
```

Los servicios utilizan el decorador @Injectable() y deben ser importados en los providers del módulo al que pertenecen o tu aplicación no lo reconocerá y tendrás errores al levantar el servidor.

```ts
// app.module.ts
import { Module } from "@nestjs/common";
import { AppService } from "./app.service";

@Module({
  imports: [],
  providers: [
    // Imports de Servicios
    AppService,
  ],
})
export class AppModule {}
```

Crea un método en el servicio para cada propósito que necesites. Uno para obtener un producto, otro para obtener un listado de productos. Uno para crear producto, para actualizar, eliminar, etc.

## Servicios en NestJS

```ts
// src/entities/product.entity.ts

export class Product {
  id: number;
  name: string;
  description: string;
  price: number;
  stock: number;
  image: string;
}
```

```bash
nest g s services/products --flat
```

```ts
// src/services/products.service.ts
import { Injectable } from "@nestjs/common";

import { Product } from "./../entities/product.entity";

@Injectable()
export class ProductsService {
  private counterId = 1;
  private products: Product[] = [
    {
      id: 1,
      name: "Product 1",
      description: "bla bla",
      price: 122,
      image: "",
      stock: 12,
    },
  ];

  findAll() {
    return this.products;
  }

  findOne(id: number) {
    return this.products.find((item) => item.id === id);
  }

  create(payload: any) {
    this.counterId = this.counterId + 1;
    const newProduct = {
      id: this.counterId,
      ...payload,
    };
    this.products.push(newProduct);
    return newProduct;
  }
}
```

```ts
// src/app.module.ts
import { Module } from '@nestjs/common';
...
import { ProductsService } from './services/products.service';

@Module({
  imports: [],
  controllers: [...],
  providers: [AppService, ProductsService], // 👈 New Service
})
export class AppModule {}
```

## Implementando servicios en tu controlador

Los servicios son el otro 50% de los controladores. Podría decirse que un controlador siempre hará uso de uno o más servicios para implementar lógica de negocio. Veamos cómo se relacionan.

## Inyeccion de dependencias

Antes de hablar de la relación entre servicios y controladores, hay que hablar del patrón de diseño que NestJS utiliza internamente.

Imagínate que tienes un Servicio A que utiliza el Servicio B y este a su vez utiliza el Servicio C. Si tuvieses que instanciar el Servicio A, primero deberías instanciar el C para poder instanciar el B y luego sí hacerlo con el A. Se vuelve confuso y poco escalable si en algún momento también tienes que instanciar el Servicio D o E.

La inyección de dependencias llega para solucionar esto, resolver las dependencias de una clase por nosotros. Cuando instanciamos en el constructor el Servicio A, NestJS internamente crea automáticamente la instancia del servicio B y C sin que nosotros nos tengamos que preocupar por estos.

## Controladores y servicios

Los controladores inyectan los servicios desde el constructor. De esta manera, cada endpoint puede hacer uso de la lógica del servicio.

```ts
import { Controller, Get } from "@nestjs/common";
import { AppService } from "./app.service";

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get()
  getHello(): string {
    return this.appService.getHello();
  }
}
```

Importa los servicios que necesites, pero hazlo de una manera controlada para mantener la escalabilidad de tu proyecto. Si necesitas importar 20 servicios en un mismo controlador, tal vez tengas que mejorar la estructura del proyecto.

## Controllers

```ts
// src/controllers/products.controller.ts

import { ProductsService } from './../services/products.service';


@Controller('products')
export class ProductsController {
  constructor(private productsService: ProductsService) {}

  @Get()
  getProducts(...) {
    return this.productsService.findAll();
  }

  @Get(':productId')
  getOne(...) {
    return this.productsService.findOne(+productId);
  }

  @Post()
  create(..) {
    return this.productsService.create(payload);
  }

  @Put(':id')
  update(...) {
    return this.productsService.update(+id, payload);
  }
}
```

**Refactor update**

```ts
// src/services/products.service.ts
 update(id: number, payload: any) {
    const product = this.findOne(id);
    if (product) {
      const index = this.products.findIndex((item) => item.id === id);
      this.products[index] = {
        ...product,
        ...payload,
      };
      return this.products[index];
    }
    return null;
  }
```

## Manejo de errores con throw y NotFoundException

Desarrollar una API correctamente también implica manejar los errores que sus endpoints pueden tener de manera clara para el front-end.

## Manejo de errores

NestJS implementa de forma muy sencilla la posibilidad de responder con errores al cliente que realiza las consultas. Esto lo hace con una serie de clases que implementan los códigos HTTP correctos dependiendo el tipo de error que necesites.

```ts
import { NotFoundException } from '@nestjs/common';

@Get('product/:idProduct')
@HttpCode(HttpStatus.OK)
async getProduct(@Param('idProduct') idProduct: string): string {
  const product = await this.appService.getProducto(idProduct);
  if (!product) {
      throw new NotFoundException(`Producto con ID #${idProduct} no encontrado.`);
  }
  return product;
}
```

Importando NotFoundException puedes arrojar un error con la palabra reservada throw indicando que un registro no fue encontrado. Esta excepción cambiará el estado HTTP 200 que envía el decorador @HttpCode(HttpStatus.OK) por un 404 que es el correspondiente para la ocasión.

También puedes lanzar errores cuando el usuario no tiene permisos para acceder a un recurso.

```ts
import { ForbiddenException } from '@nestjs/common';

@Get('product/:idProduct')
@HttpCode(HttpStatus.OK)
async getProduct(@Param('idProduct') idProduct: string): string {
  // ...
  throw new ForbiddenException(`Acceso prohibido a este recurso.`);
}
```

O incluso lanzar errores de la familia del 5XX cuando ocurre un error inesperado en el servidor.

```ts
import { InternalServerErrorException } from '@nestjs/common';

@Get('product/:idProduct')
@HttpCode(HttpStatus.OK)
async getProduct(@Param('idProduct') idProduct: string): string {
  // ...
  throw new InternalServerErrorException(`Ha ocurrido un error inesperado.`);
}
```

Explora todas las clases con estados HTTP que NestJS posee para desarrollar tus endpoints de manera profesional y manejar correctamente los errores.

[Codigos de errores en Next](https://docs.nestjs.com/exception-filters#built-in-http-exceptions)

**SRC services**

```ts
// src/services/products.service.ts

import { ..., NotFoundException } from '@nestjs/common';

@Injectable()
export class ProductsService {
  ...

  findOne(id: number) {
    const product = this.products.find((item) => item.id === id);
    if (!product) {
      throw new NotFoundException(`Product #${id} not found`);
    }
    return product;
  }

  update(id: number, payload: any) {
    const product = this.findOne(id);
    const index = this.products.findIndex((item) => item.id === id);
    this.products[index] = {
      ...product,
      ...payload,
    };
    return this.products[index];
  }

  remove(id: number) {
    const index = this.products.findIndex((item) => item.id === id);
    if (index === -1) {
      throw new NotFoundException(`Product #${id} not found`);
    }
    this.products.splice(index, 1);
    return true;
  }
}
```

```ts
// src/controllers/products.controller.ts

  @Delete(':id')
  delete(@Param('id') id: string) {
    return this.productsService.remove(+id);
  }
```

## Pipes

NestJS utiliza el concepto de PIPES para la validación y transformación de los datos antes del ingreso de estos a un controlador.

**Casos de uso de PIPES**
Los pipes tienen dos casos de uso típicos:

- Transformación: transforma los datos de entrada a la forma deseada (por ejemplo, de cadena a entero).
- Validación: evalúa los datos de entrada y, si son válidos, simplemente los pasa sin cambios; de lo contrario, lanza una excepción cuando los datos son incorrectos.

### Implementación de PIPES

NestJS ya trae consigo una serie de pipes que puedes utilizar para la manipulación de datos. Impórtalos desde @nestjs/common y úsalos de la siguiente manera.

```ts
import { ParseIntPipe } from '@nestjs/common';

@Get('product/:idProduct')
getProduct(@Param('idProduct', ParseIntPipe) idProduct: string): string {
    // ...
}
```

El pipe ParseIntPipe, agrégalo como segundo parámetro del decorador Param para transformar el parámetro idProduct y asegurar que este sea un número entero.

De no serlo, arrojará un error y al mismo tiempo estás protegiendo tu aplicación de datos erróneos o maliciosos.

Explora todos los PIPES que NestJS ya tiene preparados para ti.

[PIPES en Nest](https://docs.nestjs.com/pipes#built-in-pipes)

```ts
// src/controllers/products.controller.ts
import {..., ParseIntPipe} from '@nestjs/common';

@Get(':id')
get(@Param('id', ParseIntPipe) id: number) {
  return this.productsService.findOne(id);
}
```

## Crea tu propio Pipe

Crear tus propias validaciones de datos será muy importante para segurizar tu aplicación y evitar errores inesperados. Con el CLI de NestJS autogenera un nuevo pipe con el comando.

```bash
nest generate pipe <pipe-name>
```

o en su forma corta

```bash
nest g p <pipe-name>
```

Por defecto, verás un código como el siguiente.

```ts
import { ArgumentMetadata, Injectable, PipeTransform } from "@nestjs/common";

@Injectable()
export class ParseIntPipe implements PipeTransform {
  transform(value: any, metadata: ArgumentMetadata) {
    return value;
  }
}
```

**Implementar un pipe**
Implementa aquí tu propia lógica de transformación y validación de datos. Ten en cuenta que si los datos no son válidos, puedes arrojar excepciones para informarle al front-end que los datos son erróneos.

```ts
import {
  ArgumentMetadata,
  Injectable,
  PipeTransform,
  BadRequestException,
} from "@nestjs/common";

@Injectable()
export class ParseIntPipe implements PipeTransform {
  transform(value: string, metadata: ArgumentMetadata) {
    const finalValue = parseInt(value, 10);
    if (isNaN(finalValue)) {
      throw new BadRequestException(`${value} no es un número.`);
    }
    return finalValue;
  }
}
```

**Importa y utiliza el Pipe**
Finalmente, implementa tu custom PIPE en el controlador

```ts
import { ParseIntPipe } from './pipes/parse-int.pipe';

@Get('product/:idProduct')
getProduct(@Param('idProduct', ParseIntPipe) idProduct: string): string {
    // ...
}
```

Puedes desarrollar la lógica para validar y transformar los datos que más se adecue a tus necesidades. Es fundamental no permitir el ingreso de datos erróneos a tus controladores. Por eso, los pipes son una capa previa a los controladores para realizar esta validación.

## Generar un pipe con nest g pi common/parse-int

```ts
// src/common/parse-int.pipe.ts

import {
  ArgumentMetadata,
  Injectable,
  PipeTransform,
  BadRequestException,
} from "@nestjs/common";

@Injectable()
export class ParseIntPipe implements PipeTransform {
  transform(value: string, metadata: ArgumentMetadata) {
    const val = parseInt(value, 10);
    if (isNaN(val)) {
      throw new BadRequestException(`${value} is not an number`);
    }
    return val;
  }
}
```

## Creando Data Transfer Objects (DTOs)

NestJS utiliza el concepto de Objetos de Transferencia de Datos, o simplemente abreviado como DTO, para el tipado de datos y su segurización.

### ¿Qué es un DTO?

Los DTO no son más que clases customizadas que tu mismo puedes crear para indicar la estructura que tendrán los objetos de entrada en una solicitud.

### Creando un DTO

Crea un nuevo archivo que por lo general lleva como extensión .dto.ts para indicar que se trata de un DTO.

```ts
// products.dto.ts
export class CreateProductDTO {
  readonly name: string;
  readonly description: string;
  readonly price: number;
  readonly image: string;
}
```

La palabra reservada readonly es propia de TypeScript y nos asegura que dichos datos no sean modificados.

Crea tantos atributos como tu clase CreateProductDTO necesite para dar de alta un nuevo producto.

### Importando un DTO

Importa la clase en tu controlador para tipar el Body del endpoint POST para la creación de un producto.

```ts
import { CreateProductDTO } from 'products.dto.ts';

@Post('product')
createProducto(@Body() body: CreateProductDTO): any {
    // ...
}
```

De esta forma, ya conoces la estructura de datos que tendrá el parámetro body previo a la creación de un producto.

#### SRC:DTOS

```ts
// src/dtos/products.dtos.ts
export class CreateProductDto {
  readonly name: string;
  readonly description: string;
  readonly price: number;
  readonly stock: number;
  readonly image: string;
}

export class UpdateProductDto {
  readonly name?: string;
  readonly description?: string;
  readonly price?: number;
  readonly stock?: number;
  readonly image?: string;
}
```

```ts
// src/controllers/products.controller.ts
export class ProductsController {
  @Post()
  create(@Body() payload: CreateProductDto) { // 👈 Dto
    ...
  }

  @Put(':id')
  update(
    @Param('id') id: string,
    @Body() payload: UpdateProductDto  // 👈 Dto
   ) {
   ...
  }
}
```

```ts
// src/services/products.service.ts
export class ProductsService {
  create(payload: CreateProductDto) { // 👈 Dto
    ...
  }

  update(id: number, payload: UpdateProductDto) { // 👈 Dto
    ...
  }
}
```

## Validando parametros con class-validator y mapped-types

Los DTO no solo sirven para tipar y determinar la estructura de los datos de entrada de un endpoint, también pueden contribuir en la validación de los datos y en la entrega de mensajes al front-end en caso de error en los mismos.

### Validacion de datos con DTO

Utiliza el comando

```bash
npm i class-validator class-transformer
```

para instalar las dependencias necesarias para la validación de datos. Estas librerías traen un set de decoradores para las propiedades de los DTO y así validar los tipos de datos de entrada

```ts
import { IsNotEmpty, IsString, IsNumber, IsUrl } from "class-validator";

export class CreateProductDTO {
  @IsNotEmpty()
  @IsString()
  readonly name: string;

  @IsNotEmpty()
  @IsString()
  readonly description: string;

  @IsNotEmpty()
  @IsNumber()
  readonly price: number;

  @IsNotEmpty()
  @IsUrl()
  readonly image: string;
}
```

Estas validaciones contribuyen en la experiencia de desarrollo devolviendo mensajes al front-end sobre qué datos están faltando o cuáles no son correctos. Por ejemplo, si en el Body de la petición enviamos.

```json
{
  "name": "Nombre producto",
  "price": 100,
  "image": "imagen"
}
```

El servidor nos devolvera el siguiente mensaje

```json
{
  "statusCode": 400,
  "message": [
    "description should not be empty",
    "description must be a string",
    "image must be an URL address"
  ],
  "error": "Bad Request"
}
```

Indicando que la solicitud espera de forma obligatoria un campo description del tipo string y un campo image con una URL.

### Como reutilizar los DTO

A medida que tu aplicación crezca, tendrás que crear muchos DTO, para la creación de un producto, edición, filtros, etc. Una buena práctica es la reutilización de las clases DTO que ya tengas implementado para no repetir propiedades.

Instalar mapped-types

```bash
npm i @nestjs/mapped-types
```

Para ello, puedes utilizar la librería @nestjs/mapped-types que nos permite extender una clase DTO ya existente y agregarle nuevas propiedades.

```ts
import {
  IsNotEmpty,
  IsString,
  IsNumber,
  IsUrl,
  IsPositive,
} from "class-validator";
import { PartialType, OmitType } from "@nestjs/mapped-types";

export class CreateProductDTO {
  @IsNotEmpty()
  @IsString()
  readonly name: string;

  @IsNotEmpty()
  @IsString()
  readonly description: string;

  @IsNotEmpty()
  @IsNumber()
  @IsPositive()
  readonly price: number;

  @IsNotEmpty()
  @IsUrl()
  readonly image: string;
}

export class UpdateProductDto extends PartialType(
  OmitType(CreateProductDTO, ["name"])
) {}
```

Importa PartialType y OmitType desde @nestjs/mapped-types

PartialType permite extender una clase de otra y que todos sus campos sean opcionales. Así, el DTO UpdateProductDto no tiene como obligatorio sus campos y es posible editar todos o solo uno.

Por otro lado, OmitType, permite la omisión de campos haciendo que cierta cantidad de ellos no formen parte del DTO en el caso de que dichos campos no deban ser editados.

Instalar

```bash
 npm i class-validator class-transformer @nestjs/mapped-types
```

```ts
// src/dtos/products.dtos.ts
import {
  IsString,
  IsNumber,
  IsUrl,
  IsNotEmpty,
  IsPositive,
} from "class-validator";
import { PartialType } from "@nestjs/mapped-types";

export class CreateProductDto {
  @IsString()
  @IsNotEmpty()
  readonly name: string;

  @IsString()
  @IsNotEmpty()
  readonly description: string;

  @IsNumber()
  @IsNotEmpty()
  @IsPositive()
  readonly price: number;

  @IsNumber()
  @IsNotEmpty()
  @IsPositive()
  readonly stock: number;

  @IsUrl()
  @IsNotEmpty()
  readonly image: string;
}

export class UpdateProductDto extends PartialType(CreateProductDto) {}
```

```ts
// src/main.ts
import { ValidationPipe } from '@nestjs/common';

async function bootstrap() {
  ...
  app.useGlobalPipes(new ValidationPipe());
  ...
}
bootstrap();
```

## Como evitar parametros incorrectos

Los DTO ayudan con el tipado y la validación de datos, además de indicar la obligatoriedad de los mismos para que los registros se creen completos. Es importante también evitar que haya datos que no deben estar en las solicitudes, ya que podrían ser ataques maliciosos.

### Como hacer la prohibicion de datos

Busca el archivo main.ts que contiene el bootstrap de tu aplicación, es decir, el punto inicial de la misma. Agrega aquí la siguiente configuración.

```ts
// main.ts
import { NestFactory } from "@nestjs/core";
import { ValidationPipe } from "@nestjs/common";
import { AppModule } from "./app.module";

async function bootstrap() {
  const app = await NestFactory.create(AppModule);
  app.useGlobalPipes(
    new ValidationPipe({
      whitelist: true, // Ignorar datos que no esten en los DTO
      forbidNonWhitelisted: true, // Lanzar error si existen datos prohibidos
      disableErrorMessages: true, // Desabilitar mensajes de error (producción)
    })
  );
  await app.listen(process.env.PORT || 3000);
}
bootstrap();
```

Importa ValidationPipe desde @nestjs/common y configura en true las propiedades whitelist para ignorar datos que no estén en el DTO. Usa forbidNonWhitelisted para lanzar errores si existen datos prohibidos y disableErrorMessages que es recomendable activarlo solo en producción para no enviar mensajes de error y no dar información al front-end.

De esta simple manera, tus endpoints gracias a los DTO son súper profesionales, seguros y contribuyen a una buena experiencia de desarrollo.

```ts
// src/main.ts

app.useGlobalPipes(
  new ValidationPipe({
    whitelist: true,
    forbidNonWhitelisted: true,
  })
);
```

# Modulo 5: Programacion modular

## Encapsular logica en modulos

Las aplicaciones profesionales que se desarrollan con NestJS se realizan de forma modularizada para dividir el código fuente de forma lógica y que el proyecto sea más escalable y comprensible. Para modularizar una aplicación, el CLI de NestJS trae consigo la posibilidad de autogenerar módulos con el comando

```bash
nest generate module <module-name>
```

o en su forma corta

```bash
nest g mo <module-name>
```

Los módulos son simples clases que utilizan el decorador @Module() para importar todo lo que construyan al mismo.

```ts
import { Module } from "@nestjs/common";

@Module({
  imports: [], // Importación de otros módulos
  controllers: [], // Importación de controladores
  providers: [], // Importación de servicios
})
export class PruebaModule {}
```

De esta manera, un módulo agrupará un conjunto de controladores y servicios, además de importar otros módulos. A partir de aquí, tu aplicación podría tener un módulo para usuarios, otro para productos, otro para comentarios, etc. Crea tantos módulos como tu aplicación necesite.

**Ejemplo**

![01](https://i.imgur.com/ozsw0eb.png)

Donde los módulos deberían quedar asi:

```ts
// src/products/products.module.ts
import { Module } from "@nestjs/common";

import { ProductsController } from "./controllers/products.controller";
import { BrandsController } from "./controllers/brands.controller";
import { CategoriesController } from "./controllers/categories.controller";
import { ProductsService } from "./services/products.service";
import { BrandsService } from "./services/brands.service";
import { CategoriesService } from "./services/categories.service";

@Module({
  controllers: [ProductsController, CategoriesController, BrandsController],
  providers: [ProductsService, BrandsService, CategoriesService],
  exports: [ProductsService],
})
export class ProductsModule {}
```

```ts
// src/users/users.module.ts
import { Module } from "@nestjs/common";

import { CustomerController } from "./controllers/customers.controller";
import { CustomersService } from "./services/customers.service";
import { UsersController } from "./controllers/users.controller";
import { UsersService } from "./services/users.service";

import { ProductsModule } from "../products/products.module";

@Module({
  imports: [ProductsModule],
  controllers: [CustomerController, UsersController],
  providers: [CustomersService, UsersService],
})
export class UsersModule {}
```

```ts
// src/app.module.ts
import { Module } from "@nestjs/common";
import { AppController } from "./app.controller";
import { AppService } from "./app.service";
import { UsersModule } from "./users/users.module";
import { ProductsModule } from "./products/products.module";

@Module({
  imports: [UsersModule, ProductsModule],
  controllers: [AppController],
  providers: [AppService],
})
export class AppModule {}
```

## Interaccion entre modulos

Dentro de un módulo, puedes tener la necesidad de utilizar un servicio que pertenece a otro módulo. Importar estos servicios en otros módulos requiere de un paso adicional. Si tienes un Módulo A que posee un Servicio A y un segundo Módulo B requiere hacer uso de este, debes exportar el servicio para que otro módulo pueda utilizarlo.

```ts
// Módulo A
import { ServiceA } from "./service-A.service";

@Module({
  providers: [ServiceA],
  exports: [ServiceA],
})
export class ModuleA {}
```

```ts
// Módulo B
import { ServiceA } from "./module-A/service-A.service";

@Module({
  providers: [ServiceA],
})
export class ModuleB {}
```

Debes indicar en la propiedad exports del decorador @Module() que un módulo es exportable para que otro módulo pueda importarlo en sus providers.

De esta manera, evitas errores de compilación de tu aplicación que ocurren cuando importas servicios de otros módulos que no están siendo exportados correctamente.

**Ejemplo**

A continuación, podrás ver el código que necesitas para hacer que los módulos interactúen entre sí.

```ts
// src/users/entities/order.entity.ts
import { User } from "./user.entity";
import { Product } from "./../../products/entities/product.entity";

export class Order {
  //  // 👈 new entity
  date: Date;
  user: User;
  products: Product[];
}
```

```ts
// src/users/controllers/users.controller.ts
  @Get(':id/orders') //  👈 new endpoint
  getOrders(@Param('id', ParseIntPipe) id: number) {
    return this.usersService.getOrderByUser(id);
  }
```

```ts
// src/users/services/users.service.ts

...
import { Order } from '../entities/order.entity';

import { ProductsService } from './../../products/services/products.service';


@Injectable()
export class UsersService {
  constructor(private productsService: ProductsService) {}
  ...

  getOrderByUser(id: number): Order { // 👈 new method
    const user = this.findOne(id);
    return {
      date: new Date(),
      user,
      products: this.productsService.findAll(),
    };
  }
}
```

```ts
// src/products/products.module.ts

import { Module } from '@nestjs/common';

....

@Module({
  controllers: [ProductsController, CategoriesController, BrandsController],
  providers: [ProductsService, BrandsService, CategoriesService],
  exports: [ProductsService], // 👈 Export ProductsService
})
export class ProductsModule {}
```

```ts
// src/users/users.module.ts
import { Module } from '@nestjs/common';

...

import { ProductsModule } from '../products/products.module';

@Module({
  imports: [ProductsModule], // 👈 Import ProductsModule
  controllers: [CustomerController, UsersController],
  providers: [CustomersService, UsersService],
})
export class UsersModule {}
```

## Entendiendo la inyeccion de dependencias

Es muy sencillo crear un servicio en NestJS, inyectarlo en un componente y utilizar su lógica. A pesar de esto, siempre es recomendable entender cómo lo está haciendo y qué sucede por detrás en tu aplicación.

**Patrones de diseño de NestJS**

NestJS utiliza varios Patrones de Diseño para permitir que esto funcione. Te presentamos dos para tener en cuenta:

**1. Inyección de dependencias**

Imagínate que tienes un Servicio A que utiliza el Servicio B y este a su vez utiliza el Servicio C. Si tuvieses que instanciar el Servicio A, primero deberías instanciar el C para poder instanciar el B y luego sí hacerlo con el A. Se vuelve confuso y poco escalable si en algún momento también tienes que instanciar el Servicio D o E.

La inyección de dependencias llega para solucionar esto, resolver las dependencias de una clase por nosotros. Cuando instanciamos en el constructor el Servicio A, NestJS por detrás genera automáticamente la instancia del servicio B y C sin que nosotros nos tengamos que preocupar por estos.

**2. Singleton**

La inyección de dependencias no es el único patrón de diseño que NestJS utiliza con sus servicios. También hace uso del patrón Singleton para crear una instancia única de cada servicio. Así es como, si tienes un servicio que se utiliza en N cantidad de componentes (u otros servicios) todos estos estarán utilizando la misma instancia del servicio, compartiendo el valor de sus variables y todo su estado.

## Precaucion utilizando servicios

Un servicio puede ser importado en muchos componentes u otros servicios a la vez. Puedes inyectar la cantidad de servicio que quieras en un componente, siempre de una forma controlada y coherente.

![02](https://static.platzi.com/media/user_upload/Circular%20dependency-0c7642ea-5281-4561-b20c-1bd97bfee9ba.jpg)

Solo debes tener cuidado con las dependencias circulares. Cuando un servicio importa a otro y este al anterior. NestJS no sabrá cuál viene primero y tendrás un error al momento de compilar tu aplicación.

[Buenas prácticas en desarrollo de software: POO, SOLID y Patrones de Diseño](https://platzi.com/blog/poo-solid-patrones/)

[Inyección de Dependencias vs. Inversión de Dependencias: ¿cuál es la diferencia?](https://platzi.com/blog/inyeccion-de-dependencias/)

## useClass

Esta es la forma más común de inyectar un servicio en un módulo. Cuando utilizas el decorador @Injectable() en un servicio, este se convierte en un proveedor de la aplicación. Esto quiere decir que puedes inyectarlo en cualquier componente o servicio de tu aplicación.

```ts
import { AppService } from "./app.service";

@Module({
  providers: [AppService],
})
export class AppModule {}
```

Internamente, NestJS realiza lo siguiente:

```ts
import { AppService } from "./app.service";

@Module({
  providers: [
    {
      provide: AppService,
      useClass: AppService,
    },
  ],
})
export class AppModule {}
```

Ambas sintaxis son equivalentes, useClass es el tipo de inyección por defecto. Básicamente, indica que un servicio debe utilizar X clase para funcionar. Si el día de mañana, por algún motivo en tu aplicación, el servicio AppService queda obsoleto y tienes que reemplazarlo por uno nuevo, puedes realizar lo siguiente:

```ts
import { AppService2 } from "./app.service";

@Module({
  providers: [
    {
      provide: AppService,
      useClass: AppService2,
    },
  ],
})
export class AppModule {}
```

De este modo, no tienes necesidad de cambiar el nombre AppService en todos los controladores donde se utiliza, este será reemplazado por la nueva versión del servicio.

## useValue

Además de clases, puedes inyectar valores como un string o un número. useValue suele utilizarse para inyectar globalmente en tu aplicación la llave secreta de una API o alguna otra variable de entorno que tu app necesita.

Para esto, simplemente inyecta el valor de una constante en el providers.

```ts
const API_KEY = "1324567890";

@Module({
  providers: [
    {
      provide: "API_KEY",
      useValue: API_KEY,
    },
  ],
})
export class AppModule {}
```

Importa este valor en los controladores u otros servicios donde se necesite de la siguiente manera:

```ts
import { Controller, Inject } from "@nestjs/common";

@Controller()
export class AppController {
  constructor(@Inject("API_KEY") private apiKey: string) {}
}
```

Ahora tienes a disposición el valor de este dato en tu controlador para utilizarlo en lo que necesites.

**Cuadro de codigos para inyeccion de servicios**

```ts
// src/app.module.ts
...

const API_KEY = '12345634';
const API_KEY_PROD = 'PROD1212121SA';

@Module({
  imports: [UsersModule, ProductsModule],
  controllers: [AppController],
  providers: [
    AppService,
    {
      provide: 'API_KEY',
      useValue: process.env.NODE_ENV === 'prod' ? API_KEY_PROD : API_KEY,
    },
  ],
})
export class AppModule {}
```

```ts
// src/app.service.ts
import { Injectable, Inject } from "@nestjs/common";

@Injectable()
export class AppService {
  constructor(@Inject("API_KEY") private apiKey: string) {} // 👈 Inject API_KEY
  getHello(): string {
    return `Hello World! ${this.apiKey}`;
  }
}
```

```ts
// src/app.controller.ts

@Controller()
export class AppController {
  @Get()
  getHello(): string {
    // 👈 new enpoint
    return this.appService.getHello();
  }
}
```

## Use Factory

NestJS permite inyecciones de servicios o datos que necesiten de alguna petición HTTP o algún proceso asíncrono. El tipo de inyección useFactory permite que realices un proceso asíncrono para inyectar un servicio o datos provenientes de una API.

_A partir de NestJS v8, el servicio HttpService importado desde @nestjs/common fue deprecado. Instala la dependencia @nestjs/axios e impórtalo desde ahí. No deberás realizar ningún otro cambio en tu código. También debes asegurarte de importar el módulo HttpModule desde la misma dependencia._

Debes instalar el modulo con el siguiente comando

```bash
npm install @nestjs/axios
```

```ts
import { HttpService } from "@nestjs/axios";

@Module({
  providers: [
    {
      provide: "DATA",
      useFactory: async (http: HttpService) => {
        return await http.get("").toPromise();
      },
      inject: [HttpService],
    },
  ],
})
export class AppModule {}
```

La propiedad inject permite que inyectes (valga la redundancia) dentro de esta función asíncrona del useFactory otros servicios que este pueda necesitar. En el ejemplo anterior, se está haciendo una llamada a un request para obtener datos.

Importa estos datos en el controlador que lo necesite de la siguiente manera.

```ts
import { Controller, Inject } from "@nestjs/common";

@Controller()
export class AppController {
  constructor(@Inject("DATA") private data: any[]) {}
}
```

Así podrás hacer uso de estos datos que fueron cargados de forma asíncrona. Ten en cuenta que, al realizar una solicitud asíncrona, el controlador dependerá de la finalización de este proceso para estar disponible, pudiendo retrasar el inicio de tu aplicación. Esta funcionalidad suele utilizarse para conexiones de base de datos o procesos asíncronos similares.

**Cuadro de codigo para inyeccion de servicios useFactory**

```ts
// src/app.module.ts
import { Module, HttpModule, HttpService } from '@nestjs/common';  // 👈 imports

@Module({
  imports: [HttpModule, UsersModule, ProductsModule],
  controllers: [AppController],
  providers: [
    imports: [HttpModule, UsersModule, ProductsModule], // 👈 add HttpModule
    ...,
    {
      provide: 'TASKS',
      useFactory: async (http: HttpService) => { // 👈 implement useFactory
        const tasks = await http
          .get('https://jsonplaceholder.typicode.com/todos')
          .toPromise();
        return tasks.data;
      },
      inject: [HttpService],
    },
  ],
})
export class AppModule {}
```

```ts
// src/app.service.ts

import { Injectable, Inject } from "@nestjs/common";

@Injectable()
export class AppService {
  constructor(
    @Inject("API_KEY") private apiKey: string,
    @Inject("TASKS") private tasks: any[] // 👈 inject TASKS
  ) {}
  getHello(): string {
    console.log(this.tasks); // 👈 print TASKS
    return `Hello World! ${this.apiKey}`;
  }
}
```

en versiones 8 y posteriores

```ts
// src/app.module.ts
import { Module } from '@nestjs/common';
import { HttpModule, HttpService } from '@nestjs/axios'; //
import { lastValueFrom } from 'rxjs';

@Module({
  imports: [HttpModule, UsersModule, ProductsModule],
  controllers: [AppController],
  providers: [
    imports: [HttpModule, UsersModule, ProductsModule], // 👈 add HttpModule
    ...,
    {
      provide: 'TASKS',
      useFactory: async (http: HttpService) => { // 👈 implement useFactory
        const request = http
          .get('https://jsonplaceholder.typicode.com/todos');
        const task = await lastValueFrom(request);
        return tasks.data;
      },
      inject: [HttpService],
    },
  ],
})
export class AppModule {}
```

```ts
// src/app.service.ts

import { Injectable, Inject } from "@nestjs/common";

@Injectable()
export class AppService {
  constructor(
    @Inject("API_KEY") private apiKey: string,
    @Inject("TASKS") private tasks: any[] // 👈 inject TASKS
  ) {}
  getHello(): string {
    console.log(this.tasks); // 👈 print TASKS
    return `Hello World! ${this.apiKey}`;
  }
}
```

## Global Module

Al desarrollar una aplicación con NestJS, existen necesidades de importar módulos cruzados o de importar un mismo servicio en varios módulos. Lo anterior, hace que la cantidad de imports en cada módulo crezca y se vuelva complicado de escalar. NestJS otorga la posibilidad de crear módulos globales que se importarán automáticamente en todos los otros módulos de la aplicación, sin necesidad de importarlos explícitamente

```ts
import { Module, Global } from "@nestjs/common";

@Global()
@Module({
  // ...
})
export class MyCustomModule {}
```

Todos los servicios que importes en este módulo, estarán disponibles para su utilización en cualquier otro módulo. Es importante no abusar de esta característica y no tener más de un módulo global para controlar las importaciones. Pueden ocurrir errores de dependencias circulares que suceden cuando el Módulo A importa al Módulo B y este a su vez importa al Módulo A. El decorador @Global() te ayudará a resolver estos problemas.

**Cuadro de codigo para global module**

```ts
// src/database/database.module.ts

import { Module, Global } from "@nestjs/common";

const API_KEY = "12345634";
const API_KEY_PROD = "PROD1212121SA";

@Global()
@Module({
  providers: [
    {
      provide: "API_KEY",
      useValue: process.env.NODE_ENV === "prod" ? API_KEY_PROD : API_KEY,
    },
  ],
  exports: ["API_KEY"],
})
export class DatabaseModule {}
```

```ts
// src/app.module.ts
...
import { DatabaseModule } from './database/database.module';

@Module({
  imports: [
    HttpModule,
    UsersModule,
    ProductsModule,
    DatabaseModule // 👈 Use DatabaseModule like global Module
   ],
  ...
})
export class AppModule {}
```

```ts
// src/users/services/users.service.ts

import { Injectable, NotFoundException, Inject } from '@nestjs/common';
..

@Injectable()
export class UsersService {
  constructor(
    private productsService: ProductsService,
    @Inject('API_KEY') private apiKey: string, // 👈 Inject API_KEY
  ) {}
}
```

## Módulo de configuración

A medida que tu aplicación crezca, puedes llegar a necesitar decenas de variables de entorno. Variables que cambian de valor dependiendo si estás en un entorno de desarrollo, de pruebas o de producción.

```ts
import { ConfigModule } from "@nestjs/config";

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: ".env",
      isGlobal: true,
    }),
  ],
})
export class AppModule {}
```

El archivo que almacena las variables de entorno suele llamarse .env. Créalo en la raíz de tu proyecto con las variables que necesitas.

```ts
// .env
API_KEY = 1324567890;
API_SECRET = ABCDEFGHI;
```

De esta manera, las variables de entorno estarán disponibles en tu aplicación y utilizando el objeto global de NodeJS llamado process puedes acceder a estos valores de la siguiente manera:

```ts
process.env.API_KEY;
process.env.API_SECRET;
```

### Consejos sobre las variables de entorno

Es muy importante NO VERSIONAR el archivo .env en el repositorio de tu proyecto. No guardes las claves secretas de tu aplicación en GIT. Para asegurar esto, agrega el archivo .env a la configuración del archivo .gitignore para que no sea reconocido por Git y este no lo guarde en el repositorio. Lo que puedes hacer es crear un archivo llamado .env.example que contendrá un modelo de las variables de entorno que tu aplicación necesita, pero no sus valores.

```ts
API_KEY=
API_SECRET=
```

De este modo, cuidas tu aplicación y guardas un archivo para que cualquier desarrollador que tome el proyecto, sepa 3}qué variables necesita configurar para el funcionamiento de la misma.

**Cuadro de código para usar el módulo de configuración**

```bash
npm install --save @nestjs/config
```

**En el repo, hubo un problema al instalar la anterior dependencia**

```ts
// .gitignore
*.env
```

```ts
// .env
DATABASE_NAME = my_db;
API_KEY = "1234";
```

```ts
// src/app.module.ts
...
import { ConfigModule } from '@nestjs/config';

@Module({
  imports: [
    ConfigModule.forRoot({ // 👈 Implement ConfigModule
      envFilePath: '.env',
      isGlobal: true,
    }),
    ...
  ],
})
export class AppModule {}
```

```ts
// src/users/services/users.service.ts
import { ConfigService } from '@nestjs/config';
...

@Injectable()
export class UsersService {
  constructor(
    private productsService: ProductsService,
    private configService: ConfigService, // 👈 inject ConfigService
  ) {}
  ...

  findAll() {
    const apiKey = this.configService.get('API_KEY'); // 👈 get API_KEY
    const dbName = this.configService.get('DATABASE_NAME');  // 👈 get DATABASE_NAME
    console.log(apiKey, dbName);
    return this.users;
  }
  ...
}
```

## Configuracion por ambiente

Una aplicación profesional suele tener más de un ambiente. Ambiente local, ambiente de desarrollo, ambiente de pruebas, producción, entre otros, dependiendo la necesidad del equipo y de la organización. Veamos cómo puedes administrar N cantidad de ambientes en NestJS.

Configuremos la aplicación para intercambiar fácilmente entre diversos ambientes, cada uno con su propia configuración.

1. Archivo principal para manejo de ambientes: Crea un archivo llamado enviroments.ts (o el nombre que prefieras) que contendrá un objeto con una propiedad por cada ambiente que tenga tu aplicación.

```ts
// src/enviroments.ts
export const enviroments = {
  dev: ".env",
  test: ".test.env",
  prod: ".prod.env",
};
```

2. **Configuración por ambiente**
   Crea un archivo .env por cada ambiente que necesites. Recuerda que todos los archivos finalizados en .env no deben guardarse en GIT.

```ts
// .test.env
DATABASE_NAME = my_db_test;
API_KEY = 12345;
```

```ts
// .prod.env
DATABASE_NAME = my_db_prod;
API_KEY = 67890;
```

3. **Importando variables de entorno**
   Importa en el módulo principal de tu aplicación el archivo principal para manejo de ambientes y, a través de una única variable de entorno llamada NODE_ENV, elegirás qué configuración usar.

_NODE_ENV es una variable de entorno propia de NodeJS y del framework Express que se encuentra preseteada en tu aplicación._

```ts
import { enviroments } from "./enviroments"; // 👈

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: enviroments[process.env.NODE_ENV] || ".env", // 👈
      isGlobal: true,
    }),
  ],
})
export class AppModule {}
```

4.  **Inicio de la aplicación**
    Finalmente, para iniciar tu aplicación basta con el comando
    `NODE_ENV=test npm run start:dev` o `NODE_ENV=prod npm run start:dev` para configurar la variable de entorno principal NODE_ENV y escoger qué configuración utilizar.

5.  **Utilizando las variables de entorno**
    Puedes utilizar las variables de entorno en tu aplicación de dos maneras. Con el objeto global de NodeJS llamado process:

```ts
process.env.DATABASE_NAME;
process.env.API_KEY;
```

O puedes usar estas variables a través del servicio ConfigService proveniente de @nestjs/config.

```ts
import { ConfigService } from "@nestjs/config";

@Injectable()
export class AppService {
  constructor(private config: ConfigService) {}

  getEnvs(): string {
    const apiKey = this.config.get<string>("API_KEY");
    const name = this.config.get("DATABASE_NAME");
    return `Envs: ${apiKey} ${name}`;
  }
}
```

De este modo, configura de la mejor manera que necesites para tu aplicación el manejo de múltiples ambientes, cada uno con su propia configuración.

**Cuadro de código para configuración por ambiente**

```ts
// .stag.env
DATABASE_NAME = my_db_stag;
API_KEY = 333;
```

```ts
// .prod.env
DATABASE_NAME = my_db_prod;
API_KEY = 999;
```

```ts
// src/enviroments.ts
export const enviroments = {
  dev: ".env",
  stag: ".stag.env",
  prod: ".prod.env",
};
```

```ts
// src/app.module.ts
...

import { enviroments } from './enviroments'; // 👈

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: enviroments[process.env.NODE_ENV] || '.env', // 👈
      isGlobal: true,
    }),
    ...
  ],
  ...
})
export class AppModule {}
```

```ts
// src/app.service.ts
import { ConfigService } from "@nestjs/config"; // 👈

@Injectable()
export class AppService {
  constructor(
    @Inject("TASKS") private tasks: any[],
    private config: ConfigService // 👈
  ) {}
  getHello(): string {
    const apiKey = this.config.get<string>("API_KEY"); // 👈
    const name = this.config.get("DATABASE_NAME"); // 👈
    return `Hello World! ${apiKey} ${name}`;
  }
}
```

Run with NODE ENV

```bash
NODE_ENV=prod npm run start:dev
NODE_ENV=stag npm run start:dev
```

## Tipado en config

A medida que tu aplicación acumule más y más variables de entorno, puede volverse inmanejable y es propenso a tener errores el no recordar sus nombres o escribirlos mal. A continuación verás como tipar variables.

Seguriza tu lista de variables de entorno de manera que evites errores que son difíciles de visualizar. Veamos cómo puedes tipar tus variables.

1. **Archivo de tipado de variables**
   Crea un archivo al que denominaremos config.ts que contendrá el tipado de tu aplicación con ayuda de la dependencia @nestjs/config.

```ts
// src/config.ts
import { registerAs } from "@nestjs/config";

export default registerAs("config", () => {
  return {
    database: {
      name: process.env.DATABASE_NAME,
      port: process.env.DATABASE_PORT,
    },
    apiKey: process.env.API_KEY,
  };
});
```

Importa registerAs desde @nestjs/config que servirá para crear el tipado de datos. Crea un objeto con la estructura de datos que necesita tu aplicación. Este objeto contiene los valores de las variables de entorno tomados con el objeto global de NodeJS, process

2. **Importando el archivo de tipado**
   Importa el nuevo archivo de configuración en el módulo de tu proyecto de la siguiente manera para que este sea reconocido.

```ts
import { ConfigModule } from "@nestjs/config";
import config from "./config";

@Global()
@Module({
  imports: [
    HttpModule,
    ConfigModule.forRoot({
      envFilePath: ".env",
      load: [config],
      isGlobal: true,
    }),
  ],
})
export class AppModule {}
```

3. **Tipado de variables de entorno**
   Es momento de utilizar este objeto que genera una interfaz entre nuestra aplicación y las variables de entorno para no confundir el nombre de cada variable.

```ts
import { Controller, Inject } from "@nestjs/common";
import { ConfigType } from "@nestjs/config";
import config from "./config";

@Controller()
export class AppController {
  constructor(
    @Inject(config.KEY) private configService: ConfigType<typeof config>
  ) {}

  getEnvs(): string {
    const apiKey = this.configService.apiKey;
    const name = this.configService.database.name;
    return `Envs: ${apiKey} ${name}`;
  }
}
```

Observa la configuración necesaria para inyectar y tipar tus variables de entorno. Ahora ya no tendrás que preocuparte por posibles errores al invocar a una de estas variables y evitar dolores de cabeza debugueando estos errores.

**Cuadro de código para tipado en config**

```ts
// .env
DATABASE_NAME=my_db_prod
API_KEY=999
DATABASE_PORT=8091 // 👈

// .stag.env
DATABASE_NAME=my_db_stag
API_KEY=333
DATABASE_PORT=8091 // 👈

// .prod.env
DATABASE_NAME=my_db_prod
API_KEY=999
DATABASE_PORT=8091 // 👈

// src/config.ts // 👈 new file
import { registerAs } from '@nestjs/config';

export default registerAs('config', () => { // 👈 export default
  return {
    database: {
      name: process.env.DATABASE_NAME,
      port: process.env.DATABASE_PORT,
    },
    apiKey: process.env.API_KEY,
  };
});

// src/app.module.ts
import config from './config'; // 👈

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: enviroments[process.env.NODE_ENV] || '.env',
      load: [config], // 👈
      isGlobal: true,
    }),
    ...
  ],
  ...
})
export class AppModule {}

// src/app.service.ts
import { ConfigType } from '@nestjs/config'; // 👈 Import ConfigType
import config from './config'; // 👈 config file

@Injectable()
export class AppService {
  constructor(
    @Inject('TASKS') private tasks: any[],
    @Inject(config.KEY) private configService: ConfigType<typeof config>, // 👈
  ) {}
  getHello(): string {
    const apiKey = this.configService.apiKey; // 👈
    const name = this.configService.database.name; // 👈
    return `Hello World! ${apiKey} ${name}`;
  }
}
```

## Validacion de esquemas en .envs con Joi

Las variables de entorno son sensibles, pueden ser requeridas o no, pueden ser un string o un number. Validemos tus variables de entorno para evitar errores u omisiones de las mismas

Instala la dependencia Joi con el comando `npm instal joi --save`. La misma nos dará las herramientas para realizar validaciones de nuestras variables de entorno.

Importa Joi en el módulo de tu aplicación y a través de la propiedad validationSchema del objeto que recibe el ConfigModule crea el tipado y las validaciones de tus variables de entorno.

```ts
import { ConfigModule } from '@nestjs/config';
import * as Joi from 'joi';

import config from './config';

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: '.env',
      load: [config],
      isGlobal: true,
      validationSchema: Joi.object({
        API_KEY: Joi.string().required(),
        DATABASE_NAME: Joi.string().required(),
        DATABASE_PORT: Joi.number().required(),
      })
    }),
  ],
  ],
})
export class AppModule {}
```

Lo que hace Joi es asegurar que, en el archivo .env, existan las variables de entorno indicadas dependiendo si son obligatorias o no, además de validar el tipo para no ingresar un string donde debería ir un number.

En equipos de trabajo profesional, quienes suelen desplegar las aplicaciones en los entornos es el equipo DevOpsy ellos no necesariamente saben qué variables de entorno necesita tu aplicación y de qué tipo son. Gracias a esta configuración, tu app emitirá mensajes de error claros por consola cuando alguna variable no sea correcta.

**Cuadro de código para validacion de esquemas en .envs con Joi**

```ts
// src/app.module.ts

import * as Joi from 'joi';  // 👈

@Module({
  imports: [
    ConfigModule.forRoot({
      envFilePath: enviroments[process.env.NODE_ENV] || '.env',
      load: [config],
      isGlobal: true,
      validationSchema: Joi.object({ // 👈
        API_KEY: Joi.number().required(),
        DATABASE_NAME: Joi.string().required(),
        DATABASE_PORT: Joi.number().required(),
      }),
    }),
    ...
  ],
  ...
})
export class AppModule {}
```

# Modulo 6: Documentacion con Swagger

Una API profesional debe estar documentada. Cuando hablamos de documentación, nos suena a una tarea tediosa que nadie quiere realizar. Afortunadamente, NestJS permite automatizar fácilmente la creación de la misma. Swagger es un reconocido set de herramientas para la documentación de API Rest. Instala las dependencias necesarias con el comando `npm install --save @nestjs/swagger swagger-ui-express` y configura el archivo main.ts con el siguiente código.

```ts
// main.ts
import { NestFactory } from "@nestjs/core";
import { AppModule } from "./app.module";
import { SwaggerModule, DocumentBuilder } from "@nestjs/swagger";

async function bootstrap() {
  const app = await NestFactory.create(AppModule);

  // Configuración Swagger en NestJS
  const config = new DocumentBuilder()
    .setTitle("Platzi API")
    .setDescription("Documentación Platzi API")
    .setVersion("1.0")
    .build();
  const document = SwaggerModule.createDocument(app, config);

  // URL API
  SwaggerModule.setup("docs", app, document);

  await app.listen(process.env.PORT || 3000);
}
bootstrap();
```

Setea el título, descripción y versión de tu documentación. Lo más importante es la URL para acceder a la misma. Levanta el servidor con `npm run start:dev` y accede a `localhost:3000/docs` para visualizar la documentación autogenerada que mapea automáticamente todos los endpoints de tu aplicación.

## Tipado de la documentación

La documentación autogenerada por Swagger es bastante simple, puedes volverla más completa tipando los datos de entrada y salida de cada endpoint gracias a los DTO.

Busca el archivo `nest-cli.json` en la raíz de tu proyecto y agrega el siguiente plugin:

```json
{
  "collection": "@nestjs/schematics",
  "sourceRoot": "src",
  "compilerOptions": {
    "plugins": ["@nestjs/swagger/plugin"]
  }
}
```

A continuación, prepara tus DTO de la siguiente manera:

```ts
import { IsNotEmpty, IsString, IsNumber } from "class-validator";
import { ApiProperty, PartialType, OmitType } from "@nestjs/swagger";

export class CreateProductDTO {
  @ApiProperty()
  @IsNotEmpty()
  @IsString()
  readonly name: string;

  @ApiProperty()
  @IsNotEmpty()
  @IsString()
  readonly description: string;

  @ApiProperty()
  @IsNotEmpty()
  @IsNumber()
  readonly price: number;
}

export class UpdateAuthorDto extends PartialType(
  OmitType(CreateProductDTO, ["name"])
) {}
```

Lo más relevante aquí es importar PartialType y OmitType desde @nestjs/swagger en lugar de importarlo desde @nestjs/mapped-types. Coloca también el decorador @ApiProperty() en cada una de las propiedades que el DTO necesita.

![03](https://static.platzi.com/media/user_upload/Screenshot%20from%202022-06-17%2014-08-51%281%29-436e5207-765c-4d51-94b4-b3f72d1b8c93.jpg)

De esta manera, observarás en la documentación que indica el tipo de dato que requiere cada uno de tus endpoints.

Cada vez que se modifique la configuracion de swager.

```bash
rm -rf dist
```

```ts
// src/main.ts

import { SwaggerModule, DocumentBuilder } from '@nestjs/swagger';

async function bootstrap() {
  ...
  const config = new DocumentBuilder()
    .setTitle('API')
    .setDescription('PLATZI STORE')
    .setVersion('1.0')
    .build();
  const document = SwaggerModule.createDocument(app, config);
  SwaggerModule.setup('docs', app, document);
  ...
  await app.listen(3000);
}
bootstrap();
```

```json
# nest-cli.json
{
  "collection": "@nestjs/schematics",
  "sourceRoot": "src",
  "compilerOptions": {
    "plugins": ["@nestjs/swagger/plugin"]
  }
}
```

```ts
// src/products/dtos/brand.dtos.ts
import { PartialType } from "@nestjs/swagger";

// src/products/dtos/category.dtos.ts
import { PartialType } from "@nestjs/swagger";

// src/products/dtos/products.dtos.ts
import { PartialType } from "@nestjs/swagger";

// src/users/dtos/customer.dto.ts
import { PartialType } from "@nestjs/swagger";

// src/users/dtos/user.dto.ts
import { PartialType } from "@nestjs/swagger";
```

## Extendiendo la documentación

La documentación automática que genera NestJS y Swagger es muy fácil de implementar y otorga una buena base. La documentación de tu aplicación puede ser aún más completa y detallada, si así lo quieres con algo de trabajo de tu parte. Veamos varios decoradores que te servirán para ampliar la documentación de tu API.

**Descripción de las propiedades**

En tus DTO, puedes dar detalle sobre qué se espera recibir en cada propiedad de tus endpoints gracias al decorador @ApiProperty()

```ts
import { IsNotEmpty, IsString, IsNumber } from "class-validator";
import { ApiProperty, PartialType, OmitType } from "@nestjs/swagger";

export class CreateProductDTO {
  @ApiProperty({ description: "Nombre del producto" })
  @IsNotEmpty()
  @IsString()
  readonly name: string;

  @ApiProperty({ description: "Descripción del producto" })
  @IsNotEmpty()
  @IsString()
  readonly description: string;

  @ApiProperty({ description: "Precio del producto" })
  @IsNotEmpty()
  @IsNumber()
  readonly price: number;
}
```

**Descripción de los controladores**

Puedes agrupar los endpoints en la documentación por controlador con el decorador @ApiTags() y describir, endpoint por endpoint, la funcionalidad de cada uno con el decorador @ApiOperation().

```ts
import { ApiTags, ApiOperation } from "@nestjs/swagger";

@ApiTags("Productos")
@Controller()
export class AppController {
  @ApiOperation({ summary: "Obtener lista de productos." })
  @Get("products")
  getProducts() {
    // ...
  }
}
```

Para obtener un resultado en la documentación de tu API como el siguiente:

![04](https://static.platzi.com/media/user_upload/Screenshot%20from%202022-06-17%2015-42-27-5241b1e3-815e-483c-895c-f7387b19d55d.jpg)

De este modo, la documentación de tu aplicación es súper profesional y está lista para ser recibida por el equipo front-end o por clientes externos que consumirán el servicio.

# Modulo 7: Deploy en Heroku

Llega el momento del despliegue de tu aplicación en un entorno productivo. Utilizaremos Heroku, uno de los proveedores de servidores Cloud más utilizado y fácil de utilizar de la industria.

## Configuración del proyecto al usar Heroku

Preparar tu aplicación para Heroku requiere de algunas configuraciones sencillas. Heroku, por defecto, usa una variable de entorno llamada PORT para levantar la aplicación en un puerto aleatorio. Asegúrate de configurar esta variable dinámica en el bootstrap de tu app, además de activar CORS para no tener problemas con el mismo. Agrega las configuraciones en el archivo main.ts.

```ts
// main.ts
import { NestFactory } from "@nestjs/core";
import { AppModule } from "./app.module";

async function bootstrap() {
  const app = await NestFactory.create(AppModule);
  app.enableCors();
  await app.listen(process.env.PORT || 3000);
}
bootstrap();
```

## Configuración versión de NodeJS

Edita el archivo package.json para especificar la versión de NodeJS que tu aplicación necesita con la siguiente configuración:

```json
{
  "engines": {
    "node": "14.x"
  }
}
```

## Configuración de Heroku

Heroku requiere de un pequeño archivo adicional en la raíz de tu proyecto llamado Procfile que contiene el comando que da inicio a tu proyecto:

```bash
web: npm run start:prod
```

Además, Heroku posee su propio CLI que nos ayudará en el despliegue de cualquier aplicación. Instálalo dependiendo tu sistema operativo para estar listo para el despliegue de tu app.

[Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
[Deploy Node JS](https://devcenter.heroku.com/articles/deploying-nodejs)

Teniendo tu aplicación configurada correctamente.

1. Realiza el despliegue en Heroku instalando su CLI en primer lugar.
2. Luego de instalar el CLI, realiza un heroku login para autenticarte. Si aún no posees una cuenta en Heroku, es el momento de crearte una de forma gratuita.
3. Una vez situado en tu proyecto, utiliza el comando `heroku create -a <nombre_proyecto>` para crear un nuevo proyecto remoto en tu cuenta de Heroku.
4. Heroku, internamente, posee su propio servidor de GIT. Si realizas un git remote -v, observarás que este ha agregado a tu proyecto nuevos servidores remotos. El despliegue se hará usando los propios de Heroku.
5. Con el simple comando `git push heroku master` la aplicación demorará unos pocos minutos en desplegarse. Podrás observar el progreso en la consola. La aplicación quedará desplegada en una URL proporcionada por Heroku similar a `https://<nombre_proyecto>.herokuapp.com/`, a la cual puedes acceder para observar si tu aplicación fue desplegada con éxito.

## Variables de entorno en Heroku

Si tu aplicación utiliza variables de entorno debes configurar estas. De manera muy sencilla, el siguiente comando te permite configurar cada una de tus variables de entorno: `heroku config:set APP_KEY=12345`, mientras que el comando `heroku config` te permitirá ver una lista de las variables que ya están configuradas.

Recuerda que las variables de entorno son sensibles y debes cuidar quién tiene acceso a ellas.

```bash
heroku local web
git checkout master
git merge 14-step
git remote -v
git push heroku master
heroku logs --tail
```

# Modulo 8: Nest con MongoDB

## Instalacion de Docker

[Instalacion](https://platzi.com/clases/2276-nestjs-mongodb/37105-instalacion-de-docker/)

## Configuracion de Docker para MongoDB

Tu productividad como desarrollador/a de software se incrementará gracias a Docker. No importa si eres desarrollador/a, backend o front-end. Hoy en día, trabajar con Docker es vital para ser un buen profesional del software.

### Cuáles son los beneficios de Docker

Con Docker podrás utilizar la tecnología que quieras en simples pasos, sin preocuparte por instalarla en tu computadora. No tendrás que “llenar” tu ordenador con programas que tal vez solo necesitas por un rato. Es así como Docker simplifica la instalación de un motor de base de datos, de un lenguaje de programación para hacer algunas pruebas o de un software en particular para un propósito dado.

Veamos cómo puedes emplear Docker para levantar una base de datos MongoDB.

1. **Configuración Docker**
   Comienza creando un archivo al cual, por defecto, se lo denomina `docker-compose.yml`

_NOTA: Los archivos de Docker utilizan la extensión .yml. Tal vez tengas que instalar una extensión en tu editor de código para visualizar estos archivos correctamente._

2. **Configuración de la base de datos**
   Agrégale el siguiente contenido al archivo que te permitirá levantar un contenedor de Docker con MongoDB en su interior.

```yml
# docker-compose.yml
version: "3"
services:
  my-mongo:
    image: mongo:4.4.4
    environment:
      - MONGO_INITDB_DATABASE=nestjs_mongo
      - MONGO_INITDB_ROOT_USERNAME=mongo
      - MONGO_INITDB_ROOT_PASSWORD=secret
    ports:
      - "27017:27017"
    volumes:
      - ./mongo_data:/data/db
```

3. **Levantar el contenedor**
   Es momento de levantar el contenedor con el simple comando `docker-compose up -d`. En pocos segundos podrás corroborar si el contenedor quedó levantado en tu computador con el comando` docker ps`. Debería estar ejecutándose, en el puerto 27017 una base de datos MongoDB.

Recuerda añadir la carpeta mongo_data al gitignore

## Exploración de la base de datos con Mongo Compass

Al trabajar con un motor de base de datos, siempre es muy práctico disponer de una interfaz gráfica para visualizar nuestros datos y ejecutar consultas más cómodamente.

Mongo Compass es el software por excelencia para la visualización de bases de datos MongoDB, oficial y desarrollado por Mongo. Te permitirá conectarte a cualquier base de datos, sea local o remota, para visualizar las colecciones y los documentos en tu base.

MongoDB utiliza una sintaxis especial para establecer la conexión a una base de datos. Utiliza un string con la siguiente estructura:

```bash
mongodb://<USER>:<PASS>@<HOST>:<PORT>/<DBNAME>?authSource=admin
```

Debe completar los datos del usuario, del host y puerto, y el nombre de la base de datos, seguido de algunos parámetros opcionales de configuración. Si la información es correcta, se establecerá la conexión con la base de datos MongoDB que puedes estar corriendo en Docker o en un servidor remoto.

Recuerda que, para conectarte a tu base de datos MongoDB que está corriendo en Docker, las variables de entorno que has configurado en el docker.compose.yml son los mismos datos que tienes que utilizar para construir el string de conexión.

## Instalando y conectando MongoDB Driver

Ya sabes como hacer la configuración de Docker, Ahora, para conectar NestJS y MongoDB es necesario realizar la instalación de algunas dependencias desde NPM que nos ayudarán a lograrlo. Con el comando `npm install mongodb --save` instalarás el driver oficial para trabajar con NodeJS y MongoDB. Esta dependencia puedes utilizarla siempre que quieras, ya sea que estés trabajando con NestJS o no.

_NOTA: Adicional a la instalación del driver, al trabajar con TypeScript es necesario instalar el tipado de la dependencia con el comando `npm i @types/mongodb --save-dev` para que nos ayude a trabajar con el driver y evitar errores._

Siempre usa dependencias oficiales cuando se trata de conexiones a bases de datos. Posterior a eso, podrás instalar otras dependencias que te ayudarán a mapear los datos, pero siempre se apoyan en el driver principal para establecer la conexión y realizar las consultas.

**Código de ejemplo para instalación de MongoDB driver**

```bash
npm i mongodb --save
npm i @types/mongodb --save-dev
```

```ts
# src/app.module.ts

import { MongoClient } from 'mongodb';

const uri = 'mongodb://root:root@localhost:27017/?authSource=admin&readPreference=primary';

const client = new MongoClient(uri);
async function run() {
  await client.connect();
  const database = client.db('platzi-store');
  const taskCollection = database.collection('tasks');
  const tasks = await taskCollection.find().toArray();
  console.log(tasks);
}
run();
```

## Conexion como inyectable

Veamos una forma de realizar la conexión a una base de datos MongoDB con el driver oficial. Conectarse a una base de datos es un procedimiento asíncrono. Este puede ejecutarse de manera global al inicializar el proyecto NestJS y, posteriormente, gracias a las características de NestJS, inyectar la conexión en cualquier servicio para hacer consultas.

1. **establecer la conexión de forma global**
   Creamos un módulo al que denominaremos DatabaseModule, que contiene la configuración de forma global para establecer la conexión a una base de datos, a la vez que inyecta un servicio denominado “MONGO”. Este puede ser utilizado por cualquier otro servicio que requiere la conexión.

```ts
// src/database/database.module.ts
import { MongoClient } from "mongodb";

@Global()
@Module({
  providers: [
    {
      provide: "MONGO",
      useFactory: async () => {
        const uri =
          "mongodb://mongo:secret@localhost:27017/nestjs_mongo?authSource=admin";
        const client = new MongoClient(uri);
        await client.connect();
        const database = client.db("platzi-store");
        return database;
      },
    },
  ],
  exports: ["MONGO"],
})
export class DatabaseModule {}
```

2. **Inyectar la conexión en un servicio**
   Inyectamos el servicio que lleva el nombre de “MONGO” en cualquier otro servicio que requiere su utilización.

```ts
// src/app.service.ts
import { Db } from "mongodb";

@Injectable()
export class AppService {
  constructor(@Inject("MONGO") private database: Db) {}
}
```

De esta manera, solo usando el driver oficial de MongoDB, puedes crear un servicio reutilizable para establecer la conexión a tu base de datos.

### Código de ejemplo de: conexión como inyectable

```ts
// src/database/database.module.ts
import { MongoClient } from 'mongodb'; // 👈 Import MongoClient

@Global()
@Module({
  providers: [
    ...
    {
      provide: 'MONGO',
      useFactory: async () => { // 👈 Inject w/ useFactory
        const uri =
          'mongodb://root:root@localhost:27017/?authSource=admin&readPreference=primary';
        const client = new MongoClient(uri);
        await client.connect();
        const database = client.db('platzi-store');
        return database;
      },
    },
  ],
  exports: ['API_KEY', 'MONGO'],  // 👈 add in exports
})
```

```ts
// src/app.service.ts
import { Injectable, Inject } from "@nestjs/common";
import { Db } from "mongodb"; // 👈 Import DB Type

@Injectable()
export class AppService {
  constructor(
    // @Inject('API_KEY') private apiKey: string,
    @Inject("TASKS") private tasks: any[],
    @Inject("MONGO") private database: Db,
    @Inject(config.KEY) private configService: ConfigType<typeof config>
  ) {}

  getHello(): string {
    const apiKey = this.configService.apiKey;
    const name = this.configService.database.name;
    return `Hello World! ${apiKey} ${name}`;
  }
  getTasks() {} // 👈 Create new method
}
```

## Ejecutando un query

La parte más importante de conectarse a una base de datos es la obtención de las mismas para su posterior uso. Teniendo establecida la conexión a la base de datos, puedes ejecutar consultas de manera muy sencilla en tus servicios.

```ts
// src/app.service.ts
import { Db } from "mongodb";

@Injectable()
export class AppService {
  constructor(@Inject("MONGO") private database: Db) {}

  getProducts() {
    const productCollection = this.database.collection("products");
    return productCollection.find().toArray();
  }
}
```

Puedes utilizar estas consultas en tus controladores para la creación de endpoints

```ts
// src/app.controller.ts
import { AppService } from "./app.service";

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get("/products")
  getProducts() {
    return this.appService.getProducts();
  }
}
```

Así, tienes ya disponible la creación de todo un CRUD con persistencia en base de datos MongoDB para que juegues con tu aplicación.

**Código de ejemplo de: ejecutando un query**

```ts
// src/app.service.ts

...
@Injectable()
export class AppService {
  ...

  getTasks() { // 👈 Query
    const tasksCollection = this.database.collection('tasks');
    return tasksCollection.find().toArray();
  }
}
```

```ts
// src/app.controller.ts
import { AppService } from './app.service';

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}
  ...

  @Get('/tasks/') // 👈 New endpoint
  getTasks() {
    return this.appService.getTasks();
  }
}
```

## Usando varibales de ambiente en Mongo

Trabajar con variables de entorno será siempre la forma más correcta y segura de pasarle a nuestra aplicación los datos sensibles de conexión a bases de datos o claves secretas.

1. Asegúrate de instalar la dependencia npm i --save @nestjs/config. Esta te permitirá crear en la raíz de tu proyecto el archivo .env, que contendrá las variables de entorno que tu aplicación necesita.

```
# .env
MONGO_BBDD=nestjs_mongo
MONGO_CONF=mongodb
MONGO_HOST=localhost:27017
MONGO_PASS=secret
MONGO_USER=mongo
```

2. Importa el ConfigModule en el módulo principal de tu aplicación para leer correctamente el archivo .env.

```ts
// app.module.ts
import { ConfigModule } from "@nestjs/config";

@Module({
  imports: [ConfigModule.forRoot()],
})
export class AppModule {}
```

3. De esta manera, ya tienes disponible en tu aplicación para utilizar las variables de entorno que hayas definido en el archivo .env a través del objeto global de NodeJS process de la siguiente manera:

```ts
mongodb://mongo:secret@localhost:27017/nestjs_mongo
```

Podría quedar de la siguiente manera:

```ts
${process.env.MONGO_CONF}://${process.env.MONGO_USER}:${process.env.MONGO_PASS}@${process.env.MONGO_HOST}/${process.env.MONGO_BBDD}
```

Recuerda no versionar en el repositorio de tu proyecto el archivo .env que contiene datos sensibles como contraseñas o accesos privados. Tu aplicación está lista para conectarse a múltiples ambientes de desarrollo a través de variables de ambiente.

**Código de ejemplo de: usando variables de ambiente en Mongo**

```ts
// .env, .stag.env, .prod.env
MONGO_INITDB_ROOT_USERNAME=root
MONGO_INITDB_ROOT_PASSWORD=root
MONGO_DB=platzi-store
MONGO_PORT=27017
MONGO_HOST=localhost
MONGO_CONNECTION=mongodb

// src/config.ts
import { registerAs } from '@nestjs/config';

export default registerAs('config', () => {
  return {
    ...
    mongo: { // 👈
      dbName: process.env.MONGO_DB,
      user: process.env.MONGO_INITDB_ROOT_USERNAME,
      password: process.env.MONGO_INITDB_ROOT_PASSWORD,
      port: parseInt(process.env.MONGO_PORT, 10),
      host: process.env.MONGO_HOST,
      connection: process.env.MONGO_CONNECTION,
    },
  };
});

// src/database/database.module.ts
import { ConfigType } from '@nestjs/config';

import config from '../config'; // 👈 import config


@Global()
@Module({
  providers: [
    ...
    {
      provide: 'MONGO',
      useFactory: async (configService: ConfigType<typeof config>) => {
        const {
          connection,
          user,
          password,
          host,
          port,
          dbName,
        } = configService.mongo; // 👈 get mongo config
        const uri = `${connection}://${user}:${password}@${host}:${port}/?authSource=admin&readPreference=primary`;
        const client = new MongoClient(uri);
        await client.connect();
        const database = client.db(dbName);
        return database;
      },
      inject: [config.KEY], // 👈 Inject config
    },
  ],
  exports: ['API_KEY', 'MONGO'],
})
export class DatabaseModule {}
```

## Mongoose

Utilizar el driver oficial de MongoDB para NestJS es una buena manera de trabajar y relacionar estos dos mundos. Pero existe una forma mucho más profesional y amigable que te ayudará a trabajar más rápido y cometer menos errores. Mongoose es un ODM (Object Data Modeling) que permite realizar un mapeo de cada colección de tu base de datos MongoDB a través de esquemas. Estos te ayudarán a acceder a los datos, realizar consultas complejas y estandarizar la estructura de los mismos.

En MongoDB, al ser NoSQL, puedes guardar lo que quieras, en el orden que quieras y con la estructura que quieras. Esto es una muy mala práctica que tienes que evitar ya que traerá serios problemas en un futuro no muy lejano en tu proyecto. Los ODM llegan para solucionar esto.

## Instalación y configuración de Mongoose

1. Además de la instalación de Mongoose, NestJS posee su propia librería que te ayudará a crear los esquemas, inyectar los servicios y ejecutar las consultas a tu base de datos.

```bash
npm install --save @nestjs/mongoose mongoose
```

2. Importa el módulo MongooseModule y pásale la cadena de conexión utilizando, o no, variables de entorno.

```ts
import { MongooseModule } from "@nestjs/mongoose";
@Module({
  imports: [
    MongooseModule.forRoot(
      `${process.env.MONGO_CONF}://${process.env.MONGO_USER}:${process.env.MONGO_PASS}@${process.env.MONGO_HOST}/${process.env.MONGO_BBDD}`
    ),
  ],
})
export class AppModule {}
```

De esta manera, habrás realizado la conexión de tu base de datos a través de Mongoose, en lugar de utilizar el driver oficial.

**Código de ejemplo de: ¿Qué es Mongoose? Instalación y configuración**

```ts
// src/database/database.module.ts
import { MongooseModule } from "@nestjs/mongoose"; // 👈 Import

@Global()
@Module({
  imports: [
    // 👈
    MongooseModule.forRootAsync({
      // 👈 Implement Module
      useFactory: (configService: ConfigType<typeof config>) => {
        const { connection, user, password, host, port, dbName } =
          configService.mongo;
        return {
          uri: `${connection}://${host}:${port}`,
          user,
          pass: password,
          dbName,
        };
      },
      inject: [config.KEY],
    }),
  ],
  providers: [
    {
      provide: "API_KEY",
      inject: [config.KEY],
    },
  ],
  exports: ["API_KEY", "MONGO", MongooseModule], // 👈 add in exports
})
export class DatabaseModule {}
```

## Esquemas con Mongoose

1. Suponiendo que necesitas una colección en Mongo para almacenar productos, comienza creando un archivo llamado product.entity.ts en el módulo de productos de tu aplicación.

```ts
// modules/products/product.entity.ts
import { Prop, Schema, SchemaFactory } from "@nestjs/mongoose";
import { Document } from "mongoose";

@Schema()
export class Product extends Document {
  @Prop({ required: true })
  name: string;

  @Prop()
  description: string;

  @Prop({ type: Number })
  price: number;

  @Prop({ type: Number })
  stock: number;

  @Prop()
  image: string;
}

export const ProductSchema = SchemaFactory.createForClass(Product);
```

Observa el decorador @Prop() para mapear cada atributo de la clase Product que extiende de Document e indicarle a Mongoose que se trata de una propiedad del documento. Exportando ProductSchema que, gracias a SchemaFactory que es el responsable de crear y realizar el mapeo de datos, podrás realizar las posteriores consultas desde los servicios.

2. Ahora solo tienes que importar la entidad en el módulo al que pertenece de la siguiente manera

```ts
// modules/products/products.module.ts
import { MongooseModule } from "@nestjs/mongoose";
import { Product, ProductSchema } from "./entities/product.entity";

@Module({
  imports: [
    MongooseModule.forFeature([
      {
        name: Product.name,
        schema: ProductSchema,
      },
    ]),
  ],
})
export class ProductsModule {}
```

Importa MongooseModule y tienes que asignarle un nombre a la colección e inyectarle el schema que utilizará.

De esta forma, estarás creando la colección products en tu base de datos MongoDB y ya tienes mapeada en tu aplicación la estructura de cada documento que contendrá para evitar errores.

**Código de ejemplo de: Implementado Mongoose en Modulos**

```ts
// src/products/entities/product.entity.ts
import { Prop, Schema, SchemaFactory } from '@nestjs/mongoose';
import { Document } from 'mongoose';

@Schema()
export class Product extends Document {
  @Prop({ required: true })
  name: string;

  @Prop()
  description: string;

  @Prop({ type: Number })
  price: number;

  @Prop({ type: Number })
  stock: number;

  @Prop()
  image: string;
}

export const ProductSchema = SchemaFactory.createForClass(Product);

// src/products/products.module.ts
...
import { MongooseModule } from '@nestjs/mongoose';
import { Product, ProductSchema } from './entities/product.entity';

@Module({
  imports: [
    MongooseModule.forFeature([
      {
        name: Product.name,
        schema: ProductSchema,
      },
    ]),
  ],
  ...
})
export class ProductsModule {}
```

[Schema Types](https://mongoosejs.com/docs/schematypes.html)

## Conectando Mongo a los servicios

Establecida la conexión a la base de datos con Mongoose y creadas las entidades que mapean la información, es momento de realizar las consultas a la base de datos desde los servicios.

1. Comienza inyectando el esquema creado en el servicio que será el responsable de realizar las consultas.

```ts
// modules/products/products.service.ts
import { InjectModel } from "@nestjs/mongoose";
import { Model } from "mongoose";

@Injectable()
export class ProductsService {
  constructor(
    @InjectModel(Product.name) private productModel: Model<Product>
  ) {}

  findAll() {
    return this.productModel.find().exec();
  }

  findOne(id: string) {
    return this.productModel.findById(id).exec();
  }
}
```

Utilizando InjectModel, inyectas el esquema de productos en el servicio de productos.

2. Los servicios son los responsables de realizar las consultas a la base de datos, pero los controladores son quienes determinan cuándo hay que realizar esas consultas.

```ts
// module/products/products.controller.ts
@Controller("products")
export class ProductsController {
  @Get()
  async getAll() {
    return await this.productsService.findAll();
  }

  @Get(":productId")
  async getOne(@Param("productId") productId: string) {
    return await this.productsService.findOne(productId);
  }
}
```

Crea tantos endpoints como necesites para responder a la necesidad de obtención de los datos a través de GET.

Así, ya tienes completada tu conexión a la base de datos y obtención de datos en tu API a través de Mongoose y sus esquemas.

**Código de ejemplo de: Conectando Mongo a los servicios**

```ts
// src/products/services/products.service.ts

import { InjectModel } from '@nestjs/mongoose';
import { Model } from 'mongoose';

...

@Injectable()
export class ProductsService {
  constructor(
    @InjectModel(Product.name) private productModel: Model<Product>, // 👈
  ) {}
  ...

  findAll() { // 👈
    return this.productModel.find().exec();
  }

  async findOne(id: string) {  // 👈
    const product = await this.productModel.findById(id).exec();
    if (!product) {
      throw new NotFoundException(`Product #${id} not found`);
    }
    return product;
  }
  ...

}

// src/products/controllers/products.controller.ts

@Controller('products')
export class ProductsController {
   ...

  @Get(':productId')
  getOne(@Param('productId') productId: string) {   // 👈
    return this.productsService.findOne(productId);
  }
}

// src/users/services/users.service.ts
@Injectable()
export class UsersService {
  ...

  async getOrderByUser(id: number) {   // 👈
    const user = this.findOne(id);
    return {
      date: new Date(),
      user,
      products: await this.productsService.findAll(),   // 👈 implement await
    };
  }
}
```

## Create, update y delete

Conectarse a una base de datos implica la posibilidad de manipular en su totalidad los datos desde su creación, modificación y eliminación, además de la lectura de los mismos. La creación de un registro es bastante sencilla, basta con pasarle los datos necesarios para la creación de un nuevo documento.

```ts
// modules/products/products.service.ts
import { InjectModel } from "@nestjs/mongoose";
import { Model } from "mongoose";
import { CreateProductDto } from "./product.dto";

@Injectable()
export class ProductsService {
  constructor(
    @InjectModel(Product.name) private productModel: Model<Product>
  ) {}

  create(data: CreateProductDto) {
    const newProduct = new this.productModel(data);
    return newProduct.save();
  }
}
```

Recuerda que puedes apoyarte en los DTO de NestJS para el tipado de datos. El productModel espera que le envíes un objeto que contenga las mismas propiedades que el esquema que hayas creado para la colección.

La actualización de un registro conlleva dos partes, comprobar que el mismo exista para su posterior actualización. Afortunadamente, Mongoose puede realizar las dos acciones en una.

```ts
// modules/products/products.service.ts
import { InjectModel } from "@nestjs/mongoose";
import { Model } from "mongoose";
import { UpdateProductDto } from "./product.dto";

@Injectable()
export class ProductsService {
  constructor(
    @InjectModel(Product.name) private productModel: Model<Product>
  ) {}

  update(id: string, changes: UpdateProductDto) {
    return this.productModel
      .findByIdAndUpdate(id, { $set: changes }, { new: true })
      .exec();
  }
}
```

Para la actualización de un documento, la función findByIdAndUpdate primero busca el registro por ID y si lo encuentra, lo actualiza. Aquí ya es necesario un poco de conocimiento en el lenguaje de consulta de MongoDB para utilizar el $set que actualizará los campos que se le indique.

La eliminación de un registro es similar a la actualización. El documento debe existir para su posterior eliminación. La función findByIdAndDelete lo hará por nosotros.

```ts
// modules/products/products.service.ts
import { InjectModel } from "@nestjs/mongoose";
import { Model } from "mongoose";

@Injectable()
export class ProductsService {
  constructor(
    @InjectModel(Product.name) private productModel: Model<Product>
  ) {}

  remove(id: string) {
    return this.productModel.findByIdAndDelete(id);
  }
}
```

De esta manera, ya puedes realizar operaciones CRUD y manipular por completo los datos de tu colección de MongoDB desde una API Rest.

**Código de ejemplo de: Create, update y delete**

```ts
// src/products/services/products.service.ts
...

@Injectable()
export class ProductsService {
  ...

  create(data: CreateProductDto) {  // 👈
    const newProduct = new this.productModel(data);
    return newProduct.save();
  }

  update(id: string, changes: UpdateProductDto) {  // 👈
    const product = this.productModel
      .findByIdAndUpdate(id, { $set: changes }, { new: true })
      .exec();
    if (!product) {
      throw new NotFoundException(`Product #${id} not found`);
    }
    return product;
  }

  remove(id: string) {  // 👈
    return this.productModel.findByIdAndDelete(id);
  }
}
// src/products/controllers/products.controller.ts

@Controller('products')
export class ProductsController {
   ...

  @Post()
  create(@Body() payload: CreateProductDto) {
    return this.productsService.create(payload);  // 👈
  }

  @Put(':id')
  update(@Param('id') id: string, @Body() payload: UpdateProductDto) {
    return this.productsService.update(id, payload);  // 👈
  }

  @Delete(':id')
  delete(@Param('id') id: string) {
    return this.productsService.remove(id);  // 👈
  }
}

// Revisa que uses el ApiProperty en todos los attrs del Dto para que se haga la actualización correctamente.
// src/products/dtos/products.dtos.ts
import { ApiProperty, PartialType } from '@nestjs/swagger';

export class CreateProductDto {
  @IsString()
  @IsNotEmpty()
  @ApiProperty({ description: `product's name` }) // 👈 use ApiProperty
  readonly name: string;

  @IsString()
  @IsNotEmpty()
  @ApiProperty() // 👈 use ApiProperty
  readonly description: string;

  @IsNumber()
  @IsNotEmpty()
  @IsPositive()
  @ApiProperty() // 👈 use ApiProperty
  readonly price: number;

  @IsNumber()
  @IsNotEmpty()
  @ApiProperty() // 👈 use ApiProperty
  readonly stock: number;

  @IsUrl()
  @IsNotEmpty()
  @ApiProperty() // 👈 use ApiProperty
  readonly image: string;
}

export class UpdateProductDto extends PartialType(CreateProductDto) {}
```

## Pipe para mongoid

En ocasiones es necesario validar nuestros propios datos de entrada. Cuando esos datos sean utilizados para realizar consultas a una base de datos, es recomendable estar prevenido por posibles ataques y validarlos manualmente. Los documentos que se crean en una base de datos MongoDB, por defecto, utilizan una propiedad llamada \_id, o también llamado ObjectID, que representa el ID principal de cada documento. El mismo tiene un formato particular de 12 o 24 caracteres que podemos validar para asegurar que, el dato que el front-end nos envía, se trata efectivamente de un Mongo ID.

1. Crearemos un custom pipe con el comando nest g pi mongoId para validar el Mongo ID. El mismo contendrá la lógica del validador.

```ts
import {
  ArgumentMetadata,
  Injectable,
  PipeTransform,
  BadRequestException,
} from "@nestjs/common";
import { isMongoId } from "class-validator";

@Injectable()
export class MongoIdPipe implements PipeTransform {
  transform(value: string, metadata: ArgumentMetadata) {
    if (!isMongoId(value)) {
      throw new BadRequestException(`${value} is not a mongoId`);
    }
    return value;
  }
}
```

Afortunadamente, la dependencia class-validator nos ayudará a validar el formato del string de entrada para verificar si posee la forma de un Mongo ID.

2. Implementar un Pipe en NestJS es muy sencillo, basta con pasarlo como parámetro al decorador para que el mismo se ocupe de validar el dato de entrada.

```ts
import { MongoIdPipe } from "./mongo-id.pipe";

export class ProductsController {
  @Get(":productId")
  getOne(@Param("productId", MongoIdPipe) productId: string) {
    return this.productsService.findOne(productId);
  }
}
```

Recuerda prestar atención tanto al tipado de datos para evitar errores como la validación de los mismos para mejorar la seguridad de tu aplicación. Las aplicaciones profesionales deben desarrollarse con las mejores prácticas posibles.

**Código de ejemplo de: Pipe para mongoid**

```bash
nest g pi common/mongoId
```

```ts
// src/common/mongo-id.pipe.ts

import {
  ArgumentMetadata,
  Injectable,
  PipeTransform,
  BadRequestException,
} from '@nestjs/common';
import { isMongoId } from 'class-validator';

@Injectable()
export class MongoIdPipe implements PipeTransform { // 👈 new pipe

  transform(value: string, metadata: ArgumentMetadata) {
    if (!isMongoId(value)) {
      throw new BadRequestException(`${value} is not a mongoId`);
    }
    return value;
  }

}

// src/products/controllers/products.controller.ts
import { MongoIdPipe } from './../../common/mongo-id.pipe'; // 👈 import

...
export class ProductsController {

  @Get(':productId')
  getOne(@Param('productId', MongoIdPipe) productId: string) {  // 👈 use MongoIdPipe
    return this.productsService.findOne(productId);
  }
}
```

## Agregando paginacion

Una base de datos puede tener miles y miles de registros, los cuales conviene consultar de forma gradual y en partes para que sea más ameno para el usuario que consume la información. Las consultas que realices en MongoDB permiten separar los resultados en partes iguales y desarrollar en el front-end la típica lógica de paginación de resultados.

1. Comienza creando un DTO para el tipado de los datos que construirán la paginación.

```ts
// products/products.dto.ts

import { IsOptional, Min } from "class-validator";
export class FilterProductsDto {
  @IsOptional()
  @IsPositive()
  limit: number; // Cantidad de registros por página

  @IsOptional()
  @Min(0)
  offset: number; // Número de registros a ignorar
}
```

2. El servicio de lectura de los registros recibe los parámetros para crear el paginador y utilizarlos en la consulta.

```ts
// products/products.service.ts
import { FilterProductsDto } from "./products.dtos";

@Injectable()
export class ProductsService {
  findAll(params?: FilterProductsDto) {
    if (params) {
      const { limit, offset } = params;
      return this.productModel.find().skip(offset).limit(limit).exec();
    }
    return this.productModel.find().exec();
  }
}
```

3. El controlador será el encargado de recibir estos datos y pasárselos al servicio para devolver los datos paginados.

```ts
// products/products.controller.ts
import { FilterProductsDto } from "../dtos/products.dtos";

@Controller("products")
export class ProductsController {
  @Get()
  getProducts(@Query() params: FilterProductsDto) {
    return this.productsService.findAll(params);
  }
}
```

Los parámetros que construyen un paginador suelen recibirse por medio de Query Params y estos deben ser opcionales. El backend tiene que contemplar valores por defecto en el caso de que el front-end no envíe nada y el endpoint debe continuar funcionando correctamente.

4. Por defecto, todos los Query Params son del tipo String. NestJS nos ayuda a convertirlos a números enteros con la siguiente configuración en el archivo main.ts.

```ts
// src/main.ts
new ValidationPipe({
  transformOptions: {
    enableImplicitConversion: true, // Convertir Query Params a números entero
  },
});
```

De esta manera, tu endpoint del tipo GET se encuentra listo para permitirle al front-end crear un paginador y facilitar la lectura de resultados a los usuarios.

**Código de ejemplo de: Agregando paginacion**

```ts
// src/products/dtos/products.dtos.ts

import {
 ...
  IsOptional, // 👈 new decorator
  Min,  // 👈 new decorator
} from 'class-validator';

...

export class FilterProductsDto { // 👈 new DTO
  @IsOptional()
  @IsPositive()
  limit: number;

  @IsOptional()
  @Min(0)
  offset: number;
}

// src/products/services/products.service.ts

import {
  CreateProductDto,
  UpdateProductDto,
  FilterProductsDto,  // 👈 import DTO
} from './../dtos/products.dtos';

@Injectable()
export class ProductsService {

  findAll(params?: FilterProductsDto) { // 👈
    if (params) {
      const { limit, offset } = params;
      return this.productModel.find().skip(offset).limit(limit).exec();  // 👈
    }
    return this.productModel.find().exec();
  }

}

// src/products/controllers/products.controller.ts

import { ..., FilterProductsDto } from '../dtos/products.dtos'; // 👈 import DTO

@Controller('products')
export class ProductsController {
  ...

  @Get()
  @ApiOperation({ summary: 'List of products' })
  getProducts(@Query() params: FilterProductsDto) { // 👈
    return this.productsService.findAll(params);
  }

  ...

}

// src/main.ts
   new ValidationPipe({
      whitelist: true,
      forbidNonWhitelisted: true,
      transformOptions: {
        enableImplicitConversion: true,
      },
    }),
```

## Agregando un filtro de rango para precios

Los endpoints del tipo GET, además de paginar la información, pueden tener otro tipo de filtros más específicos para una regla de negocio. MongoDB permite crear cualquier tipo de filtro que necesite tu servicio. Crear un filtro entre dos números X e Y que podrían ser años o precios de productos es un caso de uso bastante habitual en la consulta de datos.

1. Comienza creando el DTO para que el constructor reciba estos datos.

```ts
// products/products.dto.ts
import { ValidateIf } from "class-validator";

export class FilterProductsDto {
  @IsOptional()
  @Min(0)
  minPrice: number;

  @ValidateIf((params) => params.minPrice)
  @IsPositive()
  maxPrice: number;
}
```

Utilizamos el decorador `@ValidateIf()` para validar el precio máximo solo si existe el mínimo y también es válido

2. Preparar el servicio para recibir estos nuevos datos y filtrar por rango mínimo y máximos un determinado campo del esquema.

// products/products.service.ts
import { Model, FilterQuery } from 'mongoose';

@Injectable()
export class ProductsService {

```ts
  findAll(params?: FilterProductsDto) {
    if (params) {
      const filters: FilterQuery<Product> = {};
      const { minPrice, maxPrice } = params;
      if (minPrice && maxPrice) {
        filters.price = { $gte: minPrice, $lte: maxPrice };
      }
      return this.productModel.find(filters).exec();
    }
    return this.productModel.find().exec();
  }
}
```

Para crear el filtro de rangos máximos y mínimos, MongoDB utiliza operadores de comparaciones especiales:

- $gte equivalente a >=
- $lte equivalente a <=

De esta manera, el servicio está preparado para realizar un filtro numérico si el usuario ingresa el rango. Recuerda que este tipo de filtros suelen ser opcionales, el endpoint debe seguir funcionando correctamente en el caso de que no se ingrese un filtro.

**Código de ejemplo de: Agregando un filtro de rango para precios**

```ts
// src/products/dtos/products.dtos.ts

import {
  ...,
  ValidateIf // 👈 new decorator
} from 'class-validator';

export class FilterProductsDto {
  ...
  @IsOptional()
  @Min(0)
  minPrice: number; // 👈 new field

  @ValidateIf((params) => params.minPrice)
  @IsPositive()
  maxPrice: number;  // 👈 new field
}

// src/products/services/products.service.ts
import { Model, FilterQuery } from 'mongoose';

@Injectable()
export class ProductsService {
  ...

  findAll(params?: FilterProductsDto) {
    if (params) {
      const filters: FilterQuery<Product> = {}; // 👈 create filters
      const { limit, offset } = params;
      const { minPrice, maxPrice } = params; // 👈
      if (minPrice && maxPrice) {
        filters.price = { $gte: minPrice, $lte: maxPrice };
      }
      return this.productModel.find(filters).skip(offset).limit(limit).exec();
    }
    return this.productModel.find().exec();
  }
  ..
}
```

## Agregando indexadores

Una base de datos puede tener incluso millones de documentos, lo que provocaría que las consultas sean lentas. Como desarrollador o desarrolladora de software, es tu responsabilidad asegurar la eficiencia de las consultas en tu aplicación. MongoDB utiliza el concepto de “Indexador” para permitir preseleccionar campos en tus esquemas que sabes que serán utilizados para realizar consultas a través de ellos y mejorar así la eficiencia de las mismas.

Crear un indexador en los esquemas de Mongoose y NestJS es muy sencillo. Basta con agregar al decorador `@Prop()` la propiedad `{ index: true }` para indicar que ese campo será indexado y se realizarán consultas a través de él.

```ts
// products/product.entity.ts
export class Product extends Document {
  @Prop({ type: Number, index: true })
  price: number;
}

export const ProductSchema = SchemaFactory.createForClass(Product);
ProductSchema.index({ price: 1, stock: -1 }); // Orden ascendente o descendente de la indexación
```

Otro tipo de índice que puedes crear en una propiedad es el Unique para que un campo sea único en una colección.

```ts
// products/product.entity.ts
export class Product extends Document {
  @Prop({ type: String, unique: true })
  idProducto: string;
}
```

Así, el campo idProducto será único dentro de todos los documentos de la colección a la cual pertenece. Provocará un error si se quiere ingresar un idProducto ya existente.

Recuerda elegir muy bien los índices de cada esquema. No puedes seleccionar TODOS los campos como índices, ya que si todos ellos son importantes, ninguno lo será y Mongo no priorizará las búsquedas a través de ningún campo.

También considera que los índices suelen utilizarse en bases de datos con millones de documentos en una colección. Si tu colección tiene unos pocos cientos o incluso miles de documentos, tal vez no sea necesario utilizar índices.

**Código de ejemplo de: Agregando indexadores**

```ts
// src/products/entities/product.entity.ts
...
export class Product extends Document {
  ...

  @Prop({ type: Number, index: true }) // 👈
  price: number;

}

export const ProductSchema = SchemaFactory.createForClass(Product);
ProductSchema.index({ price: 1, stock: -1 });  // 👈
```

## Relaciones uno a uno referenciadas

Las relaciones uno a uno en MongoDB pueden realizarse de varias maneras. Algunas más óptimas y escalables a largo plazo que otras.Ocurre con las relaciones uno a uno embebidas que estamos repitiendo N cantidad de veces el mismo objeto en múltiples documentos. Esto, además de ocupar espacio innecesario en la base de datos, puede ocasionar problemas si tenemos la necesidad de actualizar todos esos documentos repetidos por un cambio de nombre de categoría o similar. Para resolver este problema, las relaciones uno a uno pueden realizarse de forma referencial. O sea, guarda el ID de un documento, dentro de otro. Muy similar a lo que solemos realizar en SQL guardando llaves foráneas en registros de otras tablas.

1. Crea un esquema que hará posteriormente la colección de documentos que estarán referenciados en otros documentos.

```ts
// products/brand.entity.ts
import { Prop, Schema, SchemaFactory } from "@nestjs/mongoose";
import { Document } from "mongoose";

@Schema()
export class Brand extends Document {
  @Prop({ required: true, unique: true })
  name: string;

  @Prop()
  image: string;
}
export const BrandSchema = SchemaFactory.createForClass(Brand);
```

En este ejemplo, creamos un esquema Brand. Un producto tendrá la referencia de un Brand en su interior.

```ts
// products/product.entity.ts
import { Document, Types } from "mongoose";
import { Brand } from "./brand.entity";

export class Product extends Document {
  @Prop({ type: Types.ObjectId, ref: Brand.name })
  brand: Brand | Types.ObjectId;
}
```

Prepara tu esquema principal. El documento que contendrá la relación referenciada a través de Brand | Types.ObjectId para indicarle a Mongoose qué tiene que esperar en esa propiedad.

2. Prepara el DTO de creación de tu esquema principal, incorporando la propiedad que contendrá la referencia al otro documento.

```ts
// products/products.dtos.ts
import { IsMongoId } from "class-validator";

export class CreateProductDto {
  @IsNotEmpty()
  @IsMongoId()
  readonly brand: string;
}
```

3. Has guardado un MongoID dentro de un documento. Es momento de realizar un “JOIN” para traer la información del mismo.

En MongoDB, los Join son denominados “Populates”, lo que hará Mongo aquí es ir a buscar el objeto a la colección a la cual pertenece.

```ts
// products/products.service.ts
export class ProductsService {
  findAll() {
    return this.productModel.find().populate("brand").exec();
  }
}
```

De esta forma, el GET devolverá el objeto principal, además del objeto referenciado dentro.

Las relaciones referenciadas son más profesionales y escalables. Solucionan muchos problemas típicos de bases de datos como la redundancia de los mismos y facilita las consultas.

**Código de ejemplo de: Relaciones uno a uno referenciadas**

```ts
// src/products/entities/brand.entity.ts
import { Prop, Schema, SchemaFactory } from '@nestjs/mongoose';
import { Document } from 'mongoose';

@Schema()
export class Brand extends Document {
  @Prop({ required: true, unique: true }) // 👈 is unique
  name: string;

  @Prop()
  image: string;
}

export const BrandSchema = SchemaFactory.createForClass(Brand);

// src/products/entities/product.entity.ts

import { Document, Types } from 'mongoose';
import { Brand } from './brand.entity';

export class Product extends Document {

  @Prop({ type: Types.ObjectId, ref: Brand.name }) // 👈 relation
  brand: Brand | Types.ObjectId; // 👈 new field

}

// src/products/dtos/products.dtos.ts

import {
  ...,
  IsMongoId, // 👈 new decorator
} from 'class-validator';

export class CreateProductDto {
  ...

  @IsNotEmpty()
  @IsMongoId()
  readonly brand: string; // 👈 new field
}

// src/products/services/products.service.ts

export class ProductsService {

  findAll(params?: FilterProductsDto) {
    if (params) {
      const filters: FilterQuery<Product> = {};
      const { limit, offset } = params;
      const { minPrice, maxPrice } = params;
      if (minPrice && maxPrice) {
        filters.price = { $gte: minPrice, $lte: maxPrice };
      }
      return this.productModel
        .find(filters)
        .populate('brand') // 👈 relation
        .skip(offset)
        .limit(limit)
        .exec();
    }
    return this.productModel.find().populate('brand').exec(); // 👈 relation
  }
}
```

## Relaciones uno a muchos referenciadas

Es crucial diseñar bien tu base de datos. Las relaciones uno a muchos pueden crecer indefinidamente y es importante considerar la escalabilidad de tu base de datos. A lo igual que las relaciones uno a uno, las relaciones uno a muchos requieren contemplar la posible actualización de todo ese array de documentos. Tener un array de objetos puede no ser escalable y una no muy buena decisión de arquitectura de la base de datos. Estos problemas se solucionan creando arrays de referencias. Un simple array de string que contendrá un item por cada ID al cual deseas hacer referencia dentro de un objeto principal.

Veamos como puedes crear este tipo de relación donde un documento contendrá un array de IDs que hacen referencia a otros documentos de la base de datos.

1. Prepara la propiedad correspondiente en tu esquema que contendrá el array de referencias.

```ts
// users/order.entity.ts
import { Document, Types } from "mongoose";
import { Product } from "../../products/entities/product.entity";

@Schema()
export class Order extends Document {
  @Prop({ type: [{ type: Types.ObjectId, ref: Product.name }] })
  products: Types.Array<Product>;
}
```

Observa que el decorador @Prop() recibe como tipo un Types.ObjectId que a su vez se encuentra encerrado por un array []. También, tienes que tipar la propiedad con Types.Array<> proveniente desde mongoose.
De esta simple manera, Mongoose sabe que la propiedad products contiene un array de MongoID.

2. El DTO solo necesita recibir un array de string[] que es el equivalente para un array de MongoID.

```ts
// users/order.dto.ts
import { IsMongoId, IsNotEmpty, IsDate, IsArray } from "class-validator";
import { OmitType, PartialType } from "@nestjs/swagger";

export class CreateOrderDto {
  @IsArray()
  @IsNotEmpty()
  readonly products: string[];
}
```

Utiliza el decorador @IsArray() para validar que efectivamente se trate de un array.

3. Realizar un “Join” o, como se lo conoce en MongoDB, un “Populate” es muy sencillo. Basta con agregar la configuración después del método de búsqueda indicando el nombre de la propiedad a popular.

```ts
// users/orders.service.ts

export class OrdersService {
  constructor(@InjectModel(Order.name) private orderModel: Model<Order>) {}

  findAll() {
    return this.orderModel.find().populate("products").exec();
  }
}
```

Mongoose sabrá a qué colección ir a buscar los documentos al estar referenciado y tipado desde el esquema.

De esta manera, tu base de datos está lista para manipular grandes volúmenes de datos con los mejores tipos de relaciones que existen. Utiliza el tipo de relación más apropiado para cada escenario.

**Código de ejemplo de: Relaciones uno a muchos referenciadas**

```ts
// src/users/entities/order.entity.ts
import { Document, Types } from 'mongoose';

import { Customer } from './customer.entity';
import { Product } from '../../products/entities/product.entity';

@Schema()
export class Order extends Document {
   ...
  @Prop({ type: Types.ObjectId, ref: Customer.name, required: true })
  customer: Customer | Types.ObjectId; // 👈 relation 1:1 customer

  @Prop({ type: [{ type: Types.ObjectId, ref: Product.name }] })
  products: Types.Array<Product>; // 👈 relation 1:N
}

// src/users/dtos/order.dto.ts
import { IsMongoId, IsNotEmpty, IsDate, IsArray } from 'class-validator';
import { OmitType, PartialType } from '@nestjs/swagger';  // 👈 use OmitType

export class CreateOrderDto {
  @IsNotEmpty()
  @IsMongoId()
  readonly customer: string;

  @IsDate()
  @IsNotEmpty()
  readonly date: Date;

  @IsArray()
  @IsNotEmpty()
  readonly products: string[];
}

export class UpdateOrderDto extends PartialType(
  OmitType(CreateOrderDto, ['products']),  // 👈 implement OmitType
) {}

// src/users/services/orders.service.ts

export class OrdersService {
  constructor(@InjectModel(Order.name) private orderModel: Model<Order>) {}

  findAll() {
    return this.orderModel
      .find()
      .populate('customer') // 👈 join customer 1:1
      .populate('products') // 👈 join products 1:N
      .exec();
  }
}
```

## Manipulacion de arrays en MongoDB

Los esquemas que contienen propiedades tipo Array deben manipularse de una forma especial. Haciendo los típicos push/pullpara agregar/quitar elementos, pero considerando la asincronía y que estos arrays se guardan en una base de datos

### Agregar y quitar elementos en un array

Veamos cómo es posible agregar/quitar elementos de un array que forma parte de un documento en MongoDB:

```ts
// users/services/orders.service.ts
export class OrdersService {
  async addProducts(id: string, productsIds: string[]) {
    const order = await this.orderModel.findById(id);
    productsIds.forEach((pId) => order.products.push(pId));
    return order.save();
  }

  async removeProduct(id: string, productId: string) {
    const order = await this.orderModel.findById(id);
    order.products.pull(productId);
    return order.save();
  }
}
```

La función findById() devolverá la referencia del documento encontrado a través de su ID. Gracias a esto, puedes ejecutar otras acciones sobre ese mismo documento para agregar elementos a un array con push() o removerlos con pull(). Finalmente, la función save() actualizará en la base de datos el documento completo.

Del lado del controlador, haz una simple llamada a estas funciones que se encargarán de la manipulación de, en este caso, el array de productos.

```ts
// users/orders.controller.ts
import {
  CreateOrderDto,
  UpdateOrderDto,
  AddProductsToOrderDto,
} from "../dtos/order.dto";

@Controller("orders")
export class OrdersController {
  @Put(":id/products")
  addProducts(@Param("id") id: string, @Body() payload: AddProductsToOrderDto) {
    return this.ordersService.addProducts(id, payload.productsIds);
  }

  @Delete(":id/product/:productId")
  removeProduct(
    @Param("id") id: string,
    @Param("productId") productId: string
  ) {
    return this.ordersService.removeProduct(id, productId);
  }
}
```

Ten en cuenta que este tipo de operaciones son asíncronas, dependiendo de cómo armes tu controlador y el servicio encargado de realizar las modificaciones en la base de datos.

## Operadores especiales de MongoDB

Si trabajas directamente con MongoDB, tienes que conocer los operadores que implementa para la manipulación de arrays. Estos son:

- $addToSet para agregar items en un array
- $pull para eliminar items en un array
- $pullAll para eliminar todos los items en un array

De esta manera, tu mismo puedes crear las consultas a tu base de datos necesarias para manipular un array dentro de un documento, sin necesidad de que herramientas como Mongoose implementen una capa de abstracción que facilite la tarea.

**Código de ejemplo de: Manipulacion de arrays en MongoDB**

```ts
// src/users/services/orders.service.ts

export class OrdersService {
  ...
  async removeProduct(id: string, productId: string) { // 👈
    const order = await this.orderModel.findById(id);
    order.products.pull(productId);
    return order.save();
  }

  async addProducts(id: string, productsIds: string[]) {  // 👈
    const order = await this.orderModel.findById(id);
    productsIds.forEach((pId) => order.products.push(pId));
    return order.save();
  }
}

// src/users/dtos/order.dto.ts

...

export class AddProductsToOrderDto {
  @IsArray()
  @IsNotEmpty()
  readonly productsIds: string[];
}

// src/users/controllers/orders.controller.ts

import {
  CreateOrderDto,
  UpdateOrderDto,
  AddProductsToOrderDto,
} from '../dtos/order.dto';

@Controller('orders')
export class OrdersController {

  @Put(':id/products') // 👈 add product
  addProducts(
    @Param('id') id: string,
    @Body() payload: AddProductsToOrderDto,
  ) {
    return this.ordersService.addProducts(id, payload.productsIds);
  }

  @Delete(':id/product/:productId') // 👈 delete product
  removeProduct(
    @Param('id') id: string,
    @Param('productId') productId: string,
  ) {
    return this.ordersService.removeProduct(id, productId);
  }
}
```

# Modulo 9: Autenticacion con Passport y JWT

## Enlaces de interes

[Repositorio Codigo Base](https://github.com/platzi/nestjs-auth-mongo/tree/1-step)

## Introduccion a Guards

Los Guards son interceptores que se ejecutan antes de que un endpoint sea ejecutado. Permiten validar si un usuario tiene permisos para ejecutar una acción o no.

1. Crear un modulo de autenticación con el comando

```bash
nest g gu auth/guards/apiKey --flat
```

2. El guardia debe implementar la interfaz CanActivate para que NestJS sepa que se trata de un guardia.

```ts
// auth/guards/apiKey.guard.ts
import { CanActivate, ExecutionContext, Injectable } from "@nestjs/common";
import { Observable } from "rxjs";

@Injectable()
export class ApiKeyGuard implements CanActivate {
  canActivate(
    context: ExecutionContext
  ): boolean | Promise<boolean> | Observable<boolean> {
    return true;
  }
}
```

Puedes manipular el retorno de la funcion para que permita o no el acceso al endpoint. En este caso, siempre devuelve true, por lo que el endpoint siempre se ejecutará, si cambiamos a false y colocamos el guardian en un endpoint, este no se ejecutará.

3. Implementar el guardian en un controlador

```ts
// src/app.controller.ts
import { ApiKeyGuard } from "./auth/guards/apiKey.guard";

@Controller()
export class AppController {
  constructor(private readonly appService: AppService) {}

  @Get()
  @UseGuards(ApiKeyGuard) // 👈 use guard
  getHello(): string {
    return this.appService.getHello();
  }
}
```

4. Vamos a validar un header en el request

```ts
import { CanActivate, ExecutionContext, Injectable } from "@nestjs/common";
import { Observable } from "rxjs";

import { Request } from "express";

@Injectable()
export class ApiKeyGuard implements CanActivate {
  canActivate(
    context: ExecutionContext
  ): boolean | Promise<boolean> | Observable<boolean> {
    const request = context.switchToHttp().getRequest<Request>();
    const authHeader = request.header("Auth");
    return authHeader === "1234";
  }
}
```

5. Vamos a customizar el mensaje de error

```ts
import {
  CanActivate,
  ExecutionContext,
  Injectable,
  UnauthorizedException,
} from "@nestjs/common";
import { Observable } from "rxjs";

import { Request } from "express";

@Injectable()
export class ApiKeyGuard implements CanActivate {
  canActivate(
    context: ExecutionContext
  ): boolean | Promise<boolean> | Observable<boolean> {
    const request = context.switchToHttp().getRequest<Request>();
    const authHeader = request.header("Auth");
    const isAuthorized = authHeader === "1234";
    if (!isAuthorized) {
      throw new UnauthorizedException("You is not authorized");
    }
    return isAuthorized;
  }
}
```

## Usando un decorador

Para proteger todos los endpoints de un controlador, puedes utilizar el decorador @UseGuards() en la clase del controlador.

```ts
// src/users/controllers/users.controller.ts
import { ApiKeyGuard } from './../../auth/guards/apiKey.guard';
import { Controller, Get, Post, Body, Put, Param, Delete, UseGuards, SetMetadata } from '@nestjs/common';
import { UsersService } from '../services/users.service';

@Controller('users')
@UseGuards(ApiKeyGuard) // 👈 use guard
export class UsersController {
  constructor(private readonly usersService: UsersService) {}

  @Post()
  create(@Body() createUserDto: CreateUserDto) {
    return this.usersService.create(createUserDto);
  }

  @Get()
  findAll() {
    return this.usersService.findAll();
  }

  @Get(':id')\
  @SetMetadata('isPublic', true) // 👈 use decorator
  findOne(@Param('id') id: string) {
    return this.usersService.findOne(id);
  }

  @Put(':id')
  update(@Param('id') id: string, @Body() updateUserDto: UpdateUserDto) {
    return this.usersService.update(id, updateUserDto);
  }

  @Delete(':id')
  remove(@Param('id') id: string) {
    return this.usersService.remove(id);
  }
}
```

En el guardian

```ts
....
import { Reflector } from '@nestjs/core';
import { Observable } from 'rxjs';

import { Request } from 'express';

@Injectable()
export class ApiKeyGuard implements CanActivate {
  constructor(private reflector: Reflector) {}

  canActivate(
    context: ExecutionContext,
  ): boolean | Promise<boolean> | Observable<boolean> {
    const isPublic = this.reflector.get(isPublic, context.getHandler());
    if (isPublic) {
      return true;
    }
    const request = context.switchToHttp().getRequest<Request>();
    const authHeader = request.header('Auth');
    const isAuth = authHeader === '1234';
    if (!isAuth) {
      throw new UnauthorizedException('not allow');
    }
    return isAuth;
  }
}
```

En el modulo auth, crear una carpeta decorators y un archivo public.decorator.ts

```ts
import { SetMetadata } from "@nestjs/common";

export const IS_PUBLIC_KEY = "isPublic";

export const Public = () => SetMetadata(IS_PUBLIC_KEY, true);
```

En el controlador

```ts
import { Public } from './../../auth/decorators/public.decorator';

....

@Controller('users')
@UseGuards(ApiKeyGuard)
export class UsersController {
  constructor(private readonly usersService: UsersService) {}

  ....

  @Get(':id')
  @Public() // 👈 use decorator
  findOne(@Param('id') id: string) {
    return this.usersService.findOne(id);
  }

  ....
}
```

En el guardian

```ts
....

import { IS_PUBLIC_KEY } from './../decorators/public.decorator';
....
@Injectable()
export class ApiKeyGuard implements CanActivate {
  ....

  canActivate(
    context: ExecutionContext,
  ): boolean | Promise<boolean> | Observable<boolean> {
    const isPublic = this.reflector.get(IS_PUBLIC_KEY, context.getHandler());
    if (isPublic) {
      return true;
    }
   ....
    return isAuth;
  }
}
```

## Guardianes con variables de entorno

1. En el guardian

```ts
import {
  ....
  Inject
} from '@nestjs/common';
....

import { ConfigType } from '@nestjs/config';
import { config } from './../../config';

@Injectable()
export class ApiKeyGuard implements CanActivate {
  constructor(
    private reflector: Reflector,
    @Inject(config.KEY) private configService: ConfigType<typeof config>, // 👈 inject config
  ) {}

  canActivate(
    context: ExecutionContext,
  ): boolean | Promise<boolean> | Observable<boolean> {
    ....
    const isAuth = authHeader === this.configService.apiKey; // 👈 use config
    if (!isAuth) {
      throw new UnauthorizedException('not allow');
    }
    return isAuth;
  }
}
```

## Hashing de contraseñas en Mongo

Las contraseñas son datos sensibles que no pueden guardarse en texto plano en una base de datos. Es necesario utilizar un algoritmo de hashing para que, a partir de una contraseña, se genere un string de caracteres que no pueda ser revertido.

1. Instalar bcrypt con el comando

```bash
npm i bcrypt
npm i @types/bcrypt -D
```

2. En algun servicio de la aplicacion

```ts
....
import * as bcrypt from 'bcrypt';

@Injectable()
export class UsersService {
  ....

  async create(createUserDto: CreateUserDto) {
    const newModel = new this.userModel(createUserDto);
    const hash = await bcrypt.hash(newModel.password, 10); // 👈 hash password
    newModel.password = hash; // 👈 use hash
    const model = await newUser.save();
    const { password, ...result } = model.toJSON();
    return rta;
  }
}
```

Vamos a crear un servicio que nos va permitir encontrar un usuario por email, esto lo vamos a utilizar mas adelante para la autenticacion

```ts
// src/users/services/users.service.ts
....

@Injectable()
export class UsersService {
  ....
  findByEmail(email: string) {
    return this.userModel.findOne({ email }).exec();
  }
}
```

Luego vamos a garantizar que el userService pueda ser utilizado en otros modulos. Para esto, en el archivo users.module.ts

```ts
// src/users/users.module.ts
....
import { UsersService } from './services/users.service';

@Module({
  imports: [MongooseModule.forFeature([{ name: User.name, schema: UserSchema }])],
  controllers: [UsersController],
  providers: [UsersService], // 👈 add provider
  exports: [UsersService], // 👈 add export
})
export class UsersModule {}
```

## Autenticacion con Passport.js

Passport es un middleware para Node.js que permite autenticar usuarios a través de diferentes estrategias. Es muy utilizado en aplicaciones web y móviles.

[Documentacion](https://docs.nestjs.com/recipes/passport)

1. Instalar passport con el comando

```bash
npm i @nestjs/passport passport passport-local
npm i @types/passport-local -D
```

2. Crear un servicio dentro de auth

```bash
nest g s auth/services/auth --flat
```

4. En AuthModule, importar el modulo de usuarios y el servicio de autenticacion

```ts
// src/auth/auth.module.ts
import { PassportModule } from "@nestjs/passport";
import { UsersModule } from "./../users/users.module";
import { AuthService } from "./services/auth.service";
import { LocalStrategy } from "./strategies/local.strategy";

@Module({
  imports: [UsersModule, PassportModule], // 👈 import users module
  providers: [AuthService, LocalStrategy], // 👈 import auth service
})
export class AuthModule {}
```

3. En el servicio creado

```ts
import { Injectable } from "@nestjs/common";
import { UsersService } from "../../users/services/users.service";
import * as bcrypt from "bcrypt";

@Injectable()
export class AuthService {
  constructor(private usersService: UsersService) {}

  async validateUser(email: string, password: string) {
    const user = await this.usersService.findByEmail(email);
    if (user) {
      const isMatch = await bcrypt.compare(password, user.password); // 👈 compare password
      if (isMatch) {
        const { password, ...result } = user.toJSON();
        return result;
      }
    }
    return null;
  }
}
```

4. Crear una estrategia local en auth/strategies/local.strategy.ts

```ts
import { Injectable, UnauthorizedException } from "@nestjs/common";
import { PassportStrategy } from "@nestjs/passport";
import { Strategy } from "passport-local";
import { AuthService } from "../services/auth.service";

export class LocalStrategy extends PassportStrategy(Strategy, "local") {
  constructor(private authService: AuthService) {
    super({
      usernameField: "email",
      passwordField: "password",
    });
  }

  async validate(email: string, password: string) {
    const user = await this.authService.validateUser(email, password);
    if (!user) {
      throw new UnauthorizedException("not allow");
    }
    return user;
  }
}
```

## Ruta de login

1. Crear un controlador de autenticacion

```bash
nest g co auth/controllers/auth --flat
```

2. En el controlador

```ts
import { Controller, Post, Req, UseGuards } from "@nestjs/common";
import { Request } from "express";
import { AuthGuard } from "@nestjs/passport";

@Controller("auth")
export class AuthController {
  @UseGuards(AuthGuard("local")) // 👈 use guard
  @Post("login")
  login(@Req() req: Request) {
    return req.user;
  }
}
```

## Conectando Passport con JWT

JSON Web Tokens (JWT) es un estándar abierto basado en JSON propuesto por IETF para la creación de tokens de acceso que permiten la propagación de identidad y privilegios en aplicaciones web.

[Documentacion](https://docs.nestjs.com/recipes/passport#jwt-functionality)

1. Instalar las dependencias necesarias segun la documentacion
2. En AuthService

```ts
....
import { JwtService } from '@nestjs/jwt';
import { User } from '../../users/entities/user.entity';
import { PayloadToken } from '../models/token.model';

@Injectable()
export class AuthService {
  constructor(
    private usersService: UsersService,
    private jwtService: JwtService, // 👈 inject jwt service
  ) {}

  generateJWT(user: User){
    const payload: PayloadToken = { role: user.role, sub: user.id };
    return {
      access_token: this.jwtService.sign(payload),
      user,
    };
  }
}
```

3. Crear carpeta auth/models/token.model.ts

```ts
export interface PayloadToken {
  role: string;
  sub: number;
}
```

4. en AuthModule

```ts
....
import { JwtModule } from '@nestjs/jwt';
....
import { config } from './../config';
import { ConfigType } from '@nestjs/config';

@Module({
  imports: [ ...., JwtModule.registerAsync({
    inject: [config.KEY],

    useFactory: (configService: ConfigType<typeof config>) => ({
      secret: configService.jwtSecret,
      signOptions: { expiresIn: '10d' },
    }),
  })]
})
```

5. en .env

```env
JWT_SECRET=123456
```

6. En config.ts

```ts
....
export default registerAs('config', () => ({
  database: {
    uri: process.env.DATABASE_URI,
  },
  apiKey: process.env.API_KEY,
  jwtSecret: process.env.JWT_SECRET, // 👈 add jwt secret
}));
```

7. En app.module.ts

```ts
....
import { ConfigModule } from '@nestjs/config';

@Module({
  imports: [
    ....,
    ConfigModule.forRoot({
      load: [config],
      ....
      validationSchema: Joi.object({
        DATABASE_URI: Joi.string().required(),
        API_KEY: Joi.string().required(),
        JWT_SECRET: Joi.string().required(), // 👈 add jwt secret
      }),
    }),
  ],
})
```

8. En el controlador

```ts
....
import { AuthService } from '../services/auth.service';
import { User } from './../../users/entities/user.entity';

@Controller('auth')
export class AuthController {
  constructor(private authService: AuthService) {}

  @UseGuards(AuthGuard('local'))
  @Post('login')
  login(@Req() req: Request) {
    const user = req.user as User;
    return this.authService.generateJWT(user); // 👈 use generateJWT
  }
}
```

[Refresh Token con Nest](https://wanago.io/2020/09/21/api-nestjs-refresh-tokens-jwt/)

## Implementando JWT Guard

1. En la carpeta strategies crear un archivo jwt.strategy.ts

```ts
import { Injectable, Inject } from "@nestjs/common";
import { PassportStrategy } from "@nestjs/passport";
import { Strategy, ExtractJwt } from "passport-jwt";
import { ConfigType } from "@nestjs/config";
import { config } from "./../../config";
import { PayloadToken } from "../models/token.model";

@Injectable()
export class JwtStrategy extends PassportStrategy(Strategy, "jwt") {
  constructor(
    @Inject(config.KEY) private configService: ConfigType<typeof config>
  ) {
    super({
      jwtFromRequest: ExtractJwt.fromAuthHeaderAsBearerToken(),
      ignoreExpiration: false,
      secretOrKey: configService.jwtSecret,
    });
  }

  validate(payload: PayloadToken) {
    return payload;
  }
}
```

en auth.module.ts

```ts
....
import { JwtStrategy } from './strategies/jwt.strategy';

@Module({
  imports: [ .... ],
  providers: [AuthService, LocalStrategy, JwtStrategy], // 👈 add jwt strategy
})

```

2. En el controlador

```ts
....
import { AuthGuard } from '@nestjs/passport';

@UseGuards(AuthGuard('jwt')) // 👈 use guard
@Controller('products')
....
```

[Una ayudita adicional](https://platzi.com/comentario/2708399/)

## Extendiendo JWT Guard

1. Crear un nuevo guardian

```bash
nest g gu auth/guards/jwt --flat
```

2. En el guardian

```ts
import { Injectable, ExecutionContext } from "@nestjs/common";
import { Reflector } from "@nestjs/core";
import { AuthGuard } from "@nestjs/passport";

import { IS_PUBLIC_KEY } from "../decorators/public.decorator";

@Injectable()
export class JwtGuard extends AuthGuard("jwt") {
  constructor(private reflector: Reflector) {
    super();
  }

  canActivate(context: ExecutionContext) {
    const isPublic = this.reflector.get("IS_PUBLIC_KEY", context.getHandler());
    if (isPublic) {
      return true;
    }
    return super.canActivate(context);
  }
}
```

3. En el controlador

```ts
....
import { JwtGuard } from './../../auth/guards/jwt.guard';
import { Public } from '../../auth/decorators/public.decorator';

@UseGuards(JwtGuard) // 👈 use guard
@Controller('products')
export class ProductsController {
  ....
  @Get()
  @Public() // 👈 use decorator
  findAll(@Query() params: FilterProductsDto) {
    return this.productsService.findAll(params);
  }

  @Get(':id')
  @Public() // 👈 use decorator
  findOne(@Param('id') id: string) {
    return this.productsService.findOne(id);
  }

  @Post()
  create(@Body() createProductDto: CreateProductDto) {
    return this.productsService.create(createProductDto);
  }
  ....
}
```

## Control de roles en NestJS

1. Definir los roles dentro de nuestra aplicacion en auth/models/roles.model.ts

```ts
export enum Role {
  ADMIN = "admin",
  CUSTOMER = "customer",
}
```

2. Crear un decorador para los roles en auth/decorators/roles.decorator.ts

```ts
import { SetMetadata } from "@nestjs/common";
import { Role } from "../models/roles.model";

export const ROLES_KEY = "roles";
export const Roles = (...roles: Role[]) => SetMetadata(ROLES_KEY, roles);
```

3. En el controlador

```ts
....
import { Roles } from '../../auth/decorators/roles.decorator';
import { Role } from '../../auth/models/roles.model';

@UseGuards(JwtGuard)
@Controller('products')
export class ProductsController {
  ....
  @Post()
  @Roles(Role.ADMIN) // 👈 use decorator
  create(@Body() createProductDto: CreateProductDto) {
    return this.productsService.create(createProductDto);
  }
  ....
}
```

4. crear un nuevo guardian

```bash
nest g gu auth/guards/roles --flat
```

5. En el guardian

```ts
import {
  CanActivate,
  ExecutionContext,
  Injectable,
  UnauthorizedException,
} from "@nestjs/common";
import { Reflector } from "@nestjs/core";
import { Observable } from "rxjs";

import { ROLES_KEY } from "../decorators/roles.decorator";
import { PayloadToken } from "../models/token.model";
import { Role } from "../models/roles.model";

@Injectable()
export class RolesGuard implements CanActivate {
  constructor(private reflector: Reflector) {}
  canActivate(
    context: ExecutionContext
  ): boolean | Promise<boolean> | Observable<boolean> {
    const roles = this.reflector.get<Role[]>(ROLES_KEY, context.getHandler());
    if (!roles) {
      return true;
    }
    // ['admin', 'customer'];
    const request = context.switchToHttp().getRequest();
    const user = request.user as PayloadToken;
    // { role: 'admin', sub: 1212 }
    const isAuth = roles.some((role) => role === user.role);
    if (!isAuth) {
      throw new UnauthorizedException("your role is wrong");
    }
    return isAuth;
  }
}
```

6. En el controlador

```ts
....
import { RolesGuard } from '../../auth/guards/roles.guard';

@UseGuards(JwtGuard, RolesGuard) // 👈 use guard
@Controller('products')
export class ProductsController {
  ....
  @Post()
  @Roles(Role.ADMIN) // 👈 use decorator
  create(@Body() createProductDto: CreateProductDto) {
    return this.productsService.create(createProductDto);
  }
  ....
}
```

## Obteniendo ordenes del perfil

En la clase anterior vimos como puedes hacer para identificar un rol y de acuerdo a eso poder darle acceso a un endpoint, ahora te pongo el siguiente escenario:

¿Como crear un endpoint que retorne todas las órdenes relacionados con el usuario que tiene sesión?

Una solución válida a este problema es que puedes crear un endpoint que enviándole el ID de un usuario te retorne dichas órdenes, algo como esto:

`http://localhost:3000/users/1/orders` Este endpoint me retornaría todas las órdenes del usuario con ID 1, sin embargo puede ser algo peligroso, es decir, este endpoint solo debería estar disponible para los roles administrativos, pero no para los usuarios porque si conoces el ID de algún cliente podrías obtener la información de órdenes de compra de un usuario.

La solución más práctica para este caso es crear un endpoint de este tipo:

`http://localhost:3000/profile/my-orders`

Como ves en el endpoint anterior no estás colocando de forma explícita el ID de un usuario. ¿Entonces como sabe a qué usuario le pertenecen las órdenes? Sencillo, sí nuestro usuario ya tiene una sesión, esta información ya está en el JWT que se le otorgó a ese usuario al autentificarse en el sistema así con eso podemos inferirlo de acuerdo a la sesión

Lo primero es que vamos a hacer es crear un nuevo controlador para todos las solicitudes que sean de este tipo. Lo vamos a crear con el nombre ProfileController.

`nest g co users/controllers/profile --flat`

Allí vamos a exponer un nuevo endpoint que va a recibir la solicitud y gracias al decorador de
@UseGuards(JwtAuthGuard, RolesGuard) nos aseguramos que tenga un token válido, así que en ese método recogemos la información de usuario que tiene esa sesión así:

```ts
@Roles(Role.CUSTOMER)
@Get('my-orders')
getOrders(@Req() req: Request) {
  const user = req.user as PayloadToken;
  return this.orderService.findOne(user.sub);
}
```

Simplemente con decirle que dentro del método que queremos la información del Request podemos obtener la información del usuario que tiene sesión, luego simplemente obtenemos el ID y ya con eso podemos crear un método en nuestro servicio de órdenes que las retorne, algo así:

```ts
ordersByCustomer(customerId: number) {
  return this.orderRepo.find({
    where: {
      customer: customerId,
    },
  });
}
```

Este sería el código completo del nuevo controlador ProfileController:

```ts
import { Controller, Get, UseGuards, Req } from "@nestjs/common";
import { ApiTags } from "@nestjs/swagger";

import { Request } from "express";

import { JwtAuthGuard } from "../../auth/guards/jwt-auth.guard";
import { RolesGuard } from "../../auth/guards/roles.guard";
import { Roles } from "../../auth/decorators/roles.decorator";
import { Role } from "../../auth/models/roles.model";
import { PayloadToken } from "src/auth/models/token.model";
import { OrdersService } from "../services/orders.service";

@UseGuards(JwtAuthGuard, RolesGuard)
@ApiTags("profile")
@Controller("profile")
@Controller("profile")
export class ProfileController {
  constructor(private orderService: OrdersService) {}

  @Roles(Role.CUSTOMER)
  @Get("my-orders")
  getOrders(@Req() req: Request) {
    const user = req.user as PayloadToken;
    return this.orderService.ordersByCustomer(user.sub);
  }
}
```

Puedes ver toda esta solución en la rama 14.

# Modulo 10: Deploy de Mongo

## Configurando Mongo Atlas

Mongo Atlas es un servicio de base de datos en la nube que te permite crear y administrar bases de datos MongoDB. Es una excelente opción para desplegar tus aplicaciones en producción.

Ten en cuenta que MongoCompass tiene una version de un cluster gratuita, sin embargo, esto es util solo para pruebas y no se recomienda para produccion.

Para produccion, puedes considerar utilizar una version paga.

- En el apartado Network Access, puedes configurar las IP que pueden acceder a tu cluster. Puedes configurar una IP fija o un rango de IPs. En este caso, vamos a permitir el acceso a cualquier IP, aunque esto no es una buena practica en produccion.

## Desplegando en Heroku

1. en main.ts

```ts
....
async function bootstrap() {
  const app = await NestFactory.create(AppModule);
  app.enableCors(); // 👈 enable cors
  await app.listen(process.env.PORT || 3000);
}
bootstrap();
```

2. Verificar la version de node en package.json

```json
"engines": {
  "node": "14.x"
},
```

3. Arhivo Procfile

```
web: npm run start:prod
```

4. Correr el comando

```bash
heroku create
```

5. Ten en cuenta que todo tu codigo para despliegue debe estar en la rama main

```bash
git push heroku main
```

6. Con el comando `heroku logs --tail` puedes ver los logs de tu aplicacion

Recuerda que debes incluir las variables de entorno en heroku. Puede hacerlo mediante la interfaz grafica. Debes crear una variable de entorno que se llame MONGO_CONNECTION y que tenga como valor `mongodb+srv`:

Puedes configurar variables de entorno en heroku con el comando

`heroku config:set JWT_SECRET=...`

Las bases de datos en la nube, no requieren un puerto, por lo cual debes adaptar el codigo de database.module.ts
