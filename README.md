Docker란 무엇인가?
===============
https://www.docker.com/resources/what-container

# Get Start Part 1
https://docs.docker.com/get-started/

## 1. Docker 설치하기
```
https://www.docker.com/get-started
or
Mac : brew cask install docker
```
## 2. 설치 완료 후 Version 확인
```
docker --version
docker-compose --version
docker-machine --version
```

## 3. 간단하게 docker를 실행해보자
```
docker run hello-world
```

### List Docker CLI commands
```
docker
docker container --help
```

#### Display Docker version and info
```
docker --version
docker version
docker info
```

#### Execute Docker image
```
docker run hello-world
```

#### List Docker images
```
docker image ls
```

#### List Docker containers (running, all, all in quiet mode)
```
docker container ls
docker container ls --all
docker container ls -aq
```

#### 이미지 삭제
```
docker container ls -a
docker container stop XXXXX
docker container ls -a
docker container rm XXXXXX
docker image ls
docker image rm XXXXX
```