.. meta::
  :description: hipGRAPH documentation and API reference library
  :keywords: hipGRAPH, hipgraph, ROCm, API, documentation

.. _hipGRAPH-index:

********************************************************************
hipGRAPH documentation
********************************************************************

hipGRAPH is a GRAPH marshalling library with multiple supported backends. It is a wrapper between your application and a
'worker' GRAPH library. hipGRAPH exports an interface that doesn't require the client to change, regardless of the chosen
backend. Currently, hipGRAPH supports ROCm (via hipgraph) and CUDA (via cuGraph) back ends.

The code is open and hosted at: https://github.com/ROCm/hipGRAPH

The hipGRAPH documentation is structured as follows:

.. grid:: 2
  :gutter: 3

  .. grid-item-card:: Installation

    * :ref:`linux-install`

  .. grid-item-card:: How to

    * :ref:`hipgraph_docs`
    * :ref:`design`
    * :ref:`contributing-to`

  .. grid-item-card:: API reference

    * :ref:`hipgraph_centrality_functions_` e.g. PageRank, Betweeness.
    * :ref:`hipgraph_community_functions_` e.g. Triangle Count, Louvain, Leiden.
    * :ref:`hipgraph_core_functions_` e.g. Core, K-Core.
    * :ref:`hipgraph_labeling_functions_` e.g. Weakly/Strongly Connected Components.
    * :ref:`hipgraph_sampling_functions_` e.g. Random Walks, Uniform Neighbor Sampling.
    * :ref:`hipgraph_similarity_functions_` e.g. Jaccard, Sorenson.
    * :ref:`hipgraph_traversal_functions_` e.g. BFS, SSPP.

  .. grid-item-card:: Python reference

    modules
