# playground

kind-cluster
https://kind.sigs.k8s.io/docs/user/ingress/
kind create cluster --config=kind.yaml
This will create a single node cluster with default name "kind" with latest Kubernetes Version.
To provide a suitable name for your cluster, you can pass --name="YOUR_CLUSTER_NAME"

kind create cluster --name=kindv1.19 --config=kind-v1.19.7.yaml
This will create a single node cluster with name "kindv1.19" which installs Kubernetes version 1.19.7 on your system.

NOTE: Similarly, You can control which version of Kubernetes you want to play around with

KIND Documenation - https://kind.sigs.k8s.io/docs/user/quick-start/
