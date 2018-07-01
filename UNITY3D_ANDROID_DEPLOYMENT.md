Android Deployment Steps for Unity

1:
In Unity
Edit -> Preferences -> External Tools

Browse for Android SDK Tools or Download if unavailable

SDK
- Download Android Studio
once downloaded open
Configure -> SDK Manager -> 
	Appearance & Behavior -> System Settings -> Android SDK ->
		SKD Platforms

			Choose your target platform (Preferably of the phone you are testing on)
			To find the target version of your phone go into your phone settings
			In Android Studio
				Settings -> About Phone -> Software information -> Android Version
				
NOTE: Issues encountered with the versioning of the Android SDK Tools.
	- Version 25.2.5 currently works with the Target API level 28
	- Version 26.*.* does not currently work

JDK
- Download JDK (tested on Java SE Development Kit 8u171 - Windows x86 version)
- Java SE Development (should download as JDK 1.8 from the working tested version)

2: 
In Unity
Edit -> Project Preferences -> Player

Update the Identification Package Name to a unique name fitting the format
com.CompanyName.ProjectName

Ensure that the target platform version matches your test phone version

3: 
In Unity
File -> Build Settings -> Select Android -> Switch Platform

4:
Plug in phone via usb
- Ensure Developer mode is switched on
- Ensure USB debugging is also switched on in the developer settings
- Ensure the Phone is unlocked and has accepted permissions with the computer its plugged into

