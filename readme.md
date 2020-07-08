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
  - [Automation](#automation)
  - [Networking](#networking)
  - [Storage](#storage)
  - [Testing](#testing)
  - [Monitoring and Visualization](#monitoring-and-visualization)
  - [Backup and Diaster Recovery](#backup-and-diaster-recovery)
  - [Security and Compliance](#security-and-compliance)
  - [Service Mesh](#service-mesh)
  - [Miscellaneous](#miscellaneous)
- [Guides, Documentations, Blogs, and Trainings](#guides-documentations-blogs-and-trainings)
  - [Guides](#guides)
  - [Documentations](#documentations)
  - [Blogs](#blogs)
- [Contribute](#contribute)
- [License](#license)


## Tools and Libraries
Items with :green_heart: indicate open source projects. 

### Command Line Tools
- :green_heart:[Kubebox](https://github.com/astefanutti/kubebox) :fire::fire::fire::fire: - Terminal and Web console for Kubernetes
- :green_heart:[K9s](https://github.com/derailed/k9s) :fire::fire::fire::fire::fire: - K9s provides a terminal UI to interact with your Kubernetes clusters.
- :green_heart:[kubediff](https://github.com/weaveworks/kubediff) :fire::fire::fire: - Kubediff is a tool for Kubernetes to show you the differences between your running configuration and your version controlled configuration.
- :green_heart:[Helm](https://github.com/helm/helm) :fire::fire::fire::fire::fire: - Helm is a tool for managing Charts. Charts are packages of pre-configured Kubernetes resources.
- :green_heart:[Telepresence](https://github.com/telepresenceio/telepresence) :fire::fire::fire::fire::fire: - Telepresence provides fast, realistic local development for Kubernetes microservices.

### Cluster Provisioning
- :green_heart:[kind](https://github.com/kubernetes-sigs/kind) :fire::fire::fire::fire::fire: - kind is a tool for running local Kubernetes clusters using Docker container "nodes".
- :green_heart:[k3s](https://github.com/rancher/k3s) :fire::fire::fire::fire::fire: - Lightweight Kubernetes. Easy to install, half the memory, all in a binary less than 100 MB.
- :green_heart:[eksctl](https://github.com/weaveworks/eksctl) :fire::fire::fire::fire::fire: - `eksctl` is a simple CLI tool for creating clusters on EKS - Amazon's new managed Kubernetes service for EC2.

### Automation
- :green_heart:[Flux](https://github.com/fluxcd/flux) :fire::fire::fire::fire::fire: - Flux is a tool that automatically ensures that the state of a cluster matches the config in git.
- :green_heart:[Helm Operator](https://github.com/fluxcd/helm-operator) :fire::fire: - The Helm Operator is a Kubernetes operator, allowing one to declaratively manage Helm chart releases.
- :green_heart:[Flagger](https://github.com/weaveworks/flagger) :fire::fire::fire::fire::fire: - Flagger is a progressive delivery tool that automates the release process for applications running on Kubernetes.
- :green_heart:[Kubernetes External Secrets](https://github.com/godaddy/kubernetes-external-secrets) :fire::fire::fire: - Kubernetes External Secrets allows you to use external secret management systems, like AWS Secrets Manager or HashiCorp Vault, to securely add secrets in Kubernetes.
- :green_heart:[Argo Workflows](https://github.com/argoproj/argo) :fire::fire::fire::fire::fire: - Argo Workflows is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes.
- :green_heart:[KEDA](https://github.com/kedacore/keda) :fire::fire::fire::fire::fire: - KEDA allows for fine grained autoscaling (including to/from zero) for event driven Kubernetes workloads.

### Networking
- :green_heart:[ingress-nginx](https://github.com/kubernetes/ingress-nginx) :fire::fire::fire::fire::fire: - `ingress-nginx` is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer.
- :green_heart:[kubernetes-ingress](https://github.com/nginxinc/kubernetes-ingress) :fire::fire::fire::fire::fire:  - An implementation of an Ingress controller for NGINX and NGINX Plus (commercial).
- :green_heart:[Calico Networking](https://github.com/projectcalico/calico) :fire::fire::fire::fire: - Calico is an open source networking and network security solution for containers, virtual machines, and bare-metal workloads
- :green_heart:[CoreDNS](https://github.com/coredns/coredns) :fire::fire::fire::fire::fire: - CoreDNS is a fast and flexible DNS server that works on Kubernetes.
- :green_heart:[Kong for Kubernetes](https://github.com/Kong/kubernetes-ingress-controller) :fire::fire::fire::fire: - Configure plugins, health checking, load balancing and more in Kong for Kubernetes Services.

### Storage
- :green_heart:[Rook](https://github.com/rook/rook) :fire::fire::fire::fire::fire: - Rook is an open source cloud-native storage orchestrator for Kubernetes.
- :green_heart:[OpenEBS](https://github.com/openebs/openebs) :fire::fire::fire::fire::fire: - OpenEBS is the most widely deployed and easy to use open-source storage solution for Kubernetes.
- :green_heart:[Longhorn](https://github.com/longhorn/longhorn) :fire::fire::fire::fire: - Longhorn is a distributed block storage system for Kubernetes.


### Testing
- :green_heart:[kube-monkey](https://github.com/asobti/kube-monkey) :fire::fire::fire::fire: - It randomly deletes Kubernetes (k8s) pods in the cluster encouraging and validating the development of failure-resilient services.
- :green_heart:[Kubetest](https://github.com/vapor-ware/kubetest) :fire: - Kubetest is a pytest plugin that makes it easier to manage a Kubernetes cluster within your integration tests.
- :green_heart:[Litmus](https://github.com/litmuschaos/litmus) :fire::fire::fire: - Litmus provides tools to orchestrate chaos on Kubernetes to help SREs find weaknesses in their deployments.

### Monitoring and Visualization
- :green_heart:[Prometheus](https://github.com/prometheus/prometheus) :fire::fire::fire::fire::fire: - Prometheus, a Cloud Native Computing Foundation project, is a systems and service monitoring system.
- :green_heart:[Grafana](https://github.com/grafana/grafana) :fire::fire::fire::fire::fire: - Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored.
- :green_heart:[kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) :fire::fire::fire::fire::fire: - kube-state-metrics is a simple service that listens to the Kubernetes API server and generates metrics about the state of the objects.
- :green_heart:[Kubernetes Metrics Server](https://github.com/kubernetes-sigs/metrics-server) :fire::fire::fire::fire::fire: - Metrics Server is a scalable, efficient source of container resource metrics for Kubernetes built-in autoscaling pipelines.
- :green_heart:[Kubernetes Operational View](https://github.com/hjacobs/kube-ops-view) :fire::fire::fire::fire: - A tool that aims to provide a common operational picture for multiple Kubernetes clusters.
- :green_heart:[Kubernetes Dashboard](https://github.com/kubernetes/dashboard) :fire::fire::fire::fire::fire: - Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters.
- :green_heart:[Thanos](https://github.com/thanos-io/thanos) :fire::fire::fire::fire::fire: - Thanos is a set of components that can be composed into a highly available metric system with unlimited storage capacity.
- :green_heart:[Cortex](https://github.com/cortexproject/cortex) :fire::fire::fire::fire::fire: - Cortex provides horizontally scalable, highly available, multi-tenant, long term storage for Prometheus.

### Backup and Diaster Recovery
- :green_heart:[katafygio](https://github.com/bpineau/katafygio) :fire: - katafygio discovers Kubernetes objects (deployments, services, ...), and continuously save them as yaml files in a git repository.

### Security and Compliance
- :green_heart:[kube-bench](https://github.com/aquasecurity/kube-bench) :fire::fire::fire::fire::fire: - kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.
- :green_heart:[Gatekeeper](https://github.com/open-policy-agent/gatekeeper) :fire::fire::fire::fire: - Policy controller for Kubernetes
- :green_heart:[Konstraint](https://github.com/plexsystems/konstraint) - Konstraint is a CLI tool to assist with the creation and management of constraints when using Gatekeeper.

### Service Mesh
- :green_heart:[Istio](https://github.com/istio/istio) :fire::fire::fire::fire::fire: - An open platform to connect, manage, and secure microservices.
- :green_heart:[Linkderd](https://github.com/linkerd/linkerd) :fire::fire::fire::fire::fire: - Linkerd is a transparent service mesh, designed to make modern applications safe and sane.
- [Consul](https://www.hashicorp.com/products/consul/multi-platform-service-mesh/) - HashiCorp's service mesh service that is infrastructure agnostic.
- [AWS App Mesh](https://aws.amazon.com/app-mesh/) - A service mesh service offered by AWS that works on AWS infrastructure services such as EKS and Fargate. 

### Miscellaneous
- :green_heart:[Crossplane](https://github.com/crossplane/crossplane) :fire::fire::fire::fire::fire: - Crossplane is an open source Kubernetes add-on that extends any cluster with the ability to provision and manage cloud infrastructure, services, and applications.
- :green_heart:[Brigade](https://github.com/brigadecore/brigade/) :fire::fire::fire::fire::fire: - Brigade is the tool for creating pipelines for Kubernetes.
- :green_heart:[Strimzi](https://github.com/strimzi/strimzi-kafka-operator) :fire::fire::fire::fire: - Strimzi provides a way to run an Apache Kafka cluster on Kubernetes or OpenShift in various deployment configurations.
- :green_heart:[KubeEdge](https://github.com/kubeedge/kubeedge) :fire::fire::fire::fire::fire: - KubeEdge is built upon Kubernetes and extends native containerized application orchestration and device management to hosts at the Edge.
- :green_heart:[Volcano](https://github.com/volcano-sh/volcano) :fire::fire::fire: - Volcano is a batch system built on Kubernetes.
- :green_heart:[AWS Node Termination Handler](https://github.com/aws/aws-node-termination-handler) :fire::fire: - A Kubernetes Daemonset to gracefully handle EC2 instance shutdown
- :green_heart:[Descheduler for Kubernetes](https://github.com/kubernetes-sigs/descheduler) :fire::fire::fire::fire: - Descheduling pods from nodes based on policies

## Guides, Documentations, Blogs, and Trainings

### Guides
- [Amazon EKS Node Drainer](https://github.com/aws-samples/amazon-k8s-node-drainer) - A guide and an example to cordon and evict all evictable pods from an EC2 node being terminated.
- [Amazon EKS Workshop](https://www.eksworkshop.com/) - A comprehensive guide and list of tutorials to work with Amazon EKS.
- [Moduler and Scalable Amazon EKS Architecture](https://s3.amazonaws.com/aws-quickstart/quickstart-amazon-eks/doc/amazon-eks-architecture.pdf) - A deployment guide that provides step-by-step instructions for deploying Amazon EKS clusters. 
- [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) - `kubectl` cheat sheet
- [Troubleshooting Kubernetes deployments](https://learnk8s.io/a/troubleshooting-kubernetes.pdf) - A flow chart to troubleshoot a kubernetes deployment in case of issues
- [How to deploy a production-grade Kubernetes cluster on AWS](https://gruntwork.io/guides/kubernetes/how-to-deploy-production-grade-kubernetes-cluster-aws/#use-eks) - This guide will walk you through the process of configuring a production-grade Kubernetes cluster on AWS.
- [Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/) - This guide provides advice about protecting information, systems, and assets that are reliant on EKS while delivering business value through risk assessments and mitigation strategies.

### Documentations
- [Kubernetes API Reference Docs](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/)

### Blogs
- [10 most common mistakes using kubernetes](https://blog.pipetail.io/posts/2020-05-04-most-common-mistakes-k8s/)




## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Tom Huang has waived all copyright and
related or neighboring rights to this work.
