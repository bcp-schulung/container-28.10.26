sudo docker run -d -p 8181:80 nginx

sudo docker ps

curl localhost:8181

sudo docker logs <container-id>

sudo docker images

sudo docker stop <container-id>

sudo docker rm <container-id>

sudo docker system info

sudo docker run -d -p 8181:80 nginx

sudo docker ps

sudo docker inspect <container-id>

sudo docker exec -it <container-id>

apt update && apt install nano -y

rm /usr/share/nginx/html/index.html 

nano /usr/share/nginx/html/index.html

exit

curl localhost:8181

sudo docker stop <container-id>

sudo docker rm <container-id>

sudo docker run -d -p 8181:80 nginx

curl localhost:8181

cd app

sudo docker build -t ben-coeppicus:v1 .

sudo docker images

sudo docker run -d -p 8282:80 ben-coeppicus:v1

curl localhost:8282

sudo docker pull alpine:latest

sudo trivy image alpine

sudo docker images

sudo docker build -t databport-harbor.databport.it-scholar.com/seminar/ben-coeppicus:v2 .

sudo docker run -d -p 8383:80 databport-harbor.databport.it-scholar.com/seminar/ben-coeppicus:v2

curl localhost:8383

sudo trivy image databport-harbor.databport.it-scholar.com/seminar/ben-coeppicus:v2