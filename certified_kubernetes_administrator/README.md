# Certified Kubernetes Administrator

유데미에서 수강하는 Certified Kubernetes Administrator 강좌를 보며 정리하는 내용입니다.

## [Practice]

### [KODEKLOUD](https://kodekloud.com/courses/enrolled)
Udemy CKA강좌를 수강하는 사람에 한해서 사용이 가능합니다.
- This is not the interface of the actual example
- As many times as you like
- Temporary Environment - Only available for 1 hour
- Do not refresh the windwos with the terminal screen.
- No Personal details/Persitent work
- This is not to test your skills alone. This is to practice

## Core Concepts

### PODs
- [nginx](./pod-definition.yml)
- [redis](./pod-redis.yml)

### ReplicaSets
- [nginx-replicas 3](./rs-definition.yml)
- [rc-nginx-replicas 3](./rc-definition.yml)

### Deployments
- [nginx-replicas 3](./deployment-definition.yml)

### Namespaces
- [namespace](./namespace-dev.yml)
- [Quota](./compute-quota.yaml)

### Services
- [NodePort](./nodeportservice-definition.yml)
- [ClusterIP](./clusteripservice-definition.yml)

## Scheduling

