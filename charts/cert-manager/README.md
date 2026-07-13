## Docs

https://docs.nginx.com/nginx-gateway-fabric/install/secure-certificates/#install-cert-manager


## Command

helm install cert-manager jetstack/cert-manager \
  --namespace cert-manager \
  --create-namespace \
  -f values.yaml
