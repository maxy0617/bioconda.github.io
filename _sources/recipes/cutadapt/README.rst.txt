:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'cutadapt'
.. highlight: bash

cutadapt
========

.. conda:recipe:: cutadapt
   :replaces_section_title:
   :noindex:

   Trim adapters from high\-throughput sequencing reads

   :homepage: https://cutadapt.readthedocs.io/
   :license: MIT
   :recipe: /`cutadapt <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cutadapt>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cutadapt/meta.yaml>`_
   :links: biotools: :biotools:`cutadapt`, doi: :doi:`10.14806/ej.17.1.200`

   


.. conda:package:: cutadapt

   |downloads_cutadapt| |docker_cutadapt|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.10-0</code>,  <code>2.9-0</code>,  <code>2.8-0</code>,  <code>2.7-0</code>,  <code>2.6-0</code>,  <code>2.5-0</code>,  <code>2.4-0</code>,  <code>2.3-0</code>,  <code>2.2-0</code>,  </span></summary>
      

      ``2.10-0``,  ``2.9-0``,  ``2.8-0``,  ``2.7-0``,  ``2.6-0``,  ``2.5-0``,  ``2.4-0``,  ``2.3-0``,  ``2.2-0``,  ``2.1-0``,  ``2.0-0``,  ``1.18-1``,  ``1.18-0``,  ``1.17-0``,  ``1.16-2``,  ``1.16-1``,  ``1.16-0``,  ``1.15-0``,  ``1.14-0``,  ``1.13-0``,  ``1.12-1``,  ``1.12-0``,  ``1.11-0``,  ``1.10-0``,  ``1.9.1-0``,  ``1.8.3-0``,  ``1.8.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends dnaio: ``>=0.4.2``
   :depends libgcc-ng: ``>=7.3.0``
   :depends pigz: 
   :depends python: ``>=3.6,<3.7.0a0``
   :depends python_abi: ``3.6.* *_cp36m``
   :depends xopen: ``>=0.8.4``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install cutadapt

   and update with::

      conda update cutadapt

   or use the docker container::

      docker pull quay.io/biocontainers/cutadapt:<tag>

   (see `cutadapt/tags`_ for valid values for ``<tag>``)


.. |downloads_cutadapt| image:: https://img.shields.io/conda/dn/bioconda/cutadapt.svg?style=flat
   :target: https://anaconda.org/bioconda/cutadapt
   :alt:   (downloads)
.. |docker_cutadapt| image:: https://quay.io/repository/biocontainers/cutadapt/status
   :target: https://quay.io/repository/biocontainers/cutadapt
.. _`cutadapt/tags`: https://quay.io/repository/biocontainers/cutadapt?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/cutadapt/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/cutadapt/README.html