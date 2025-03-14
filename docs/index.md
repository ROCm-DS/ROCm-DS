---
myst:
  html_meta:
    "description": "Learn about the features, capabilities, and ways to ROCm for Data Science"
    "keywords": "Data Science, GPU, how to, conceptual"
---

# AMD ROCm-DS

The ROCm Data Science toolkit (or ROCm-DS) is an open-source software collection for high-performance data science applications built on the core ROCm platform. ROCm-DS is a fork of the RAPIDS open source project from NVIDIA and enables users to accelerate their data processing and analysis workloads on AMD GPUs. You can leverage ROCm-DS to accelerate both new and existing data science workloads, allowing you to execute intensive applications with larger datasets at lightning speed. ROCm-DS enables the creation of scalable solutions addressing the pressing needs of today's data-driven landscape. With ROCm-DS you can build pre- and post-processing applications for your AI models, create new big data processing workloads, or accelerate your existing data science pipelines with minimal effort.

The available libraries in ROCm-DS provide you with the tools to build a complete workflow for data science acceleration on AMD GPUs. hipDF enables you to create data frames and execute GPU accelerated operations on them. It even includes the ability to accelerate many existing Pandas workflows with minimal effort and no code changes. hipGraph can be used to create, analyze, and review complex networks. Both the hipDF and hipGraph libraries in the early access release provide these capabilities for acceleration on AMD Instinct GPUs, with hipMM providing supporting functions for the memory management of these high performance GPU-based applications. 

ROCm-DS is an open source project found at [https://github.com/ROCm-DS](https://github.com/ROCm-DS).

::::{grid} 1 2 2 2
:gutter: 3
:class-container: rocm-doc-grid

:::{grid-item-card} Installation
:class-body: rocm-card-banner rocm-hue-2

* [Release Compatibility](./compatibility/compatibility.rst)

:::

:::{grid-item-card} Components
:class-body: rocm-card-banner rocm-hue-12

* [hipDF](./how-to/hipDF-index.rst)
* [hipGraph](./how-to/hipGRAPH-index.rst)
* [hipMM](./how-to/hipMM-index.rst)

:::

:::{grid-item-card} Related Content
:class-body: rocm-card-banner rocm-hue-8

* [hipDF Pandas Accelerated](https://github.com/ROCm/rocm-blogs-internal/tree/ffloresy/cuDF_pandas_accelerated)
* [cuPY and cuDF Portfolio Options](https://github.com/ROCm/rocm-blogs-internal/tree/ffloresy/cupy_cudf_portfolio_opt)

:::
::::
