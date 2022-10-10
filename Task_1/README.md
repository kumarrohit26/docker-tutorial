# 15 Basic docker commands

## 1. Docker Version : Get the currently installed version of docker.
```
docker -version
```

![](./1_version.jpg)

## 2. Docker Login : Login to the docker hub repository.

```
docker login
```
![](./2_login.jpg)

## 3. Docker Pull : Pull images from [docker hub repository](https://hub.docker.com/).

```
docker pull <image-name>
```
![](./3_pull_image.jpg)

## 4. Docker images : Lists all locally stored docker images.

```
docker images
```
![](./4_list_images.jpg)

## 5. Docker run : create container from the image.

```
docker run -d -p 80:80 docker/getting-started
```
![](./5_run_docker_image.jpg)

## 6. Docker ps : List all running container.

```
docker ps
```
![](./6_list_running_containers.jpg)

## 7. Docker ps -a : List all containers, running and exited.

```
docker ps -a
```
![](./7_list_all_containers.jpg)

## 8. Docker rmi : Delete image.

```
docker rmi <image-name>
```
![](./8_remove_docker_image.jpg)

## 9. Docker stop : Stops running container.

```
docker stop <container-id>
```
![](./9_stop_running_container.jpg)

## 10. Docker kill : Kills running container by stopping its execution immediately. 'docker stop' gives time to shutdown normally and 'docker kill' shutdown immediately.

```
docker kill <container-id>
```
![](./10_kill_running_container.jpg)

## 11. Docker rm : Removes container from local.

```
docker rm <container-id>
```
![](./11_remove_container.jpg)

## 12. Docker logs : Get logs of container.

```
docker logs <container-id>
```
![](./12_get_logs_of_container.jpg)

## 13. Docker build : Build docker image from specified docker file.

```
docker build -t <image-name> .
```
![](./13_build_docker_image.jpg)

## 14. Docker push : Push docker image from local to [docker hub repository](https://hub.docker.com/).

```
docker push <username/image-name>:<tag-name>
```
![](./14_push_image_to_repository.jpg)

## 15. Docker exec : Access running container.

```
docker exec -it <container-name> bash
```
![](./15_access_running_container.jpg)
