# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 89581936add788411d75f3206bf34fa8caa9c7a6
helm template . --name-template test-app --namespace default --include-crds
```
