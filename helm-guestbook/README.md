# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout ffbeeaffac19fa47919bd759b604728c9cf36b81
helm template . --name-template test-app --namespace aayojak --include-crds
```
