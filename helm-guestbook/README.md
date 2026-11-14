# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 8fa8ef1c85782f8be230d777257f44888c9cb16e
helm template . --name-template test-app --namespace default --include-crds
```
