# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 3c6df9e984484e053e1da3673605d79aee5346b2
helm template . --name-template test-app --namespace aayojak --include-crds
```
