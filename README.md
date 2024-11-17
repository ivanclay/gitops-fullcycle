# Git Ops Full Cycle

![Badge de Licença](https://img.shields.io/badge/git-0.0.0-lightgrey.svg?style=flat-square&logo=git)
![Badge de Licença](https://img.shields.io/badge/golang-1.19.0-blue.svg?style=flat-square&logo=go)
![Badge de Licença](https://img.shields.io/badge/docker-27.2.0-orange.svg?style=flat-square&logo=docker)
![Badge de Licença](https://img.shields.io/badge/kind-0.23.0-orange.svg?style=flat-square&logo=kind)
![Badge de Licença](https://img.shields.io/badge/kustomize-5.4.3-yellow.svg?style=flat-square&logo=kustomize)
![Badge de Licença](https://img.shields.io/badge/argocd-0.0.0-yellow.svg?style=flat-square&logo=argo)

![Badge de Versão](https://img.shields.io/badge/app-v_1.0.0-green.svg?style=flat-square&logo=app)
![Badge de Status do Projeto](https://img.shields.io/badge/status-training-blue.svg?style=flat-square)

It is a GitOps course taught on the Full Cycle platform

## Build a Docker image

```sh
docker build -t <YOUR_DOCKER_USERNAME>/gitopsfc:latest .
```

## Execute app in Docker

```sh
docker run --rm -p 8080:8080 <YOUR_DOCKER_USERNAME>/gitopsfc:latest 
```

## Create a local cluster (using `KIND`)

```sh
    kind create cluster --name=gitopsfc
```

## Apply context

```sh
kubectl cluster-info --context kind-gitopsfc
```
