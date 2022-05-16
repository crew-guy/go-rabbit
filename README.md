## Go-rabbit

A simple implementation of rabbit mq in golang using [blog](https://github.com/rabbitmq/rabbitmq-tutorials/blob/master/go/receive.go) as a reference

Ran the following command to have a simple instance of RabbitMQ running that would support this current config

`docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.10-management`