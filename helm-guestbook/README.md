# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 9519eab69f36f877c9dc9ca41d047dbe8c7a068b
helm template . --name-template test-app --namespace aayojak --include-crds
```
