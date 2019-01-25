# Dockerfile

## redis Dockerfile
* docker build -t redis_liu:v1 .
* docker run -it -d -p 6379:6379 -v /data/:/data/ --name testredis2 redis_liu:v1 /bin/bash
