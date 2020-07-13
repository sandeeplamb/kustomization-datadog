# kustomization-datadog

Example how to convert Helm Chart to Kustomization

## Commands to create Manifests

```sh
[⎈ k8s ] cd k8s/overlays/dev/
[⎈ k8s ] kustomize build .
[⎈ k8s ] kustomize build . | kubectl apply -f -
```


```sh
[⎈ k8s ] cd k8s/overlays/prod/
[⎈ k8s ] kustomize build .
[⎈ k8s ] kustomize build . | kubectl apply -f -
```
