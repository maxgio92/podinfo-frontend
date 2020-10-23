# Deploy demo webapp 

Deploy the demo in the `dev` namespace:

```bash
kustomize build ./overlays/dev | kubectl apply -f-
```

Deploy the demo in the `staging` namespace:

```bash
kustomize build ./overlays/staging | kubectl apply -f-
```

Deploy the demo in the `production` namespace:

```bash
kustomize build ./overlays/production | kubectl apply -f-
```
