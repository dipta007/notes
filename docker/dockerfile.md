## Docker File
A text file with instructions to build image.

### Instructions:
1. FROM
2. RUN
3. CMD

### Sample Docker File
FROM `image-name`
RUN apt-get update
CMD ["echo", "Hello World"]


### Difference between RUN & CMD
#### RUN: 
Run is executed during the image creation.

#### CMD:
CMD is executed only when container is created.

### Commands:
1. docker build -t `my-image:tag` .  
   Create a docker from this folder's Dockerfile name `image-name` with tag `tag`


### Steps:
1. Create a file name Dockerfile
2. Add instructions in Dockerfile
3. Build Dockerfile to create image
4. Run image to create container


## Dockerfile References
* https://github.com/Microsoft/vscode-docker
* https://docs.docker.com/engine/reference/builder/#environment-replacement