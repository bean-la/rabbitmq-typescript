# RabbitMQ implementation using NodeJS (amqplib) and TypeScript 

Simple application template to use RabbitMQ with TypeScript.

## Running

* Environment variable RABBITMQ_ADDRESS should set your RabbitMQ address.
* By default, it'll use 'amqp://guest:guest@localhost:5672'

### Production

```
npm i 
npm run build
node dist/out-tsc/server.js
```

### Development

```
npm i 
npm run build
npm run watch
```