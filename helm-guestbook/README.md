# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 7bf01d282f83064b9f426cc1f2dd3bc3f9e31d13
helm template . --name-template test-app --namespace default --include-crds
```
