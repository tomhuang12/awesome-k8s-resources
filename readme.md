# Awesome Kubernetes Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Kubernetes tools and resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome) list and [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws).

## The Fiery Meter of AWSome

* Repo with 0050+ Stars: :fire:
* Repo with 0200+ Stars: :fire::fire:
* Repo with 0500+ Stars: :fire::fire::fire:
* Repo with 1000+ Stars: :fire::fire::fire::fire:
* Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Idea taken from [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws). 


## Contents

- [Tools and Libraries](#tools-and-libraries)
  - [Command Line Tools](#command-line-tools)
  - [Automation](#automation)
  - [Testing](#testing)
  - [Backup and Diaster Recovery](#backup-and-diaster-recovery)
  - [Security and Compliance](#security-and-compliance)
  - [Worker Node Operations](#worker-node-operations)
- [Guides, Tutorials, Documentations, and Trainings](#guides-tutorials-documentations-and-trainings)
  - [Guides](#guides)
  - [Tutorials](#tutorials)
- [Contribute](#contribute)
- [License](#license)


## Tools and Libraries
Items with :green_heart: indicate open source projects. 

### Command Line Tools
- :green_heart:[Kubebox](https://github.com/astefanutti/kubebox) :fire::fire::fire::fire: - Terminal and Web console for Kubernetes
- :green_heart:[K9s](https://github.com/derailed/k9s) :fire::fire::fire::fire::fire: - K9s provides a terminal UI to interact with your Kubernetes clusters.
- :green_heart:[eksctl](https://github.com/weaveworks/eksctl) :fire::fire::fire::fire::fire: - `eksctl` is a simple CLI tool for creating clusters on EKS - Amazon's new managed Kubernetes service for EC2.
- :green_heart:[kubediff](https://github.com/weaveworks/kubediff) :fire::fire::fire: - Kubediff is a tool for Kubernetes to show you the differences between your running configuration and your version controlled configuration.

### Automation
- :green_heart:[Flux](https://github.com/fluxcd/flux) :fire::fire::fire::fire::fire: - Flux is a tool that automatically ensures that the state of a cluster matches the config in git.
- :green_heart:[Helm Operator](https://github.com/fluxcd/helm-operator) :fire::fire: - The Helm Operator is a Kubernetes operator, allowing one to declaratively manage Helm chart releases.
- :green_heart:[Flagger](https://github.com/weaveworks/flagger) :fire::fire::fire::fire::fire: - Flagger is a progressive delivery tool that automates the release process for applications running on Kubernetes.
- :green_heart:[Kubernetes External Secrets](https://github.com/godaddy/kubernetes-external-secrets) :fire::fire::fire: - Kubernetes External Secrets allows you to use external secret management systems, like AWS Secrets Manager or HashiCorp Vault, to securely add secrets in Kubernetes.

### Testing
- :green_heart:[kube-monkey](https://github.com/asobti/kube-monkey) :fire::fire::fire::fire: - It randomly deletes Kubernetes (k8s) pods in the cluster encouraging and validating the development of failure-resilient services.
- :green_heart:[Kubetest](https://github.com/vapor-ware/kubetest) :fire: - Kubetest is a pytest plugin that makes it easier to manage a Kubernetes cluster within your integration tests.

### Backup and Diaster Recovery
- :green_heart:[katafygio](https://github.com/bpineau/katafygio) :fire: - katafygio discovers Kubernetes objects (deployments, services, ...), and continuously save them as yaml files in a git repository.

### Security and Compliance
- :green_heart:[kube-bench](https://github.com/aquasecurity/kube-bench) :fire::fire::fire::fire::fire: - kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.
- :green_heart:[Gatekeeper](https://github.com/open-policy-agent/gatekeeper) :fire::fire::fire::fire: - Policy controller for Kubernetes
- :green_heart:[Konstraint](https://github.com/plexsystems/konstraint) - Konstraint is a CLI tool to assist with the creation and management of constraints when using Gatekeeper.

### Worker Node Operations
- :green_heart:[AWS Node Termination Handler](https://github.com/aws/aws-node-termination-handler) :fire::fire: - A Kubernetes Daemonset to gracefully handle EC2 instance shutdown
- :green_heart:[Descheduler for Kubernetes](https://github.com/kubernetes-sigs/descheduler) :fire::fire::fire::fire: - Descheduling pods from nodes based on policies


## Guides, Documentations, and Trainings

### Guides
- [Amazon EKS Node Drainer](https://github.com/aws-samples/amazon-k8s-node-drainer) - A guide and an example to cordon and evict all evictable pods from an EC2 node being terminated.
- [Amazon EKS Workshop](https://www.eksworkshop.com/) - A comprehensive guide and list of tutorials to work with Amazon EKS.



## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Tom Huang has waived all copyright and
related or neighboring rights to this work.
