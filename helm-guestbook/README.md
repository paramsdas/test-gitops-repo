# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 58a61e13b106608393d673575e89b951bb5fa664
helm template . --name-template test-app --namespace default --include-crds
```
