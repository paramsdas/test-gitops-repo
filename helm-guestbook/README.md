# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 11b13995bf0b6e5d8daeb84b66a63b38dd6c7d6d
helm template . --name-template test-app --namespace aayojak --include-crds
```
