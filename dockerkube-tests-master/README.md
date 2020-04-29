# dockerkube-tests
Sample project for K8 and Docker samples


# Commands used
 docker build --rm --tag local:my-nginx-1.2 .
 docker run -d -p 8080:80 local:my-nginx-1.2
 curl http://localhost:8080; echo ""
 
 docker exec -it 50e662cf8921 /bin/bash


# K8 Pre-reqs
- Git hub projects
- install VirtualBox https://www.virtualbox.org/wiki/Downloads
- Install docker
- Install mini cube https://kubernetes.io/docs/tasks/tools/install-minikube/
- https://github.com/DanWahlin/DockerAndKubernetesCourseCode

minikube start --driver=virtualbox
