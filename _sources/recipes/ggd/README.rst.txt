:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ggd'
.. highlight: bash

ggd
===

.. conda:recipe:: ggd
   :replaces_section_title:
   :noindex:

   GoGetData \(GGD\) is a genomic data managment system. It provide simple and reproducible access to a repository of genomic data. Simply put\, it is \'Conda\' for genomic data

   :homepage: https://github.com/gogetdata/ggd-cli
   :license: MIT
   :recipe: /`ggd <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ggd>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ggd/meta.yaml>`_

   


.. conda:package:: ggd

   |downloads_ggd| |docker_ggd|

   :versions:
      
      

      ``0.1.2-0``,  ``0.1.1-1``,  ``0.1.1-0``,  ``0.1.0-1``,  ``0.1.0-0``

      

   
   :depends check-sort-order: 
   :depends conda: ``4.7.12.*``
   :depends conda-build: ``3.18.11.*``
   :depends future: 
   :depends fuzzywuzzy: 
   :depends git: 
   :depends gitpython: 
   :depends gsort: ``>=0.1.3``
   :depends htslib: 
   :depends krb5: 
   :depends oyaml: 
   :depends pytest: 
   :depends pytest-socket: 
   :depends python: 
   :depends python-levenshtein: 
   :depends pyyaml: 
   :depends requests: ``>=2.20.0``
   :depends ripgrep: 
   :depends samtools: 
   :depends wget: 
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ggd

   and update with::

      conda update ggd

   or use the docker container::

      docker pull quay.io/biocontainers/ggd:<tag>

   (see `ggd/tags`_ for valid values for ``<tag>``)


.. |downloads_ggd| image:: https://img.shields.io/conda/dn/bioconda/ggd.svg?style=flat
   :target: https://anaconda.org/bioconda/ggd
   :alt:   (downloads)
.. |docker_ggd| image:: https://quay.io/repository/biocontainers/ggd/status
   :target: https://quay.io/repository/biocontainers/ggd
.. _`ggd/tags`: https://quay.io/repository/biocontainers/ggd?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ggd/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ggd/README.html