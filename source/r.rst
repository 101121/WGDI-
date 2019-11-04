retain
------

retain is show subgenomes in gene retention or genome fractionation.

.. rubric:: Parameters

Use command to enter the folder ``wgdi -r ? > retain.conf`` Take out the parameter file.::

   [retain]
   alignment = alignment file
   gff = gff file
   colors = red,blue,green
   refgenome = shorthand
   figsize = 10,12
   step = 50
   ylabel = y label
   savefile = retain file(result)
   figurefile = result(.png,.pdf)

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
alignment         Type:str     default:- 
                     
					 共线性列表
---------------- ------------------------------------------------------------------------
colors            Type:{red,blue,green}     default:-
                  
				     根据分组，设定多组颜色，用逗号分割
---------------- ------------------------------------------------------------------------
refgenome         Type:str     default:- 
                  
				     参考物种的简写
---------------- ------------------------------------------------------------------------	  
figsize           Type:str     default:- 
                  
				     The size ratio of the image
---------------- ------------------------------------------------------------------------	  
step              Type:int     default:- 
                  
				     滑动窗口的大小
---------------- ------------------------------------------------------------------------	  
ylabel            Type:str     default:- 
                     
					 图片的y轴标签
---------------- ------------------------------------------------------------------------	  
savefile          Type:str     default:-  
                  
				     绘图的结果
---------------- ------------------------------------------------------------------------	  
figurefile        Type:str     default:- 
                  
				     生成的图片
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi -r retain.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left