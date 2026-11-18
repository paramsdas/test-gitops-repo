# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout e82e36861014c547417d0672132beb623cf70101
helm template . --name-template test-app --namespace default --include-crds
```
