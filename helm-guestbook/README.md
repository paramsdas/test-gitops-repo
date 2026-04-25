# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 20fa1307303c8c163b900b2484215dc7831ecf39
helm template . --name-template test-app --namespace aayojak --include-crds
```
