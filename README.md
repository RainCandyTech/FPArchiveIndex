# FPArchiveIndex
Index of my Adobe Flash Player Archive Collection. Currently under construction.

## Flash Player International Edition by Adobe
### Introduction
This is the normal version released by Adobe themselves. </br>
Adobe stopped supporting this version in December 31, 2020.</br>
The last version is v32.0.0.465.
### Tech Specs
Before version 30, this version is available for customers all around the world.</br>
Beginning from version 30, this version is not available for customers in mainland China.</br>
After it was released, if Chinese users still visiting Adobe's Flash Player Download Site, they will be redirected to ZhongCheng's "Flash Player China Official Website".</br>
For Windows exe installers, if Chinese users try to install them, the setup will not launch and will lead the user to ZhongCheng's website too.</br>
If they are disconnected from the internet, they will able to install the program successfully.</br>
But if the Player detected the user is located in China, it will refuse to run any flash content with an error message "not compatible with your region" and requires user to reinstall.</br>
The reinstall button will lead the user to ZhongCheng's website.</br>
There's no region lock on macOS & Linux version.</br></br>
Starting from version 32.0.0.403, Adobe integrates a timebomb in the program. It will refuse to play any flash content starting from January 12, 2021.
### Available Archives
The original binaries of this version is available in Internet Archive. 

