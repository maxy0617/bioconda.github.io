:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cexor'
.. highlight: bash

bioconductor-cexor
==================

.. conda:recipe:: bioconductor-cexor
   :replaces_section_title:
   :noindex:

   An R package to uncover high\-resolution protein\-DNA interactions in ChIP\-exo replicates

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/CexoR.html
   :license: Artistic-2.0 | GPL-2 + file LICENSE
   :recipe: /`bioconductor-cexor <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cexor>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cexor/meta.yaml>`_
   :links: biotools: :biotools:`cexor`, doi: :doi:`10.14806/ej.21.0.837`

   Strand specific peak\-pair calling in ChIP\-exo replicates. The cumulative Skellam distribution function \(package \'skellam\'\) is used to detect significant normalised count differences of opposed sign at each DNA strand \(peak\-pairs\). Irreproducible discovery rate for overlapping peak\-pairs across biological replicates is estimated using the package \'idr\'.


.. conda:package:: bioconductor-cexor

   |downloads_bioconductor-cexor| |docker_bioconductor-cexor|

   :versions:
      
      

      ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.8.0-0``

      

   
   :depends bioconductor-genomation: ``>=1.20.0,<1.21.0``
   :depends bioconductor-genomeinfodb: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-rsamtools: ``>=2.4.0,<2.5.0``
   :depends bioconductor-rtracklayer: ``>=1.48.0,<1.49.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-idr: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cexor

   and update with::

      conda update bioconductor-cexor

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cexor:<tag>

   (see `bioconductor-cexor/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cexor| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cexor.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cexor
   :alt:   (downloads)
.. |docker_bioconductor-cexor| image:: https://quay.io/repository/biocontainers/bioconductor-cexor/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cexor
.. _`bioconductor-cexor/tags`: https://quay.io/repository/biocontainers/bioconductor-cexor?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cexor/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cexor/README.html