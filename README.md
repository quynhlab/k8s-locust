## Distributed Load Testing Using Kubernetes and Locust


## Architecture

<img src="https://github.com/quynhlab/k8s-locust/blob/main/images/dl-architecture.svg">

## How to run
```
git clone https://github.com/quynhlab/k8s-locust.git
```
## Building the image
```
docker build -t ndquynhz/locust:stable .
```
Then push to private registry or docker hub

## Run on Kubernetes
```
cd kubernetes-config
kubectl create -f .
```

Enjoy!


