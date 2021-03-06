:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ltr_retriever'
.. highlight: bash

ltr_retriever
=============

.. conda:recipe:: ltr_retriever
   :replaces_section_title:
   :noindex:

   Identification of LTR retrotransposons

   :homepage: https://github.com/oushujun/LTR_retriever
   :license: GPL / GPLv3
   :recipe: /`ltr_retriever <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ltr_retriever>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ltr_retriever/meta.yaml>`_

   


.. conda:package:: ltr_retriever

   |downloads_ltr_retriever| |docker_ltr_retriever|

   :versions:
      
      

      ``2.8.7-0``,  ``2.8-0``

      

   
   :depends cd-hit: 
   :depends perl: 
   :depends perl-text-soundex: 
   :depends repeatmasker: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ltr_retriever

   and update with::

      conda update ltr_retriever

   or use the docker container::

      docker pull quay.io/biocontainers/ltr_retriever:<tag>

   (see `ltr_retriever/tags`_ for valid values for ``<tag>``)


.. |downloads_ltr_retriever| image:: https://img.shields.io/conda/dn/bioconda/ltr_retriever.svg?style=flat
   :target: https://anaconda.org/bioconda/ltr_retriever
   :alt:   (downloads)
.. |docker_ltr_retriever| image:: https://quay.io/repository/biocontainers/ltr_retriever/status
   :target: https://quay.io/repository/biocontainers/ltr_retriever
.. _`ltr_retriever/tags`: https://quay.io/repository/biocontainers/ltr_retriever?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ltr_retriever/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ltr_retriever/README.html