## Flash Player Enterprise by HARMAN
### Introduction
On the [Adobe Flash Player EOL Enterprise Information Page](https://www.adobe.com/products/flashplayer/enterprise-end-of-life.html), 
Adobe announced the official enterprise distributor for Flash Player outside China mainland, HARMAN International. From unknown sources, their Flash support service costs about $50,000 per year.
### Tech Specs
The Flash Player version provided by them is v50. In our archive, only ActiveX & PPAPI version available.</br>
This version of Flash has been limited in the URLs that it can load, to avoid accidental access of potentially malicious content.</br>
If you load a flash content and it is not located on the URL whitelist, the Player will refuse to load and will show the info button.</br>
If you click the button it will lead you to [this page](https://airsdk.harman.com/flashplayer/blocked?url=URL). You can also get more informations at this page.
### Available Archives
|Date (CST)|Version|ActiveX|PPAPI|
|:---|:---|:---|:---|
|12/30/2020|50.0.20.216|:heavy_multiplication_x:|:heavy_check_mark:(x64)|
|1/5/2021|50.0.20.314|:heavy_check_mark:(x86)|:heavy_multiplication_x:|
|1/8/2021|50.0.20.373|:heavy_check_mark:(x86)|:heavy_check_mark:(x64)|
|2/16/2021|50.0.20.183|:heavy_multiplication_x:|:heavy_check_mark:(x64)|
|3/16/2021|50.0.20.338|:heavy_check_mark:(x86)|:heavy_multiplication_x:|

## Flash Player China Edition by ZhongCheng (General Consumer Edition)
### Introduction
In February 28, 2018, Adobe announced the exclusive partner of Flash Player in China Mainland:</br>
2144 and its subsidiary ZhongCheng Network.</br>
Starting from version 30, they started to distribute a China-Specific version of Flash Player.</br>
On their "Flash Player China Official Website", they provide online installers of Flash Player for Windows users,</br>
and offline installers for Mac and Linux users.</br>
Unfortunately, they decided to stop offering Linux binaries for general users in May 2021.</br>
(They will continue to offer Linux binaries for paid enterprise user.)</br>
The last Linux version is v34.0.0.137.</br>
The latest Windows & macOS version can be checked in ["Flash Player China Official Website"](https://www.flash.cn/download-wins).</br></br>
There're also offline installers for Windows too. You can download them from some 3rd party website or software,</br>
such as 360 Software Manager (360 软件管家) and Tencent Software Center (腾讯软件中心).</br>
They're also available on flash.cn server, but ZhongCheng doesn't publish them to the public.
### Tech Specs
Before September 2020, the version number of China Edition is synchronized with the international version.</br>
Starting in September 2020, the version number is raised to 33.</br>
In the end of 2020, Microsoft is preparing to push a Windows Update to remove Adobe Flash Player ActiveX that integrated on Windows 8.x and Windows 10.</br>
To let Chinese Flash Player users to play content on an ActiveX-based browser on Windows 8.x & 10, They released version 33.0.0.432 in December 2020 with a Windows 8.x & 10 ActiveX special edition.</br>
In January 2021, the version number is raised to 34.</br></br>
And the Windows version contains "Flash Helper Service".</br>
The service will "make sure that the latest version of the Flash Player is installed" and "send anonymous usage data" to Zhongcheng to "help improve Flash Player".</br>
But according to user's feedback, this service will push ads to the computer.</br>
And even worse, according to the early version of Flash Helper Service Software License Agreement, This service will collect privacy data such as visited websites and ZhongCheng can share these datas to 3rd parties without any liability.</br>
If users try to disable or remove this service, Flash Player will refuse to play any content with an error message "A required system component is not running properly" and ask users to reinstall.</br>
This makes users angry and dissatisfy and many users appeal to uninstall Flash Player and boycutt ZhongCheng Network.</br>
### Available Archives (Windows Normal Installer)
|Date|Version|ActiveX|PPAPI|NPAPI|ActiveX (Debug)|PPAPI (Debug)|NPAPI (Debug)|Projector|Projector (Debug)|SWC Lib|
|:---|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|2020.9β|33.0.0.397|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.9β|33.0.0.399|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.9|33.0.0.401|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.10|33.0.0.413|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.11|33.0.0.417|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.12|33.0.0.432|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.1|34.0.0.92|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2021.2|34.0.0.105|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.3β|34.0.0.110|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.3|34.0.0.118|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.4|34.0.0.137|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.5|34.0.0.155|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.6|34.0.0.164|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.7|34.0.0.175|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.8|34.0.0.184|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.9|34.0.0.192|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.11|34.0.0.201|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2022.1β|34.0.0.209|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2022.1|34.0.0.211|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2022.4|34.0.0.231|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2022.5|34.0.0.242|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2022.6|34.0.0.251|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2022.8|34.0.0.267|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.11|34.0.0.277|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2023.3|34.0.0.282|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2023.6|34.0.0.289|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
### Available Archives (Windows Offline Installer)
|Date|Version|ActiveX|PPAPI|NPAPI|
|:---|:----:|:----:|:----:|:----:|
|2018.12|32.0.0.101|:heavy_multiplication_x:|:heavy_check_mark:|:heavy_multiplication_x:|
|2020.5|32.0.0.330|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.6|32.0.0.387|:heavy_check_mark: (360 & Tencent)|:heavy_check_mark:|:heavy_check_mark:|
|2020.7|32.0.0.403|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2020.9|33.0.0.401|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2020.10|33.0.0.413|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_check_mark:|
|2021.4|34.0.0.137|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.5|34.0.0.155|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.6|34.0.0.164|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.7|34.0.0.175|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.9|34.0.0.192|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.1|34.0.0.211|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.4|34.0.0.231|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.5|34.0.0.242|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.8|34.0.0.267|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.11|34.0.0.277|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.3|34.0.0.282|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
### Available Archives (macOS DMG image)
|Date|Version|PPAPI|NPAPI|
|:---|:---|:----:|:----:|
|2020.4|32.0.0.363|:heavy_check_mark:|:heavy_check_mark:|
|2020.12|33.0.0.432|:heavy_check_mark:|:heavy_check_mark:|
|2021.4|34.0.0.137|:heavy_check_mark:|:heavy_check_mark:|
|2021.5|34.0.0.155|:heavy_check_mark:|:heavy_check_mark:|
|2021.6|34.0.0.164|:heavy_check_mark:|:heavy_check_mark:|
|2021.7|34.0.0.175|:heavy_check_mark:|:heavy_check_mark:|
|2021.8|34.0.0.184|:heavy_check_mark:|:heavy_check_mark:|
|2021.9|34.0.0.192|:heavy_check_mark:|:heavy_check_mark:|
|2021.11|34.0.0.201|:heavy_check_mark:|:heavy_check_mark:|
|2022.1|34.0.0.211|:heavy_check_mark:|:heavy_check_mark:|
|2022.4|34.0.0.231|:heavy_check_mark:|:heavy_check_mark:|
|2022.5|34.0.0.242|:heavy_check_mark:|:heavy_check_mark:|
|2022.6|34.0.0.251|:heavy_check_mark:|:heavy_check_mark:|
|2022.8|34.0.0.267|:heavy_check_mark:|:heavy_check_mark:|
|2022.11|34.0.0.277|:heavy_check_mark:|:heavy_check_mark:|
|2023.3|34.0.0.282|:heavy_check_mark:|:heavy_check_mark:|
|2023.6|34.0.0.289|:heavy_check_mark:|:heavy_check_mark:|

### Available Archives (Linux)
|Date|Version|PPAPI (tar.gz)|PPAPI (rpm)|NPAPI (tar.gz)|NPAPI (rpm)|
|:---|:---|:----:|:----:|:----:|:----:|
|2021.1|34.0.0.92|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|
|2021.4|34.0.0.137|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|

## Flash Player China Edition by ZhongCheng (Enterprise & Education Edition)
### Introduction
Placeholder
### Tech Specs
After the purchase or application is finished, users will get a compressed file.
It contains three variants of Flash Player Installer (ActiveX+PPAPI+NPAPI) and a license file (license.dat).
The user need copy the license file to the following path.
```
x86 OS: %WINDIR%\System32\Macromed\Flash
AMD64 OS: %WINDIR%\SysWOW64\Macromed\Flash
```
The installer will deploy a special version of Flash Helper Service. The service will read the license file to check is it vaild.</br>
If the answer is no, the Player will show a warning symbol and it will lead the user to this page ([Problems of Flash Player Enterprise is running abnormally](https://www.flash.cn/enterprise/errordialog)).</br>
And it won't push any ads to the computer.</br>
The binary file of the service is protected by VMProtect 3.x.
### Available Archives (Windows)
|Date|Version|Is MSI installer available|
|:---|:----:|:----:|
|2019.6|32.0.0.207|:heavy_multiplication_x:|
|2019.7|32.0.0.223|:heavy_multiplication_x:|
|2019.10|32.0.0.270|:heavy_check_mark:|
|2019.11|32.0.0.293|:heavy_check_mark:|
|2019.12|32.0.0.303|:heavy_check_mark:|
|2020.3|32.0.0.344|:heavy_check_mark:|
|2020.4|32.0.0.363|:heavy_check_mark:|
|2020.5|32.0.0.371|:heavy_check_mark:|
|2020.6|32.0.0.387|:heavy_check_mark:|
|2020.7|32.0.0.403|:heavy_check_mark:|
|2020.8|32.0.0.414|:heavy_check_mark:|
|2021.7|34.0.0.175|:heavy_check_mark:|
|2021.10|34.0.0.192|:heavy_multiplication_x:|
|2021.11|34.0.0.201|:heavy_multiplication_x:|
|2021.12|34.0.0.211|:heavy_check_mark:|
|2022.4|34.0.0.231|:heavy_check_mark:|
|2022.5|34.0.0.242|:heavy_check_mark:|
|2022.6|34.0.0.251|:heavy_check_mark:|
|2022.8|34.0.0.267|:heavy_check_mark:|
|2022.11|34.0.0.277|:heavy_multiplication_x:|

## Flash Player China Edition by ZhongCheng (Embedded Edition for Flash Center)
### Introduction
This is an Embedded version of PPAPI Flash Player for ZhongCheng's Flash Center Application. Only 32-bit version is available.
### Tech Specs
It refuses to play any flash content outside the Flash Center application.</br></br>
### Available Archives
|Date|Version|
|:---|:----:|
|2020.5|32.0.0.371|
|2021.4|34.0.0.137|
|2021.8|34.0.0.184|
## Flash Player Built-In Edition in Windows 8.x & 10
### Introduction
Starting from Windows 8, Microsoft begins to integrate a special edition of Flash Player ActiveX into the Windows OS.
The last version is v32.0.0.445.
### Tech Specs
The version number is synchronized with the international version.</br>
As same as the normal international version, starting from version 32.0.0.403, Adobe integrates a timebomb in the program.</br>
It will refuse to play any flash content starting from January 12, 2021.</br></br>
This version has no region lock and Chinese users can use it too.</br>
If the user installs Windows 8.x & 10 ActiveX special edition for China,</br>
This version will be uninstalled. </br></br>
It can be uninstalled by installing KB4577586 update too.</br>
### Available Archives
Unfortunately we don't have collected them. There are lots of files, for different Windows versions.
