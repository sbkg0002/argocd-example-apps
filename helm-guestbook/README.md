# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 8e231e87ccb105b58a93cb692b2b629d4ae4092c
helm template . --name-template production-helm-guestbook --include-crds
```
