:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'iced'
.. highlight: bash

iced
====

.. conda:recipe:: iced
   :replaces_section_title:
   :noindex:

   The python module iced implements the ICE normalization of hic data.

   :homepage: https://github.com/hiclib/iced
   :license: BSD / new BSD
   :recipe: /`iced <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/iced>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/iced/meta.yaml>`_

   


.. conda:package:: iced

   |downloads_iced| |docker_iced|

   :versions:
      
      

      ``0.5.6-1``,  ``0.5.6-0``,  ``0.5.4-0``,  ``0.5.2-0``,  ``0.5.0-0``,  ``0.4.2-0``

      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends matplotlib-base: 
   :depends numpy: ``>=1.14.6,<2.0a0``
   :depends pandas: 
   :depends python: ``>=3.6,<3.7.0a0``
   :depends python_abi: ``3.6.* *_cp36m``
   :depends scikit-learn: 
   :depends scipy: ``>=0.13.3``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install iced

   and update with::

      conda update iced

   or use the docker container::

      docker pull quay.io/biocontainers/iced:<tag>

   (see `iced/tags`_ for valid values for ``<tag>``)


.. |downloads_iced| image:: https://img.shields.io/conda/dn/bioconda/iced.svg?style=flat
   :target: https://anaconda.org/bioconda/iced
   :alt:   (downloads)
.. |docker_iced| image:: https://quay.io/repository/biocontainers/iced/status
   :target: https://quay.io/repository/biocontainers/iced
.. _`iced/tags`: https://quay.io/repository/biocontainers/iced?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/iced/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/iced/README.html