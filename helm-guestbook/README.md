# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 948f0fb0bc38dc9716b830230c666b248ecd68af
helm template . --name-template test-app --namespace aayojak --include-crds
```
