:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'biscuit'
.. highlight: bash

biscuit
=======

.. conda:recipe:: biscuit
   :replaces_section_title:
   :noindex:

   A utility for analyzing sodium bisulfite conversion\-based DNA methylation\/modification data

   :homepage: https://github.com/huishenlab/biscuit
   :license: MIT
   :recipe: /`biscuit <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biscuit>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biscuit/meta.yaml>`_

   


.. conda:package:: biscuit

   |downloads_biscuit| |docker_biscuit|

   :versions:
      
      

      ``0.3.16.20200420-0``,  ``0.3.15.20200318-0``

      

   
   :depends libcurl: ``>=7.64.1,<8.0a0``
   :depends libgcc-ng: ``>=7.3.0``
   :depends ncurses: ``>=6.1,<6.2.0a0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install biscuit

   and update with::

      conda update biscuit

   or use the docker container::

      docker pull quay.io/biocontainers/biscuit:<tag>

   (see `biscuit/tags`_ for valid values for ``<tag>``)


.. |downloads_biscuit| image:: https://img.shields.io/conda/dn/bioconda/biscuit.svg?style=flat
   :target: https://anaconda.org/bioconda/biscuit
   :alt:   (downloads)
.. |docker_biscuit| image:: https://quay.io/repository/biocontainers/biscuit/status
   :target: https://quay.io/repository/biocontainers/biscuit
.. _`biscuit/tags`: https://quay.io/repository/biocontainers/biscuit?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/biscuit/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/biscuit/README.html