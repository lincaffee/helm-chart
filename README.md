# helm-chart

## helm的chart仓库，地址为：lincaffee.github.io/helm-chart

### 本Chart仓库的使用方法：  
1、添加chart仓库   
\# helm repo add lc https://lincaffee.github.io/helm-chart   
\# helm repo update  
2、添加成功  
\# helm repo list  
NAME  	URL                                   
lc	https://lincaffee.github.io/helm-chart  
\# helm search repo lc  
NAME   	CHART VERSION	APP VERSION	DESCRIPTION   
lc/aaa 	0.1.0        	1.16.0     	A Helm chart for Kubernetes  
lc/test	0.1.0        	1.16.0     	A Helm chart for Kubernetes  
4、安装chart包  
\# helm install xxx lc/test   
xxx为relaese名字   
