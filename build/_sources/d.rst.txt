dotplot
-------

dotplot is................

.. image :: _static/7.png
   
.. rubric:: Parameters

Use command to enter the folder ``wgdi -d ? > dotplot.conf`` Take out the parameter file.

.. image :: _static/dotplot.png

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
multiple          Type: int    default: 1
              
                  The best number of homologous genes.
---------------- ------------------------------------------------------------------------         
score             Type: int    default: 100
				  
                  Score value in blast results.
---------------- ------------------------------------------------------------------------
evalue            Type: float    default: 1e-5

                  evalue value in blast result.
---------------- ------------------------------------------------------------------------   
repnum            Type: int    default: 20
				  
                  The maximum number of homologous genes is allowed 
				  
				  to be removed more than part of the population.
---------------- ------------------------------------------------------------------------  
position          Type: {start,order,end}    default: order

                  The position of the gene corresponds to the gff file.
---------------- ------------------------------------------------------------------------   
markersiz         Type: float    default: 0.5
  
                  The size of the point in the plot.
---------------- ------------------------------------------------------------------------
figsize           Type: int,int    default: 10,10
				  
                  Controls the proportion of the size of the saved picture.
---------------- ------------------------------------------------------------------------  
savefile          Type: str    default: .png

                  Save pictures support png, PDF, svg formats.
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run

.. rubric:: Begin

Use ``wgdi -d dotplot.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left