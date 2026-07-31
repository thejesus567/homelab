## Docs

https://docs.nginx.com/nginx-gateway-fabric/install/secure-certificates/#install-cert-manager


## Command

helm install cert-manager oci://quay.io/jetstack/charts/cert-manager:v1.21.1\
  --namespace cert-manager \
  --create-namespace \
  -f values.yaml
