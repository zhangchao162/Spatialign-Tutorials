Welcome to Spatialign's documentation!
===================================

Spatialign: An Unsupervised Method for Integration and Denoising Gene Expression Profiles in Spatially Resolved Transcriptomics
=====================================================================================================================================================

.. toctree::
   :maxdepth: 1
   :caption: Contents

   Installation
   Tutorial

Overview
=========================================================
The integration of multiple spatially resolved transcriptomics (SRT) datasets can enhance the statistical power to investigate biological phenomena. However, batch effects can lead to irregular data distribution among tissue sections, potentially compromising the reliability of downstream analyses. While various data integration methods have been developed, most are designed for scRNA-seq datasets without considering spatial context. Therefore, we propose Spatialign, an unsupervised method that utilizes spatial embedding and across-domain adaptation contrastive learning to align latent representations and denoise gene expression profiles. We perform benchmarking analyses on four publicly available SRT datasets, demonstrating the superior performance of Spatialign compared to state-of-the-art methods. Furthermore, Spatialign is shown to be applicable to SRT datasets from diverse platforms. Overall, our results highlight the potential of Spatialign to improve the reliability of downstream analyses in spatially resolved transcriptomics studies.