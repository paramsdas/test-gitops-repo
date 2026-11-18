# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 306e2fe29af8bd192d67619afe6c657658a40ce6
helm template . --name-template test-app --namespace default --include-crds
```
