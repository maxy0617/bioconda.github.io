:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-damefinder'
.. highlight: bash

bioconductor-damefinder
=======================

.. conda:recipe:: bioconductor-damefinder
   :replaces_section_title:
   :noindex:

   Finds DAMEs \- Differential Allelicly MEthylated regions

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/DAMEfinder.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-damefinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-damefinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-damefinder/meta.yaml>`_

   \'DAMEfinder\' offers functionality for taking methtuple or bismark outputs to calculate ASM scores and compute DAMEs. It also offers nice visualization of methyl\-circle plots.


.. conda:package:: bioconductor-damefinder

   |downloads_bioconductor-damefinder| |docker_bioconductor-damefinder|

   :versions:
      
      

      ``1.0.1-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-biostrings: ``>=2.56.0,<2.57.0``
   :depends bioconductor-bumphunter: ``>=1.30.0,<1.31.0``
   :depends bioconductor-genomeinfodb: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicalignments: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-limma: ``>=3.44.0,<3.45.0``
   :depends bioconductor-rsamtools: ``>=2.4.0,<2.5.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-ggplot2: 
   :depends r-plyr: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-stringr: 
   :depends r-vcfr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-damefinder

   and update with::

      conda update bioconductor-damefinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-damefinder:<tag>

   (see `bioconductor-damefinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-damefinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-damefinder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-damefinder
   :alt:   (downloads)
.. |docker_bioconductor-damefinder| image:: https://quay.io/repository/biocontainers/bioconductor-damefinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-damefinder
.. _`bioconductor-damefinder/tags`: https://quay.io/repository/biocontainers/bioconductor-damefinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-damefinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-damefinder/README.html