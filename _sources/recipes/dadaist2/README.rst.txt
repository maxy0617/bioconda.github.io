:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'dadaist2'
.. highlight: bash

dadaist2
========

.. conda:recipe:: dadaist2
   :replaces_section_title:
   :noindex:

   Command line wrapper to run DADA2 on a set of paired\-end reads

   :homepage: https://github.com/quadram-institute-bioscience/dadaist2
   :license: MIT
   :recipe: /`dadaist2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dadaist2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dadaist2/meta.yaml>`_

   Command line wrapper to run DADA2 on a set of paired\-end reads


.. conda:package:: dadaist2

   |downloads_dadaist2| |docker_dadaist2|

   :versions:
      
      

      ``0.1.04-0``

      

   
   :depends bioconductor-dada2: 
   :depends clustalo: 
   :depends fastp: 
   :depends fasttree: 
   :depends perl: 
   :depends perl-fastx-reader: ``>=0.90``
   :depends vsearch: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install dadaist2

   and update with::

      conda update dadaist2

   or use the docker container::

      docker pull quay.io/biocontainers/dadaist2:<tag>

   (see `dadaist2/tags`_ for valid values for ``<tag>``)


.. |downloads_dadaist2| image:: https://img.shields.io/conda/dn/bioconda/dadaist2.svg?style=flat
   :target: https://anaconda.org/bioconda/dadaist2
   :alt:   (downloads)
.. |docker_dadaist2| image:: https://quay.io/repository/biocontainers/dadaist2/status
   :target: https://quay.io/repository/biocontainers/dadaist2
.. _`dadaist2/tags`: https://quay.io/repository/biocontainers/dadaist2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/dadaist2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/dadaist2/README.html