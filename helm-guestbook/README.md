# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 42c32258fba93f81ccb505be8692da9f3c83349e
helm template . --name-template test-app --namespace aayojak --include-crds
```
