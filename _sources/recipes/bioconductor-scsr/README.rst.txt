:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scsr'
.. highlight: bash

bioconductor-scsr
=================

.. conda:recipe:: bioconductor-scsr
   :replaces_section_title:
   :noindex:

   SiRNA correction for seed mediated off\-target effect

   :homepage: https://bioconductor.org/packages/3.11/bioc/html/scsR.html
   :license: GPL-2
   :recipe: /`bioconductor-scsr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scsr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scsr/meta.yaml>`_

   Corrects genome\-wide siRNA screens for seed mediated off\-target effect. Suitable functions to identify the effective seeds\/miRNAs and to visualize their effect are also provided in the package.


.. conda:package:: bioconductor-scsr

   |downloads_bioconductor-scsr| |docker_bioconductor-scsr|

   :versions:
      
      

      ``1.23.0-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.18.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.34.0,<0.35.0``
   :depends bioconductor-biostrings: ``>=2.56.0,<2.57.0``
   :depends bioconductor-iranges: ``>=2.22.0,<2.23.0``
   :depends bioconductor-stringdb: ``>=2.0.0,<2.1.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-hash: 
   :depends r-plyr: 
   :depends r-rcolorbrewer: 
   :depends r-sqldf: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scsr

   and update with::

      conda update bioconductor-scsr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scsr:<tag>

   (see `bioconductor-scsr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scsr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scsr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scsr
   :alt:   (downloads)
.. |docker_bioconductor-scsr| image:: https://quay.io/repository/biocontainers/bioconductor-scsr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scsr
.. _`bioconductor-scsr/tags`: https://quay.io/repository/biocontainers/bioconductor-scsr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scsr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scsr/README.html