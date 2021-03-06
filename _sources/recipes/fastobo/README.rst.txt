:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'fastobo'
.. highlight: bash

fastobo
=======

.. conda:recipe:: fastobo
   :replaces_section_title:
   :noindex:

   Faultless AST for Open Biomedical Ontologies in Python

   :homepage: https://github.com/fastobo/fastobo-py
   :documentation: https://fastobo.readthedocs.io
   
   :license: MIT / MIT
   :recipe: /`fastobo <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/fastobo>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/fastobo/meta.yaml>`_
   :links: doi: :doi:`10.7490/f1000research.1117405.1`

   


.. conda:package:: fastobo

   |downloads_fastobo| |docker_fastobo|

   :versions:
      
      

      ``0.7.2-0``,  ``0.7.1-0``,  ``0.7.0-0``,  ``0.6.2-0``,  ``0.6.1-0``,  ``0.6.0-0``,  ``0.5.4-0``

      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends python: ``>=3.6,<3.7.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install fastobo

   and update with::

      conda update fastobo

   or use the docker container::

      docker pull quay.io/biocontainers/fastobo:<tag>

   (see `fastobo/tags`_ for valid values for ``<tag>``)


.. |downloads_fastobo| image:: https://img.shields.io/conda/dn/bioconda/fastobo.svg?style=flat
   :target: https://anaconda.org/bioconda/fastobo
   :alt:   (downloads)
.. |docker_fastobo| image:: https://quay.io/repository/biocontainers/fastobo/status
   :target: https://quay.io/repository/biocontainers/fastobo
.. _`fastobo/tags`: https://quay.io/repository/biocontainers/fastobo?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/fastobo/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/fastobo/README.html