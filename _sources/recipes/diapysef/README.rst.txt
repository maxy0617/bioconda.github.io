:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'diapysef'
.. highlight: bash

diapysef
========

.. conda:recipe:: diapysef
   :replaces_section_title:
   :noindex:

   Analysis\, conversion and visualization of diaPASEF data.

   :homepage: https://github.com/Roestlab/dia-pasef
   :license: MIT / MIT
   :recipe: /`diapysef <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/diapysef>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/diapysef/meta.yaml>`_

   


.. conda:package:: diapysef

   |downloads_diapysef| |docker_diapysef|

   :versions:
      
      

      ``0.3.5-0``

      

   
   :depends matplotlib-base: 
   :depends numpy: 
   :depends pandas: 
   :depends patsy: 
   :depends pyopenms: 
   :depends python: 
   :depends statsmodels: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install diapysef

   and update with::

      conda update diapysef

   or use the docker container::

      docker pull quay.io/biocontainers/diapysef:<tag>

   (see `diapysef/tags`_ for valid values for ``<tag>``)


.. |downloads_diapysef| image:: https://img.shields.io/conda/dn/bioconda/diapysef.svg?style=flat
   :target: https://anaconda.org/bioconda/diapysef
   :alt:   (downloads)
.. |docker_diapysef| image:: https://quay.io/repository/biocontainers/diapysef/status
   :target: https://quay.io/repository/biocontainers/diapysef
.. _`diapysef/tags`: https://quay.io/repository/biocontainers/diapysef?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/diapysef/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/diapysef/README.html