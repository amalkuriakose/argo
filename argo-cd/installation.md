` helm -n argo install argocd argo/argo-cd -f values.yaml`

`kubectl port-forward service/argocd-server -n argo 8080:443`

`kubectl -n argo get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d`
