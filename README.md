# celery-flower-heroku

Use [Flower](https://github.com/mher/flower/) to monitor [Celery](http://www.celeryproject.org/).

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Configure the app by providing your `BROKER_URL` (RabbitMQ, Redis) and the `FLOWER_BASIC_AUTH` as a `user:pass` pair for logging into Flower.
