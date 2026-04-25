# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 21827f4f0bffa57481bc0993f956c28be01208bf
helm template . --name-template test-app --namespace aayojak --include-crds
```
