```
## Goal
Instead of running multiple commands to deploy, use one single file for deploying.

```

---

## 🔧 How to Deploy

Make sure you have a **Kubernetes cluster** running (Minikube, Kind, or a cloud provider).

1. Apply the manifest:
```

kubectl apply -f deployment-service.yaml

```

2. Check Deployment:
```

kubectl get deployments

```

3. Check Pods:
```

kubectl get pods

```

4. Check Service:
```

kubectl get svc backend

```

- On **Minikube**:
  ```
  minikube service backend
  ```
- On **Cloud Providers**: An **External IP** will be provisioned and visible under the `EXTERNAL-IP` column.

---
