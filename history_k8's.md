links:
deployment file in kubernetes
deployment: https://kubernetes.io/docs/concepts/workloads/controllers/deployment/

manifest file for pod in kubernetes:
https://kubernetes.io/docs/concepts/workloads/pods/

k8's api version:
https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.24/

eksctl create cluster --name project-cluster --region ap-south-1 --node-type t2.small --nodes-min 2 --nodes-max 2
cat /root/.kube/config
kubectl get nodes
kubectl get all
kubectl run webapp --image=httpd
kubectl get po
kubectl get pods
kubectl create deploymnent demo-nginx --image=nginx --replicas=2 --port=80
kubectl create deployment demo-nginx --image=nginx --replicas=2 --port=80
kubectl get all
kubectl expose deployment demo-nginx --port =80
kubectl expose deployment demo-nginx --port =80 --type=LoadBalancer
kubectl expose deployment demo-nginx --port=80 --type=LoadBalancer
kubectl get all
kubectl get pod
kubectl run tomcat --image=tomcat
kubectl get all
kubectl expose deployment demo-tomcat --port=80 --type=LoadBalancer
kubectl create deployment demo-tomcat --image=tomcat:latest --replicas=2 --port=80
kubectl expose deployment demo-tomcat --port=80 --type=LoadBalancer
kubectl get deployment
kubectl get all
kubectl describe svc demo-tomcat
kubectl expose deployment demo-tomcat --type=LoadBalancer --port=80 --target-port=8080 --name=demo-tomcat
kubectl get all
kubectl delete service demo-tomcat
kubectl get all
kubectl delete deployment demo-tomcat
kubectl get all
kubectl create deployment demo-tomcat --image=tomcat:latest --replicas=2 --port=8080
kubectl get all
kubectl describe svc demo-catt
kubectl describe svc demo-cat
kubectl describe svc demo-tomcat
kubectl expose deployment demo-tomcat --port=8080 --type=LoadBalancer
kubectl get all
curl http://a68e9dfc2770541bc9c1d8f09b94c928-2124035451.ap-south-1.elb.amazonaws.com
kubectl pod
kubectl get pod
kubectl exec -it demo-tomcat-55bd77568c-7fwjj -- /bin/bash
./startup.sh
ll
kubectl exec -it demo-tomcat-55bd77568c-7fwjj -- /bin/bash
kubectl delete pod demo-tomcat-55bd77568c-7fwjj
kubectl get all
kubectl get pod
kubectl exec -it demo-tomcat-55bd77568c-69k6b -- /bin/bash
tomup
kubectl get all
kubectl exec -it demo-tomcat-55bd77568c-69k6b -- /bin/bash
kubectl get all
kubectl exec -it demo-tomcat-55bd77568c-69k6b -- ls /usr/tomcat/webapps
kubectl exec -it demo-tomcat-55bd77568c-69k6b -- ls /usr/local/tomcat/webapps
kubectl delete service demo-nginx
kubectl get all
kubectl delete service /demo-nginx
eksctl delete sluster aws --region ap-south-1
eksctl delete cluster aws --region ap-south-1
eksctl delete cluster project-cluster --region ap-south-1
ll
kubectl get all
kubectl get po
kubectl get all po
kubectl get all pods
kubectl all pods
kubectl get pods
pod.yml
vi pod.yml
cat pod.yml
vi service.yml
cat
cat service.yml
vi pod.yml
kubectl apply -f pod.yml
vi pod.yml
kubectl apply -f pod.yml
vi pod.yml
kubectl get all
clear
cat service.yml
vi service.yml
kubectl apply -f service.yml
kubectl get all
vi pod.yml
vi service.yml
cat pod.yml
cat service.yml
kubectl apply -f pod.yml
kubectl get all
kubectl apply -f service.yml
kubectl get all
kubectl describe service/demo-service
kubectl get pod -o wide
kubectl get pods
kubectl delete pod demo-pod
kubectl get pods
kubectl get all
kubectl delete service/demo-service
kubectl get all
vi deployment.yml
vi service-deploy.yml
ll
kubectl apply -f deployment.yml
kubectl get all
kubectl get pod -o wide
kubectl apply -f service-deploy.yml
kubectl get all
kubectl describe service/demo-service
cat deployment.yml
kubectl get pod
kubectl delete pod demo-deployment-64dd9dcdbb-d6gtj
kubectl get pod

Finally delete the cluster
kubectl get all
history
