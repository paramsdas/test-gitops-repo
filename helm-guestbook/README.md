# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 5f407a243a43f06bb116d5698d26786dabd402b6
helm template . --name-template test-app --namespace aayojak --include-crds
```
