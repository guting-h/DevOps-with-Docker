Aftering rebuilding the images after changes to the Dockerfiles:
```
$ docker run -d -p 8080:8080 hello-backend

$ docker run -p 5001:5001 hello-frontend

```
Then check the result at http://localhost:5001 