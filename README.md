# _Microservices Architecture project in nodejs._ 🚀

[![N|Solid](https://nodejs.org/static/images/logo.svg)](https://nodejs.org/en/)

Implementes RabbitMQ broker as a messaging queue channel and amqp package to manage and send messages to channel.
Some REST api endpoints which lisitens and then sends messages to queues. 
This is just a demo which you can try locally.

Download rabbitMQ from https://www.rabbitmq.com/download.html and set it up locally or you can also user online providers like https://www.cloudamqp.com/

Know more about microservices from https://www.youtube.com/playlist?list=PLaLqLOj2bk9ZV2RhqXzABUP5QSg42uJEs

Amqplib https://www.npmjs.com/package/amqplib

Docker files and docker compose are added and tested. Working as expected!


Start node gateway by doing
```sh
cd mini-project/gateway
npm i
npm start
```

Remember to start other services as well by going into their directories and do the following:-
```sh
npm i
npm start
````
