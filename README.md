# FPArchiveIndex
Index of our Adobe Flash Player Archive Collection. Currently under construction.

## Flash Player Consumer Edition by Adobe (Worldwide)
### Introduction
This is the normal version released by Adobe themselves. Adobe stopped supporting this version in December 31, 2020.</br>
The last version is v32.0.0.465.
### Tech Specs
Before version 30, this version is available for consumers all around the world. After that, it is not available for consumers in Chinese Mainland.</br>
Chinese Mainland consumers who are still visiting Adobe's own Flash Player website will be redirected to Zorange's "Flash Player China Official Website".</br>
Windows exe installers will also check for IPs from Chinese Mainland, if detected the setup will not launch and it will lead users to Zorange's website too.</br>
Although they can install the global version of the application successfully by disconnecting from the internet, they will get an error message "not compatible with your region"
and the Player will refuse to run any contents and requires user to reinstall. The reinstall button will lead the user to Zorange's website.</br></br>
But there's no region lock on macOS & Linux version.</br></br>
Starting from version 32.0.0.403, Adobe integrates a timebomb in this edition. It will refuse to play any contents starting from January 12, 2021.
### Available Archives
The original binaries of this version are available in the following links from Internet Archive. <br>
* [Flash Player Archive @ Internet Archive](https://archive.org/details/flashplayerarchive) - Backup of Adobe's official "Archived Flash Player Versions" pages, up to version 32.0.0.387<br>
* [Adobe Flash Player 32.0.0.453 / 32.0.0.465 @ Internet Archive](https://archive.org/details/fp_32.0.0.465_archive) - Archive of version 32.0.0.453 & 32.0.0.465<br>

However, some versions are not fully archived. You might be able to find them at other places.

## Flash Player Enterprise Edition by HARMAN (Worldwide)
### Introduction
On the [Adobe Flash Player EOL Enterprise Information Page](https://www.adobe.com/products/flashplayer/enterprise-end-of-life.html), 
Adobe announced the official enterprise distributor for Flash Player outside Chinese Mainland, HARMAN International. From unknown sources, their Flash support service costs about $50,000 per year.
### Tech Specs
The Flash Player version provided by them is v50. In our archive, only ActiveX & PPAPI version available. This version of Flash has been limited in the URLs that it can load. </br>
If users load a flash content and it is not located on the URL whitelist, the Player will refuse to load it and show the info button. </br>
The button will lead users to [this page](https://airsdk.harman.com/flashplayer/blocked?url=URL). By the way, you can also get more informations at this page.
### Available Archives
|Date (CST)|Version|ActiveX|PPAPI|
|:---|:---|:---|:---|
|12/30/2020|50.0.20.216|:heavy_multiplication_x:|:heavy_check_mark:(x64)|
|1/5/2021|50.0.20.314|:heavy_check_mark:(x86)|:heavy_multiplication_x:|
|1/8/2021|50.0.20.373|:heavy_check_mark:(x86)|:heavy_check_mark:(x64)|
|2/16/2021|50.0.20.183|:heavy_multiplication_x:|:heavy_check_mark:(x64)|
|3/16/2021|50.0.20.338|:heavy_check_mark:(x86)|:heavy_multiplication_x:|

## Flash Player Consumer Edition by Zorange (Chinese Mainland)
### Introduction
In February 28, 2018, Adobe announced the exclusive partner of Flash Player in Chinese Mainland: 2144 and its subsidiary Chongqing Zhongcheng Network Technology Co. Ltd. (Zorange).</br>
Starting from version 30, they started to distribute a China-Specific version of Flash Player.</br>
On their "Flash Player China Official Website", they provide online installers of Flash Player for Windows users, and offline installers for Mac and Linux users.</br>
Unfortunately, they decided to stop offering Linux binaries for general users in May 2021.</br>
(They will continue to offer Linux binaries for paid enterprise user.)</br>
The last Linux version is v34.0.0.137.</br>
The latest Windows & macOS version can be checked in ["Flash Player China Official Website"](https://www.flash.cn/download-wins).</br></br>
The offline installers for Windows is also available at some 3rd party websites or softwares, like 360 Software Manager (360 软件管家) and Tencent Software Center (腾讯软件中心). They're also available on flash.cn server, but normally Zorange will not provide the links of these files to the public.
### Tech Specs
Before September 2020, the version number of China Edition is synchronized with the international version.</br>
Starting in September 2020, the version number is raised to 33.</br>
In the end of 2020, Microsoft is preparing to push a Windows Update to remove Adobe Flash Player ActiveX that integrated on Windows 8.x and Windows 10.</br>
To let Chinese Flash Player users to play contents on an ActiveX-based browser on Windows 8.x & 10, They released version 33.0.0.432 in December 2020 with a Windows 8.x & 10 ActiveX special edition.</br>
In January 2021, the version number is raised to 34.</br></br>
And the Windows version contains "Flash Helper Service", a replacement of Adobe's own Flash Player Update Service.</br>
The service will "make sure that the latest version of the Flash Player is installed" and "send anonymous usage data" to Zorange to "help improve Flash Player".</br>
But according to user's feedback, this service will push ads to the computer.</br>
And even worse, according to the early version of Flash Helper Service Software License Agreement, this service will collect privacy data such as visited websites and Zorange can share these datas to 3rd parties without any liability.</br>
If users try to disable or remove this service, Flash Player will refuse to play any contents with an error message "A required system component is not running properly" and ask users to reinstall.</br>
This makes users angry and dissatisfy and many users appeal to uninstall Flash Player and boycutt Zorange.</br>
In addition, when the service detects an enterprise environment (an Active Directory environment), Flash Player will refuse to play contents too, so business users have to purchase their Enterprise Service.</br>

The "Updates" tab in Flash Player Settings Manager is also hiddened in the Windows version.
### Available Archives (Windows Normal Installer)
|Date|Version|ActiveX|PPAPI|NPAPI|ActiveX (Debug)|PPAPI (Debug)|NPAPI (Debug)|Projector|Projector (Debug)|SWC Lib|
|:---|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|2018.6|30.0.0.113|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|N/A|N/A|N/A|N/A|N/A|N/A|
|2020.9β|33.0.0.397|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|
|2020.9β|33.0.0.399|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|
|2020.9|33.0.0.401|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|
|2020.10|33.0.0.413|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|:grey_question:|
|2020.11|33.0.0.417|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:grey_question:|:grey_question:|:grey_question:|:heavy_check_mark:|:grey_question:|:grey_question:|
|2020.12|33.0.0.432|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:grey_question:|:grey_question:|:grey_question:|:heavy_multiplication_x:|:grey_question:|:grey_question:|
|2021.1|34.0.0.92|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2021.2|34.0.0.105|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2021.3β|34.0.0.110|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: (Legacy & Win8+)|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.3|34.0.0.118|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2021.4|34.0.0.137|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.5|34.0.0.155|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.6|34.0.0.164|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.7|34.0.0.175|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
|2021.8|34.0.0.184|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2021.9|34.0.0.192|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_multiplication_x:|
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
|2023.8|34.0.0.295|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2023.9|34.0.0.301|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
### Available Archives (Windows Offline Installer)
|Date|Version|ActiveX|PPAPI|NPAPI|
|:---|:----:|:----:|:----:|:----:|
|2018.9|30.0.0.154|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2018.9|31.0.0.108|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2018.11 #1|31.0.0.148|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2018.11 #2|31.0.0.153|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2018.12|32.0.0.101|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2020.5|32.0.0.330|:heavy_check_mark:|:heavy_multiplication_x:|:heavy_multiplication_x:|
|2020.6|32.0.0.387|:heavy_check_mark: (360 & Tencent)|:heavy_check_mark:|:heavy_check_mark:|
|2020.7|32.0.0.403|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2020.9|33.0.0.401|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2020.10|33.0.0.413|:heavy_multiplication_x:|:heavy_multiplication_x:|:heavy_check_mark:|
|2021.4|34.0.0.137|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.5|34.0.0.155|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.6|34.0.0.164|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.7|34.0.0.175|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.9|34.0.0.184|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.9|34.0.0.192|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2021.9|34.0.0.201|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.1|34.0.0.211|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.4|34.0.0.231|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.5|34.0.0.242|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.8|34.0.0.267|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2022.11|34.0.0.277|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|2023.3|34.0.0.282|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
### Available Archives (macOS DMG image)
|Date|Version|PPAPI|NPAPI|
|:---|:---|:----:|:----:|
|2020.4|32.0.0.363|:heavy_check_mark:|:heavy_check_mark:|
|2020.12|33.0.0.432|:heavy_check_mark:|:heavy_check_mark:|
|2021.1|34.0.0.92|:heavy_check_mark:|:heavy_check_mark:|
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
|2023.8|34.0.0.295|:heavy_check_mark:|:heavy_check_mark:|
|2023.9|34.0.0.301|:heavy_check_mark:|:heavy_check_mark:|

### Available Archives (Linux)
|Date|Version|PPAPI (tar.gz)|PPAPI (rpm)|NPAPI (tar.gz)|NPAPI (rpm)|
|:---|:---|:----:|:----:|:----:|:----:|
|2021.1|34.0.0.92|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|
|2021.4|34.0.0.137|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|:heavy_check_mark: (x86 & x64)|

## Flash Player Enterprise Edition by Zorange (Chinese Mainland)
### Introduction
In May 2019, Zorange started accepting free trial applications for their new enterprise services.</br>
Enterprises in Chinese Mainland can apply for a free Enterprise Trial Edition of the Player.</br>
They will be asked for a copy of their "Business License of Legal Entity" to identify themselves.</br>

In August 2020, Zorange announced the old "Enterprise Trial Edition" will reached the end of the trial period soon.</br>
At the same time, they started to provide [paid services for enterprises](https://www.flash.cn/enterprise/pay.html). </br>
Enterprises applied for trial edition will have a discount for this paid service until October.</br>
The last "Enterprise Trial Edition" provided by Zorange is 32.0.0.414.

In March 2021, Zorange started accepting free Education Edition applications of the Player for public primary schools, </br>
public middle schools and public collages. To identify themselves, schools will be asked for a copy of their</br>
"Certificate of Legal Institutions" or "Organization Code Certificate".</br>
For collages, Zorange only accepts application from a education email address (normally ends like "edu.cn").</br>
This service is not applicable for private schools.

"Education Edition" is basically a free version of "Enterprise Edition" for Education purposes without Linux support (mentioned below).

In May 2021, Zorange stopped providing Linux version of the Player for general customers. But they said they will
continue providing updates of Linux version for paid enterprise versions.

### Tech Specs
After the purchase or application is finished, users will get a compressed file.
It contains three variants of Flash Player Installer (ActiveX+PPAPI+NPAPI) and a license file (license.dat).
The user need copy the license file to the following path.
```
x86 OS: %WINDIR%\System32\Macromed\Flash
AMD64 OS: %WINDIR%\SysWOW64\Macromed\Flash
```
The installer will deploy a special version of Flash Helper Service. The service will read the license file to check is it vaild.</br>
If the answer is no, the Player will show a warning symbol and lead users to this page ([Problems of Flash Player Enterprise is running abnormally](https://www.flash.cn/enterprise/errordialog)).</br>
And it won't push any ads to the computer.</br>
The binary file of the service is protected by VMProtect 3.x.</br>

MSI Installers are also available for this edition.

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

## Flash Player Embedded Edition by Zorange (Chinese Mainland)
### Introduction
This is an Embedded version of PPAPI Flash Player for Zorange's [Flash Center Application](https://soft.flash.cn/flashcenter/index.html) & [Global Zorange Application](https://zorange.flash.cn/). Only 32-bit version is available.
### Tech Specs
It refuses to play any flash contents outside the dedicated application.</br></br>
### Available Archives
|Date|Version|
|:---|:----:|
|2020.5|32.0.0.371|
|2021.4|34.0.0.137|
|2021.8|34.0.0.184|
|2022.1|34.0.0.211|

## Flash Player ActiveX Built-In Edition by Microsoft (Worldwide)
### Introduction
Starting from Windows 8, Microsoft begins to integrate a special edition of Flash Player ActiveX into the Windows OS.
The last version is v32.0.0.445.
### Tech Specs
The version number is synchronized with the international version.</br>
As same as the normal international version, starting from version 32.0.0.403, Adobe integrates a timebomb in the program.</br>
It will refuse to play any flash contents starting from January 12, 2021.</br></br>
This version has no region lock and Chinese users can use it too.</br>
If the user installs Windows 8.x & 10 ActiveX special edition for China,</br>
This version will be uninstalled. </br></br>
It can be uninstalled by installing KB4577586 update too.</br>
### Available Archives
Unfortunately we don't have collected them. There are lots of files, for different Windows versions.
