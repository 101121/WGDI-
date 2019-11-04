kspeaks
-------

kspeaks is a simple way to get ks peaks.
   
.. rubric:: Parameters

Use command to enter the folder ``wgdi -kp ? > kp.conf`` Take out the parameter file.::

  [kspeaks]

   blockinfo = block information (*.csv)
   pvalue = 0.05
   tandem = true
   block_ length = int number
   ks_ area = 0,10
   multiple = 1
   homo = 0,1
   fontsize = 9
   area = 0,3
   figsize = 10,6.18
   savefig = saving image(.png, .pdf)
   savefile = ks medain savefile

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
blockinfo         Type:str     default:- 
                     
					 整合共线性和ks的文件
---------------- ------------------------------------------------------------------------
pvalue            Type:str     default:- 

                     共线性结果中的p值
---------------- ------------------------------------------------------------------------	  
tandem            Type:str     default:- 
                     
					 判定标准是基因位置相差不超过200个基因
---------------- ------------------------------------------------------------------------	  
block_length      Type:str     default:- 
                  
				     共线性区块的最小长度
---------------- ------------------------------------------------------------------------	  
ks_area           Type:str     default:- 
                     
					 显示ks的范围
---------------- ------------------------------------------------------------------------	  
multiple          Type:str     default:- 
                  
				     同源基因的最佳数量。
---------------- ------------------------------------------------------------------------	  
homo              Type:str     default:- 
                  
				     共线性片段偏向最好匹配的值，范围是【-1，1】
---------------- ------------------------------------------------------------------------	  
fontsize          Type:str     default:- 
                      
				     字体的大小
---------------- ------------------------------------------------------------------------	  
area              Type:str     default:- 
                  
				     绘图显示的范围
---------------- ------------------------------------------------------------------------	  
figsize           Type:str     default:- 
                  
				     The size ratio of the image
---------------- ------------------------------------------------------------------------	  
savefig           Type:str     default:- 
                     
					 生成的图片
---------------- ------------------------------------------------------------------------	  
savefile          Type:str     default:- 
                         
				     保存的文件
================ ========================================================================

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run.

.. rubric:: Begin

Use ``wgdi -kp kp.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left