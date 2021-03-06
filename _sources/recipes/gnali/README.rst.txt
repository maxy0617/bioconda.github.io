:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gnali'
.. highlight: bash

gnali
=====

.. conda:recipe:: gnali
   :replaces_section_title:
   :noindex:

   gNALI \(gene nonessentiality and loss\-of\-function identifier\) is a tool for finding PLoF gene variants.

   :homepage: https://github.com/phac-nml/gnali
   :license: APACHE / Apache-2.0
   :recipe: /`gnali <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gnali>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gnali/meta.yaml>`_

   


.. conda:package:: gnali

   |downloads_gnali| |docker_gnali|

   :versions:
      
      

      ``0.1.1-0``,  ``0.1.0-0``

      

   
   :depends filelock: 
   :depends numpy: 
   :depends pandas: 
   :depends pybiomart: 
   :depends pysam: 
   :depends python: ``>=3.6``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gnali

   and update with::

      conda update gnali

   or use the docker container::

      docker pull quay.io/biocontainers/gnali:<tag>

   (see `gnali/tags`_ for valid values for ``<tag>``)


.. |downloads_gnali| image:: https://img.shields.io/conda/dn/bioconda/gnali.svg?style=flat
   :target: https://anaconda.org/bioconda/gnali
   :alt:   (downloads)
.. |docker_gnali| image:: https://quay.io/repository/biocontainers/gnali/status
   :target: https://quay.io/repository/biocontainers/gnali
.. _`gnali/tags`: https://quay.io/repository/biocontainers/gnali?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gnali/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gnali/README.html