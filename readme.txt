**This is just one example for CE2.19**

Three steps are included.

Step1: Each ply file in dataset is divided into two ply files.
       You can use up_partition.exe and down_partition.exe in ../plyedit/partition folder.
       
	e.g., up_partition.exe longdress_vox10_ 1051 1350
     	      down_partition.exe longdress_vox10_ 1051 1350

Step2: Replace the updated source files in ../source to TMC2.20 Reference software
       Please run (C2 lossyG,lossyA,intra) conditions in N17766_CTC 
       and please replace cfg files in ../cfg folder to enable HM to support tile/slice coding.


Step3: two sets of decoded ply files should be combined .
       You can use combination.exe in ../plyedit/combination folder.
    
       e.g., combination.exe head body 0 300



Ps: more general version of source for CE2.19 will be implemented later.  
If you have any question, please do not hesitate to contact me (Lcui2000@gmail.com).
      
