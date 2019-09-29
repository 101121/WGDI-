Installation
------------

Method
""""""

Python package and command line interface (CLI) for the analysis of whole genome duplications (WGDI). The environment required for installation is python3.

Install directly with python

We recommend using the pre-compiled binary wheels available on PyPI using:

.. code-block:: python

   pip install wgdi

upgrade or uninstall with just one terminal command:

.. code-block:: python

   pip install --upgrade wgdi
   pip uninstall wgdi

Or use git to download the latest version of the installation

Then either download and decompress our source code, or fetch it using git. Now change directory to the Biopython source code folder and run:

.. code-block:: python

   git clone https://github.com/SunPengChuan/wgdi.git
   cd wgdi
   python setup.py install

Third party software
""""""""""""""""""""

`paml <http://abacus.gene.ucl.ac.uk/software/paml.html>`_

`mafft <https://mafft.cbrc.jp/alignment/software/>`_

`muscle <http://www.drive5.com/muscle/downloads.htm>`_

`pal2nal <http://www.bork.embl.de/pal2nal/#Download>`_

When the above software is installed, put the required files into the same folder to begin our work.

Unloading
"""""""""

When you are not in need of wgdi, you can uninstall with ``pip uninstall wgdi``.