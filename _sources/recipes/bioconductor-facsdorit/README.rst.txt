:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-facsdorit'
.. highlight: bash

bioconductor-facsdorit
======================

.. conda:recipe:: bioconductor-facsdorit
   :replaces_section_title:
   :noindex:

   DKFZ FACS example data

   :homepage: https://bioconductor.org/packages/3.11/data/experiment/html/facsDorit.html
   :license: GPL-2
   :recipe: /`bioconductor-facsdorit <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-facsdorit>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-facsdorit/meta.yaml>`_

   FACS example data for cell\-based assays. This data is used in the examples and vignettes of the package prada.


.. conda:package:: bioconductor-facsdorit

   |downloads_bioconductor-facsdorit| |docker_bioconductor-facsdorit|

   :versions:
      
      

      ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-1``,  ``1.24.0-0``

      

   
   :depends bioconductor-prada: ``>=1.63.0,<1.64.0``
   :depends curl: ``>=7.69.1,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-facsdorit

   and update with::

      conda update bioconductor-facsdorit

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-facsdorit:<tag>

   (see `bioconductor-facsdorit/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-facsdorit| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-facsdorit.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-facsdorit
   :alt:   (downloads)
.. |docker_bioconductor-facsdorit| image:: https://quay.io/repository/biocontainers/bioconductor-facsdorit/status
   :target: https://quay.io/repository/biocontainers/bioconductor-facsdorit
.. _`bioconductor-facsdorit/tags`: https://quay.io/repository/biocontainers/bioconductor-facsdorit?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-facsdorit/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-facsdorit/README.html