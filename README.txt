
Binary code for Part-based Tracker v1.0-20130912
-----------------------------------------------------------------
Copyright Rui Yao, Qinfeng (Javen) Shi, September 2013.
ruiyao@cumt.edu.cn, qinfeng.shi@ieee.org



Please cite the following paper if you use this code: 


@inproceedings{CVPR13eYao,
   author    = "R. Yao and  Q. Shi and  C. Shen and  Y. Zhang and  A. {van den Hengel}",
   title     = "Part-based visual tracking with online latent structural learning",
   booktitle = "IEEE Conference on Computer Vision and Pattern Recognition (CVPR'13)",
   address   = "Oregon, USA",
   url       = "http://hdl.handle.net/2440/77413",
   year      = "2013",
 }



@article{Part2016Yao,
   author    = "R. Yao and  Q. Shi and  C. Shen and  Y. Zhang and  A. {van den Hengel}",
   title     = "Part-based robust tracking using online latent structured learning",
   journal   = "IEEE Transactions on Circuits and Systems for Video Technology",
   year      = "2016",
 }

-------
General
-------

This distribution includes the executable code for the tracker in [1]. It is written in C++ and uses the OpenCV 2.1. It has been tested on a machine running Windows 7, using Visual Studio 9.0.
	
-----
Usage
-----

1. Prepare a config file called "config.txt" and place it in the same directory as the executable file.

2. Run the executable file "PartTracker_v1.0.exe".

3. The following output should be obtained:

	- during the run - a visual window with the tracking results
	- a result file called "PartTracker_[sequence name]_gt.txt" containing the tracking results in the same directory as the tracking sequence
	

---------
Sequences
---------

Sequences are assumed to be of the format of those used in:

http://www.samhare.net/research/struck
