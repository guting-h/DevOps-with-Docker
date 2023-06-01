```
$ git clone https://github.com/docker-hy/material-applications.git

$ cp Dockerfile ./material-applications/example-frontend

$ cd ./material-applications/example-frontend

$ docker build . -t hello-frontend

$ docker run -p 5001:5001 hello-frontend
```
Navigate to http://localhost:5001 to see result