# Lens Contest

The Simple NGINX application for the Lens Contest is a fairly simple, static website running on NGINX to demonstrating NGINX in a Docker container.

## Running the Pre-Built Container

```
$ docker run -it -p 8080:80 docker.io/mirantis/lens-contest
```

## Deploying to Kubernetes

Using your Kubernetes distribution of choice, deploy the Lens demo application

```
$ kubectl apply -f lens.contest.yaml
```
