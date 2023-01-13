# k8s-local-registry

local registry

## install

```bash
helm upgrade --install registry registry \
  --repo https://github.com/yinheli/k8s-local-registry/charts \
  --namespace default
```
