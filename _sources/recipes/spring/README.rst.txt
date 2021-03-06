:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'spring'
.. highlight: bash

spring
======

.. conda:recipe:: spring
   :replaces_section_title:
   :noindex:

   Spring is a compression tool for Fastq files

   :homepage: https://github.com/shubhamchandak94/Spring
   :license: Free for non-commercial use
   :recipe: /`spring <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spring>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spring/meta.yaml>`_

   


.. conda:package:: spring

   |downloads_spring| |docker_spring|

   :versions:
      
      

      ``1.0-0``

      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install spring

   and update with::

      conda update spring

   or use the docker container::

      docker pull quay.io/biocontainers/spring:<tag>

   (see `spring/tags`_ for valid values for ``<tag>``)


.. |downloads_spring| image:: https://img.shields.io/conda/dn/bioconda/spring.svg?style=flat
   :target: https://anaconda.org/bioconda/spring
   :alt:   (downloads)
.. |docker_spring| image:: https://quay.io/repository/biocontainers/spring/status
   :target: https://quay.io/repository/biocontainers/spring
.. _`spring/tags`: https://quay.io/repository/biocontainers/spring?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/spring/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/spring/README.html