# docker_login

To login to your running container do the following:

1. Run docker
```docker-compose up```
2. Display running containers
```docker ps```
3.  Login with your container id i.e. for backend
```docker exec -t -i <container_id> bash```
4. You are now in the root of your container and can run migrations etc. (edited) 
