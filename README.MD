```
docker build -t flask_app .
docker run -p 5000:5000 flask_app
```
-p <host_port>:<container_port> - publish a container's port(s) to the host