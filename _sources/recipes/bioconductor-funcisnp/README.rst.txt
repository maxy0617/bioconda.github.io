:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-funcisnp'
.. highlight: bash

bioconductor-funcisnp
=====================

.. conda:recipe:: bioconductor-funcisnp
   :replaces_section_title:
   :noindex:

   Integrating Functional Non\-coding Datasets with Genetic Association Studies to Identify Candidate Regulatory SNPs

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/FunciSNP.html
   :license: GPL-3
   :recipe: /`bioconductor-funcisnp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-funcisnp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-funcisnp/meta.yaml>`_

   FunciSNP integrates information from GWAS\, 1000genomes and chromatin feature to identify functional SNP in coding or non\-coding regions.


.. conda:package:: bioconductor-funcisnp

   |downloads_bioconductor-funcisnp| |docker_bioconductor-funcisnp|

   :versions:
      
      

      ``1.32.0-0``,  ``1.30.0-1``,  ``1.28.0-1``,  ``1.26.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.48.0,<2.49.0``
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-chippeakanno: ``>=3.22.0,<3.23.0``
   :depends bioconductor-funcisnp.data: ``>=1.21.0,<1.22.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-rsamtools: ``>=2.4.0,<2.5.0``
   :depends bioconductor-rtracklayer: ``>=1.48.0,<1.49.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-snpstats: ``>=1.38.0,<1.39.0``
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: ``>=3.2.0,<3.3.0``
   :depends bioconductor-variantannotation: ``>=1.34.0,<1.35.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: ``>=0.9.0``
   :depends r-plyr: 
   :depends r-reshape: ``>=0.8.4``
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-funcisnp

   and update with::

      conda update bioconductor-funcisnp

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-funcisnp:<tag>

   (see `bioconductor-funcisnp/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-funcisnp| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-funcisnp.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-funcisnp
   :alt:   (downloads)
.. |docker_bioconductor-funcisnp| image:: https://quay.io/repository/biocontainers/bioconductor-funcisnp/status
   :target: https://quay.io/repository/biocontainers/bioconductor-funcisnp
.. _`bioconductor-funcisnp/tags`: https://quay.io/repository/biocontainers/bioconductor-funcisnp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-funcisnp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-funcisnp/README.html