---
template: main.html
hide:
- toc
---

# Generating Requests Externally

All Iter8 tutorials use [`Fortio`](https://github.com/fortio/fortio) or `curl`-based Kubernetes jobs that run inside the cluster to simulate user requests during experiments. You can try other variations of these tutorials where requests are generated outside the cluster.

- The Knative service setup of [quick start](../../../getting-started/quick-start/with-knative/), [canary + progressive + Helm](../../../tutorials/knative/canary-progressive/), [canary + fixed split + Kustomize](../../../tutorials/knative/canary-fixedsplit/), and [conformance](../../../tutorials/knative/conformance/) tutorials is similar to that of this [Knative tutorial](https://knative.dev/docs/serving/samples/traffic-splitting/index.html#traffic-splitting).

- The Istio virtual service setup of [conformance + mirroring](../../../tutorials/knative/mirroring/) and [canary + traffic segmentation](../../../tutorials/knative/traffic-segmentation/) tutorials is similar to that of this [Knative tutorial](https://knative.dev/docs/serving/samples/knative-routing-go/index.html#access-the-services).

Refer to the above mentioned Knative tutorials for generating requests for your applications from outside the cluster.
