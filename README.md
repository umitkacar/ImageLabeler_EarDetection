# ImageLabeler_EarDetection

Tools: Matlab, ImageLabeler

1- You have to adjust the paths of ear images & ear labels **** It is important ****** 

2- Open terminal on UBUNTU 18.04

3- Create folders (MainPath is "/media/cutesafe/983f8bd1-436f-40a5-a881-e997598e5e6f/xOpenImage/")
Use the following commands to do this,respectively:

>>> sudo mkdir /media/cutesafe

>>> sudo mkdir /media/cutesafe/983f8bd1-436f-40a5-a881-e997598e5e6f

>>> sudo mkdir /media/cutesafe/983f8bd1-436f-40a5-a881-e997598e5e6f/xOpenImage/

4- Cut & paste "ear_img" folder & "PixelLabelData_5" folder into MainPath
The download link is below:

https://drive.google.com/open?id=1uDHCUqWZaodPFWcN8r9XiXhjxKdoWB4m

https://drive.google.com/open?id=18SQ3B_SMBc4OMVFoHWEbvCNGyMd64QqG

5- Cut & paste "gTruth_v5.mat" & imageLabelingSession_v5.mat" into MainPath
The download link is below:

https://github.com/umitkacar/ImageLabeler_EarDetection.git

6- Open terminal on desktop UBUNTU 18.04 
7- Run, respectively.

>>> cd /media/cutesafe/983f8bd1-436f-40a5-a881-e997598e5e6f/xOpenImage/

>>> matlab

8- Then, write & run "imageLabeler" in Command Window (matlab)

9- Go "Label-> Load-> Session", Select "imageLabelingSession_v5.mat" (matlab)

10- Everything is READY, then you can use LABEL PIXELS TOOL, draw ear regions.

11- GOAL: Control ear regions - fix - draw new ear regions - fix

12- After labeling is finished:

Label -> Save -> Session As -> imageLabelingSession_v6.mat -> SAVE  

****current version is v5, so you must continue v6 ******

Label -> Export Labels -> To File -> gTruth_v6 -> OK 

****current version is v5, so you must continue v6 ******

Good luck with the project!

