.. meta::
    :description: ROCm compatibility matrix
    :keywords: GPU, architecture, hardware, compatibility, system, requirements, components, libraries

**************************************************************************************
Compatibility matrix
**************************************************************************************

Use this matrix to view the ROCm-DS compatibility and system requirements across successive major and minor releases.

Accelerators and GPUs listed in the following table support compute workloads (no display
information or graphics). If you’re using ROCm with AMD Radeon or Radeon Pro GPUs for graphics
workloads, see the `Use ROCm on Radeon GPU documentation
<https://rocm.docs.amd.com/projects/radeon/en/latest/docs/compatibility.html>`_ to verify
compatibility and system requirements.

.. |br| raw:: html

   <br/>

.. container:: format-big-table

  .. csv-table::
      :header: "ROCm-DS Version","1.0.0"
      :stub-columns: 1

      :ref:`Operating systems & kernels <OS-kernel-versions>`,Ubuntu 24.04.2
      ,"RHEL 9.5, 9.4"
      ,RHEL 8.10
      ,"SLES 15 SP6"
      ,Oracle Linux 8.10 [#mi300x]_
      ,Debian 12 [#mi300x]_
      ,Azure Linux 3.0 [#mi300x]_
      ,.. _architecture-support-compatibility-matrix:
      :doc:`Architecture <rocm-install-on-linux:reference/system-requirements>`,CDNA3
      ,CDNA2
      ,CDNA
      ,RDNA3
      ,RDNA2
      ,.. _gpu-support-compatibility-matrix:
      :doc:`GPU / LLVM target <rocm-install-on-linux:reference/system-requirements>`,gfx1100
      ,gfx1030
      ,gfx942
      ,gfx90a
      ,gfx908
      ,
      THIRD PARTY COMMS,.. _thirdpartycomms-support-compatibility-matrix:
      `UCC <https://github.com/ROCm/ucc>`_,>=1.3.0
      `UCX <https://github.com/ROCm/ucx>`_,>=1.15.0
      ,
      THIRD PARTY ALGORITHM,.. _thirdpartyalgorithm-support-compatibility-matrix:
      Thrust,2.3.2
      CUB,2.3.2
      ,
      KMD & USER SPACE [#kfd_support]_,.. _kfd-userspace-support-compatibility-matrix:
      Tested user space versions,"6.3.x, 6.2.x, 6.1.x"
      ,
      Packages,.. _mllibs-support-compatibility-matrix:
      hipDF,1.1.0
      hipGraph,2.11.0
      hipMM,3.3.0
      hipRAFT,3.1.0

.. rubric:: Footnotes

.. [#mi300x] Oracle Linux, Debian, and Azure Linux are supported only on AMD Instinct MI300X.
.. [#mi300_620] **For ROCm 6.2.0** - MI300X (gfx942) is supported on listed operating systems *except* Ubuntu 22.04.5 [6.8 HWE] and Ubuntu 22.04.4 [6.5 HWE].
.. [#kfd_support] ROCm provides forward and backward compatibility between the AMD Kernel-mode GPU Driver (KMD) and its user space software for +/- 2 releases. These are the compatibility combinations that are currently supported.


.. _OS-kernel-versions:

Operating systems and kernel versions
*************************************

Use this lookup table to confirm which operating system and kernel versions are supported with ROCm.

.. csv-table::
   :header: "OS", "Version", "Kernel"
   :widths: 40, 20, 40
   :stub-columns: 1

   `Ubuntu <https://ubuntu.com/about/release-cycle#ubuntu-kernel-release-cycle>`_, 24.04.2, "6.8 GA, 6.11 HWE"
   , 24.04, "6.8 GA"
   ,,
   `Ubuntu <https://ubuntu.com/about/release-cycle#ubuntu-kernel-release-cycle>`_, 22.04.5, "5.15 GA, 6.8 HWE"
   , 22.04.4, "5.15 GA, 6.5 HWE"
   ,,
   `Red Hat Enterprise Linux (RHEL 9) <https://access.redhat.com/articles/3078#RHEL9>`_, 9.5, 5.14.0
   ,9.4, 5.14.0
   ,9.3, 5.14.0
   ,,
   `Red Hat Enterprise Linux (RHEL 8) <https://access.redhat.com/articles/3078#RHEL8>`_, 8.10, 4.18.0
   ,8.9, 4.18.0
   ,,
   `SUSE Linux Enterprise Server (SLES) <https://www.suse.com/support/kb/doc/?id=000019587#SLE15SP4>`_, 15 SP6, 6.4.0
   ,15 SP5, 5.14.21
   ,,
   `Oracle Linux <https://blogs.oracle.com/scoter/post/oracle-linux-and-unbreakable-enterprise-kernel-uek-releases>`_, 8.10, 5.15.0
   ,8.9, 5.15.0
   ,,
   `Debian <https://www.debian.org/download>`_,12, 6.1
   ,,
   `Azure Linux <https://techcommunity.microsoft.com/blog/linuxandopensourceblog/azure-linux-3-0-now-in-preview-on-azure-kubernetes-service-v1-31/4287229>`_,3.0, 6.6
   ,,

..
   Footnotes and ref anchors in below historical tables should be appended with "-past-60", to differentiate from the
   footnote references in the above, latest, compatibility matrix.  It also allows to easily find & replace.
   An easy way to work is to download the historical.CSV file, and update open it in excel. Then when content is ready,
   delete the columns you don't need, to build the current compatibility matrix to use in above table.  Find & replace all
   instances of "-past-60" to make it ready for above table.


