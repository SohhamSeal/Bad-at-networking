It is a container orchestration system, popularised by docker.

It bundles the code for an application and the configuration required to run the code itself, in a singe unit called minon or node.

Containers have the following architecture:


Kubernetes automatically helps in:
- Load balancing
- Scaling (noth up and down)
- Management of resources, etc
- Resource sharing, etc.

Common words and definitions:
- Node: It is a machine(both physical or virtual) on which kubernetes is installed.
- Cluster: A collection of nodes. What happens, if a node fails, the availability of the container or th eapplication will reduce incredibly, therefore it is better to have more than one nodewith containers deployed in them for high availability.
- Master and Worker nodes: Multiple nodes in a cluster needs to be managed, such as what are the resources that are to be shared, storing details of ultiple nodes, what are they doing, storing, etc. Therfore, a master is created that controls the other worker nodes. 
