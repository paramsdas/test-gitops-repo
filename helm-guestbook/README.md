# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 67c6ef5678f96f6029f48cbb4619018d9815b89d
helm template . --name-template test-app --namespace default --include-crds
```
