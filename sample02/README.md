간단한 node 서버 실행하기
===============
아무 기능을 제공하지 않는 간단한 node 서버를 제공한다.

해당 폴더에서 아래 명령어로 결과를 확인 할 수 있다.
```
docker build --tag=sample02 .
docker image ls

docker run -d -p 4440:8080 --name=node_sample sample02
docker container ls -all
```