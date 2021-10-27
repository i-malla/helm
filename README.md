# HELM

#### Helm installation in centos 7 :  
wget https://get.helm.sh/helm-v3.7.1-linux-amd64.tar.gz  
tar -xvzf helm-v3.7.1-linux-amd64.tar.gz  
cd linux-amd64/  
mv helm /usr/local/bin/    

#### Commands
helm create application-1  
helm install chart-1 . 
helm list  
helm uninstall chart-1   
helm install chart-2 . -f newvalues.yaml  <!-- to use custom values file -->  
helm uninstall chart-2

#### Troubleshooting:  
Stay in folder where the charts are available --> /root/charts/helm/application-1  
helm lint  
helm template .  
helm template . | kubectl apply -f -  


