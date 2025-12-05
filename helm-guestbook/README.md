# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mrkswn/argocd-example-apps.git
# cd into the cloned directory
git checkout 6d15353331b306e78218188a75b6982f9132b500
helm template . --name-template hydrator-guestbook --include-crds
```
