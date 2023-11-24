
# Run following command on terminal

docker build --tag=101392515_hello_docker .

docker build -t 101392515_hello_docker .

docker image ls

docker run -p 4000:80 101392515_hellodocker

docker run -d --name=lab11DevOps -p 4000:80 101392515_hello_docker

docker container stop CONTAINER_ID

docker container ls