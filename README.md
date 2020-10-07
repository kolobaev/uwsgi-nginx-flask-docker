For tests with python3.7:
```sh
docker run -d --name flask --network host vkolobaev/uwsgi-nginx-flask-docker:python3.7
open http://127.0.0.1:8888
```

For tests with python3.8:
```sh
docker run -d --name flask --network host vkolobaev/uwsgi-nginx-flask-docker:python3.8
open http://127.0.0.1:8888
```
