# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 0d0f4ce0183d04dd098e27696295940bc5d75dd1
helm template . --name-template test-app --namespace default --include-crds
```
