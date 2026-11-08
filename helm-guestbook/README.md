# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 08a8d9eea759992c1c3b11ae53514b2a9e14b424
helm template . --name-template test-app --namespace test --include-crds
```
