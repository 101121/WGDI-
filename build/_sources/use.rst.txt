usage 
-----

.. image :: _static/wgdi.png
   :scale: 100%

We support the use of ``WGDI`` to complete the work on the icon number.

Common file
"""""""""""

In the conf file, gff1, lens1, gff2, and lens2 represent the information of species 1 and species 2, respectively.

* gff

.. image :: _static/gff.png

.. tabularcolumns:: column spec

====== ============ ==============================
Column Information  Explanation
1      Chr          Chromosome number 
2      ID           Gene name
3      Strat        The location of the gene 
4      End          Gene ending position
5      Direction    Direction of the gene sequence
6      Order name   Full name
====== ============ ==============================

* lens

.. image :: _static/lens.png

.. tabularcolumns:: column spec

====== =========== ==============================
Column Information Explanation                   
1                  Chromosome number
2      Chr lens    Number of chromosome sequences
3                  Number of chromosome genes
====== =========== ==============================

* Blast is the output file for `blast+ <ftp://ftp.ncbi.nlm.nih.gov/blast/executables/LATEST/>`_ , in -6 and m-8 formats.

In the conf file, gff1, lens1, gff2, and lens2 represent the files of species 1 and 2, respectively, and genome1_name and genome1_name represent the names of species 1 and 2, respectively. We will not explain in detail when we explain the parameters.

Contents
""""""""

.. toctree::

   a
   bk
   ci
   cl
   d
   kp
   ks
   r
   
Convenient
""""""""""

* When a folder runs ``WGDI``, ``WGDI`` automatically generates results for you in the background, and you can exit the folder and go to the next folder to start working.
* ``WGDI`` performs the ``conf`` file for the current folder, so you can copy the ``conf`` file in bulk and make parameter modifications that apply to the target folder.

.. image :: _static/4.png
   :scale: 50%