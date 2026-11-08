# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/paramsdas/test-gitops-repo
# cd into the cloned directory
git checkout f405b7decc9d335213944d71406bd67e9b5a268c
helm template . --name-template test-app --namespace test --include-crds
```
