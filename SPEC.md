# Overview
## What is CDI?

Composable Disaggregated Infrastructure (CDI) is a new server architecture that enables flexible rearrangement of server components and on-demand configuration of servers with the required specifications.

Previously, using a large number of GPUs required preparing numerous servers, which resulted in wasted CPU and memory resources. The server components are disassembled and connected to PCIe, CXL, and optical switches to create a resource pool. This switch enables the configuration of custom servers by connecting only the necessary components according to a software-defined configuration. We call this server composed bare metal, and we are trying to achieve both high performance and low power consumption by dynamically changing specifications according to the workload.

![What_is_CDI](https://github.com/user-attachments/assets/26b691d6-28c4-4958-a36d-0bbee97fac0f)

## Why is CDI needed?

Today, generative AI opened a new era of AI, and as a result, an enormous amount of computational resources are required. They need lots of power to operate. On the other hand, realizing a sustainable world is an urgent issue for us. We are constantly expected to reduce power consumption. That means we need to achieve both high performance and reduced power consumption concurrently. Composable Disaggregated Infrastructure is expected to address these conflicting requirements.

## How it works

CDI system is composed of resource pool and Composable Disaggregated Infrastructure manager (CDI manager) software. In resource pool, all components are connected to PCIe or CXL switches. The CDI manager controls the switches to create composed bare metal servers by software definition. It has Composable Resource API and Composable Resource Operator or Kubernetes may call the API. Once composed bare metal servers are created users can install any operating system or container infrastructure.

![IOWN2025-InfraDDSreadme](https://github.com/user-attachments/assets/f737661c-579f-4cbd-9c2e-d1c23de7f60d)
