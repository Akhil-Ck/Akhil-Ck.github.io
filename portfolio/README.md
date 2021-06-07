### Deploying dropwizard java application with Docker and Kubernetes

to list : `docker ps -a`
to remove: `docker rm $(docker ps -a -f status=exited -q)`

```
kubectl delete service dw-hw
kubectl delete replicationcontroller dw-hw
```
