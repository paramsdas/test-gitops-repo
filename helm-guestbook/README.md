# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 38c9c12173760b86c16295bbafc69c56a91fcfbe
helm template . --name-template test-app --namespace test --include-crds
```
