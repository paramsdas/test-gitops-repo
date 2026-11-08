# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 0ac26d9c84abdf57ee22c6cb1a8b39b692b02b7e
helm template . --name-template test-app --namespace test --include-crds
```
