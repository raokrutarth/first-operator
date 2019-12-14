# first-operator

Project to get started with writing a Kubernetes operator for an understanding of the Operator API.

## Outline

- A cluster running a replicated Go application that responds with a random number using gRPC.
- The operator calls an endpoint on the service if it's latency increases to X ms.
- The operator removes an instance of the service if the latency increases to Y ms.
- The operator logs all the activity done so far.

## Resources

[2019 Medium Article](https://medium.com/faun/writing-your-first-kubernetes-operator-8f3df4453234)

[2018 Kubecon Controller talk](https://www.youtube.com/watch?v=AUNPLQVxvmw)

