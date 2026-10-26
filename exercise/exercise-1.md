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