# Docker 
1. sudo docker --version
2. create a Dockerfile
    1. From {base image}
    2. WORKDIR /app
    3. COPY . .
    4. CMD ["main.py"]
3. sudo docker build -t my_app . {image building}
4. sudo docker image ls{or images}
5. sudo docker rmi <image name> or sudo docker rmi -f <image name>
6. sudo docker run my_python_app
7. sudo docker ps
8. sudo docker stop <container id {or name}>
9. sudo docker rm <container id>

10. sudo docker login
11. sudo docker tag my_python_app <docker Uname>/my_python_app
12. sudo docker push <docker Uname>/my_python_app
13. docker pull <Uname>/my_python_app
14. docker run <uUname>/my_python_app
