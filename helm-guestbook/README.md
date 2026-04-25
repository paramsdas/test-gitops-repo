# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout fa9a5ef58fba507ab693b946cfe95751608c3e92
helm template . --name-template test-app --namespace aayojak --include-crds
```
