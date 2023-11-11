
Bruce's D&D Projects
====================



.. toctree::
   :maxdepth: 1
   :caption: Projects:

   classes.rst
   green_gray.rst
   broken_world.rst
   distant_moon.rst


Acknowledgments
---------------

Document theme
~~~~~~~~~~~~~~

This is a `Sphinx <http://www.sphinx-doc.org/>`__ document using the
lovely `{book}theme
<https://sphinx-book-theme.readthedocs.io/en/latest/index.html>`__
from the `The Executable Book Project
<https://ebp.jupyterbook.org/>`__.

Contributing to this effort
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Please feel free to fork this from
https://github.com/NSLS-II-BMM/XAS_Workshops, write up your own
content, and submit a pull request to have your content included. 

To get started, first install `sphinx <http://www.sphinx-doc.org/>`__
and the {book}theme `as explained here
<https://sphinx-book-theme.readthedocs.io/en/latest/tutorials/get-started.html>`__

Next install these Sphinx extensions:

* ``sphinx-math-dollar`` to render equations and mathematical symbols

..
  * ``sphinxemoji`` to render cute emojis

by doing this:

.. code-block:: bash

   pip install sphinx-math-dollar

..
   pip install sphinxemoji
   Alas, Github actions was unable to install this package.  Sigh...

Download a fork of `the repository
<https://github.com/NSLS-II-BMM/XAS_Workshops>`__ and edit away!
You can check that your contributions build correctly by going to the
``docs`` folder and running ``make html``.  Once your contributions
contain all your wisdom and build correctly, go ahead and make a pull
request.


Automated workflow at GitHub
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Automated building of this sphinx document is accomplished using the
very cool `Sphinx-docs-to-gh-pages action
<https://github.com/uibcdf/action-sphinx-docs-to-gh-pages>`__
developed by `the Computational Biology and Drug Design Research
Unit -UIBCDF- at the Mexico City Children's Hospital Federico Gómez
<https://www.uibcdf.org/>`__.

