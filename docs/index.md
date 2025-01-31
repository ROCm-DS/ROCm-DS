---
myst:
  html_meta:
    "description": "Learn about the features, capabilities, and ways to ROCm for Data Science"
    "keywords": "Data Science, GPU, how to, conceptual"
---

# AMD ROCm-DS

ROCm™-DS is an open-source software platform that enables high-performance computing and machine learning applications. It features the ability to accelerate training, fine-tuning, and inference for data science models. With ROCm, you can access the full power of AMD GPUs, which can significantly improve the performance, productivity, and computation of data science models.

You can use ROCm to perform distributed training, which enables you to train models across multiple GPUs or nodes simultaneously. Additionally, ROCm supports mixed-precision training, which can help reduce the memory and compute requirements of training workloads. For fine-tuning, ROCm provides access to various algorithms and optimization techniques. In terms of inference, ROCm provides several techniques that can help you optimize your models for deployment, such as quantization, GEMM tuning, and optimization with composable kernel.

Overall, ROCm can be used to improve the performance and efficiency of your data science models. With its training, fine-tuning, and inference support, ROCm provides a complete solution for optimizing data science workflows and achieving the optimum results possible on AMD GPUs.

The ROCm for Data Science Developer Hub contains AMD ROCm tutorials for training, fine-tuning, and inference. ROCm supports programming models, such as OpenMP and OpenCL, and includes all necessary open
source software compilers, debuggers, and libraries. ROCm is fully integrated into machine learning
(ML) frameworks, such as PyTorch and TensorFlow.

::::{grid} 1 2 2 2
:gutter: 3
:class-container: rocm-doc-grid


:::{grid-item-card} How to
:class-body: rocm-card-banner rocm-hue-12

* [Use hipDF](./how-to/use_hipDF.rst)
* [Use hipGraph](./how-to/use_hipGraph.rst)
* [Use hipMM](./how-to/use_hipMM.rst)
* [Use hipRAFT](./how-to/use_hipRAFT.rst)

:::

:::{grid-item-card} Conceptual
:class-body: rocm-card-banner rocm-hue-8

* [Data exploration](./conceptual/data_exploration.rst)
* [Data processing](./conceptual/data_processing.rst)
* [Data modeling](./conceptual/data_modeling.rst)
:::

::::
