# MongoDB and MongoExpress with kubernetes

This project aims to expose internal service of mongoDB to external clients like mongo-express using kubernets. we are using secrets to store mongo User names and passwords along and configMap to store the configrations of the internal service as they can used by multiple services in future.

![image](https://user-images.githubusercontent.com/60577767/219970679-2f07d337-e48b-413b-92cc-3ba4f86a4139.png)


This small project is just for reference and is not ment to be used in prod.

### Commmanly used commands:

-   `minikube start --vm=qemu`
-   `kubectl get all`
-   `kubectl apply -f <file-name>`
-   `kubectl get pod`

Ref:

-   [Youtube by Nana](https://www.youtube.com/watch?v=X48VuDVv0do)
-   https://hub.docker.com/_/mongo
