# Container Networking Interface (CNI)

This repository provides the Container Networking Interface (CNI) for PSP.

## Usage

For development, run `skaffold dev`.

It is useful for debugging to look at the traffic through the CNI.
This is done through Hubble:
```
kubectl port-forward -n kube-system svc/hubble-ui 12000:80
```
You can then access Hubble through `localhost:12000`.

