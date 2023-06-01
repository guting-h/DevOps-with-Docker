```
$ git clone https://github.com/docker-hy/material-applications.git

$ cp Dockerfile ./material-applications/example-backend

$ cd ./material-applications/example-backend

$ docker build . -t hello-backend

$ docker run -p 8080:8080 hello-backend
```