# k8s-rac-demo
create and test role-base-access-control on kubernetes

helm install webapp app-rbac-test/ --namespace=demo --set rbac.enabled=true