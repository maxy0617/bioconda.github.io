:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mutationalpatterns'
.. highlight: bash

bioconductor-mutationalpatterns
===============================

.. conda:recipe:: bioconductor-mutationalpatterns
   :replaces_section_title:
   :noindex:

   Comprehensive genome\-wide analysis of mutational processes

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/MutationalPatterns.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-mutationalpatterns <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mutationalpatterns>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mutationalpatterns/meta.yaml>`_

   An extensive toolset for the characterization and visualization of a wide range of mutational patterns in base substitution catalogs.


.. conda:package:: bioconductor-mutationalpatterns

   |downloads_bioconductor-mutationalpatterns| |docker_bioconductor-mutationalpatterns|

   :versions:
      
      

      ``2.0.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.8.0-0``,  ``1.6.1-0``,  ``1.4.3-0``,  ``1.4.1-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-biostrings: ``>=2.56.0,<2.57.0``
   :depends bioconductor-genomeinfodb: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends bioconductor-variantannotation: ``>=1.34.0,<1.35.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: ``>=0.9.2``
   :depends r-ggdendro: ``>=0.1-20``
   :depends r-ggplot2: ``>=2.1.0``
   :depends r-nmf: ``>=0.20.6``
   :depends r-plyr: ``>=1.8.3``
   :depends r-pracma: ``>=1.8.8``
   :depends r-reshape2: ``>=1.4.1``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mutationalpatterns

   and update with::

      conda update bioconductor-mutationalpatterns

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mutationalpatterns:<tag>

   (see `bioconductor-mutationalpatterns/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mutationalpatterns| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mutationalpatterns.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mutationalpatterns
   :alt:   (downloads)
.. |docker_bioconductor-mutationalpatterns| image:: https://quay.io/repository/biocontainers/bioconductor-mutationalpatterns/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mutationalpatterns
.. _`bioconductor-mutationalpatterns/tags`: https://quay.io/repository/biocontainers/bioconductor-mutationalpatterns?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mutationalpatterns/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mutationalpatterns/README.html