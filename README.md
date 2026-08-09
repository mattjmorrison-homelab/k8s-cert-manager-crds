# homelab-cert-manager-crds

CustomResourceDefinitions for [cert-manager](https://cert-manager.io) (v1.21.1), managed via ArgoCD.

Kept as a separate repo/Application from `homelab-cert-manager` and applied with `ServerSideApply=true` — cert-manager's CRDs are large enough to exceed the `kubectl.kubernetes.io/last-applied-configuration` annotation size limit under a normal client-side apply. Same pattern as `homelab-external-secrets-crds`.

---

[Homelab Docs](https://github.com/mattjmorrison/homelab/blob/main/docs/INDEX.md)
