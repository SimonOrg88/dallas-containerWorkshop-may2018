kubectl create -f frontend-deployment.yaml
kubectl get deploy
kubectl create -f frontend-service.yaml
kubectl get service
kubectl describe deploy frontend
kubectl create -f redis-master-deployment.yaml
kubectl describe deploy redis-master
kubectl create -f redis-master-service.yaml
kubectl create -f redis-slave-deployment.yaml
kubectl create -f redis-slave-service.yaml
kubectl get service
http://192.168.99.100:32715/
