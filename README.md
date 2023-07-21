###  Why use docker?

Make it easy to install and run software on any computer and webserver without worrying about setups or dependencies

### What is docker

Is a platform or ecosystem around creating and running containers

<img width="820" alt="image" src="https://github.com/MutiatOba/docker/assets/118978642/47573366-e4d6-4fe5-a26b-172a4befc712">

An image is a single file with all the deps and config required to run a program. you can use image to create a container.

A container is an instance of image. Runs a programme. A container is programme with own isolated set of resources. it has space of memory and networking tech and harddrive space. 

### installing docker

When we install docker this includes a docker client (cli - tool used to issue commands) and docker server (docker deamon -responsible for creating images and running containers)

### using docker cli

when type  command '''docker run hello-world''' this starts docker client on your computer. this is communicated to docker server. The docker server know want to start container. it first chaeck if we have image locally and if not downloads it from docker hub. this command create a new container with the hello-world image

### what is a container

