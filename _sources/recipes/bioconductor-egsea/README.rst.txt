:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-egsea'
.. highlight: bash

bioconductor-egsea
==================

.. conda:recipe:: bioconductor-egsea
   :replaces_section_title:
   :noindex:

   Ensemble of Gene Set Enrichment Analyses

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/EGSEA.html
   :license: GPL-3
   :recipe: /`bioconductor-egsea <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-egsea>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-egsea/meta.yaml>`_
   :links: biotools: :biotools:`egsea`

   This package implements the Ensemble of Gene Set Enrichment Analyses \(EGSEA\) method for gene set testing.


.. conda:package:: bioconductor-egsea

   |downloads_bioconductor-egsea| |docker_bioconductor-egsea|

   :versions:
      
      

      ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.50.0,<1.51.0``
   :depends bioconductor-biobase: ``>=2.48.0,<2.49.0``
   :depends bioconductor-edger: ``>=3.30.0,<3.31.0``
   :depends bioconductor-egseadata: ``>=1.16.0,<1.17.0``
   :depends bioconductor-gage: ``>=2.37.0,<2.38.0``
   :depends bioconductor-glimma: ``>=1.16.0,<1.17.0``
   :depends bioconductor-globaltest: ``>=5.42.0,<5.43.0``
   :depends bioconductor-gsva: ``>=1.36.0,<1.37.0``
   :depends bioconductor-limma: ``>=3.44.0,<3.45.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.11.0,<3.12.0``
   :depends bioconductor-org.mm.eg.db: ``>=3.11.0,<3.12.0``
   :depends bioconductor-org.rn.eg.db: ``>=3.11.0,<3.12.0``
   :depends bioconductor-padog: ``>=1.30.0,<1.31.0``
   :depends bioconductor-pathview: ``>=1.28.0,<1.29.0``
   :depends bioconductor-safe: ``>=3.27.0,<3.28.0``
   :depends bioconductor-topgo: ``>=2.40.0,<2.41.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dt: 
   :depends r-ggplot2: ``>=1.0.0``
   :depends r-gplots: ``>=2.14.2``
   :depends r-htmlutils: ``>=0.1.5``
   :depends r-htmlwidgets: 
   :depends r-hwriter: ``>=1.2.2``
   :depends r-metap: 
   :depends r-plotly: 
   :depends r-rcolorbrewer: 
   :depends r-stringi: ``>=0.5.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-egsea

   and update with::

      conda update bioconductor-egsea

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-egsea:<tag>

   (see `bioconductor-egsea/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-egsea| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-egsea.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-egsea
   :alt:   (downloads)
.. |docker_bioconductor-egsea| image:: https://quay.io/repository/biocontainers/bioconductor-egsea/status
   :target: https://quay.io/repository/biocontainers/bioconductor-egsea
.. _`bioconductor-egsea/tags`: https://quay.io/repository/biocontainers/bioconductor-egsea?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-egsea/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-egsea/README.html