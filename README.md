## my-app

*Build docker image*
```
docker build -t my-app:latest .
```
*Run docker container*
```
docker run --rm -dp 80:80 my-app:latest
```