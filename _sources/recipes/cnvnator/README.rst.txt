:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'cnvnator'
.. highlight: bash

cnvnator
========

.. conda:recipe:: cnvnator
   :replaces_section_title:
   :noindex:

   Tool for calling copy number variations.

   :homepage: https://github.com/abyzovlab/CNVnator
   :license: MIT
   :recipe: /`cnvnator <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cnvnator>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cnvnator/meta.yaml>`_

   


.. conda:package:: cnvnator

   |downloads_cnvnator| |docker_cnvnator|

   :versions:
      
      

      ``0.4.1-0``

      

   
   :depends htslib: ``>=1.10.2,<1.11.0a0``
   :depends libgcc-ng: ``>=7.3.0``
   :depends root: 
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install cnvnator

   and update with::

      conda update cnvnator

   or use the docker container::

      docker pull quay.io/biocontainers/cnvnator:<tag>

   (see `cnvnator/tags`_ for valid values for ``<tag>``)


.. |downloads_cnvnator| image:: https://img.shields.io/conda/dn/bioconda/cnvnator.svg?style=flat
   :target: https://anaconda.org/bioconda/cnvnator
   :alt:   (downloads)
.. |docker_cnvnator| image:: https://quay.io/repository/biocontainers/cnvnator/status
   :target: https://quay.io/repository/biocontainers/cnvnator
.. _`cnvnator/tags`: https://quay.io/repository/biocontainers/cnvnator?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/cnvnator/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/cnvnator/README.html