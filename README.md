
# docker commands

### build an image
    docker build --build-arg GITHUB_PAT=<GITHUB_PAT> --tag alert-api-service .

### run a container
    docker run -d -p 8000:5006 alert-api-service

### see running containers
    docker ps -a

### kill all containers
    docker rm $(docker ps -a -q)

### delete all images
    docker image prune -a -f

## https://grpc.io/docs/languages/go/basics/#setup


## https://github.com/ZscalerCWP/cwp-tenant-mgmt-rest/blob/main/docker-compose.yaml

# Kubernetes commands
    kubectl config get-clusters
