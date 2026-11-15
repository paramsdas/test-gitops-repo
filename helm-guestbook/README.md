# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 2ecb591e4e47cb83e287c02151d3b04d992d936c
helm template . --name-template test-app --namespace default --include-crds
```
