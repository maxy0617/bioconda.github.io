:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bowtie'
.. highlight: bash

bowtie
======

.. conda:recipe:: bowtie
   :replaces_section_title:
   :noindex:

   An ultrafast memory\-efficient short read aligner

   :homepage: https://github.com/BenLangmead/bowtie
   :license: Artistic License 2.0
   :recipe: /`bowtie <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bowtie>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bowtie/meta.yaml>`_
   :links: biotools: :biotools:`bowtie`, doi: :doi:`10.1186/gb-2009-10-3-r25`

   


.. conda:package:: bowtie

   |downloads_bowtie| |docker_bowtie|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.2.3-1</code>,  <code>1.2.3-0</code>,  <code>1.2.2-1</code>,  <code>1.2.2-0</code>,  <code>1.2.1.1-0</code>,  <code>1.2.0-0</code>,  <code>1.1.2-2</code>,  <code>1.1.2-1</code>,  <code>1.1.2-0</code>,  </span></summary>
      

      ``1.2.3-1``,  ``1.2.3-0``,  ``1.2.2-1``,  ``1.2.2-0``,  ``1.2.1.1-0``,  ``1.2.0-0``,  ``1.1.2-2``,  ``1.1.2-1``,  ``1.1.2-0``,  ``1.1.1-0``,  ``1.0.0-1``,  ``1.0.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends libstdcxx-ng: ``>=7.3.0``
   :depends perl: 
   :depends python: ``>=3.6,<3.7.0a0``
   :depends python_abi: ``3.6.* *_cp36m``
   :depends tbb: ``>=2020.1``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bowtie

   and update with::

      conda update bowtie

   or use the docker container::

      docker pull quay.io/biocontainers/bowtie:<tag>

   (see `bowtie/tags`_ for valid values for ``<tag>``)


.. |downloads_bowtie| image:: https://img.shields.io/conda/dn/bioconda/bowtie.svg?style=flat
   :target: https://anaconda.org/bioconda/bowtie
   :alt:   (downloads)
.. |docker_bowtie| image:: https://quay.io/repository/biocontainers/bowtie/status
   :target: https://quay.io/repository/biocontainers/bowtie
.. _`bowtie/tags`: https://quay.io/repository/biocontainers/bowtie?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bowtie/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bowtie/README.html