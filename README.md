# nginx-kubie-conf

NGINX image with custom config that serves as a reverse proxy for my k8s pod.
<br /> To add volumes

<br />kubectl apply -f nginx-config.yaml && kubectl apply -f nginx-deployment.yaml && kubectl apply -f nginx-service.yaml