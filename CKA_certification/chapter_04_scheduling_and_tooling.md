#### Resrouce Limits Affect Pod Scheduling


*Resources Requests* - The minimum amount of CPU or memory that a container is guaranteed to have.
*Resource Limits* - The maximum amount of CPU or memory that a container can use.

- Defining Container Resource Requests

spec.containers[].resources.limits.cpu
spec.containers[].resources.limits.memory
spec.containers[].resources.limits.hugepages-<size>
spec.containers[].resources.requests.cpu
spec.containers[].resources.requests.memory
spec.containers[].resources.requests.hugepages-<size>

Pod resource request/limit is the sum of the resource requests/limits of that type for each container in the Pod.

- Defining Container Resource Limits
- Defining Container Resource Requests and Limits

### Pod-level resource specification - Kubernetes v1.32 [alpha] (enabled by default: false)

spec.resources.limits.cpu
spec.resources.limits.memory
spec.resources.requests.cpu
spec.resources.requests.memory

#### Managing Objects

- Declarative Object Management Using Configuration Files

- Declarative Object Management Using Kustomize

#### Common Templaing Tools
- Using the YAML Processor yq
- Using Helm

#### Summary

#### Sample Exercise Notes 

