# Kustomize

https://kubectl.docs.kubernetes.io/guides/example

https://github.com/kubernetes-sigs/kustomize/blob/master/examples/README.md

```sh
# DRY-RUn
kustomize build <path_to_kustomization>
kubectl apply --dry-run=client -k ./overlays/dev -o yaml
```