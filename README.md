# MkDocs Kubernetes Deployment with CronJob

* Clean README GitHub repo with intuitive documentation
* Git clone/pull public repo automatically from K8S CronJob
* Single YAML file configuration (`mkdocs.yaml`)
* No need for any tokens or ssh keys
* Material for MkDocs  
  <https://squidfunk.github.io/mkdocs-material/>

## Start Kind Cluster

```
kind create cluster --config kind.yaml
```

Access via port 30000 from localhost for testing.
