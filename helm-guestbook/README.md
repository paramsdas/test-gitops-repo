# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 5d2cb51db15a675f95dbb917d7b103d1ad3dad93
helm template . --name-template test-app --namespace default --include-crds
```
