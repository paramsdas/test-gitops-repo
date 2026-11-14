# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 43a9121788646d3fdc0bb1fa36392857055e4426
helm template . --name-template test-app --namespace default --include-crds
```
