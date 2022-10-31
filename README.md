# FPArchiveIndex
Index of our Adobe Flash Player Archive Collection. Currently under construction.

## Flash Player International Edition by Adobe
### Introduction
This is the normal version released by Adobe themselves. </br>
Adobe stopped supporting this version in December 31, 2020.</br>
The last version is v32.0.0.465.
### Tech Specs
Before version 30, this version is available for customers all around the world.</br>
Beginning from version 30, the international version is not available for customers in mainland China.</br>
After it released, if Chinese users still visiting Adobe's Flash Player Download Site,</br>
they will be redirected to ZhongCheng's "Flash Player China Official Website".</br>
If they downloaded the exe installer of international version and tried to install,</br>
the setup will not launch and will lead the user to ZhongCheng's website too.</br>
If they disconnected from the internet, they will able to install the program successfully.</br>
But if the Player detected the user is located in China, it will refuse to run any flash content</br>
with an error message "not compatible with your region" and require a reinstall.</br>
The reinstall button will lead the user to ZhongCheng's website.</br></br>
Starting from version 32.0.0.403, Adobe integrates a timebomb in the program.</br>
It will refuse to play any flash content starting from January 12, 2021.
### Available Archives
The original binaries of this version is available in Internet Archive. 

## Flash Player Enterprise by HARMAN
### Introduction
On the [Adobe Flash Player EOL Enterprise Information Page](https://www.adobe.com/products/flashplayer/enterprise-end-of-life.html), 
Adobe announced the official enterprise distributor for Flash Player</br>
outside China mainland, HARMAN International. From unknown sources, their Flash support service costs $50,000 per year.
### Tech Specs
The Flash Player version provided by them is v50. In our archive, only ActiveX & PPAPI version available.</br>
This version of Flash has been limited in the URLs that it can load, to avoid accidental access of potentially malicious content.</br>
If you load a flash content and it is not located on the URL whitelist, the Player will refuse to load and will show the info button.</br>
If you click the button it will lead you to [this page](https://airsdk.harman.com/flashplayer/blocked?url=URL). You can also get more informations at this page.
### Available Archives
|Date (CST)|Version|ActiveX|PPAPI|
|:---|:---|:----:|:----:|
|12/30/2020|50.0.20.216|Unavailable|Available (x64)|
|1/5/2021|50.0.20.314|Available (x86)|Unavailable|
|1/8/2021|50.0.20.373|Available (x86)|Available (x64)|
|2/16/2021|50.0.20.183|Unavailable|Available (x64)|
|3/16/2021|50.0.20.338|Available (x86)|Unavailable|

## Flash Player China Edition by ZhongCheng (General Consumer Edition)
### Introduction
In February 28, 2018, Adobe announced the exclusive partner of Flash Player in China Mainland:</br>
2144 and its subsidiary ZhongCheng Network.</br>
Starting from version 30, they started to distribute a China-Specific version of Flash Player.</br>
On their "Flash Player China Official Website", they provide online installers of FLash Player for Windows users,</br>
and offline installers for Mac and Linux users.</br>
Unfortunately, they decided to stop offering Linux binaries for general users in May 2021.</br>
(They will continue to offer Linux binaries for paid enterprise user.)</br>
The last Linux version is v34.0.0.137.</br>
The latest Windows & macOS version can be checked in ["Flash Player China Official Website"](https://www.flash.cn/download-wins).
### Tech Specs
Before September 2020, the version number of China Edition is synchronized with the international version.</br>
Starting in Sep 2020, the version number is raised to 33.</br>
In the end of 2020, Microsoft is preparing to push a Windows Update to remove Adobe Flash Player ActiveX that</br>
integrated on Windows 8.x and Windows 10.</br>
To let Chinese Flash Player users to play content on an ActiveX-based browser on Windows 8.x & 10,</br>
They released version 33.0.0.432 in December 2020 with a Windows 8.x & 10 ActiveX special edition.</br>
In January 2021, the version number is raised to 34.</br>
Placeholder</br>
TODO:FlashHelperService
### Available Archives
Placeholder

## Flash Player China Edition by ZhongCheng (Enterprise & Education Edition)
### Introduction
Placeholder
### Tech Specs
Placeholder
### Available Archives
Only versions release before 2022 are listed. :)</br>
Unfortunately I can't share them to the public, whether the info or binaries.
|Date|Version|exe|msi|
|:---|:---|:----:|:----:|
|2019.6|32.0.0.207|Available|Unavailable|
|2019.7|32.0.0.223|Available|Unavailable|
|2019.10|32.0.0.270|Available|Available|
|2019.11|32.0.0.293|Available|Available|
|2019.12|32.0.0.303|Available|Available|
|2020.3|32.0.0.344|Available|Available|
|2020.4|32.0.0.363|Available|Available|
|2020.5|32.0.0.371|Available|Available|
|2020.6|32.0.0.387|Available|Available|
|2020.7|32.0.0.403|Available|Available|
|2020.8|32.0.0.414|Available|Available|
|2021.7|34.0.0.175|Available|Available|
|2021.10|34.0.0.192|Available|Unvailable|
|2021.11|34.0.0.201|Available|Unvailable|
|2021.12|34.0.0.211|Available|Available|

## Flash Player Built-In Edition in Windows 8.x & 10
### Introduction
Placeholder
### Tech Specs
Placeholder
### Available Archives
Unfortunately we don't have collected them. There are lots of files, for different Windows versions:</br>
Windows 8, Windows Embedded 8, Windows Server 2012</br>
Windows 8.1, Windows Embedded 8.1, Windows Server 2012 R2</br>
Windows 10 (Original Release)</br>
Windows 10 Version 1511, Windows Server 2016 Technical Preview 4</br>
Windows 10 Version 1607, Windows Server 2016</br>
Windows 10 Version 1703</br>
Windows 10 Version 1709</br>
Windows 10 Version 1803</br>
Windows 10 Version 1809, Windows Server 2019</br>
Windows 10 Version 1903 & 1909</br>
Windows 10 Version 2004 & 20H2</br>
Each line for one package.
