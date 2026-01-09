# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sbkg0002/argocd-example-apps.git
# cd into the cloned directory
git checkout 8938d430ba2171a7e2989318e4b06b463a7584fd
helm template . --name-template development-helm-guestbook --include-crds
```
