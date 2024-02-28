# K8s_LABs: Minikube, Kind, AWS EC2 and Docker

## AWS Cloud9
[Cloud9](https://aws.amazon.com/cloud9/)
## Docker
-```docker build . -t k8s-flask-app:latest```<br>

-```docker image list```<br>
-```docker run -d -p 5000:5000 k8s-flask-app:latest```<br>
-```docker ps```<br>

### Testing
-```curl http://127.0.0.1:5000```
```curl http://172.17.0.2:5000```


### Push Docker image to Docker hub
tag
```docker tag k8s-flask-app sword2yk/k8s-flask-app:v1.0```<br>
Docker login
Enter your docker hub login details

## Minikube
[Minikube](https://minikube.sigs.k8s.io/docs/start/)
## Kind
[Kind](https://kind.sigs.k8s.io/)
