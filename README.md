# django-cicd-kubernetes
django project pipeline cicd github actions to deploy on kubernetes cluster
# cicd
La aplicación de prueba escrita en Python/django es dockerizada, pusheada al registry de Docker y deployada en un cluster de Kubernetes mediante pipeline en Github Actions.

Mi Docker Hub: https://hub.docker.com/repository/docker/nicosistemas/probando-django/general

Por el momento no es accedible a una url https poqrue no tengo Ingress ni dominio propio, lo que hago es emularlo con ngrok para ser consumida,
ej:https://c116-2803-9800-98c4-8511-3c4-7187-7855-f2ea.ngrok.io/hola/


To Do on cluster la primera vez:

kubectl apply -f deployment.yaml -n test-nico
