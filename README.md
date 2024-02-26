# K8s_LABs

docker build . -t k8s-flask-app:latest
docker image list
docker run -d -p 5000:5000 k8s-flask-app:latest
docker ps

curl http://127.0.0.1:5000/

