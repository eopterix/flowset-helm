# EOEPCA Deployment Playground

Implementing [[https://github.com/flowset/flowset-control-community/blob/main/docker-compose/docker-compose-core.yaml|docker-compose]] setup as a helm chart on EOEPCA workspace.

## Usage

    helm install flowset-control .

...and follow instructions :P

## Issues

The (connection to the) vCluster on EOEPCA Workspace seems kind of unstable?
Current workaround is to loop this until it's up:

    helm install flowset-control .
    helm uninstall flowset-control

