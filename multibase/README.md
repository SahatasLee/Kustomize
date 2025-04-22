# Kustomize

https://kubectl.docs.kubernetes.io/guides/example/multi_base/#kustomize--root-dir

```sh
# DRY-RUn
kustomize build <path_to_kustomization>
kubectl apply --dry-run=client -k ./overlays/dev -o yaml
```