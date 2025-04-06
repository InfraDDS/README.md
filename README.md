# Infrastracture for Dynamic Device Scaling(InfraDDS) project vision statement

The objective of the InfraDDS initiative is to foster a community-driven, standards-based open ecosystem for next-generation architectures and frameworks built on Composable Disaggregated Infrastructure technology.
Composable Disaggregated Infrastructure enables data center operators to realize the cost-efficiency, availability, and sustainability advantages of disaggregated cloud computing while utilizing on-premises equipment.
However, there remains a gap between Kubernetes and composable systems, posing challenges for achieving more dynamic composability in line with Kubernetes' cloud-native environment.

The InfraDDS project aims to bridge this gap by collaborating with the Dynamic Resource Allocation, Auto-scaler, and Scheduler projects.

# InfraDDS Project Goals
- Create a community-driven, standards-based open ecosystem for composable resource technologies
- Develop a vendor-agnostic framework and architecture for composable resource software stacks
- Reuse existing APIs or define a new set of common APIs for composable resource technologies as needed
- Provide implementation examples to validate the architectures/APIs

# InfraDDS Project Backgrounder
A cloud data-centric infrastructure is emerging in the market. New infrastructure elements in cloud data center services and the IOWN Global Forum's Data-Centric Infrastructure as a Service (DCIaaS) require more dynamic composability with various types of PCIe-connected devices, including GPUs, DPUs/IPUs/Smart NICs, FPGAs, NVMe, and CXL memory.
These components must be dynamically composed and decomposed into CPU hosts running Kubernetes nodes via PCIe/CXL switch fabrics, in order to support flexible combinations of host server scale-up/scale-down and application scale-out/scale-in within a Kubernetes cluster.
InfraDDS provides a Kubernetes Operator that enables dynamic device scaling in Kubernetes environments.

![IOWN2025-InfraDDSreadme](https://github.com/user-attachments/assets/5b2638f6-72e1-403b-96b0-9cbd80c7cef8)

# How To Contribute
This project welcomes contributions and suggestions. We are happy to have the Community involved via submission of Issues and Pull Requests (with substantive content or even just fixes). We are hoping for the documents, test framework, etc. to become a community process with active engagement. PRs can be reviewed by by any number of people, and a maintainer may accept.

See CONTRIBUTING and GitHub Basic Process for more details.
