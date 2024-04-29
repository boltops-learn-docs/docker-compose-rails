<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/docker-compose-rails/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Docker Compose Rails Example Tutorial

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This tutorial shows you how to set up docker compose with Rails.

Walks you through the process from a brand new rails app to the docker-compose.yml.

Setting this up so development works with both local and docker setup. Found this to be more useful.

## Docker Compose Commands

    docker-compose build
    docker-compose up
    docker-compose exec web

More:

    docker-compose start
    docker-compose stop

## Docker Commands

    docker build -t boltops/docker-compose-rails .
    docker run boltops/docker-compose-rails
    docker push boltops/docker-compose-rails

## Notes

Replace boltops with your own DockerHub username if you are going through the tutorial.

## Video

[![Watch the video](https://uploads-learn.boltops.com/q15yf9l7qunju58qluvnfxaeqalm)](https://learn.boltops.com/courses/docker/lessons/docker-compose-with-rails)

Note: Premium video content requires a subscription.
