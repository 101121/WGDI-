blockks
-------

blockks is show Ks of blocks in a dotplot.
  
.. rubric:: Parameters

Use command to enter the folder ``wgdi -bk ? > blockks.conf`` Take out the parameter file.::

   [blockks]
   blast = blast file
   gff1 = gff1 file
   gff2 = gff2 file
   lens1 = lens1 file
   lens2 = lens2 file
   genome1_ name = Genome1 name
   genome2_ name = Genome2 name
   colinearity = colinearity(colinearscan,mcscanx)
   ks= ks file
   markersize = 1
   area = 0,1
   block_length = int number
   position = order
   figsize = 10,10 
   savefile = savefile(.png,.pdf)

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
colinearity       Type: str    default: -
                     
					 colinearscan的结果文件
---------------- ------------------------------------------------------------------------
ks                Type: str    default: -
                     
					 ks计算结果
---------------- ------------------------------------------------------------------------
markersize        Type: str    default: -
                     
					 控制点的大小			 
---------------- ------------------------------------------------------------------------
area              Type: str    default: -
                     
					 显示ks的范围
---------------- ------------------------------------------------------------------------
block_length      Type: str    default: -
                     
					 显示共线性区块的最小长度
---------------- ------------------------------------------------------------------------
position          Type: str    default: -
                     
					 The position of the gene corresponds to the gff file.
---------------- ------------------------------------------------------------------------
figsize           Type: str    default: 10,10
                     
					 The size ratio of the image.
---------------- ------------------------------------------------------------------------
savefile          Type: str    default: -
                     
					 生成的图片
================ ========================================================================

.. rubric:: Example


.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi –bk blockks.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left