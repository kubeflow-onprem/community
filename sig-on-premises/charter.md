# SIG On Premises Charter

This charter adheres to the conventions, roles and organization management outlined in [wg-governance].

## Scope

SIG On Premises 

### In scope

#### Product Functionality

This SIG aims to coordinate projects and technologies necessary to enable the core functionality required to deploy and operate a feature store in Kubeflow.

- Ensure that users have a registry to define and manage features and their related metadata.
- Ensure that users have a means of data ingestion, management, and storage for the purposes of model training and online serving.
- Ensure that users have a unified feature serving layer for both model training and online serving.
- Ensure that users have the ability to both generate and validate feature statistics.
- Ensure that users have operational instrumentation necessary to safely run a feature store in production.
- Ensure that users have the documentation and tutorials necessary to both deploy, operate, and use a feature store.
- Ensure that Kubeflow maintains a cohesive data tooling vision with respect to feature stores.
- Ensure that users have access to a list of validated reference designs for setting clusters.
- Ensure that a process is defined that will enable users to contribute to reference designs.
- Ensure that there is always at least one working and validated complete software stack. This software stack would be defined as a list of OSes and component versions that have been verified to create a working solution.
 


#### Cross-cutting and Externally Facing Processes

- Coordinating with Pipelines/KFData WG to ensure both datasets and streams can be ingested, persisted, and served.
- Coordinating with Training WG to make sure that its possible to create training datasets using the feature store.
- Coordinating with Serving WG to make sure that its possible to retrieve online feature data from the feature store.
- Coordinating with Manifests WG to ensure that feature store manifests are properly deployed with Kubeflow.
- Coordinating with release teams to ensure that the feature store functionality can be released properly.
- Maintaining a list of hardware stacks known to work with Kubeflow.
- Maintaining instructions on how to verify a working stack.
- Maintaining a template for how to run benchmarks to verify a performant stack.

### Out of scope

- Data pipelining, immutability, and lineage.

## Roles and Organization Management

This SIG follows adheres to the Roles and Organization Management outlined in [wg-governance]
and opts-in to updates and modifications to [wg-governance].

### Subproject Creation

SIG Technical Leads.

[wg-governance]: ../wgs/wg-governance.md
