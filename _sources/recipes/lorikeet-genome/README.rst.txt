:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'lorikeet-genome'
.. highlight: bash

lorikeet-genome
===============

.. conda:recipe:: lorikeet-genome
   :replaces_section_title:
   :noindex:

   Metagenomic Strain Resolver

   :homepage: https://github.com/rhysnewell/Lorikeet
   :license: GPL3
   :recipe: /`lorikeet-genome <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/lorikeet-genome>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/lorikeet-genome/meta.yaml>`_

   Lorikeet aims to generate strain level genotypes from metagenomic communities using information from both long and short reads.


.. conda:package:: lorikeet-genome

   |downloads_lorikeet-genome| |docker_lorikeet-genome|

   :versions:
      
      

      ``0.3.2-0``

      

   
   :depends bwa: ``>=0.7.17``
   :depends dashing: 
   :depends fastani: 
   :depends gsl: ``>=2.6,<2.7.0a0``
   :depends libgcc-ng: ``>=7.5.0``
   :depends libstdcxx-ng: ``>=7.5.0``
   :depends minimap2: 
   :depends openblas: ``>=0.3.6,<0.3.7.0a0``
   :depends openssl: ``>=1.1.1g,<1.1.2a``
   :depends snippy: ``>=4.4.5``
   :depends starcode: 
   :depends svim: 
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install lorikeet-genome

   and update with::

      conda update lorikeet-genome

   or use the docker container::

      docker pull quay.io/biocontainers/lorikeet-genome:<tag>

   (see `lorikeet-genome/tags`_ for valid values for ``<tag>``)


.. |downloads_lorikeet-genome| image:: https://img.shields.io/conda/dn/bioconda/lorikeet-genome.svg?style=flat
   :target: https://anaconda.org/bioconda/lorikeet-genome
   :alt:   (downloads)
.. |docker_lorikeet-genome| image:: https://quay.io/repository/biocontainers/lorikeet-genome/status
   :target: https://quay.io/repository/biocontainers/lorikeet-genome
.. _`lorikeet-genome/tags`: https://quay.io/repository/biocontainers/lorikeet-genome?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/lorikeet-genome/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/lorikeet-genome/README.html