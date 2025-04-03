# Infrastracture for Dynamic Device Scaling(InfraDDS) project vision statement

The objective of the InfraDDS initiative is to foster a community-driven, standards-based open ecosystem for next-generation architectures and frameworks based on Composable Disaggregated Infrastructure technology.
Composable Disaggregated Infrastructure (CDI) is a technology that allows data center operators to achieve the cost, availability, and sustainability benefits of disaggregated cloud computing using on-premises equipment.

There is a whitespace between Kubernetes and the CDI systems that challenges more dynamic composability to meet the Kubernetes cloud-native environment.

This InfraDDS project will address this whitespace and will work with the Dynamic Resource Allocation project, Auto-scaler project, and Scheduler project.

# InfraDDS Project Goals
- Create community-driven standards-based open ecosystem for the CDI-like technologies
- Create vendor agnostic framework and architecture for the CDI-based software stacks
- Reuse existing or define a set of new common APIs for the CDI-like technologies when required
- Provide implementation examples to validate the architectures/APIs

# InfraDDS Project Backgrounder
A cloud data-centric infrastructure is emerging in the market. This new infrastructure element, such as cloud data center services and IOWN Global Forum's Data-Centric Infrastructure as a Service (DCIaaS), will require more dynamic composability with various types of PCIe cards, such as GPUs, DPUs/IPUs/Smart NICs, FPGAs, NVMe, and CXL memory. These components will need to be composed and decomposed into CPU hosts running Kubernetes nodes via PCIe/CXL switch fabric to dynamically support a combination of host server scale-up/scale-down and application scale-out/scale-in within a Kubernetes cluster.
InfraDDS provides the CDI Operator, which supports dynamic device scaling for Kubernetes.


# How To Contribute
