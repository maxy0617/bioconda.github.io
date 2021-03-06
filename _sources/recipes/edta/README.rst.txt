:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'edta'
.. highlight: bash

edta
====

.. conda:recipe:: edta
   :replaces_section_title:
   :noindex:

   Extensive de\-novo TE Annotator

   :homepage: https://github.com/oushujun/EDTA
   :license: GPL / GPLv3
   :recipe: /`edta <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/edta>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/edta/meta.yaml>`_

   


.. conda:package:: edta

   |downloads_edta| |docker_edta|

   :versions:
      
      

      ``1.8.3-0``,  ``1.8.2-0``,  ``1.7.8-0``,  ``1.7.7-0``

      

   
   :depends biopython: 
   :depends blast: 
   :depends cd-hit: 
   :depends genericrepeatfinder: 
   :depends genometools-genometools: 
   :depends glob2: 
   :depends keras: ``>=2.2.4``
   :depends ltr_finder: 
   :depends ltr_retriever: 
   :depends mdust: 
   :depends multiprocess: 
   :depends muscle: 
   :depends openjdk: 
   :depends pandas: 
   :depends perl: 
   :depends perl-text-soundex: 
   :depends python: ``>=3.6``
   :depends regex: 
   :depends repeatmodeler: 
   :depends scikit-learn: ``>=0.19.0``
   :depends tensorflow: ``>=1.14.0``
   :depends tesorter: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install edta

   and update with::

      conda update edta

   or use the docker container::

      docker pull quay.io/biocontainers/edta:<tag>

   (see `edta/tags`_ for valid values for ``<tag>``)


.. |downloads_edta| image:: https://img.shields.io/conda/dn/bioconda/edta.svg?style=flat
   :target: https://anaconda.org/bioconda/edta
   :alt:   (downloads)
.. |docker_edta| image:: https://quay.io/repository/biocontainers/edta/status
   :target: https://quay.io/repository/biocontainers/edta
.. _`edta/tags`: https://quay.io/repository/biocontainers/edta?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/edta/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/edta/README.html