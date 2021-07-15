# Glossary

### System Design
___
**Monolith:**<br>
application design where all application tiers are managed as a single unit

**Microservice:**<br> 
application design where application tiers are managed as independent, smaller units

### Docker and Kubernetes
___

**Dockerfile:**<br>
set of instructions used to create a Docker image

**Docker image:**<br>
a read-only template used to spin up a runnable instance of an application

**Docker registry:**<br>
a central mechanism to store and distribute Docker images

**CRD:**<br>
Custom Resource Definition provides the ability to extend Kubernetes API and create new resources

**Node:**<br>
a physical or virtual server

**Cluster:**<br>
a collection of distributed nodes that are used to manage and host workloads

**Master node:**<br> 
a node from the Kubernetes control plane, that has installed components to make global, cluster-level decisions

**Worker node:**<br>
a node from the Kubernetes data plane, that has installed components to host workloads

**Bootstrap:**<br>
the process of provisioning a Kubernetes cluster, by ensuring that each node has the necessary components to be fully operational

**Kubeconfig:**<br>
a metadata file that grants a user access to a Kubernetes cluster

**Pod:**<br>
smallest manageable uint within a cluster that provides the execution environment for an application

**ReplicaSet:**<br>
a mechanism to ensure a number of pod replicas are up and running at all times

**Deployment:**<br>
describe the desired state of the application to be deployed

**Service:**<br>
an abstraction layer over a collection of pods running an application

**Ingress:**<br>
a mechanism to manage the access from external users and workloads to the services within the cluster

**Configmap:**<br>
a resource to store non-confidential data in key-value pairs.

**Secret:**<br>
a resource to store confidential data in key-value pairs. These are base64 encoded.

**Namespace:**<br>
a logical separation between multiple applications and associated resources.

**Imperative configuration:**<br>
resource management technique, that operates and interacts directly with the live objects within the cluster.

**Declarative configuration:**<br>
resource management technique, that operates and manages resources using YAML manifests stored locally.

### Cloud-Computing Services
___

**On-premise:** <br>
cloud-computing service, where a team owns the entire technology stack.

**IaaS or Infrastructure as a Service:** <br>
cloud-computing service that offers the abstraction of networking, storage, server, and virtualization layers.

**PaaS or Platform as a Service:**<br>
cloud-computing service, where the infrastructure components are managed fully by a 3rd party provider, and a team manages only the application and the data associated with it.

**Cloud Foundry:**<br>
an open-source PaaS offering, that can be hosted on any available infrastructure

**FaaS or Function as a Service:**<br> 
event-driven cloud-computing service that requires only the application code to execute successfully.

### Ci/CD
___

**Continuous Integration:** <br> 
a mechanism that produces the package of an application that can be deployed.

**Continuous Delivery:** <br>
a mechanism to push the packaged application through multiple environments, including production.

**Continuous Deployment:**<br>
a procedure that contains the Continuous Integration and Continuous Delivery of a product.

**GitOps:**<br>
an operating model that refers to the Git repositories as the source of truth for declarative infrastructure and applications.

**Helm:** <br>
package manager tool used to template a suite of Kubernetes manifests.

**Helm chart:**<br>
a collection of configuration, input, and templated YAML files used to deploy Kubernetes resources.