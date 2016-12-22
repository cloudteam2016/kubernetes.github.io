---
title: Reference Documentation
---

In the reference section, you can find reference documentation for Kubernetes APIs, CLIs, and tools, as well as our glossary and design docs. 

## API References

* [Kubernetes API](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/api.md) - The core API for Kubernetes.
* [Autoscaling API](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/api-reference/autoscaling/v1/operations.html) - Manages autoscaling resources such as HorizontalPodAutoscalers.
* [Batch API](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/api-reference/batch/v1/operations.html - Manages batch resources such as Jobs.
* [Apps API](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/api-reference/apps/v1beta1/operations.html) - Manages apps resources such as StatefulSets.
* [Extensions API](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/api-reference/extensions/v1beta1/operations.html) - Manages extensions resources such as Ingress, Deployments, and ReplicaSets.


## CLI References

* [kubectl](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/user-guide/kubectl-overview.md/) - Runs commands against Kubernetes clusters.
	* [JSONPath](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/user-guide/jsonpath.md/) - Syntax 	guide for using [JSONPath expressions](http://goessner.net/articles/JsonPath/) with kubectl.
* [kube-apiserver](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/admin/kube-apiserver.md) - REST API that validates and configures data for API objects such as  pods, services, replication controllers.
* [kube-proxy](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/admin/kube-proxy.md/) - Can do simple TCP/UDP stream forwarding or round-robin TCP/UDP forwarding across a set of backends.
* [kube-scheduler](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/admin/kube-proxy.md/) - A policy-rich, topology-aware, workload-specific function that significantly impacts availability, performance, and capacity.
* [kubelet](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/admin/kubelet.md/) - The primary "node agent" that runs on each node. The kubelet takes a set of PodSpecs and ensures that the described containers are running and healthy.

## Glossary

Explore the glossary of essential Kubernetes concepts. Some good starting points are the entries for [Pods](/docs/user-guide/pods/), [Nodes](https://github.com/kubernetes/kubernetes.github.io/blob/master/docs/admin/node.md), [Services](/docs/user-guide/services/), and [ReplicaSets](/docs/user-guide/replicasets/).

## Design Docs

An archive of the design docs for Kubernetes functionality. Good starting points are [Kubernetes Architecture](https://github.com/kubernetes/kubernetes/blob/release-1.1/docs/design/architecture.md) and [Kubernetes Design Overview](https://github.com/kubernetes/kubernetes/tree/release-1.1/docs/design).
