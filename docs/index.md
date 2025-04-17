---
myst:
  html_meta:
    "description": "Learn about the features and capabilities of ROCm for Data Science (ROCm-DS)"
    "keywords": "Data-analytics, RAPIDS, cuDF, cuGraph, RMM, hipDF, hipGraph, hipMM, Pandas, NetworkX, High-Performance Computing, GPU Acceleration, GPU Computing, Parallel Computing, Scalable Data Science, Python"
---

# AMD ROCm-DS

> **Note:**
  ROCm-DS is in an early access state. Running production workloads is not recommended.

The ROCm Data Science toolkit (or ROCm-DS) is an open-source software collection for high-performance data science applications built on the core ROCm platform. ROCm-DS is a fork of the RAPIDS open-source project from NVIDIA and enables users to accelerate their data processing and analysis workloads on AMD GPUs. You can leverage ROCm-DS to accelerate both new and existing data science workloads, allowing you to execute intensive applications with larger datasets at lightning speed. ROCm-DS enables the creation of scalable solutions addressing the pressing needs of today's data-driven landscape. With ROCm-DS, you can build pre- and post-processing applications for your AI models, create new big data processing workloads, or accelerate your existing data science pipelines with minimal effort.

The available libraries in ROCm-DS provide the tools to build a complete workflow for data science acceleration on AMD GPUs. hipDF enables you to create data frames and execute GPU-accelerated operations on them. It also includes the ability to accelerate many existing Pandas workflows with minimal effort and no code changes. hipGraph can be used to create, analyze, and review complex networks. Both the hipDF and hipGraph libraries (currently in early access) provide these capabilities for acceleration on AMD Instinct GPUs, with hipMM providing supporting functions for the memory management of these high-performance GPU-based applications. For information about installing hipDF or hipGRAPH components, and required elements, see the Installation instructions for the components.

ROCm-DS is open and hosted at [https://github.com/ROCm-DS](https://github.com/ROCm-DS).

ROCm-DS documentation is organized into the following categories:

::::{grid} 1 2 2 2
:gutter: 3
:class-container: rocm-doc-grid

:::{grid-item-card} Installation
:class-body: rocm-card-banner rocm-hue-2

* [System requirements](./install/requirements.rst)
* [ROCm-DS Installation instructions](./install/install.rst)

:::

:::{grid-item-card} Components
:class-body: rocm-card-banner rocm-hue-12

* [hipDF](https://rocm.docs.amd.com/projects/hipDF-internal/en/latest/)
* [hipMM](https://rocm.docs.amd.com/projects/hipMM-internal/en/latest/)
* [hipGraph](https://rocm.docs.amd.com/projects/hipGRAPH-internal/en/latest/)

:::

:::{grid-item-card} Related Content
:class-body: rocm-card-banner rocm-hue-8

* [Instinct docs](https://advanced-micro-devices-dcgpu-documentation--65.com.readthedocs.build/65/)
* [ROCm-DS blogs](https://advanced-micro-devices-dcgpu-documentation--65.com.readthedocs.build/65/data-science/ROCmDS-Blogs.html)
* {ref}`contributing-to-rocm-ds`
:::
::::
