# helm-chart
helm的chart仓库，地址为：lincaffee.github.io/helm-chart

本Chart仓库的使用方法：

## 添加chart仓库
helm repo add myrepo https://lincaffee.github.io/helm-chart

helm repo update

## 添加成功后查看仓库
helm repo list

NAME         	URL

myrepo       	https://lincaffee.github.io/helm-chart

## 搜索chart包
helm search repo myrepo

NAME       	CHART VERSION	APP VERSION	DESCRIPTION

myrepo/test	0.1.0        	1.16.0     	A Helm chart for Kubernetes 

## 安装chart包
helm install xxx myrepo/test

xxx为relaese名字
