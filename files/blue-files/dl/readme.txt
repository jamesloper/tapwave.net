Softick Blue Files 1.07 Readme File
----------------------------

(c) Copyright by Dmytro Pohromskyy 2002-2005. All Rights reserved.
* Softick Blue Files, Softick are trademarks of Dmytro Pohromskyy.

* Palm OS, HotSync, Tungsten are registered trademarks and Palm is a trademark 
of PalmOne, Inc. 

All other brand names, product names or trademarks are the property of 
their respective owners. 

1.What is Softick Blue Files

Softick Blue Files lets you wirelessly transfer files between your Palm
powered device and any Bluetooth device, including PC and Mac computer
using Bluetooth File Transfer service.

Softick Blue Files implements Bluetooth File Transfer server application.
Bluetooth File Transfer client is implemented in most Bluetooth stack on
the market.

2. System requirements

Softick Blue Files requires Palm OS 5.x.x handheld with Bluetooth radio module. 
It was tested on Palm Tungsten T, T2, T3, Palm Zire 72, Tapwave Zodiac/Zodiac 2, 
PalmOne Treo 650, Sony Clie UX series.

Softick Blue Files does NOT require Palm Desktop software installed.

Softick Blue Files requires 100K of storage space on Palm OS handheld and 256K heap.

3. Installation

 a. Unpack archive to some temporary folder
 b. You need to install:

 	BlueFiles.prc, 	a Softick Blue Files application 
	vfs-export.prc, an external cards access plugin (VFS)
	mem-export.prc, provides access to RAM and ROM databases

	files to your handheld using HotSync (r) technology. After installation
	Softick Blue Files will be accessible in Unfiled category in the application
	launcher.

 c. Press HotSync button on the cradle to install program files to your handheld PC.
 d. Launch Softick Blue Files on handheld.

3.2 Uninstallation

  To remove Softick Blue Files you need to:
  	1. Remove Softick Blue Files as any other Palm OS application via Launcher
  	   Delete menu.
	2. Softick Blue Files uses number of plugins to provide access to files and
	   folders. These plugins may be shared with other Softick application, please
	   check your product documentation about this. Currently during Softick 
	   Blue Files uinstallation these plugins don't removed from the system and you
	   need manually remove them using any file manager.

	   Plugin list (at time of writing)

	   1. vfs-export.prc           Provides access to external storage cards (SD/MMC, 
	   							   Compact Flash, Memory Stick)
	   2. mem-export.prc		   Provides access to the internal memory.

4.Known issues:
  Make sure to turn on '&' translation if you are going to use Softick
  Blue Files on Mac OS X or Linux.

5. Disclaimer

This software is provided without warranty. We will not take responsibility 
for any form of damage or loss that occurs when/by using or not using this 
software including but not limited to data/information loss, loss of profit, 
hardware or media damage.

6. Contact

If you have any questions, suggestions or problems, please e-mail us at:

    support@softick.com

For more information, please visit our site. The latest version can be 
downloaded at: 

    http://www.softick.com

7. History
    1.07:
    	* Fixed freezing on very large file transfer on some handhelds
    	* Softick Blue Files now can store incoming OBEX objects on 
    	  storage cards. The size of these objects isn't limited by
    	  main memory size. This is very usefull for transferring MP3 files
    	  from Windows Explorer.
    	* Softick Blue Files now can reference cards by index rather by 
    	  volume label. It is possible to specify /@@1/Incoming in default 
    	  path to store all incoming files in /Incoming folder on the first 
    	  card.
    1.06:
    	* Fixed fatal exceptions after browsing large folders
    	* Fixed Treo 650 and Mac OS compatibility problem
    1.05
		* Alarms now disable when connection is established
	    * Default destination for received objects in "//Card1/Folder1"
		* Progress indication for Get and Put.
		* mem-export plugin provides access to memory databases
		* Fix: Storage Card absence now is non fatal error
		* Fix: No plugin fatal error
		* Interface changes
		* Extended errors
		* Fix: Card arrive/removal notifications handled properly
	    * Fix: National symbols support
		* Fix: minor bugs
    1.02:
    	* OBEX Object Push support (Windows, MacOS, Linux, PocketPC)
		* Trusted device list (Access restriction)
		* Support '&' symbols conversion in file names under Linux and Mac OS X 10.3.5 and 10.3.6 (see notes)
		* Better national symbols support
		* Mac OS X 10.3.6 support
		* Added workaround for PalmOS 5.4 devices  (Tungsten T5, Treo 650)
		* Minor bugs fixes

	1.01
		* Fixed compatibility problem with Mac OS X 10.3.5
		* Fixed compatibility problems with Linux KDE Bluetooth

	11 Oct 2004 First public beta