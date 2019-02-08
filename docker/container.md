## Docker container
Docker container is the instance of the the docker image.

### Commands
1. docker ps  
   List all the running containers
2. docker ps -a  
   List all the containers
3. docker run `image-name`
   Run the docker with the image `image-name`
4. docker run -it `image-name`
   Run the docker interactively
5. docker run --name myUbuntu `image-name`
   Run the docker with my given name
6. docker start `container-id`
7. docker stop `container-id`
8. docker pause `container-id`
9. docker unpause `container-id`
10. docker top `container-id`  
    Get the processes of the containcer
11. docker stats `container-id`  
    Get the stats of the container like memory, cpu
12. docker attach `container-id`  
    Attach to the os of container
13. docker kill `container-id`  
    Kill the container os
14. docker rm `container-id`
    Remove the container
15. docker history `image-id`
    Get the history of the image
