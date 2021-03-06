:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'blasr'
.. highlight: bash

blasr
=====

.. conda:recipe:: blasr
   :replaces_section_title:
   :noindex:

   BLASR \- The PacBio long read aligner

   :homepage: https://github.com/PacificBiosciences/blasr
   :license: BSD-3-Clause-Clear
   :recipe: /`blasr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/blasr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/blasr/meta.yaml>`_

   


.. conda:package:: blasr

   |downloads_blasr| |docker_blasr|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>5.3.3-2</code>,  <code>5.3.3-1</code>,  <code>5.3.3-0</code>,  <code>5.3.2-5</code>,  <code>5.3.2-4</code>,  <code>5.3.2-3</code>,  <code>5.3.2-2</code>,  <code>5.3.2-1</code>,  <code>5.3.2-0</code>,  </span></summary>
      

      ``5.3.3-2``,  ``5.3.3-1``,  ``5.3.3-0``,  ``5.3.2-5``,  ``5.3.2-4``,  ``5.3.2-3``,  ``5.3.2-2``,  ``5.3.2-1``,  ``5.3.2-0``,  ``5.3.1-0``,  ``5.2p1-0``

      
      .. raw:: html

         </details>
      

   
   :depends hdf5: ``>=1.10.5,<1.10.6.0a0``
   :depends htslib: ``>=1.9,<1.10.0a0``
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install blasr

   and update with::

      conda update blasr

   or use the docker container::

      docker pull quay.io/biocontainers/blasr:<tag>

   (see `blasr/tags`_ for valid values for ``<tag>``)


.. |downloads_blasr| image:: https://img.shields.io/conda/dn/bioconda/blasr.svg?style=flat
   :target: https://anaconda.org/bioconda/blasr
   :alt:   (downloads)
.. |docker_blasr| image:: https://quay.io/repository/biocontainers/blasr/status
   :target: https://quay.io/repository/biocontainers/blasr
.. _`blasr/tags`: https://quay.io/repository/biocontainers/blasr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/blasr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/blasr/README.html