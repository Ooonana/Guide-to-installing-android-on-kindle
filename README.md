# Guide-to-installing-android-on-kindle
A guide, translation for original project.



In XDA, there are people who translated this project first. but it is outdated and is missing a few important infos.

Important: I did not make this. This is just a guide to the project. original developer is ygjsz. you can find him [here](https://space.bilibili.com/33072537/upload/opus) and [here](https://github.com/ygjsz)
Important 2: Do NOT try this if your device doesn't support it. The device listed here is
pw2, pw3, voyage, basic 7, basic 8, oasis 1, kindleXmigu 
Note: This is a fork project. Original project link: [kdroid.club](http://kdroid.club/)



Instructions

I am gonna assume the device is pw3, so the file name should be kpw3.20230303.zip

## 1.Preparing 

1. Jailbreak your Kindle. I personally used [winterbreak](https://kindlemodding.org/jailbreaking/WinterBreak/)
2. Set up mrpi and install Kual. The process is included in the winterbreak site

3. Download the Kdroid.zip file on the release page. unzip it.

(If you get a virus detection error, your computer denys you, follow these instructions: make an empty folder. then open virus settings -> exclusion -> add exclusion folder and select the folder you created. Move the zip file to the folder you created. unzip it from there.)

4. Go to kpw3.20230303 folder. inside you will see kpw3.20230303 folder. go in and you will see kpw3 folder and uboot folder. go in uboot folder. you will see main-htmlviewer.tar.gz and extension.zip.  Unzip extension.zip and put the kual extension to your kindle. Do NOT unzip main-htmlviewer.tar.gz. Put main-htmlviewer.tar.gz to the root usb to your kindle. if you are accessing your kindle via ssh, the path will be /mnt/us/

5. In your windows computer, open Kdroid folder, go to fastboot driver folder and run adb-setup-1.4.3.exe as administrator. Click Y in every question.
(If your computer fails saying 0 files copied instead of 4 files copied, check [this video](https://www.youtube.com/watch?v=31DiGhjnUxw&t=00s)

## 2. Installation 

1. Connect your kindle to computer. Exject your kindle in the windows but keep kindle plugged in to your computer.
###IMPORTANT###: Make sure your kindle is charged sufficiently. Recommend amount is over 80%.
In your kindle, open kual, click FlashAndroid. Your kindle should reboot. Then the bar will load and stop. you will hear some repeated connection/disconnection sounds.
(Just to check, open device manager in your windows. you will see android bootloader)

2. Go back to kpw3.20230303 folder. go to the kpw3 folder and run start.exe. you dont need to run it as a administrator. After you run it, unless your windows system language is Chinese, you will see some broken characters.

Info: The window are supposed to show 
###正在进行安卓系统升级, 当前系统: 原生系统
###1. 升级安卓系统
###2. 升级安卓系统并重置安卓系统
###3. 升级原生系统
###4. 升级安卓&原生系统
###5. 升级安卓&原生系统并重置所有系统
###6. 转换为安卓系统
###7. 转换为原生系统
###8. 转换为双系统
###9. 重置安卓系统
###A. 重置原生系统
###B. 写入授权数据
###C. 写入Z05 U-Boot
###0. 退出
###请选择 (-c):

Translation:

1. Upgrade Android system
2. Upgrade Android system and reset Android
3. Upgrade Kindle (native) system
4. Upgrade both Android & Kindle systems
5. Upgrade both Android & Kindle systems and reset everything
6. Switch to Android system only
7. Switch to Kindle (native) system only
8. Switch to dual system (Android + Kindle)
9. Reset Android system
A. Reset Kindle (native) system
B. Write authorization data
C. Write Z05 U-Boot (bootloader)
0. Exit

(If your kindle isnt detected/the start.exe dosent show this and show one line, force reboot your kindle by pressing button for long time)

(More info about option 8. For kindle pw3 3gb users, 2gb will be allocated to android and 1gb will be allocated to kindle naive system.

3. Enter 8 and press enter. The system will do it's thing. While running do NOT try to unplug, close the program, turn off computer, force reboot kindle. This may brick your kindle. The process might take up to 5 minutes. When the process ends, kindle will reboot itself. And you will see your kindle displaying CRACKDROID. 

# 3.Setting up.

1. The language will be chinese. So go to settings, (click gear icon) and select 语言. Change language to English.
2. In the below, touch □. you will see bunch of settings. on the top, select other, select jailbreak button. then select e ink and select power off.
Yeah, you will see two power off button. select the right side. The message will pop up in chinese. Select the right one.
3. When the screen goes blank, press power button for one sec. the kindle will now boot to Kindle OS.



