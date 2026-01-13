# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 37c966f375f32a2c9824e263813971bbeeb80777
helm template . --name-template development-helm-guestbook --include-crds
```
