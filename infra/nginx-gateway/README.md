## Commands: 

- kubectl create namespace nginx-gateway
- kubectl apply -f .
- helm install ngf oci://ghcr.io/nginx/charts/nginx-gateway-fabric --create-namespace -n nginx-gatewayi -f ./helm/values.yaml

