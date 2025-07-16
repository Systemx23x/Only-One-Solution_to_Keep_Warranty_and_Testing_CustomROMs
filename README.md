## Only-One-Solution_to_Keep_Warranty_and_Testing_CustomROMs

## HowToDo with all Included


Hi,<br>

This is a Tutorial 4 Peoples they would dont Loose their Warranty of Device with DSU Sideloader Option.<br>


## What i Need 4 This Solution?<br>

- Android Platform Tools 4 Windows or Linux 4 PC/Laptop<br>
Download Here >>>>>> <a href=https://developer.android.com/tools/releases/platform-tools>Android Platform Tools Download</a><br>


- Vegabobo DSU Sideloader App 4 Android<br>
Download Here >>>>>>  <a href=https://github.com/VegaBobo/DSU-Sideloader/releases/tag/2.03>DSU Sideloader APP Download</a><br>
Attention with the Modules >>>> They only Work in Magisk with Android 13 Flashed in Magisk Manager (Warranty Lost,when you Modify Device)<br>

- Device Drivers of your Device for Windows<br>
Download Here >>>>>>  <a href=https://developer.samsung.com/android-usb-driver>USB Driver Download</a><br>

- BackUp Software 4 Samsung 4 PC/Laptop<br>
Download Here >>>>>>  <a href=https://www.samsung.com/de/apps/smart-switch/>SmartSwitch Download</a><br>

Thats in the Base all what we Need!!!!!!<br>

Or use the Full Package with Full Setup created By Me<br>
Download Here >>>>>> <a href= https://c.1und1.de/@1157988897574099954/E6kNgL5EAyarLmFYYV8CmA>Full Package Download</a><br>


<br>


## So let me Explain First what Necsessary 4 You >>>>>
````
 A brief explanation of what it's all about: DSU (Dynamic System Update) is a standard feature integrated by Android developers into the Android developer options. The Vegabobo app allows us to easily install custom ROMs as a second operating system with little interaction, without changing or affecting the original system on your device in any way. Of course, in order to be able to launch custom ROMs via the DSU sideloader, we need an unlocked bootloader. This slightly restricts the basic functions of KNOX on Samsung as long as it is open. 
 NOTE: If you unlock the bootloader on your Samsung device, your warranty will not be voided as long as you do not modify the device with custom files.
 The DSU Sideloader can be used without any concerns, as it won't modify your device in a way that would affect your warranty. So, to put it simply, if you root your device or install a custom recovery like TWRP, etc., your warranty will be voided, and you won't receive a replacement for damage, loss, etc. 
 While there are providers who will replace devices despite this, this usually involves a one-time fee. Furthermore, if you modify the device, KNOX sets a flag in the bootloader, which then severely restricts the operating system's security features through KNOX, and applications like SamPass, SamWallet, banking apps, etc., will no longer work.
 For security reasons, this cannot be handled with custom files at the moment. In this regard, we can use the DSU Sideloader to install any custom ROM and test its functionality. 
 There are even custom GSIs that include internal system rooting and allow a rooted system alongside the STOCK ROM, it all depends on the custom ROM you choose. So think about whether you want to modify your device or whether you'd rather keep your warranty. 
 Not every device thread allows for significant modification, simply because the developer doesn't offer support.
 ````


