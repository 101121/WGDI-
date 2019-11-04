correspondence
--------------

correspondence is extract event-related genomic alignment.

.. rubric:: Parameters

Use command to enter the folder ``wgdi -c ? > correspondence.conf`` Take out the parameter file.::

   [correspondence]
   blockinfo = blockinfo file(.csv)
   lens1 = lens1 file
   lens2 = lens2 file
   tandem = (true/false)
   pvalue = 0.05
   block_length = 5
   multiple = 1
   homo = 0,1
   savefile = savefile(.csv) 

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
blockinfo         Type: str    default: -
---------------- ------------------------------------------------------------------------
tandem            Type: str    default: -
---------------- ------------------------------------------------------------------------
pvalue            Type: str    default: -
---------------- ------------------------------------------------------------------------
block_length      Type: str    default: -
---------------- ------------------------------------------------------------------------
multiple          Type: str    default: -
---------------- ------------------------------------------------------------------------
homo              Type: str    default: -
---------------- ------------------------------------------------------------------------
savefile          Type: str    default: -
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi –c correspondence.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left