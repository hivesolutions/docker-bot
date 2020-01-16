# Docker Bot

Simple bot for [Docker](https://docker.com) automation, that makes used of the [Docker API](http://docker-api.hive.pt) project.

## Configuration

* `DOCKER_KEY` (`str`) - Secret key that should be passed in protected calls so that the server side
"trusts" the client side (authentication) (defaults to `None`)
