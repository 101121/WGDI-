circos
------

circos is a simple way to run circos.

.. rubric:: Parameters

Use command to enter the folder ``wgdi -ci ? > circos.conf`` Take out the parameter file.::

   [circos]
   gff =  gff file
   lens = lens file
   radius = 0.2
   angle_gap = 0.05
   ring_width= 0.015
   colors  = color confige(chr:color,chr:color)
   position = end
   alignment = text.txt
   chr_label = Shorthand
   figsize = 10,10
   savefig = saving image(.png,.pdf)

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
radius            Type: float    default: -
                     
					 半径，o-1之间的数值
---------------- ------------------------------------------------------------------------
angle_gap         Type: float    default: -
                     
					 染色体之间的gap
---------------- ------------------------------------------------------------------------
ring_width        Type: float    default: -
                     
					 圆环的宽度
---------------- ------------------------------------------------------------------------
colors            Type: str    default: -
                     
					 根据分组，设定多组颜色，用逗号分割
---------------- ------------------------------------------------------------------------
position          Type: str    default: -
                     
					 The position of the gene corresponds to the gff file.
---------------- ------------------------------------------------------------------------
alignment         Type: str    default: -
                     
					 共线性列表
---------------- ------------------------------------------------------------------------
chr_label         Type: str    default: -
                     
					 染色体的简写
---------------- ------------------------------------------------------------------------
figsize           Type: str    default: 10,10
                     
					 The size ratio of the image
---------------- ------------------------------------------------------------------------
savefile          Type: str    default: -

                     生成的图片
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use `wgdi –ci circos.conf` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left