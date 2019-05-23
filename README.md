# kubernetes-lemp

Deploy nginx with php-fpm in kubernetes version 1.14

kubectl apply -f pvc.yaml

kubectl apply -f pv-nginx.yaml

kubectl apply -f php-service.yaml

kubectl apply -f nginx-configmap.yaml

kubectl apply -f php-fpm-deploy.yaml

kubectl apply -f php-service.yaml
