:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'sccaf'
.. highlight: bash

sccaf
=====

.. conda:recipe:: sccaf
   :replaces_section_title:
   :noindex:

   Single\-Cell Clustering Assessment Framework

   :homepage: https://github.com/SCCAF/sccaf
   :license: MIT / MIT
   :recipe: /`sccaf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sccaf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sccaf/meta.yaml>`_

   


.. conda:package:: sccaf

   |downloads_sccaf| |docker_sccaf|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.0.10-0</code>,  <code>0.0.9-0</code>,  <code>0.0.8-0</code>,  <code>0.0.7.post1-1</code>,  <code>0.0.7.post1-0</code>,  <code>0.0.7-0</code>,  <code>0.0.6-0</code>,  <code>0.0.5-0</code>,  <code>0.0.3-0</code>,  </span></summary>
      

      ``0.0.10-0``,  ``0.0.9-0``,  ``0.0.8-0``,  ``0.0.7.post1-1``,  ``0.0.7.post1-0``,  ``0.0.7-0``,  ``0.0.6-0``,  ``0.0.5-0``,  ``0.0.3-0``,  ``0.0.2-0``

      
      .. raw:: html

         </details>
      

   
   :depends h5py: ``<2.10``
   :depends louvain: 
   :depends numpy: 
   :depends pandas: 
   :depends psutil: 
   :depends python: ``>=3``
   :depends scanpy: ``>=1.4.4``
   :depends scikit-learn: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install sccaf

   and update with::

      conda update sccaf

   or use the docker container::

      docker pull quay.io/biocontainers/sccaf:<tag>

   (see `sccaf/tags`_ for valid values for ``<tag>``)


.. |downloads_sccaf| image:: https://img.shields.io/conda/dn/bioconda/sccaf.svg?style=flat
   :target: https://anaconda.org/bioconda/sccaf
   :alt:   (downloads)
.. |docker_sccaf| image:: https://quay.io/repository/biocontainers/sccaf/status
   :target: https://quay.io/repository/biocontainers/sccaf
.. _`sccaf/tags`: https://quay.io/repository/biocontainers/sccaf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/sccaf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/sccaf/README.html