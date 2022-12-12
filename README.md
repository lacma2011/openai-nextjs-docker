This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# To run:

## create .env.docker

Copy example file .env.docker.example and add your openai secret key

## Build Docker Image

```
docker-compose build
```

## Run Docker Image

```
docker-compose up
```

# Creating this demo

## step 1

I started with this project, ben marte nextjs-docker:

https://github.com/benmarte/nextjs-docker

https://benmarte.com/blog/nextjs-in-docker/

## step 2

I then changed the docker setup so I can use it strictly for docker-based development of node/nextjs, with this. Specifically the Dockerfile and docker-compose:

https://jameschambers.co.uk/nextjs-hot-reload-docker-development

The previous Dockerfile is meant for deployment

## step 3

Quickstart node example for using the openai API

https://github.com/openai/openai-quickstart-node
