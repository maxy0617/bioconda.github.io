:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ihwpaper'
.. highlight: bash

bioconductor-ihwpaper
=====================

.. conda:recipe:: bioconductor-ihwpaper
   :replaces_section_title:
   :noindex:

   Reproduce figures in IHW paper

   :homepage: https://bioconductor.org/packages/3.11/data/experiment/html/IHWpaper.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ihwpaper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ihwpaper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ihwpaper/meta.yaml>`_

   This package conveniently wraps all functions needed to reproduce the figures in the IHW paper \(https\:\/\/www.nature.com\/articles\/nmeth.3885\) and the latest arXiv preprint available under http\:\/\/arxiv.org\/abs\/1701.05179. Thus it is a companion package to the Bioconductor IHW package.


.. conda:package:: bioconductor-ihwpaper

   |downloads_bioconductor-ihwpaper| |docker_bioconductor-ihwpaper|

   :versions:
      
      

      ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.10.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.48.0,<2.49.0``
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-biocparallel: ``>=1.22.0,<1.23.0``
   :depends bioconductor-deseq2: ``>=1.28.0,<1.29.0``
   :depends bioconductor-genefilter: ``>=1.70.0,<1.71.0``
   :depends bioconductor-ihw: ``>=1.16.0,<1.17.0``
   :depends bioconductor-qvalue: ``>=2.20.0,<2.21.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends curl: ``>=7.69.1,<8.0a0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libcxx: ``>=9.0.1``
   :depends liblapack: ``>=3.8.0,<3.9.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-dplyr: 
   :depends r-fdrtool: 
   :depends r-ggplot2: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ihwpaper

   and update with::

      conda update bioconductor-ihwpaper

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ihwpaper:<tag>

   (see `bioconductor-ihwpaper/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ihwpaper| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ihwpaper.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ihwpaper
   :alt:   (downloads)
.. |docker_bioconductor-ihwpaper| image:: https://quay.io/repository/biocontainers/bioconductor-ihwpaper/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ihwpaper
.. _`bioconductor-ihwpaper/tags`: https://quay.io/repository/biocontainers/bioconductor-ihwpaper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ihwpaper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ihwpaper/README.html