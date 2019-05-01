Hello Docker
===============
Docker 홈페이지에서는 Part2를 파이썬으로 예제를 보여주고 있다. 여기서는 node.js 기반으로 hello docker를 출력하는 간단한 예제를 실행해보고자 한다.

해당 폴더에서 아래 명령어로 결과를 확인 할 수 있다.
```
docker build --tag=sample01 .
docker image ls

docker run --name=node_sample sample01
docker container ls -all
```