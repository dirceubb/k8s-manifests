# k8s-manifests
Kubernetes manifests to be called invoked by kubectl or argocd to install applications

Pull manifest without cloning and applying argocd app
```
curl -L https://raw.githubusercontent.com/dirceubb/k8s-manifests/main/argocd-apps/istio/istio-app.yaml | k apply -f -
```