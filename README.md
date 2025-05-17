# 🐳 Docker Cheatsheet

## 🏁 Container Commands
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Start a new container from an image | `docker run [IMAGE]`                         |
| List running containers              | `docker ps`                                  |
| List all containers                  | `docker ps -a`                               |
| Stop a running container             | `docker stop [CONTAINER]`                    |
| Start a stopped container            | `docker start [CONTAINER]`                   |
| Remove a container                   | `docker rm [CONTAINER]`                      |
| Run a command in a running container| `docker exec -it [CONTAINER] [COMMAND]`      |
| Restart a container                  | `docker restart [CONTAINER]`                 |
| View container logs                  | `docker logs [CONTAINER]`                    |
| Inspect container details            | `docker inspect [CONTAINER]`                 |

## 📦 Image Commands
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Pull an image from a registry        | `docker pull [IMAGE]`                        |
| Build an image from Dockerfile       | `docker build -t [NAME] [PATH]`              |
| List all images                      | `docker images`                              |
| Remove an image                      | `docker rmi [IMAGE]`                         |
| Tag an image                         | `docker tag [IMAGE] [NEW_TAG]`               |
| Show image history                   | `docker history [IMAGE]`                     |
| Inspect image details                | `docker inspect [IMAGE]`                     |

## 💾 Volume Commands
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Create a volume                      | `docker volume create [NAME]`                |
| List all volumes                     | `docker volume ls`                           |
| Remove a volume                      | `docker volume rm [NAME]`                    |
| Inspect volume details               | `docker volume inspect [NAME]`               |

## 🌐 Network Commands
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Create a network                     | `docker network create [NAME]`               |
| List networks                        | `docker network ls`                          |
| Remove a network                     | `docker network rm [NAME]`                   |
| Connect container to a network       | `docker network connect [NETWORK] [CONTAINER]` |
| Disconnect container from a network | `docker network disconnect [NETWORK] [CONTAINER]` |

## 📋 Docker Compose
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Start services                       | `docker-compose up`                          |
| Stop and remove services             | `docker-compose down`                        |
| Build services                       | `docker-compose build`                       |
| List containers                      | `docker-compose ps`                          |
| View logs                            | `docker-compose logs`                        |
| Run a command in a service           | `docker-compose exec [SERVICE] [COMMAND]`    |
| Stop a service                       | `docker-compose stop`                        |
| Start a service                      | `docker-compose start`                       |
| Restart a service                    | `docker-compose restart`                     |

## 🧹 System & Info
| Description                          | Command                                      |
|--------------------------------------|----------------------------------------------|
| Show disk usage                      | `docker system df`                           |
| Remove unused data                   | `docker system prune`                        |
| Display Docker system info           | `docker info`                                |
| Show Docker version                  | `docker version`                             |
