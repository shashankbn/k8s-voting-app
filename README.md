# example-voting-app-kubernetes-v2

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) from docker-examples(https://github.com/dockersamples)

modified to work on Kubernetes

## Pre-requisites
Install minikube and kubectl

## To create pods and services
kubectl apply -f .

## To access result-service
minikube service result-service --url

## To access voting-service
minikube service voting-service --url

## To delete pods and services
kubectl delete -f .


