---
myst:
  html_meta:
    "description": "Learn about the features, capabilities, and ways to ROCm for Data Science"
    "keywords": "Data Science, GPU, how to, conceptual"
---

# AMD ROCm-DS

The ROCm Data Science toolkit (or ROCm™-DS) is an open-source software platform for high-performance computing and machine learning applications that features the ability to accelerate training, fine-tuning, and inference for data science models on AMD GPUs. You can use ROCm-DS to perform distributed training, which enables you to train models across multiple GPUs or nodes simultaneously. Additionally, ROCm-DS supports mixed-precision training, which can help reduce the memory and compute requirements of training workloads. For fine-tuning, ROCm-DS provides access to various algorithms and optimization techniques. In terms of inference, ROCm-DS provides several techniques that can help you optimize your models for deployment, such as quantization, GEMM tuning, and optimization with composable kernel. 

The available libraries in ROCm-DS provide a complete workflow for data science acceleration on GPUs, replacing the use of common Python-based tools such as Pandas for data manipulation and analysis, or NetworkX for the creation and review of complex networks. The hipDF and hipGRAPH libraries in the early access release provide these capabilities for acceleration on AMD GPUs. The hipMM and hipRAFT libraries provide supporting functions for memory management, and vector and matrix operations to simplify coding for high performance GPU-based applications. 

How is ROCm-DS different from the more traditional ROCm libraries, which are a requirement of ROCm-DS in any case? The answer to this question is in the reference material provided below. ROCm-DS is an open source project found at [https://github.com/ROCm/ROCm-DS](https://github.com/ROCm/ROCm-DS).

::::{grid} 1 2 2 2
:gutter: 3
:class-container: rocm-doc-grid

:::{grid-item-card} Components
:class-body: rocm-card-banner rocm-hue-12

* [hipDF](./how-to/hipDF-index.rst), "Create Data frames in Pandas-like library"
* [hipGraph](./how-to/hipGRAPH-index.rst), "Graph inference and analysis of data models"
* [hipMM](./how-to/hipMM-index.rst), "Memory Management features"
* [hipRAFT](./how-to/hipRAFT-index.rst), "Vector and Matrix analysis"

:::

:::{grid-item-card} Related Content
:class-body: rocm-card-banner rocm-hue-8

* [hipDF Pandas Accelerated](https://github.com/ROCm/rocm-blogs-internal/tree/ffloresy/cuDF_pandas_accelerated)
* [cuPY and cuDF Portfolio Options](https://github.com/ROCm/rocm-blogs-internal/tree/ffloresy/cupy_cudf_portfolio_opt)

:::

::::
