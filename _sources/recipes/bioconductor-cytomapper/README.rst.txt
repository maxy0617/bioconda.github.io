:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cytomapper'
.. highlight: bash

bioconductor-cytomapper
=======================

.. conda:recipe:: bioconductor-cytomapper
   :replaces_section_title:
   :noindex:

   Visualization of highly multiplexed imaging cytometry data in R

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/cytomapper.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-cytomapper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cytomapper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cytomapper/meta.yaml>`_

   Highly multiplexed imaging cytometry acquires the single\-cell expression of selected proteins in a spatially\-resolved fashion. These measurements can be visualized across multiple length\-scales. First\, pixel\-level intensities represent the spatial distributions of feature expression with highest resolution. Second\, after segmentation\, expression values or cell\-level metadata \(e.g. cell\-type information\) can be visualized on segmented cell areas. This package contains functions for the visualization of multiplexed read\-outs and cell\-level information obtained by multiplexed imaging cytometry. The main functions of this package allow 1. the visualization of pixel\-level information across multiple channels and 2. the display of cell\-level information \(expression and\/or metadata\) on segmentation masks.


.. conda:package:: bioconductor-cytomapper

   |downloads_bioconductor-cytomapper| |docker_bioconductor-cytomapper|

   :versions:
      
      

      ``1.0.0-0``

      

   
   :depends bioconductor-ebimage: ``>=4.30.0,<4.31.0``
   :depends bioconductor-s4vectors: ``>=0.26.0,<0.27.0``
   :depends bioconductor-singlecellexperiment: ``>=1.10.0,<1.11.0``
   :depends bioconductor-summarizedexperiment: ``>=1.18.0,<1.19.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-raster: 
   :depends r-rcolorbrewer: 
   :depends r-viridis: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cytomapper

   and update with::

      conda update bioconductor-cytomapper

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cytomapper:<tag>

   (see `bioconductor-cytomapper/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cytomapper| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cytomapper.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cytomapper
   :alt:   (downloads)
.. |docker_bioconductor-cytomapper| image:: https://quay.io/repository/biocontainers/bioconductor-cytomapper/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cytomapper
.. _`bioconductor-cytomapper/tags`: https://quay.io/repository/biocontainers/bioconductor-cytomapper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cytomapper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cytomapper/README.html