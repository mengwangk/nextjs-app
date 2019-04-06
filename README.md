# nextjs-app

```

docker build -t mengwangk/nextjs-app .

docker run -d -p 8889:3000 mengwangk/nextjs-app:latest

docker kill $(docker ps -q)

docker rm $(docker ps -a -q)

docker rmi $(docker images -q)

```