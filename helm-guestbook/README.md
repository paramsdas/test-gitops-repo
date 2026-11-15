# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 36a9021f9195ff05de9ccf7b20c7d2de0d9a1a4c
helm template . --name-template test-app --namespace default --include-crds
```
