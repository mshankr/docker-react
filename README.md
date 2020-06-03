Dockerized simple weather app

**Demonstrates:**
- Make custom Docker image
- Up and running
- Work with Travis CI

## dev
- dev version where ```src``` and ```public``` folders are referenced (docker-volume mounted)
- able to rerun on ```src``` code change!!
- uses ```npm start```
- to clarify: uses ```node_modules``` in docker container itself

## prod
prod version where docker just serves the ```build``` folder

1. uses multi-step docker building to build ```build``` folder first!
2. uses nginx to serve
