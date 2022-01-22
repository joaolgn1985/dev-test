# Helm 

## Helm v2

Repositories > Helm CLI > Tiller (K8S)

## Helm v3

Repositories > Helm CLI > Kube-API (K8S)

## Commands Helm

- helm repo add
- helm search repo
- helm install
- helm upgrade
- helm rollback
- helm create
- helm status
- helm list

## Example:

- `helm upgrade ingress-nginx -n ingress-nginx ingress-nginx/ingress-nginx --values ./values.yaml`
- `helm history nginx-ingress`
- `helm rollback nginx-ingress`

## Structure

```
|
├── demochart
|   ├── templates
|   |    ├── _helpers.tpl
|   |    ├── deployment.yaml
|   |    ├── ingress.yaml
|   |    ├── NOTES.txt
|   |    ├── service.yaml
|   |    ├── serviceaccount.yaml
|   |    ├── .helmignore
|   |
|   ├── Chart.yaml
|   ├── values.yaml
|
```
