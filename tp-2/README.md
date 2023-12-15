# kubernetes-training
# TP-2

Deploiement d'objet de type pod et deployment de 2 facons : déclarative et impérative

Les commandes pour la voie impérative sont :

kubectl run webapp-color --image=mmumshad/simple-webapp-color --port=8080

kubectl run --image=mmumshad/simple-webapp-color \

 --env="APP_COLOR=red" \

 --restart=Never \

 simple-webapp-color


kubectl create deployment nginx-deploy --image=nginx:1.18 --replicas=2

