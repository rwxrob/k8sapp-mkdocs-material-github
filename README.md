# MkDocs Kubernetes Deployment with CronJob

1. Clean README GitHub repo with intuitive documentation
1. K8S PVC to hold `git pull` updates from GitHub repo
1. K8S `CronJob` (busybox) calling `git pull` at reasonable intervals
1. K8S `Deployment` containing MkDocs-Material in `serve` mode pointing to PVC
1. K8S Istio `VirtualServer` allowing access to web server from world

* Material for MkDocs  
  <https://squidfunk.github.io/mkdocs-material/>
