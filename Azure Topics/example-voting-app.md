## Architecture

![alt text](image-12.png)



![alt text](image-13.png)



# Deploying a Three Tier application E-Commerce ( 8 Services, 2 Data bases) on AKS.

![alt text](image-16.png)

![alt text](image-17.png)

![alt text](image-18.png)

![alt text](image-19.png)



## commands

- kubectl config get-contexts

- for switching  to aks nd minikue

the kubectl config use-context three-tier


- kubectl create ns robot-shop

- helm install robot-shop --namespace robot-shop .

- kubectl get storageclass

-  kubectl get pods -n robot-shop

- kubectl describe pod redis-0 -n robot-shop

- kubectl get svc


## when to use PVS and azure storage 


- if storage acccessed  single pod use EBS or Azure disk 

- if your volume accessed y multiple containers accross diff. multiple nodes use EFS  or Azure files. 


![alt text](image-20.png)