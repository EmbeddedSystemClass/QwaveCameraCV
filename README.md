# QwaveCameraCV

LabVIEW Camera Driver library for Raspberry Pi 3B/3B+/3A+.
 
![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-08.png)
 
[**QwaveCameraCV**](https://github.com/QWaveSystems/QwaveCameraCV) is a additional functions for camera driver. It is a peripheral VIs provides enhance functions over LINX 3.0 standard library.

with QwaveCameraCV library you can aquired image or video then processsing using [**OpenCV**](https://opencv.org/) or [**NI-VISION**](http://www.ni.com/vision/software/vdm/) toolkit under Raspberry Pi 3B/3B+/3A+ boards.

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-01.png)

**QwaveCameraCV** package is required [LINX 3.0](http://sine.ni.com/nips/cds/view/p/lang/en/nid/212478) driver to deploy the code and run under Raspberry Pi (ARMv7 Linux enviromnent).

The [**LINX 3.0**](https://github.com/MakerHub/LINX/tree/master/LabVIEW) library is created by Digilent/LabVIEW MakerHubMakerHub
and maintain the support at [labviewmakerhub.com](https://www.labviewmakerhub.com/doku.php?id=libraries:linx:start).

**LINX 3.0** for Raspberry Pi is works with **LabVIEW 2014 SP1** only (Home/Student/Base.) and it **FREE** to use for Non-commercial purpose.It is great platfrom for student and home users to experienced with LabVIEW under 3rd party low cost single board computer.

You can get started with the [LabVIEW 45-Day Evaluation](http://ftp.ni.com/support/softlib/labview/labview_development_system/2014%20SP1/2014sp1LV-WinEng.exe) or buy LabVIEW 2014 SP1 Home Edition to use with Raspberry Pi 3B, 3B+ and 3A+.

Please note: To run QwaveCameraCV you need a run-time license. To get such a license please contact : amornthep@qwavesys.com
 
![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-10.png)

**Installation**

1.Download and Install **"qwave_cameracv_raspberrypi-xx.xx.vip"** using VIPM (VI Package Manager).

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-00.png)

2.After installed you can find functions under **Vision and Motion > QwaveCameraCV** palette.

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-01.png)

3.The example project is located at "C:\Program Files (x86)\National Instruments\LabVIEW 2014\examples\QwaveCameraCV". Open "QwaveCameraCV-License_Check.lvproj"

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-02.png)

4.Run the "License Check.vi" to get the board id.

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-03.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-04.png)

5.Create a empty file, renamed to "qwaveopencv.lic" and put the activation code insite file. and upload to Raspberry Pi at directory "/home/pi/qwaveopencv.lic"

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-05.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-06.png)

6.Run the "License Check.vi" again.

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-07.png)

7.Run the "Camera_Test.vi"

![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-08.png)


![](http://ftp.qwavesys.com/tmp_pics/QwaveCameraCV-09.png)


------------------------------------------------------------------

-Raspberry Pi™ is a registered trademark of the Raspberry Pi foundation.

-LINX 3.0 for Raspberry Pi 2B/3B create by `www.labviewmakerhub.com` (LabVIEW 2014 only,***Non-commercial use)

-OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. `(http://opencv.org/)`

------------------------------------------------------------------
Created by `Amornthep Phunsin` and `Supawat Armart` (Q-Wave Systems)
Contact : `"amornthep@qwavesys.com"`
