# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 185cdf3a9a746dbdeb5def8956063c73b9a73311
helm template . --name-template test-app --namespace default --include-crds
```
