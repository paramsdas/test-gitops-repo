# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 878176325085afb46cf46dbef8bdc54fcc2e6829
helm template . --name-template test-app --namespace test --include-crds
```
