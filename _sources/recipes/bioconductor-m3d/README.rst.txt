:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-m3d'
.. highlight: bash

bioconductor-m3d
================

.. conda:recipe:: bioconductor-m3d
   :replaces_section_title:
   :noindex:

   Identifies differentially methylated regions across testing groups

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/M3D.html
   :license: Artistic License 2.0
   :recipe: /`bioconductor-m3d <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-m3d>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-m3d/meta.yaml>`_
   :links: biotools: :biotools:`m3d`, doi: :doi:`10.1093/bioinformatics/btu749`

   This package identifies statistically significantly differentially methylated regions of CpGs. It uses kernel methods \(the Maximum Mean Discrepancy\) to measure differences in methylation profiles\, and relates these to inter\-replicate changes\, whilst accounting for variation in coverage profiles.


.. conda:package:: bioconductor-m3d

   |downloads_bioconductor-m3d| |docker_bioconductor-m3d|

   :versions:
      
      

      ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-biseq: ``>=1.28.0,<1.29.0``
   :depends bioconductor-genomicranges: ``>=1.40.0,<1.41.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=7.3.0``
   :depends liblapack: ``>=3.8.0,<3.9.0a0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-m3d

   and update with::

      conda update bioconductor-m3d

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-m3d:<tag>

   (see `bioconductor-m3d/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-m3d| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-m3d.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-m3d
   :alt:   (downloads)
.. |docker_bioconductor-m3d| image:: https://quay.io/repository/biocontainers/bioconductor-m3d/status
   :target: https://quay.io/repository/biocontainers/bioconductor-m3d
.. _`bioconductor-m3d/tags`: https://quay.io/repository/biocontainers/bioconductor-m3d?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-m3d/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-m3d/README.html