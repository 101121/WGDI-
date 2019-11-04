align
-----

align is show event-related genomic alignment in a dotplot.

.. rubric:: Parameters

Use command to enter the folder ``wgdi -a ? > align.conf`` Take out the parameter file.::

   [alignment]
   gff1 =  gff1 file
   gff2 =  gff2 file
   lens1 = lens1 file
   lens2 = lens2 file
   genome1_ name =  Genome1 name
   genome2_ name =  Genome2 name
   markersize = 0.5
   position = order
   colors = red,blue,green
   figsize = 10,10
   savefile = savefile(.csv)
   savefig= savefig(.png,.pdf)
   block_list = 1.txt
   blockinfo = block information file

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
markersize        Type: str    default: -

                     控制点的大小					 
---------------- ------------------------------------------------------------------------
position          Type: str    default: order

                     The position of the gene corresponds to the gff file.
---------------- ------------------------------------------------------------------------
colors		      Type: str    default: red	
	 
                     根据分组，设定多组颜色，用逗号分割
---------------- ------------------------------------------------------------------------
figsize           Type: str    default: 10,10

                     The size ratio of the image.
---------------- ------------------------------------------------------------------------
savefile          Type: str    default: -

                     生成的共线性列表
---------------- ------------------------------------------------------------------------
savefig           Type: str    default: -

                     生成的图片
---------------- ------------------------------------------------------------------------
block_list        Type: str    default: -

                     对blockinfo文件添加class一列进行分组，用拉伯数字表述不同的组别     
---------------- ------------------------------------------------------------------------
blockinfo         Type: str    default: -
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi -a align.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left