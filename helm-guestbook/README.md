# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout f0cd6191cc9ea53a6c1def83643c9025f8c7f523
helm template . --name-template test-app --namespace aayojak --include-crds
```
