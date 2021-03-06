:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'vmatch'
.. highlight: bash

vmatch
======

.. conda:recipe:: vmatch
   :replaces_section_title:
   :noindex:

   The Vmatch large scale sequence analysis software

   :homepage: http://www.vmatch.de/
   :license: OTHER / Unknown
   :recipe: /`vmatch <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vmatch>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vmatch/meta.yaml>`_
   :links: biotools: :biotools:`vmatch`

   


.. conda:package:: vmatch

   |downloads_vmatch| |docker_vmatch|

   :versions:
      
      

      ``2.3.0-2``,  ``2.3.0-1``,  ``2.3.0-0``

      

   
   :depends libgcc-ng: ``>=7.3.0``
   :depends perl: ``>=5.10,<6``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install vmatch

   and update with::

      conda update vmatch

   or use the docker container::

      docker pull quay.io/biocontainers/vmatch:<tag>

   (see `vmatch/tags`_ for valid values for ``<tag>``)


.. |downloads_vmatch| image:: https://img.shields.io/conda/dn/bioconda/vmatch.svg?style=flat
   :target: https://anaconda.org/bioconda/vmatch
   :alt:   (downloads)
.. |docker_vmatch| image:: https://quay.io/repository/biocontainers/vmatch/status
   :target: https://quay.io/repository/biocontainers/vmatch
.. _`vmatch/tags`: https://quay.io/repository/biocontainers/vmatch?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/vmatch/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/vmatch/README.html