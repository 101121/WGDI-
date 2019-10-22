colinearscan
------------

colinearscan is a simple way to run ColinearScan.

.. image :: _static/5.png
   
.. rubric:: Parameters


Use command to enter the folder ``wgdi -cl ? > colinearscan.conf`` Take out the parameter file.

.. image :: _static/colinearscan.png

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
dir               Type: str    default: -
              
                  The directory of the generated file.
---------------- ------------------------------------------------------------------------ 
evalue            Type: float    default: 1e-5

                  evalue value in blast result.
---------------- ------------------------------------------------------------------------         
score             Type: int    default: 100
				  
                  Score value in blast results.
---------------- ------------------------------------------------------------------------  
mg                Type: int,int    default: 50,50

                  This is the parameter of the colinearscan program mg.
---------------- ------------------------------------------------------------------------ 
repnum            Type: int    default: 20
				  
                  The maximum number of homologous genes is allowed 
				  
				  to be removed more than part of the population.
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi -cl colinearscan.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left