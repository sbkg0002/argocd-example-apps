# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 4a49c4590a096164cca3a89416c88f94340b297c
helm template . --name-template development-helm-guestbook --include-crds
```
