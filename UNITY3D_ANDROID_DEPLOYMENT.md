Android Deployment Steps for Unity

One:
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
				Settings -> About Phone -> Software information -> Android Version

JDK
- Download JDK
- Java SE Development - I have tested version 1.8 working version

Two: 
Edit -> Project Preferences -> Player

Update the Bundle Identifier to a unique name fitting the format
com.CompanyName.ProjectName

Ensure that the target platform version matches your test phone version

Three: 
File -> Build Settings -> Select Android -> Switch Platform

Four:
Plug in phone via usb
- Ensure Developer mode is switched on
- Ensure USB debugging is also switched on in the developer settings

