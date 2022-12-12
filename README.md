This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# To run:

## Create .env.docker

Copy example file .env.docker.example and add your OpenAI secret key

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

I sort of started with Ben Marte's nextjs-docker project:

https://github.com/benmarte/nextjs-docker

Explained in https://benmarte.com/blog/nextjs-in-docker/, I didn't really use the docker files in the end since it didn't support using docker for the development environment which is what I was looking for.

## step 2

I changed the docker setup so I can use it strictly for docker-based development of node/nextjs. Specifically the Dockerfile and docker-compose.yml:

https://jameschambers.co.uk/nextjs-hot-reload-docker-development

The previous Dockerfile was meant for deployment issues.

## step 3

The app code is replaced by the official quickstart node project for OpenAI API:

https://github.com/openai/openai-quickstart-node
