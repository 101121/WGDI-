ks
--

ks is................

.. rubric:: Parameters

Use command to enter the folder ``wgdi -ks ? > ks.conf`` Take out the parameter file.

.. image :: _static/ks.png

.. tabularcolumns:: column spec

================ ========================================================================
Parameters        Standards and instructions
---------------- ------------------------------------------------------------------------
cds_file          Type:str     default:-
                  
                  A cds file of one or more genomes.				  
---------------- ------------------------------------------------------------------------
pep_file          Type:str     default:- 

                  A protein file for one or more genomes. 非必需文件，如果不写这个参数，
				  那么这个文件将通过biopython模块翻译cds_file得到。
---------------- ------------------------------------------------------------------------
align_software    Type:{muscle,mafft}     default: muscle

                  多序列比对软件。
---------------- ------------------------------------------------------------------------
pairs_file        Type:str     default: 

                  需要计算ka,ks的同源基因对，可以是按``,``或者``\t``分隔的列表，也可以是ColinearScan的输出结果。
---------------- ------------------------------------------------------------------------
ks_file           Type:str     default: 

                  ks的输出文件名。
================ ========================================================================	  

.. rubric:: Example

.. rubric:: Modify

Modify the parameters that are right for you to run

.. rubric:: Begin

Use ``wgdi -ks ks.conf`` to run the parameter file and output the results you want.

.. image :: _static/1.png
   :align: left