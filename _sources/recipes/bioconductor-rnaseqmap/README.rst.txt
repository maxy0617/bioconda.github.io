:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnaseqmap'
.. highlight: bash

bioconductor-rnaseqmap
======================

.. conda:recipe:: bioconductor-rnaseqmap
   :replaces_section_title:
   :noindex:

   rnaSeq secondary analyses

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/rnaSeqMap.html
   :license: GPL-2
   :recipe: /`bioconductor-rnaseqmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaseqmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaseqmap/meta.yaml>`_
   :links: biotools: :biotools:`rnaseqmap`, doi: :doi:`10.1186/1471-2105-12-200`

   The rnaSeqMap library provides classes and functions to analyze the RNA\-sequencing data using the coverage profiles in multiple samples at a time


.. conda:package:: bioconductor-rnaseqmap

   |downloads_bioconductor-rnaseqmap| |docker_bioconductor-rnaseqmap|

   :versions:
      
      

      ``2.46.0-0``,  ``2.44.0-0``,  ``2.42.0-1``,  ``2.40.0-0``,  ``2.38.0-0``,  ``2.36.0-0``,  ``2.34.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.48.0,<2.49.0``
   :depends bioconductor-deseq: ``>=1.39.0,<1.40.0``
   :depends bioconductor-edger: ``>=3.30.0,<3.31.0``
   :depends bioconductor-genomicalignments: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-rsamtools: ``>=2.4.0,<2.5.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=7.3.0``
   :depends liblapack: ``>=3.8.0,<3.9.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dbi: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnaseqmap

   and update with::

      conda update bioconductor-rnaseqmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnaseqmap:<tag>

   (see `bioconductor-rnaseqmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnaseqmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnaseqmap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnaseqmap
   :alt:   (downloads)
.. |docker_bioconductor-rnaseqmap| image:: https://quay.io/repository/biocontainers/bioconductor-rnaseqmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnaseqmap
.. _`bioconductor-rnaseqmap/tags`: https://quay.io/repository/biocontainers/bioconductor-rnaseqmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnaseqmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnaseqmap/README.html