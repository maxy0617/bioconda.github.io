:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-circrnaprofiler'
.. highlight: bash

bioconductor-circrnaprofiler
============================

.. conda:recipe:: bioconductor-circrnaprofiler
   :replaces_section_title:
   :noindex:

   circRNAprofiler\: An R\-Based Computational Framework for the Downstream Analysis of Circular RNAs

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/circRNAprofiler.html
   :license: GPL-3
   :recipe: /`bioconductor-circrnaprofiler <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-circrnaprofiler>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-circrnaprofiler/meta.yaml>`_

   R\-based computational framework for a comprehensive in silico analysis of circRNAs. This computational framework allows to combine and analyze circRNAs previously detected by multiple publicly available annotation\-based circRNA detection tools. It covers different aspects of circRNAs analysis from differential expression analysis\, evolutionary conservation\, biogenesis to functional analysis.


.. conda:package:: bioconductor-circrnaprofiler

   |downloads_bioconductor-circrnaprofiler| |docker_bioconductor-circrnaprofiler|

   :versions:
      
      

      ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.20.0,<2.21.0``
   :depends bioconductor-biostrings: ``>=2.56.0,<2.57.0``
   :depends bioconductor-bsgenome: ``>=1.56.0,<1.57.0``
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg19: ``>=1.4.0,<1.5.0``
   :depends bioconductor-deseq2: ``>=1.28.0,<1.29.0``
   :depends bioconductor-edger: ``>=3.30.0,<3.31.0``
   :depends bioconductor-genomeinfodb: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-gwascat: ``>=2.20.0,<2.21.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-rtracklayer: ``>=1.48.0,<1.49.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-magrittr: 
   :depends r-r.utils: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-rlang: 
   :depends r-seqinr: 
   :depends r-stringi: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-circrnaprofiler

   and update with::

      conda update bioconductor-circrnaprofiler

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-circrnaprofiler:<tag>

   (see `bioconductor-circrnaprofiler/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-circrnaprofiler| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-circrnaprofiler.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-circrnaprofiler
   :alt:   (downloads)
.. |docker_bioconductor-circrnaprofiler| image:: https://quay.io/repository/biocontainers/bioconductor-circrnaprofiler/status
   :target: https://quay.io/repository/biocontainers/bioconductor-circrnaprofiler
.. _`bioconductor-circrnaprofiler/tags`: https://quay.io/repository/biocontainers/bioconductor-circrnaprofiler?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-circrnaprofiler/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-circrnaprofiler/README.html