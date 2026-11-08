# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 24b47a4d05cc21d22b5efbf48db083bb46b64018
helm template . --name-template test-app --namespace test --include-crds
```