<br>

 
## This is the procedure for non-modified devices (warranty remains intact)
 ````
 - Make a BackUp of your Samsung Device with SmartSwitch
 - Goto Phone Information >> Software Information and Tap 7 Times on Build Information to Enable Developer Options
 - Go in Settings to Security Options and Disable Auto Locking
 - Now Enable in Developer Options the Funktions >>> USB-Debugging & OEM-Unlock
 - Install Android-Plattform-Tools,Samsung-Drivers to your System on PC/Laptop 
 (When you use Windows Copy the Tools to C:\Windows\System32 & C:\Windows\SysWOW64) than you can use Them System Wide in your Complete   System with Terminal. You can do it so >>>>> Open Terminal as Administrator >>> Change with 
 "cd X:\xxx\xxx\platform-tools-latest-windows\platform-tools\" & give these Commands "adb kill-server" & "xcopy *.* /F/R/X C:\Windows\System32" & "xcopy *.* /F/R/X C:\Windows\SysWOW64" and you have done it for System Wide useability.
 - Now Connect Device with PC/Laptop and Open Terminal, and give the Command "adb devices" and Confirm on Device the Notification and give Command again "adb devices" now you see that >>>>> 1#.jpeg
 - Now you give Command "adb reboot -p" (This Power Off the Device without Rebooting).
 - Now you let Connect Device with PC/Laptop and Hold Pushed Volume Up & Volume Down with more Times Pushed Power Button to start the Download Mode and in this Long Time Pushed Volume Up you can Unlock your Bootloader, Confirm and All Done (Attention all Datas would be Deleted).
 - Now Device are Rebooting in Recovery Mode and show you that you are would make a Factory Reset, Confirm That and Wait if the Device Rebooting in System.
 - Make the First Setting Up of Android System.
 - - Goto Phone Information >> Software Information and Tap 7 Times on Build Information to Enable Developer Options
 - Go in Settings to Security Options and Disable Auto Locking
 - Now Enable in Developer Options the Funktions >>> USB-Debugging
 - Now Connect Device with PC/Laptop and Open Terminal, and give the Command "adb devices" and Confirm on Device the Notification and give Command again "adb devices" now you see that >>>>> 1#.jpeg
 - Now you have a Clear Android System (Restore Data or Not, Think when you Lock the Bootloader again, you Lost your Datas even, and must Restore them).
 - Install the Vegabobo DSU Sideloader APK on your Device, and Start it and Set it Up, on the Storage i Preffer create a Directory Called "DSU" and Confirm, and Confirm, and the APP is Usable.
 - So USB-Debugging and the APP are Ready to USE.
 - Download some Custom ROM/GSI/System Image, and equal wich Format of Archive it has (img,gz,xz,zip,tar), Put it on Device in the Created Directory "DSU" with your PC/Laptop, when you have Download it with that, when you have Download it with Android than use File Explorer to Push them to DSU Directory.
 - Now Open Vegabobo DSU Sideloader APP and choose the Image File to Installation, than you Enable Userspace and give them a Size like   25GB or 50GB, thats a thing of your Device Space that you have. (Your Choice).
 - When you have done This, Push on Install Button.
 - Now you become a Notification that Say give Command to start Installation >>>>> Open Terminal and give that Command 
 "adb shell sh "/storage/emulated/0/Android/data/vegabobo.dsusideloader/files/install" >>> Now the Setup starts.
 - When it Finished, goto Notificationbar and Look at "Dynamic System Update" and Push "Reboot" and start into Second System.
 - When the Second System are Started Look into Notificationbar at "Dynamic System Update" and Push "Reboot" and start into STOCK System.
 - So you would Change the Systems, when you would Install a other ROM/GSI/SYSTEM than in Notificationbar at "Dynamic System Update" and Push "Discard" and the Second Installation would be Completly deleted, and You can Install a new one.
 ````
 ## That All of the Solution that not Void your Warranty, and let You Freely Install/Test Custom ROMs on Your Device.
 

 ## INFO >>> When a Installed Custom ROM not would Boot, than it wouldt Work with your Device, than Setup a other!!!! And Remember dont Modify anything even you use the Second System, than you lost your Warranty.

 ## A lot of Resources for Android you can Test.
 
 <a href=https://sourceforge.net/projects/andyyan-gsi/>AndyYans GSI - LineageOS</a><br>
 <a href=https://sourceforge.net/directory/gsis/>GSI Index - Sourceforge</a><br>
 <a href=https://developer.android.com/about/versions/16/gsi-release-notes?hl=de#downloads>Google Android 16 Beta GSI</a><br>
 <a href=https://github.com/musabcel/android_rom_list>Android ROM Index</a><br>
 <a href=https://github.com/phhusson/treble_experimentations/wiki/Generic-System-Image-%28GSI%29-list>GSI ROM Index - phhussen</a><br>
 <a href=https://github-wiki-see.page/m/phhusson/treble_experimentations/wiki/Generic-System-Image-%28GSI%29-list>Github Wiki - GSI Index</a><br>
 <a href=https://github.com/devadigax/awesome-android-custom-rom>Awesome CROM Index</a><br>
 <a href=https://magiskzip.com/gsi-list-phhusson/>phhussen GSI Index</a><br>
