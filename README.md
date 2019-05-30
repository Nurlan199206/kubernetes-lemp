kubernetes-lemp


Deploy nginx with php-fpm in kubernetes version 1.14

1) create folder called "nginx" in /mnt

2) use commands for deploy environment

kubectl apply -f pvc.yaml

kubectl apply -f pv-nginx.yaml

kubectl apply -f php-service.yaml

kubectl apply -f nginx-configmap.yaml

kubectl apply -f php-fpm-deploy.yaml

kubectl apply -f php-service.yaml

http://localhost:32444 - nginx web page
http://localhost:32443 - phpmyadmin web page
