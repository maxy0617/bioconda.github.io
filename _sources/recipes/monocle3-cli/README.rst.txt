:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'monocle3-cli'
.. highlight: bash

monocle3-cli
============

.. conda:recipe:: monocle3-cli
   :replaces_section_title:
   :noindex:

   A set of wrappers for individual components of the monocle3 package. Functions R packages are hard to call when building workflows outside of R\, so this package adds a set of simple wrappers with robust argument parsing. Intermediate steps are currently monocle3 R objects\, but the ultimate objective is to have language\-agnostic intermediate formats allowing composite workflows using a variety of software packages.

   :homepage: https://github.com/ebi-gene-expression-group/monocle-scripts
   :license: Apache / Apache-2.0
   :recipe: /`monocle3-cli <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/monocle3-cli>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/monocle3-cli/meta.yaml>`_

   


.. conda:package:: monocle3-cli

   |downloads_monocle3-cli| |docker_monocle3-cli|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.0.9-0</code>,  <code>0.0.8-0</code>,  <code>0.0.7-1</code>,  <code>0.0.7-0</code>,  <code>0.0.6-0</code>,  <code>0.0.5-1</code>,  <code>0.0.5-0</code>,  <code>0.0.4-0</code>,  <code>0.0.3-1</code>,  </span></summary>
      

      ``0.0.9-0``,  ``0.0.8-0``,  ``0.0.7-1``,  ``0.0.7-0``,  ``0.0.6-0``,  ``0.0.5-1``,  ``0.0.5-0``,  ``0.0.4-0``,  ``0.0.3-1``,  ``0.0.3-0``

      
      .. raw:: html

         </details>
      

   
   :depends fonts-conda-ecosystem: 
   :depends r-base: ``>=3.6,<3.7.0a0``
   :depends r-monocle3: ``<=0.2.0``
   :depends r-optparse: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install monocle3-cli

   and update with::

      conda update monocle3-cli

   or use the docker container::

      docker pull quay.io/biocontainers/monocle3-cli:<tag>

   (see `monocle3-cli/tags`_ for valid values for ``<tag>``)


.. |downloads_monocle3-cli| image:: https://img.shields.io/conda/dn/bioconda/monocle3-cli.svg?style=flat
   :target: https://anaconda.org/bioconda/monocle3-cli
   :alt:   (downloads)
.. |docker_monocle3-cli| image:: https://quay.io/repository/biocontainers/monocle3-cli/status
   :target: https://quay.io/repository/biocontainers/monocle3-cli
.. _`monocle3-cli/tags`: https://quay.io/repository/biocontainers/monocle3-cli?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/monocle3-cli/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/monocle3-cli/README.html