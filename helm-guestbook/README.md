# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout a4e71663c0f03e81e94c66feca693a7968876563
helm template . --name-template test-app --namespace test --include-crds
```
