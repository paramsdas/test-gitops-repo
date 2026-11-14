# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 2e8f1685b66d102d4c991f45a54321a480789704
helm template . --name-template test-app --namespace default --include-crds
```
