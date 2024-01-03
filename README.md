# RedMica deployment by Kamal

This repository contains a minimum configuration for deploying [RedMica](https://github.com/redmica/redmica) with [Kamal](https://kamal-deploy.org/) to Amazon EC2, etc.

## Prerequisite

These configurations assume the following environments.

* Deploy to EC2
* Use [official RedMica Docker images](https://hub.docker.com/r/redmica/redmica/) to deploy
* Use Ruby 3.2

## How to deploy

1. Execute `bundle install`
1. Copy `.env.sample` to create `.env` and set each configuration in `.env`
1. Copy `config/deploy.sample.yml` to `config/deploy.yml` and set each configuration
1. Execute `kamal setup`
