# Dockerfile

## redis Dockerfile
* docker build -t redis_liu:v1 .
* docker run -p 6379:6379 -v /data/:/data/ --name testredis2 redis_liu:v1 /bin/bash -c "nohup ping -i 1000 www.baidu.com"
