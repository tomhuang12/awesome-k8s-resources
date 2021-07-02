# Awesome Kubernetes Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Kubernetes tools and resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome) list and [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws).

## The Fiery Meter of Awesomeness

* Repo with 0050+ Stars: :fire:
* Repo with 0200+ Stars: :fire::fire:
* Repo with 0500+ Stars: :fire::fire::fire:
* Repo with 1000+ Stars: :fire::fire::fire::fire:
* Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Idea taken from [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws). 


## Contents
- [Tools and Libraries](#tools-and-libraries)
  - [Command Line Tools](#command-line-tools)
  - [Cluster Provisioning](#cluster-provisioning)
  - [Automation and CI/CD](#automation-and-cicd)
  - [Cluster Resources Management](#cluster-resources-management)
  - [Secrets Management](#secrets-management)
  - [Networking](#networking)
  - [Storage](#storage)
  - [Testing and Troubleshooting](#testing-and-troubleshooting)
  - [Monitoring, Alerts, and Visualization](#monitoring-alerts-and-visualization)
  - [Backup and Restore](#backup-and-restore)
  - [Security and Compliance](#security-and-compliance)
  - [Service Mesh](#service-mesh)
  - [Development Tools](#development-tools)
  - [Data Processing and Machine Learning](#data-processing-and-machine-learning)
  - [Miscellaneous](#miscellaneous)
- [Guides, Documentations, Blogs, and Learnings](#guides-documentations-blogs-and-learnings)
  - [Guides](#guides)
  - [Blogs and Videos](#blogs-and-videos)
  - [Learnings and Documentations](#learnings-and-documentations)
  - [Certification Guides](#certification-guides)
- [Contribute](#contribute)
- [License](#license)


## Tools and Libraries
Items with :green_heart: indicate open source projects. 

### Command Line Tools
- :green_heart:[Helm](https://github.com/helm/helm) :fire::fire::fire::fire::fire: - Helm is a tool for managing Charts. Charts are packages of pre-configured Kubernetes resources.
- :green_heart:[K9s](https://github.com/derailed/k9s) :fire::fire::fire::fire::fire: - K9s provides a terminal UI to interact with your Kubernetes clusters.
- :green_heart:[Ktunnel](https://github.com/omrikiei/ktunnel) :fire: - Ktunnel is a CLI tool that establishes a reverse tunnel between a kubernetes cluster and your local machine.
- :green_heart:[Kubebox](https://github.com/astefanutti/kubebox) :fire::fire::fire::fire: - Terminal and Web console for Kubernetes
- :green_heart:[Kubetail](https://github.com/johanhaleby/kubetail) :fire::fire::fire::fire: - Bash script that enables you to aggregate (tail/follow) logs from multiple pods into one stream.
- :green_heart:[kube-shell](https://github.com/cloudnativelabs/kube-shell) :fire::fire::fire::fire: - Kube-shell: An integrated shell for working with the Kubernetes CLI.
- :green_heart:[kubectl tree](https://github.com/ahmetb/kubectl-tree) :fire::fire::fire::fire: - A kubectl plugin to explore ownership relationships between Kubernetes objects through owners.
- :green_heart:[kubectl-aliases](https://github.com/ahmetb/kubectl-aliases) :fire::fire::fire::fire: - This repository contains a script to generate hundreds of convenient shell aliases for kubectl.
- :green_heart:[kubectx + kubens](https://github.com/ahmetb/kubectx) :fire::fire::fire::fire::fire: - `kubectx` helps you switch between clusters back and forth, and `kubens` helps you switch between Kubernetes namespaces smoothly.
- :green_heart:[kubediff](https://github.com/weaveworks/kubediff) :fire::fire::fire: - Kubediff is a tool for Kubernetes to show you the differences between your running configuration and your version controlled configuration.
- :green_heart:[kubeprompt](https://github.com/jlesquembre/kubeprompt) - Isolates KUBECONFIG in each shell and shows the current Kubernetes context/namespace in your prompt
- :green_heart:[Kubevela](https://github.com/oam-dev/kubevela) :fire::fire::fire::fire: - KubeVela is an easy-to-use yet extensible platform that enables them to design and ship applications with minimal effort.
- :green_heart:[nova](https://github.com/FairwindsOps/nova/) - Nova scans your cluster for installed Helm charts, then cross-checks them against all known Helm repositories.
- :green_heart:[stern](https://github.com/wercker/stern) :fire::fire::fire::fire::fire: - Stern allows you to tail multiple pods on Kubernetes and multiple containers within the pod.

### Cluster Provisioning
- :green_heart:[Bootkube](https://github.com/kubernetes-sigs/bootkube) :fire::fire::fire::fire: - Bootkube is a tool for launching self-hosted Kubernetes clusters.
- :green_heart:[eksctl](https://github.com/weaveworks/eksctl) :fire::fire::fire::fire::fire: - `eksctl` is a simple CLI tool for creating clusters on EKS - Amazon's new managed Kubernetes service for EC2.
- :green_heart:[k3d](https://github.com/rancher/k3d) :fire::fire::fire::fire: - k3d,and Windows.,destroy,half the memory,highly available,is a tool for running local k3s clusters in docker. It's a single binary about 20 MB. You need to have docker installed.
- :green_heart:[k3s](https://github.com/rancher/k3s) :fire::fire::fire::fire::fire: - Lightweight Kubernetes. Easy to install,Kubernetes clusters from the command line.
- :green_heart:[kind](https://github.com/kubernetes-sigs/kind) :fire::fire::fire::fire::fire: - kind is a tool for running local Kubernetes clusters using Docker container "nodes".
- :green_heart:[kops](https://github.com/kubernetes/kops) :fire::fire::fire::fire::fire: - `kops` helps you create,like kind,upgrade and maintain production-grade
- :green_heart:[kube-aws](https://github.com/kubernetes-incubator/kube-aws) :fire::fire::fire::fire: - `kube-aws` is a command-line tool to create/update/destroy Kubernetes clusters on AWS.
- :green_heart:[kubespray](https://github.com/kubernetes-sigs/kubespray) :fire::fire::fire::fire::fire: - Deploy a production ready Kubernetes cluster
- :green_heart:[Minikube](https://github.com/kubernetes/minikube) :fire::fire::fire::fire::fire: - minikube implements a local Kubernetes cluster on macOS,Linux,all in a binary less than 100 MB.
- [Kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/) - kubeadm performs the actions necessary to get a minimum viable cluster up and running.

### Automation and CI/CD
- :green_heart:[Apollo](https://github.com/logzio/apollo) :fire::fire: - Apollo is a simple, lightweight, Continuous Deployment (CD) solution on top of Kubernetes.
- :green_heart:[Argo CD](https://github.com/argoproj/argo-cd) :fire::fire::fire::fire::fire: - Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes.
- :green_heart:[Argo Events](https://github.com/argoproj/argo-events) :fire::fire::fire: - Argo Events is an event-driven workflow automation framework for Kubernetes which helps you trigger K8s objects, Argo Workflows, Serverless workloads, etc.
- :green_heart:[Argo Rollouts](https://github.com/argoproj/argo-rollouts) :fire::fire::fire: - Argo Rollouts controller, uses the Rollout custom resource to provide additional deployment strategies such as Blue Green and Canary to Kubernetes.
- :green_heart:[Argo Workflows](https://github.com/argoproj/argo) :fire::fire::fire::fire::fire: - Argo Workflows is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes.
- [Codefresh](https://codefresh.io/) - Codefresh is a Docker-native CI/CD platform. Instantly build, test and deploy Docker images to Kubernetes.
- :green_heart:[Flagger](https://github.com/weaveworks/flagger) :fire::fire::fire::fire::fire: - Flagger is a progressive delivery tool that automates the release process for applications running on Kubernetes.
- :green_heart:[Flux](https://github.com/fluxcd/flux) :fire::fire::fire::fire::fire: - Flux is a tool that automatically ensures that the state of a cluster matches the config in git.
- :green_heart:[Flux2](https://github.com/fluxcd/flux2) :fire::fire::fire: - Flux version 2 is built from the ground up to use Kubernetes' API extension system, and to integrate with Prometheus and other core components of the Kubernetes ecosystem.
- :green_heart:[Helm Operator](https://github.com/fluxcd/helm-operator) :fire::fire: - The Helm Operator is a Kubernetes operator, allowing one to declaratively manage Helm chart releases.
- :green_heart:[k8s-image-swapper](https://github.com/estahn/k8s-image-swapper/) :fire: - `k8s-image-swapper` is a mutating webhook for Kubernetes, downloading images into your own registry and pointing the images to that new location.
- :green_heart:[KEDA](https://github.com/kedacore/keda) :fire::fire::fire::fire::fire: - KEDA allows for fine grained autoscaling (including to/from zero) for event driven Kubernetes workloads.
- :green_heart:[KubeSphere](https://github.com/kubesphere/kubesphere) :fire::fire::fire::fire::fire: - KubeSphere is a distributed operating system providing cloud native stack with Kubernetes as its kernel, and aims to be plug-and-play architecture for third-party applications seamless integration to boost its ecosystem.
- :green_heart:[Reloader](https://github.com/stakater/Reloader) :fire::fire::fire::fire: - Reloader can watch changes in `ConfigMap` and `Secret` and do rolling upgrades on Pods with their associated `DeploymentConfigs`, `Deployments`, `Daemonsets` and `Statefulsets`.
- :green_heart:[Skaffold](https://github.com/GoogleContainerTools/skaffold) :fire::fire::fire::fire::fire: - Skaffold is a command line tool that facilitates continuous development for Kubernetes applications.
- :green_heart:[Spinnaker](https://github.com/spinnaker/spinnaker) :fire::fire::fire::fire::fire: - Spinnaker is an open-source continuous delivery platform for releasing software changes with high velocity and confidence.
- :green_heart:[werf](https://github.com/werf/werf) :fire::fire::fire::fire::fire: - werf is a CLI tool glueing Git, Docker, Helm & Kubernetes with any CI system to implement CI/CD and GitOps. 

### Cluster Resources Management
- :green_heart:[Grafana Tanka](https://github.com/grafana/tanka) :fire::fire::fire: - The clean, concise and super flexible alternative to YAML for your Kubernetes cluster.
- :green_heart:[Kruise](https://github.com/openkruise/kruise) :fire::fire::fire::fire: - Kruise consists of several controllers which extend and complement the Kubernetes core controllers for workload management.
- :green_heart:[KubeDirector](https://github.com/bluek8s/kubedirector) :fire::fire: - KubeDirector uses standard Kubernetes (K8s) facilities of custom resources and API extensions to implement stateful scaleout application clusters.
- :green_heart:[Kubenav](https://github.com/kubenav/kubenav) :fire::fire::fire: - kubenav is the navigator for your Kubernetes clusters right in your pocket.
- :green_heart:[Liqo](https://github.com/liqotech/liqo) :fire: - Liqo implements Dynamic resource sharing across different Kubernetes clusters (e.g.; offloading pods and services), supporting decentralized governance.
- :green_heart:[The Hierarchical Namespace Controller](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc) :fire::fire::fire: - Hierarchical namespaces make it easier to share your cluster by making namespaces more powerful.

### Secrets Management
- :green_heart:[Kubernetes External Secrets](https://github.com/godaddy/kubernetes-external-secrets) :fire::fire::fire: - Kubernetes External Secrets allows you to use external secret management systems, like AWS Secrets Manager or HashiCorp Vault, to securely add secrets in Kubernetes.
- :green_heart:[Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) :fire::fire::fire::fire::fire: - Encrypt your Secret into a SealedSecret, which is safe to store - even to a public repository.

### Networking
- :green_heart:[Calico Networking](https://github.com/projectcalico/calico) :fire::fire::fire::fire: - Calico is an open source networking and network security solution for containers, virtual machines, and bare-metal workloads
- :green_heart:[cert-manager](https://github.com/jetstack/cert-manager) :fire::fire::fire::fire::fire: - cert-manager is a Kubernetes add-on to automate the management and issuance of TLS certificates from various issuing sources.
- :green_heart:[CoreDNS](https://github.com/coredns/coredns) :fire::fire::fire::fire::fire: - CoreDNS is a fast and flexible DNS server that works on Kubernetes.
- :green_heart:[ingress-nginx](https://github.com/kubernetes/ingress-nginx) :fire::fire::fire::fire::fire: - `ingress-nginx` is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer.
- :green_heart:[Kong for Kubernetes](https://github.com/Kong/kubernetes-ingress-controller) :fire::fire::fire::fire: - Configure plugins, health checking, load balancing and more in Kong for Kubernetes Services.
- :green_heart:[ksniff](https://github.com/eldadru/ksniff) :fire::fire::fire: - A kubectl plugin that utilize tcpdump and Wireshark to start a remote capture on any pod in your Kubernetes cluster.
- :green_heart:[kubectl trace](https://github.com/iovisor/kubectl-trace) :fire::fire::fire: - `kubectl trace` is a kubectl plugin that allows you to schedule the execution of bpftrace programs in your Kubernetes cluster.
- :green_heart:[Kube Karp](https://github.com/immanuelfodor/kube-karp) :fire: - Add a floating virtual IP to Kubernetes cluster nodes for load balancing easily based on the CARP protocol
- :green_heart:[kubernetes-ingress](https://github.com/nginxinc/kubernetes-ingress) :fire::fire::fire::fire::fire:  - An implementation of an Ingress controller for NGINX and NGINX Plus (commercial).
- :green_heart:[kube-ovn](https://github.com/alauda/kube-ovn) :fire::fire::fire:  - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.

### Storage
- :green_heart:[Longhorn](https://github.com/longhorn/longhorn) :fire::fire::fire::fire: - Longhorn is a distributed block storage system for Kubernetes.
- :green_heart:[OpenEBS](https://github.com/openebs/openebs) :fire::fire::fire::fire::fire: - OpenEBS is the most widely deployed and easy to use open-source storage solution for Kubernetes.
- :green_heart:[Rook](https://github.com/rook/rook) :fire::fire::fire::fire::fire: - Rook is an open source cloud-native storage orchestrator for Kubernetes.
- [Amazon EBS CSI Driver](https://github.com/kubernetes-sigs/aws-ebs-csi-driver) - The Amazon Elastic Block Store Container Storage Interface (CSI) Driver provides a CSI interface used by Container Orchestrators to manage the lifecycle of Amazon EBS volumes.
- [Amazon EFS CSI Driver](https://github.com/kubernetes-sigs/aws-efs-csi-driver) - The Amazon Elastic File System Container Storage Interface (CSI) Driver implements the CSI specification for container orchestrators to manage the lifecycle of Amazon EFS filesystems.
- [Amazon FSx for Lustre CSI Driver](https://github.com/kubernetes-sigs/aws-fsx-csi-driver) - The Amazon FSx for Lustre Container Storage Interface (CSI) Driver implements CSI specification for container orchestrators (CO) to manage lifecycle of Amazon FSx for Lustre filesystems.

### Testing and Troubleshooting
- :green_heart:[Chaos Mesh](https://github.com/pingcap/chaos-mesh) :fire::fire::fire::fire: - Chaos Mesh® is a cloud-native Chaos Engineering platform that orchestrates chaos on Kubernetes environments.
- :green_heart:[chaoskube](https://github.com/linki/chaoskube) :fire::fire::fire::fire: - `chaoskube` periodically kills random pods in your Kubernetes cluster.
- :green_heart:[Conftest](https://github.com/open-policy-agent/conftest) :fire::fire::fire::fire: - Conftest helps you write tests against structured configuration data.
- :green_heart:[Copper](https://github.com/cloud66-oss/copper) :fire::fire: - A configuration file validator for Kubernetes. This is specifically useful with Kubernetes configuration files to enforce best practices, apply policies and compliance requirements.
- :green_heart:[k6](https://github.com/loadimpact/k6) :fire::fire::fire::fire::fire: - k6 is a modern load testing tool, building on Load Impact's years of experience in the load and performance testing industry.
- :green_heart:[ksniff](https://github.com/eldadru/ksniff) :fire::fire::fire: - A kubectl plugin that utilize tcpdump and Wireshark to start a remote capture on any pod in your Kubernetes cluster.
- :green_heart:[Kube DOOM](https://github.com/storax/kubedoom) :fire::fire::fire::fire: - The next level of chaos engineering is here! Kill pods inside your Kubernetes cluster by shooting them in Doom!
- :green_heart:[kube-monkey](https://github.com/asobti/kube-monkey) :fire::fire::fire::fire: - It randomly deletes Kubernetes (k8s) pods in the cluster encouraging and validating the development of failure-resilient services.
- :green_heart:[kube-score](https://github.com/zegl/kube-score) :fire::fire::fire: - `kube-score` is a tool that performs static code analysis of your Kubernetes object definitions.
- :green_heart:[Kubectl-debug](https://github.com/aylei/kubectl-debug) :fire::fire::fire::fire: - `kubectl-debug` is an out-of-tree solution for troubleshooting running pods, which allows you to run a new container in running pods for debugging purpose.
- :green_heart:[KubeInvaders](https://github.com/lucky-sideburn/KubeInvaders) :fire::fire::fire: - Through KubeInvaders you can stress Kubernetes cluster in a fun way and check how it is resilient.
- :green_heart:[Kubetest](https://github.com/vapor-ware/kubetest) :fire: - Kubetest is a pytest plugin that makes it easier to manage a Kubernetes cluster within your integration tests.
- :green_heart:[Litmus](https://github.com/litmuschaos/litmus) :fire::fire::fire: - Litmus provides tools to orchestrate chaos on Kubernetes to help SREs find weaknesses in their deployments.
- :green_heart:[popeye](https://popeyecli.io/) :fire::fire::fire::fire::fire: - Popeye is a utility that scans live Kubernetes cluster and reports potential issues with deployed resources and configurations.
- :green_heart:[PowerfulSeal](https://github.com/bloomberg/powerfulseal) :fire::fire::fire::fire: - PowerfulSeal injects failure into your Kubernetes clusters, so that you can detect problems as early as possible.

### Monitoring, Alerts, and Visualization
- :green_heart:[BotKube](https://github.com/infracloudio/botkube) :fire::fire::fire: - BotKube integration with Slack or Mattermost helps you monitor your Kubernetes cluster, debug critical deployments and gives recommendations for standard practices by running checks on the Kubernetes resources.
- :green_heart:[Cortex](https://github.com/cortexproject/cortex) :fire::fire::fire::fire::fire: - Cortex provides horizontally scalable, highly available, multi-tenant, long term storage for Prometheus.
- :green_heart:[Goldilocks](https://github.com/FairwindsOps/goldilocks) :fire::fire: - This tool creates a vertical pod autoscaler for each deployment in a namespace and then queries them for information.
- :green_heart:[Grafana](https://github.com/grafana/grafana) :fire::fire::fire::fire::fire: - Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored.
- :green_heart:[k8s-image-availability-exporter](https://github.com/flant/k8s-image-availability-exporter) :fire: - Prometheus exporter that warns you proactively about images that are defined in Kubernetes objects but are not available in the container registry. 
- :green_heart:[Kiali](https://github.com/kiali/kiali) :fire::fire::fire::fire::fire: - Kiali works with Istio to visualise the service mesh topology.
- :green_heart:[kube-capacity](https://github.com/robscott/kube-capacity) :fire::fire::fire: - This is a simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster.
- :green_heart:[kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) :fire::fire::fire::fire::fire: - kube-state-metrics is a simple service that listens to the Kubernetes API server and generates metrics about the state of the objects.
- :green_heart:[Kubernetes Dashboard](https://github.com/kubernetes/dashboard) :fire::fire::fire::fire::fire: - Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters.
- :green_heart:[Kubernetes Metrics Server](https://github.com/kubernetes-sigs/metrics-server) :fire::fire::fire::fire::fire: - Metrics Server is a scalable, efficient source of container resource metrics for Kubernetes built-in autoscaling pipelines.
- :green_heart:[Kubernetes Operational View](https://github.com/hjacobs/kube-ops-view) :fire::fire::fire::fire: - A tool that aims to provide a common operational picture for multiple Kubernetes clusters.
- :green_heart:[kubewatch](https://github.com/bitnami-labs/kubewatch) :fire::fire::fire::fire: - `kubewatch` is a Kubernetes watcher that currently publishes notification to available collaboration hubs/notification channels.
- :green_heart:[Lens](https://github.com/lensapp/lens) :fire::fire::fire::fire::fire: - Lens it's an useful, attractive, open source user interface (UI) for working with Kubernetes clusters.
- :green_heart:[Octant](https://github.com/vmware-tanzu/octant) :fire::fire::fire::fire::fire: - Octant is a highly extensible platform for developers to better understand the complexity of Kubernetes clusters. 
- :green_heart:[Popeye](https://github.com/derailed/popeye) :fire::fire::fire::fire::fire: - Popeye is a utility that scans live Kubernetes cluster and reports potential issues with deployed resources and configurations.
- :green_heart:[Prometheus](https://github.com/prometheus/prometheus) :fire::fire::fire::fire::fire: - Prometheus, a Cloud Native Computing Foundation project, is a systems and service monitoring system.
- :green_heart:[Searchlight](https://github.com/searchlight/searchlight) :fire::fire: - Searchlight/Icinga periodically runs various checks on a Kubernetes cluster and sends notifications if detects an issue.
- :green_heart:[Sloop](https://github.com/salesforce/sloop) :fire::fire::fire: - Sloop monitors Kubernetes, recording histories of events and resource state changes and providing visualizations to aid in debugging past events.
- :green_heart:[Thanos](https://github.com/thanos-io/thanos) :fire::fire::fire::fire::fire: - Thanos is a set of components that can be composed into a highly available metric system with unlimited storage capacity.
- :green_heart:[Kubedev](https://github.com/relferreira/kubedev) :fire: - Kubedev is a powerful and beautiful user interface for managing Kubernetes clusters.
- :green_heart:[KubeHelper](https://github.com/KubeHelper/kubehelper) :fire: - KubeHelper - simplifies many daily Kubernetes cluster tasks through a web interface.

### Backup and Restore
- :green_heart:[katafygio](https://github.com/bpineau/katafygio) :fire: - katafygio discovers Kubernetes objects (deployments, services, ...), and continuously save them as yaml files in a git repository.
- :green_heart:[Velero](https://github.com/vmware-tanzu/velero) :fire::fire::fire::fire::fire: - Velero (formerly Heptio Ark) gives you tools to back up and restore your Kubernetes cluster resources and persistent volumes.

### Security and Compliance
- :green_heart:[Falco](https://github.com/falcosecurity/falco) :fire::fire::fire::fire::fire: - Falco is a behavioral activity monitor designed to detect anomalous activity in your applications. You can use Falco to monitor run-time security of your Kubernetes applications and internal components.
- :green_heart:[Gatekeeper](https://github.com/open-policy-agent/gatekeeper) :fire::fire::fire::fire: - Policy controller for Kubernetes
- :green_heart:[k-rail](https://github.com/cruise-automation/k-rail) :fire::fire: - k-rail is a workload policy enforcement tool for Kubernetes. It can help you secure a multi tenant cluster with minimal disruption and maximum velocity.
- :green_heart:[Konstraint](https://github.com/plexsystems/konstraint) - Konstraint is a CLI tool to assist with the creation and management of constraints when using Gatekeeper.
- :green_heart:[kube-bench](https://github.com/aquasecurity/kube-bench) :fire::fire::fire::fire::fire: - kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.
- :green_heart:[kube-hunter](https://github.com/aquasecurity/kube-hunter) :fire::fire::fire::fire::fire: - kube-hunter hunts for security weaknesses in Kubernetes clusters.
- :green_heart:[KubeLinter](https://github.com/stackrox/kube-linter) :fire::fire::fire: - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.
- :green_heart:[Kubesploit](https://github.com/cyberark/kubesploit) :fire::fire: - Kubesploit is a cross-platform post-exploitation HTTP/2 Command & Control server and agent dedicated for containerized environments written in Golang and built on top of Merlin project by Russel Van Tuyl (@Ne0nd0g).
- :green_heart:[KubiScan](https://github.com/cyberark/KubiScan) :fire::fire::fire: - A tool for scanning Kubernetes cluster for risky permissions in Kubernetes's Role-based access control (RBAC) authorization model.
- :green_heart:[Permission manager](https://github.com/sighupio/permission-manager) :fire::fire::fire: - Permission Manager is an application developed by SIGHUP that enables a super-easy and user-friendly RBAC management for Kubernetes.
- :green_heart:[rakkess](https://github.com/corneliusweig/rakkess) :fire::fire::fire: - kubectl plugin to show an access matrix for server resources
- [Kube-Scan](https://github.com/octarinesec/kube-scan) :fire::fire: - Kube-Scan gives a risk score, from 0 (no risk) to 10 (high risk) for each workload.
- [Teleport](https://github.com/gravitational/teleport) :fire::fire::fire::fire::fire: - Teleport Unified Access Plane enables engineers to quickly access any computing resource anywhere.
  
### Service Mesh
- :green_heart:[Istio](https://github.com/istio/istio) :fire::fire::fire::fire::fire: - An open platform to connect, manage, and secure microservices.
- :green_heart:[Linkerd](https://github.com/linkerd/linkerd) :fire::fire::fire::fire::fire: - Linkerd is a transparent service mesh, designed to make modern applications safe and sane.
- :green_heart:[Open Service Mesh](https://github.com/openservicemesh/osm/) :fire::fire::fire::fire: - Open Service Mesh (OSM) is a lightweight, extensible, Cloud Native service mesh that allows users to uniformly manage, secure, and get out-of-the-box observability features for highly dynamic microservice environments.
- [AWS App Mesh](https://aws.amazon.com/app-mesh/) - A service mesh service offered by AWS that works on AWS infrastructure services such as EKS and Fargate.
- [Consul](https://www.hashicorp.com/products/consul/multi-platform-service-mesh/) - HashiCorp's service mesh service that is infrastructure agnostic.
- [NGINX Service Mesh](https://www.nginx.com/products/nginx-service-mesh) - NGINX Service Mesh (NSM) provides a turnkey, secure, service-to-service solution for container traffic management, with a unified data plane for ingress and egress management in a single configuration.

### Development Tools
- :green_heart:[garden](https://github.com/garden-io/garden) :fire::fire::fire::fire::fire: - Garden provides production-like Kubernetes testing environments for integration tests, QA, and development.
- :green_heart:[ko](https://github.com/google/ko) :fire::fire::fire::fire: - `ko` is a tool for building and deploying Golang applications to Kubernetes.
- :green_heart:[Konfig](https://github.com/cloud66-oss/konfig) :fire: - Konfig is a Kubernetes friendly Rails gem. It can load configuration and secrets from both YAML or folders with individual files and present them to your application the same way.
- :green_heart:[kubevious](https://github.com/kubevious/Kubevious) :fire::fire::fire: - Kubevious renders all configurations relevant to the application in one place. That saves a lot of time from operators, eliminating the need for looking up settings and digging within selectors and labels.
- :green_heart:[kubectl-warp](https://github.com/ernoaapa/kubectl-warp) :fire::fire: - Kubernetes CLI plugin for syncing and executing local files in Pod on Kubernetes
- :green_heart:[kubernix](https://github.com/saschagrunert/kubernix) :fire::fire: - This project aims to provide single dependency Kubernetes clusters for local testing, experimenting and development purposes.
- :green_heart:[Makisu](https://github.com/uber/makisu) :fire::fire::fire::fire::fire: - Makisu is a fast and flexible Docker image build tool designed for unprivileged containerized environments such as Mesos or Kubernetes.
- :green_heart:[Okteto](https://github.com/okteto/okteto) :fire::fire::fire::fire: - `okteto` accelerates the development workflow of Kubernetes applications.
- :green_heart:[Telepresence](https://github.com/telepresenceio/telepresence) :fire::fire::fire::fire::fire: - Telepresence provides fast, realistic local development for Kubernetes microservices.
- :green_heart:[Tilt](https://github.com/tilt-dev/tilt) :fire::fire::fire::fire::fire: - Tilt powers multi-service development and makes sure they behave.
- :green_heart:[Tye](https://github.com/dotnet/tye) :fire::fire::fire::fire: - Tye is a developer tool that makes developing, testing, and deploying microservices and distributed applications easier.

### Data Processing and Machine Learning
- :green_heart:[Kubeflow](https://github.com/kubeflow/kubeflow) :fire::fire::fire::fire::fire: - Kubeflow is a Cloud Native platform for machine learning based on Google’s internal machine learning pipelines.
- :green_heart:[Strimzi](https://github.com/strimzi/strimzi-kafka-operator) :fire::fire::fire::fire: - Strimzi provides a way to run an Apache Kafka cluster on Kubernetes or OpenShift in various deployment configurations.
- :green_heart:[Volcano](https://github.com/volcano-sh/volcano) :fire::fire::fire: - Volcano is a batch system built on Kubernetes.
- :green_heart:[yunikorn](https://github.com/apache/incubator-yunikorn-core) :fire::fire: - a light-weight, universal resource scheduler for container orchestrator systems.

### Miscellaneous
- :green_heart:[Agones](https://github.com/googleforgames/agones) :fire::fire::fire::fire::fire: - Agones is a library for hosting, running and scaling dedicated game servers on Kubernetes.
- :green_heart:[AWS Controllers for Kubernetes](https://github.com/aws/aws-controllers-k8s) :fire::fire::fire::fire: - AWS Controllers for Kubernetes (ACK) lets you define and use AWS service resources directly from Kubernetes.
- :green_heart:[AWS Node Termination Handler](https://github.com/aws/aws-node-termination-handler) :fire::fire: - A Kubernetes Daemonset to gracefully handle EC2 instance shutdown
- :green_heart:[Brigade](https://github.com/brigadecore/brigade/) :fire::fire::fire::fire::fire: - Brigade is the tool for creating pipelines for Kubernetes.
- :green_heart:[Crossplane](https://github.com/crossplane/crossplane) :fire::fire::fire::fire::fire: - Crossplane is an open source Kubernetes add-on that extends any cluster with the ability to provision and manage cloud infrastructure, services, and applications.
- :green_heart:[Descheduler for Kubernetes](https://github.com/kubernetes-sigs/descheduler) :fire::fire::fire::fire: - Descheduling pods from nodes based on policies
- :green_heart:[Devtron](https://github.com/devtron-labs/devtron) :fire::fire::fire::fire: - It is designed as a self-serve platform for operationalizing and maintaining applications (AppOps) on kubernetes in a developer friendly way.
- :green_heart:[Kubecost](https://github.com/kubecost/cost-model) :fire::fire::fire: - Kubecost models give teams visibility into current and historical Kubernetes spend and resource allocation.
- :green_heart:[KubeEdge](https://github.com/kubeedge/kubeedge) :fire::fire::fire::fire::fire: - KubeEdge is built upon Kubernetes and extends native containerized application orchestration and device management to hosts at the Edge.
- :green_heart:[Kubeless](https://github.com/kubeless/kubeless) :fire::fire::fire::fire::fire: - `kubeless` is a Kubernetes-native serverless framework that lets you deploy small bits of code without having to worry about the underlying infrastructure plumbing.
- :green_heart:[KubePug](https://github.com/rikatz/kubepug) :fire: - A tool to check deprecations before upgrading Kubernetes version
- :green_heart:[Shell-operator](https://github.com/flant/shell-operator) :fire::fire::fire::fire: - Shell-operator is a tool for running event-driven scripts in a Kubernetes cluster.

## Guides, Documentations, Blogs, and Learnings

### Guides
- [A Beginner’s Guide to Kubernetes](https://medium.com/containermind/a-beginners-guide-to-kubernetes-7e8ca56420b6) - A comprehensive introduction to Kubernetes architecture
- [A Guide to the Kubernetes Networking Model](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model/) - A in-depth run-through of Kubernetes networking
- [Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/) - This guide provides advice about protecting information, systems, and assets that are reliant on EKS while delivering business value through risk assessments and mitigation strategies.
- [Amazon EKS Node Drainer](https://github.com/aws-samples/amazon-k8s-node-drainer) - A guide and an example to cordon and evict all evictable pods from an EC2 node being terminated.
- [Comparison of Kubernetes Ingress controllers](https://docs.google.com/spreadsheets/d/191WWNpjJ2za6-nbG4ZoUMXMpUK8KlCIosvQB0f-oq3k/htmlview?pru=AAABdXUHlbs*g6XkyoZXhanlhRazst77Xw) - This research compares the capabilities of 14 different Kubernetes Ingress controllers.  
- [Configuring HA Kubernetes cluster on bare metal servers with kubeadm](https://medium.com/faun/configuring-ha-kubernetes-cluster-on-bare-metal-servers-with-kubeadm-1-2-1e79f0f7857b) - A guide to standing up a HA Kubernetes cluster on bare metal servers with kubeadm.
- [Introduction to Using Google Kubernetes Engine; Explain Like I’m Five!](https://medium.com/faun/google-kubernetes-engine-explain-like-im-five-1890e550c099) - Creating your first managed Kubernetes cluster on Google Kubernetes Engine using Terraform.
- [Kubernetes Network Policy Recipes](https://github.com/ahmetb/kubernetes-network-policy-recipes) - This repository contains various use cases of Kubernetes Network Policies and sample YAML files to leverage in your setup.
- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) - Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication.
- [Kubernetes Working Group for Multi-Tenancy](https://github.com/kubernetes-sigs/multi-tenancy) - This is a working place for multi-tenancy related proposals and prototypes.
- [Production grade Kubernetes Monitoring using Prometheus](https://medium.com/faun/production-grade-kubernetes-monitoring-using-prometheus-78144b835b60) - A in-depth guide to deploy Prometheus monitoring solution.
- [The Illustrated Children’s Guide to Kubernetes](https://www.cncf.io/the-childrens-illustrated-guide-to-kubernetes/) - Graphical explanations of Kubernetes
- [Troubleshooting Kubernetes deployments](https://learnk8s.io/a/troubleshooting-kubernetes.pdf) - A flow chart to troubleshoot a kubernetes deployment in case of issues
 - [Vertical Pod Autoscaling: The Definitive Guide](https://povilasv.me/vertical-pod-autoscaling-the-definitive-guide/) - An in-depth explanation on Kubernetes VPA: what it is, how it works, how to use it and which limitations it has. 
- [Writing Your First Kubernetes Operator](https://medium.com/faun/writing-your-first-kubernetes-operator-8f3df4453234) - In this article, we’ll see how to build and deploy your first Kubernetes Operator using the Operator SDK.

### Blogs and Videos
- [10 most common mistakes using kubernetes](https://blog.pipetail.io/posts/2020-05-04-most-common-mistakes-k8s/) - Common pitfalls and how to avoid them.  
- [How the Department of Defense Moved to Kubernetes and Istio](https://www.youtube.com/watch?v=YjZ4AZ7hRM0) - Focus on the sidecar security stack leveraging Envoy and sidecar containers to ensure zero trust security and baked-in multi-layer security.  
- [Kubernetes at Reddit: Tales from Production](https://youtu.be/WTbIBqNcjoQ) - Hear of successes, share in the heartbreak of production explosions, and gain insight into what has and hasn't worked well for one of the world's busiest web properties.  
- [Kubernetes Failure Stories](https://github.com/hjacobs/kubernetes-failure-stories) - A compiled list of links to public failure stories related to Kubernetes.  
- [Life of a Packet](https://www.youtube.com/watch?v=0Omvgd7Hg1I) - Tracing the path of network traffic in the Kubernetes system.  
- [OPA Deep Dive](https://www.youtube.com/watch?v=Uj2N9S58GLU) - Deep dive on some exciting new features in the OPA project presented by the co-creators.  
- [Scaling Kubernetes to 2,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-2500-nodes/) + [Scaling Kubernetes to 7,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-7500-nodes/) - Issues you will encounter when running high-scale Kubernetes workloads.
- [Service Mesh Comparison](https://servicemesh.es/) - An easy compensation to help choose one of the service Mesh implementations.  

### Learnings and Documentations
- [A Beginner’s Guide to Kubernetes](https://medium.com/containermind/a-beginners-guide-to-kubernetes-7e8ca56420b6) - A comprehensive introduction to Kubernetes architecture
- [ConfigMaps in Kubernetes: how they work and what you should remember](https://blog.flant.com/configmaps-in-kubernetes-how-they-work-and-what-you-should-remember/) - Understanding the evolution to ConfigMaps, how they work and what happens when they change. 
- [Configuring Redis using a ConfigMap](https://kubernetes.io/docs/tutorials/configuration/configure-redis-using-configmap/) - A walkthrough that provides a real world example of how to configure Redis using a ConfigMap
- [Example: Deploying Cassandra with a StatefulSet](https://kubernetes.io/docs/tutorials/stateful-application/cassandra/) - This tutorial shows you how to run Apache Cassandra on Kubernetes. Cassandra, a database, needs persistent storage to provide data durability.
- [Example: Deploying PHP Guestbook application with Redis](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/) - This tutorial shows you how to build and deploy a simple, multi-tier web application using Kubernetes and Docker.
- [Example: Deploying WordPress and MySQL with Persistent Volumes](https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/) - This tutorial shows you how to deploy a WordPress site and a MySQL database using Minikube.
- [Exposing an External IP Address to Access an Application in a Cluster](https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/) - This guide shows how to create a Kubernetes Service object that exposes an external IP address.
- [Katacoda](https://www.katacoda.com/courses/kubernetes/playground) - This is a Kubernetes playground, a safe place designed for experimenting, exploring and learning Kubernetes.
- [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) - An official list of commonly used kubectl commands and flags.  
- [Kubectl Kubernetes CheatSheet](https://github.com/dennyzhang/cheatsheet-kubernetes-A4) - A cheatsheet containing many helpful kubectl commands
- [Kubernetes API Reference Docs](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/) - A high-level overview of the basic types of resources provided by the Kubernetes API and their primary functions.  
- [Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/) - This tutorial provides a walkthrough of the basics of the Kubernetes cluster orchestration system.
- [Play with Kubernetes](https://labs.play-with-k8s.com/) - Play with Kubernetes is a playground which allows users to run K8s clusters in a matter of seconds.
- [Ready-to-use commands and tips for kubectl](https://blog.flant.com/ready-to-use-commands-and-tips-for-kubectl/) - Various kubectl tips and tricks by Flant’s engineers.  
- [Running ZooKeeper, A Distributed System Coordinator](https://kubernetes.io/docs/tutorials/stateful-application/zookeeper/) - This tutorial demonstrates running Apache Zookeeper on Kubernetes using StatefulSets, PodDisruptionBudgets, and PodAntiAffinity.
- [Set Up a CI/CD Pipeline with Kubernetes](https://www.linux.com/audience/enterprise/set-cicd-pipeline-kubernetes-part-1-overview/) - A end-to-end guide to set up a CI/CD Pipeline with Kubernetes.
- [StatefulSet Basics](https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/) - This tutorial provides an introduction to managing applications with StatefulSets.
- [Webinar: K8s with OPA Gatekeeper](https://www.youtube.com/watch?v=v4wJE3I8BYM) - How to use OPA to control what end-users can do on the cluster and ways to ensure that clusters are in compliance with company policies.  

### Certification Guides
- [Certified Kubernetes Security Specialist - CKSS](https://github.com/ijelliti/CKSS-Certified-Kubernetes-Security-Specialist) - This repository is a collection of resources to prepare for the Certified Kubernetes Security Specialist (CKSS) exam.
- [CKS "Certified Kubernetes security specialist certification](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist) - Kubernetes security resources primarly from material allowed during the exam, and extra optional items to help you advance your container and kubernetes security journey.
- [How to pass the Certified Kubernetes Administrator (CKA) exam on the first attempt](https://medium.com/faun/how-to-pass-certified-kubernetes-administrator-cka-exam-on-first-attempt-36c0ceb4c9e) - A guide to pass CKA exam
- [The ultimate CKA "Certfified Kuberenetes Administator" resource since exam inception](https://github.com/walidshaari/Kubernetes-Certified-Administrator)  - An updated repo of offical resources to help you master the CKA exam as well some extra resources to consolidate your kubernetes administration knowledge.
- [Kubernetes Exam Simulator](https://killer.sh/) - CKS/CKA/CKAD exams scenarios and environment.  

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Tom Huang has waived all copyright and
related or neighboring rights to this work.
