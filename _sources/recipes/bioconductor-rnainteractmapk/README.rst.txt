:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnainteractmapk'
.. highlight: bash

bioconductor-rnainteractmapk
============================

.. conda:recipe:: bioconductor-rnainteractmapk
   :replaces_section_title:
   :noindex:

   Mapping of Signalling Networks through Synthetic Genetic Interaction Analysis by RNAi

   :homepage: https://bioconductor.org/packages/3.11/data/experiment/html/RNAinteractMAPK.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rnainteractmapk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnainteractmapk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnainteractmapk/meta.yaml>`_

   This package includes all data used in the paper \-Mapping of Signalling Networks through Synthetic Genetic Interaction Analysis by RNAi\- by Horn\, Sandmann\, Fischer et al..\, Nat. Methods\, 2011. The package vignette shows the R code to reproduce all figures in the paper.


.. conda:package:: bioconductor-rnainteractmapk

   |downloads_bioconductor-rnainteractmapk| |docker_bioconductor-rnainteractmapk|

   :versions:
      
      

      ``1.25.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.0-0``

      

   
   :depends bioconductor-genefilter: ``>=1.70.0,<1.71.0``
   :depends bioconductor-rnainteract: ``>=1.36.0,<1.37.0``
   :depends curl: ``>=7.69.1,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-fields: 
   :depends r-gdata: 
   :depends r-mass: 
   :depends r-sparselda: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnainteractmapk

   and update with::

      conda update bioconductor-rnainteractmapk

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnainteractmapk:<tag>

   (see `bioconductor-rnainteractmapk/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnainteractmapk| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnainteractmapk.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnainteractmapk
   :alt:   (downloads)
.. |docker_bioconductor-rnainteractmapk| image:: https://quay.io/repository/biocontainers/bioconductor-rnainteractmapk/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnainteractmapk
.. _`bioconductor-rnainteractmapk/tags`: https://quay.io/repository/biocontainers/bioconductor-rnainteractmapk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnainteractmapk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnainteractmapk/README.html