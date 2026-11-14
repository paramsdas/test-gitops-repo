# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 88b9cdad746f88ea2329505b6c5ca77d3ed20c32
helm template . --name-template test-app --namespace default --include-crds
```
