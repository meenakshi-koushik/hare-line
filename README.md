# hare-line
A repo to learn RabbitMQ

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/meenakshi-koushik/hare-line)

# Run rabbitmq

```
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 -v /workspace/hare-line/rabbitmq.conf:/etc/rabbitmq/rabbitmq.conf rabbitmq:3.9-management
```
