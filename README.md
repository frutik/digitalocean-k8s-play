Attempt to provision ELK into DigitalOcean k8s

```
kubectl --kubeconfig="k8s-1-16-2-do-1-ams3-kubeconfig.yaml" apply -f manifests/pods.yml
kubectl --kubeconfig="k8s-1-16-2-do-1-ams3-kubeconfig.yaml" apply -f manifests/services.yml
```