# SecureK8s
Projet personnel Kubernetes avec un angle DevSecOps.
## Phase 1 : Bases
- Cluster kind (1 control plane, 2 workers)
- Deployment nginx, Service, scaling

## Phase 2 : Automatisation
- Manifests YAML dans `k8s/` (Namespace, Deployment, Service)
- Chart Helm dans `webapp/` (image nginx 1.27 par defaut)
- Commandes testees : helm install, upgrade, history, rollback
