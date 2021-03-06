:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scrnaseq'
.. highlight: bash

bioconductor-scrnaseq
=====================

.. conda:recipe:: bioconductor-scrnaseq
   :replaces_section_title:
   :noindex:

   Collection of Public Single\-Cell RNA\-Seq Datasets

   :homepage: https://bioconductor.org/packages/3.11/data/experiment/html/scRNAseq.html
   :license: CC0
   :recipe: /`bioconductor-scrnaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scrnaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scrnaseq/meta.yaml>`_

   Gene\-level counts for a collection of public scRNA\-seq datasets\, provided as SingleCellExperiment objects with cell\- and gene\-level metadata.


.. conda:package:: bioconductor-scrnaseq

   |downloads_bioconductor-scrnaseq| |docker_bioconductor-scrnaseq|

   :versions:
      
      

      ``2.2.0-0``,  ``1.99.8-0``,  ``1.10.0-1``,  ``1.8.0-0``,  ``1.6.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-experimenthub: ``>=1.14.0,<1.15.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-singlecellexperiment: ``>=1.10.0,<1.11.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends curl: ``>=7.69.1,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scrnaseq

   and update with::

      conda update bioconductor-scrnaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scrnaseq:<tag>

   (see `bioconductor-scrnaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scrnaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scrnaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scrnaseq
   :alt:   (downloads)
.. |docker_bioconductor-scrnaseq| image:: https://quay.io/repository/biocontainers/bioconductor-scrnaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scrnaseq
.. _`bioconductor-scrnaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-scrnaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scrnaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scrnaseq/README.html