## Jakie API wybrac?

https://koajs.com/#introduction



        const Koa = require('koa');
        const app = new Koa();

        app.use(async ctx => {
          ctx.body = 'Hello World';
        });

        app.listen(3000);


## Lista API

    restana-turbo-http: Requests/sec 57622.13
    restana: Requests/sec 43575.36
    restana-cluster: Requests/sec 71626.33
    fastify: Requests/sec 36894.86
    koa: Requests/sec 23486.64
    restify: Requests/sec 21903.95
    hapi: Requests/sec 16509.12
    express: Requests/sec 16057.22
## Restify
restify is a framework, utilizing connect style middleware for building REST APIs. For full details, 
http://restify.com
https://github.com/restify/node-restify

https://www.npmjs.com/package/swagger-ui-restify
https://www.npmjs.com/package/restify-swagger-jsdoc
https://www.npmjs.com/package/swagger-restify

## Fastify
https://www.fastify.io/
https://github.com/fastify/fastify

#### fastify-swagger
Swagger documentation generator for Fastify. It uses the schemas you declare in your routes to generate a swagger compliant doc.
https://github.com/fastify/fastify-swagger
fastify-swagger/examples/dynamic.js

#### fastify-cli
Command line tools for Fastify. Generate, write and run an application with one single command!
https://github.com/fastify/fastify-cli

## Koa Info
https://github.com/koajs/examples
https://github.com/koajs/koa/wiki#middleware

### koa-joi-swagger 
Using joi schema to validate request & response, and generate swagger document to create beautiful API documents.
https://github.com/zaaack/koa-joi-swagger


Therefore, to make this library simple and reliable, I just mixed joi and swagger document, and using joi-to-json-schema to transform joi schema to swagger schema. You don't have to learn a new schema, just replace the JSON schema in your swagger document to joi schema, then let this library to do the rest.



### Koa-OAI-Router
Koa Router, based on OpenAPI, Swagger and Json Schema.
https://github.com/BiteBit/koa-oai-router

### Koa-OAI-Router Examples
A repository containing small examples to illustrate the use of koa-oai-router for creating web applications and other HTTP servers.
https://github.com/oaijs/koa-oai-router-examples


### Koa REST API Boilerplate
Boilerplate for Node.js Koa RESTful API application with Docker, Swagger, Jest, Coveralls, and Circle CI 
https://github.com/posquit0/koa-rest-api-boilerplate
https://github.com/koajs/api-boilerplate

### node-koajs-rest-skeleton v3.5
https://github.com/ria-com/node-koajs-rest-skeleton


