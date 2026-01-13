# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 3e0be3e5a7323e985de05826c68bab7695bcfc61
helm template . --name-template production-helm-guestbook --include-crds
```
