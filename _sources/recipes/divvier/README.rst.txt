:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'divvier'
.. highlight: bash

divvier
=======

.. conda:recipe:: divvier
   :replaces_section_title:
   :noindex:

   A program for removing MSA uncertainty

   :homepage: https://github.com/simonwhelan/Divvier
   :license: GPL3 / GNU General Public v3 or later (GPLv3+)
   :recipe: /`divvier <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/divvier>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/divvier/meta.yaml>`_

   


.. conda:package:: divvier

   |downloads_divvier| |docker_divvier|

   :versions:
      
      

      ``1.01-0``

      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install divvier

   and update with::

      conda update divvier

   or use the docker container::

      docker pull quay.io/biocontainers/divvier:<tag>

   (see `divvier/tags`_ for valid values for ``<tag>``)


.. |downloads_divvier| image:: https://img.shields.io/conda/dn/bioconda/divvier.svg?style=flat
   :target: https://anaconda.org/bioconda/divvier
   :alt:   (downloads)
.. |docker_divvier| image:: https://quay.io/repository/biocontainers/divvier/status
   :target: https://quay.io/repository/biocontainers/divvier
.. _`divvier/tags`: https://quay.io/repository/biocontainers/divvier?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/divvier/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/divvier/README.html