# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout 9bbbcd91765fabb6a9c9a5f5dfbe6d9a0a12c02c
helm template . --name-template test-app --namespace aayojak --include-crds
```
