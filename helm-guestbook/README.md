# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 66c9306ec6db70d061b7f45c5e0510b0603f12d2
helm template . --name-template test-app --namespace test --include-crds
```
