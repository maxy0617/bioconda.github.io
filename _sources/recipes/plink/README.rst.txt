:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'plink'
.. highlight: bash

plink
=====

.. conda:recipe:: plink
   :replaces_section_title:
   :noindex:

   Whole genome association analysis toolset\, designed to perform a range of basic\, large\-scale analyses in a computationally efficient manner.

   :homepage: https://www.cog-genomics.org/plink2
   :license: GPL
   :recipe: /`plink <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/plink>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/plink/meta.yaml>`_

   


.. conda:package:: plink

   |downloads_plink| |docker_plink|

   :versions:
      
      

      ``1.90b6.12-1``,  ``1.90b6.12-0``,  ``1.90b5-1``,  ``1.90b5-0``,  ``1.90b4-3``,  ``1.90b4-2``,  ``1.90b4-1``,  ``1.90b4-0``

      

   
   :depends libgcc-ng: ``>=7.5.0``
   :depends libgfortran-ng: ``>=7,<8.0a0``
   :depends libstdcxx-ng: ``>=7.5.0``
   :depends openblas: ``>=0.3.6,<0.3.7.0a0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install plink

   and update with::

      conda update plink

   or use the docker container::

      docker pull quay.io/biocontainers/plink:<tag>

   (see `plink/tags`_ for valid values for ``<tag>``)


.. |downloads_plink| image:: https://img.shields.io/conda/dn/bioconda/plink.svg?style=flat
   :target: https://anaconda.org/bioconda/plink
   :alt:   (downloads)
.. |docker_plink| image:: https://quay.io/repository/biocontainers/plink/status
   :target: https://quay.io/repository/biocontainers/plink
.. _`plink/tags`: https://quay.io/repository/biocontainers/plink?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/plink/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/plink/README.html