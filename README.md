# Lytro Power Tools

Advanced Lytro camera control and light field image processing

Formerly `https://www.lytro.com/platform/power-tools` [(archived in archive.org)](https://web.archive.org/web/20150912094947/https://www.lytro.com/platform/power-tools/)

* License: LYTRO POWER TOOLS (BETA) LICENSE
* Documentation: see: [`docs/Lytro_Power_Tools_Beta_1.0.1_User_Manual.pdf`](docs/Lytro_Power_Tools_Beta_1.0.1_User_Manual.pdf)

Features
--------
See Documentation for full list of Features and Quick Setup Guide

    * Camera Controls
    * Camera Tool
    * LFP Tool
    * Recipe Tool
    * Web Tool


Requirements
-------
+ ADB https://developer.android.com/studio/command-line/adb
+ Enable ADB in your Lytro Illum: Press and hold 'AEL' + 'Lytro' Button `([])`-shaped (next to shutter) while powering on the camera.
+ Micro USB 3.0 Cable
+ SD Card inside the camera (can it be avoided?)


Other resources:
------
+ For the v1 Lytro: http://optics.miloush.net/lytro/TheResources.aspx


Linux port notes:
------
This is completely untested, and the purpose is to send camera control commands. There's no Linux build for the original Lytro app build, so the image processing commands most likely won't work.

The Lytro app dir will be set to:
```
    /home/$USER/.Lytro/
```
