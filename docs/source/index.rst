Welcome to Spatialign's documentation!
=======================================

.. toctree::
   :maxdepth: 1
   :caption: Contents

   Installation
   Tutorial-1-simulate-datasets
   Tutorial-2-Integrate-datasets-measured-by-different-platforms

Overview
========
Integrative analysis of spatially resolved transcriptomics (SRT) datasets is crucial for gaining a comprehensive understanding of complex biological systems. However, analyzing these datasets together presents challenges, particularly when the datasets are measured by various technologies at different times, resulting in batch effects that may compromise integration. Most existing integration methods are designed for scRNA-seq datasets while few methods utilize the available spatial information for SRT datasets. Here, we present Spatialign, an algorithm that employs spatial embedding and across-domain adaptation to align biological effects in a shared space, while simultaneously enhancing gene expression profiles in original space. In benchmarking analyses, we demonstrate the superior performance of Spatialign compared to previous algorithms. Using structure-specific datasets, we demonstrate that, Spatialign can effectively capture the unique characteristics of tissue sections. Moreover, applies to mouse embryogenesis datasets, Spatialign further showcases its facilitating for downstream analysis, particularly for the analytical methods that require original gene space.