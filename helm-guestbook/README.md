# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout ea4b120eacc0ab15c39cbe295f0eb334e68ce046
helm template . --name-template production-helm-guestbook --include-crds
```
