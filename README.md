# nginx-kubie-conf

NGINX image with custom config that serves as a reverse proxy for my k8s node.
<br /> To add volumes

<br />kubectl apply -f nginx-configmap.yaml && kubectl apply -f nginx-deployment.yaml && kubectl apply -f nginx-service.yaml