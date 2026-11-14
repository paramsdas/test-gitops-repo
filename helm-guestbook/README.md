# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 8b37d222b1c03c968c167212f771ff99d81a2274
helm template . --name-template test-app --namespace default --include-crds
```
