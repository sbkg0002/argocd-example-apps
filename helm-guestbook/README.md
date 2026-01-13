# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 6a1114cd81120569195189659bec4b0f81d90b0a
helm template . --name-template development-helm-guestbook --include-crds
```
