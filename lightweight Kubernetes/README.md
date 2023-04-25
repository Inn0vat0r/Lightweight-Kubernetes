Minikube <>	K3s <>	MicroK8s	<> K0s	<> K3d
Kubernetes project <> Rancher	<> Canonical<> Mirantis	<> Rancher
********************************************
Minikube is a local Kubernetes cluster that focuses on making Kubernetes development and learning simple.
K3s is a single binary that fully implements the Kubernetes API and is less than 40MB in size. It's possible to run a cluster on machines with as little as 512MB of RAM because of its minimal resource needs. As a result, pods can now run on the master as well as nodes.
MicroK8s is the smallest, fastest, and most conformant Kubernetes that tracks upstream releases and simplifies clustering. 
MicroK8s is ideal for prototyping, testing, and offline development. Use it as a small, affordable, and dependable CI/CD k8s on a virtual machine. 
It's also the finest Kubernetes for appliances for production. Create IoT apps for k8s and deploy them to MicroK8s running on your Linux systems.	
Like k3s, k0s also comes as a single binary which achieves a very quick setup times. k0s binary is massive (170MB) compared to k3s (50MB). 
k0s drastically reduces the complexity of installing and running a fully conformant Kubernetes distribution. New kube clusters can be bootstrapped in minutes.
Developer friction is reduced to zero, allowing anyone, with no special skills or expertise in Kubernetes to easily get started.
K3d is a docker wrapper for running k3s (Rancher Lab's basic Kubernetes distribution).
k3d makes it simple to establish single- and multi-node k3s clusters in docker
*********************************************

K0s in the Kubernetes distro market directly competes with k3s from Rancher and microk8s from Canonical. K3s, a CNCF certified project, already has tremendous support from the community and is already a part of various embedded computing organizations from different domains. Microk8s from Canonical has recently added some features to make it more production-ready but compared to k3s; it is not a mature distribution for deployments on a large scale.
K0s has many stand-out features like k3s. For Instance, Kine allows integration of external databases such as MySQL and PostgreSQL, The single binary installation and architecture support is also very similar to k3s. The k0s community is also looking forward to adding support for Microsoft Windows Server 2019-based worker nodes on Linux’s control plane, which allows the running of hybrid workloads.
Mirantis with k0s has blended Pharos and Docker’s best ideas to create a very modern 100% upstream Kubernetes distribution. Mirantis has also acquired Docker Enterprise and Lens project to complete its cloud-native portfolio and compete aggressively in the market.
kops - Kubernetes Operations (kOps) - Production Grade k8s Installation, Upgrades and Management 
okd - The self-managing, auto-upgrading, Kubernetes distribution for everyone 
kind - Kubernetes IN Docker - local clusters for testing Kubernetes 
keepalived - Keepalived 
