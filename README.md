# helm
Helm installation in centos 7 : Helm installation
https://get.helm.sh/helm-v3.7.1-linux-amd64.tar.gz
tar -xvzf helm-v3.7.1-linux-amd64.tar.gz
cd linux-amd64/
mv helm /usr/local/bin/


helm create application-1
helm install chart-1
helm list
helm uninstall chart-1
