# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 997d81483a48f1dfc0c3e2765054b507923babd6
helm template . --name-template test-app --namespace aayojak --include-crds
```
