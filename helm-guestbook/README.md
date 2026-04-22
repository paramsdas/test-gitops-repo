# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 8103c97bf9fc06481ceaaed5a3dab87106d289e1
helm template . --name-template test-app --namespace aayojak --include-crds
```
