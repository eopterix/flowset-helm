# flowset-help

Helm Charts for Flowset

## How to install
### Add the Helm Chart Repository
To add the Helm chart repository for Flowset, run:

```shell
helm repo add flowset https://dlr-terrabyte.github.io/flowset-helm/
```

### Verify the Repository
To confirm that the repository has been added successfully, list all available repositories:

```shell
helm repo list
```

### Update Helm Repositories
Fetch the latest available chart versions by updating your Helm repositories:

```shell
helm repo update
```

### List Available Flowset Versions

To check the available versions of the Flowset chart, use the following command:

```shell
helm search repo flowset --devel
```
