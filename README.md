# Kubernetes Course

Base on the following:

- https://youtu.be/2T86xAtR6Fo?si=JcXDaUSpAU6KWgKd
- https://github.com/sidpalas/devops-directive-kubernetes-course

Progress:

- 8/24/26 - Started Section 4 Namespaces
- 8/24/25 - Finished Section 3

## GCP

Error Seen on cluster created on 8/25/24:

```
Default change: VPC-native is the default mode during cluster creation for versions greater than 1.21.0-gke.1500. To create advanced routes based clusters, please pass the `--no-enable-ip-alias` flag
Note: The Kubelet readonly port (10255) is now deprecated. Please update your workloads to use the recommended alternatives. See https://cloud.google.com/kubernetes-engine/docs/how-to/disable-kubelet-readonly-port for ways to check usage and for migration instructions.
Note: Your Pod address range (`--cluster-ipv4-cidr`) can accommodate at most 1008 node(s).
```
