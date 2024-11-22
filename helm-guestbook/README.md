
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/ashutosh16/argocd-example-apps.git
# cd into the cloned directory
git checkout de228e3f2d9a970ff003141dd2ecc226c6c85c46
helm template . --name-template production-usw1 --include-crds
```