## Helm

Chart, Repository and Release

```
brew install kubernetes-helm
helm init --history-max 200
helm create currency-exchange
git clone https://github.com/awstutorials/docker-crash-course.git
kubectl delete all -l app=currency-exchange
cd /Ranga/001.Notes/00.CoursePreparations/2019-11-KubernetesWithGCP/kubernetes-crash-course/04-currency-exchange-microservice 
helm install ./helm/generic-microservice --debug --dry-run
helm install --name=currency-exchange-helm ./helm/generic-microservice
helm upgrade currency-exchange-helm ./generic-microservice 
helm history currency-exchange-helm
helm rollback currency-exchange-helm 1
helm history
helm install ./currency-services/ --debug --dry-run

kubectl delete all -l app=currency-exchange
kubectl delete clusterrolebinding fabric8-rbac
kubectl delete ingress gateway-ingress-1

helm install ./currency-services/ --name=currency-services

helm repo list
helm search
helm search mysql
helm inspect stable/mysql
helm inspect values stable/mysql


```