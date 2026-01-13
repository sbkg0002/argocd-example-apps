# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 2a9180621f1089a35df0ba5da606ba5f975d7af8
helm template . --name-template development-helm-guestbook --include-crds
```
