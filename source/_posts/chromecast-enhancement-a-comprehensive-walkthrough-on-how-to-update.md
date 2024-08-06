---
title: "Chromecast Enhancement: A Comprehensive Walkthrough on How to Update"
date: 2024-08-03 19:50:53
updated: 2024-08-05 12:49:26
categories:
  - BestProducts
description: "This Article Describes Chromecast Enhancement: A Comprehensive Walkthrough on How to Update"
excerpt: "This Article Describes Chromecast Enhancement: A Comprehensive Walkthrough on How to Update"
thumbnail: https://thmb.techidaily.com/6e815c1b64efb14276b71fc721777a9cc6b2edabdceffdbe6557dc25c31661ee.jpg
---

## Chromecast Enhancement: A Comprehensive Walkthrough on How to Update

Close 

###  What to Know

* Install the**Google Home** app on an iOS or Android device. Power on the Chromecast device and connect it to the same Wi-Fi network.
* Open the app. Locate the Chromecast device. Tap the**device** icon for an overview. Tap the**Gear** for the settings.
* Tap the**three horizontal dots** . Tap**Reboot** . During the reboot, the Chromecast dongle downloads the latest firmware.

 This article explains how to prompt an automatic update of the Chromecast firmware using the iOS and Android Google Home app. It also includes information on forcing an update on Windows, Mac, and Linux computers. These instructions apply to all generations of Chromecast and Chromecast Audio.

##  How to Update Your Chromecast Firmware Automatically 

 Google automatically pushes out new Chromecast firmware, so in most instances you should have the latest available version. However, such rollouts are often staggered, so the latest firmware version may take time to install. Here's what you can do to try and prompt an automatic update.

1. Go to Google’s Chromecast support page to check the latest firmware version available for your Chromecast device.
2. If you haven’t already,[ download the Google Home iOS app](https://apps.apple.com/app/google-home/id680819774) or the[ Google Home Android app](https://play.google.com/store/apps/details?id=com.google.android.apps.chromecast.app) .
3. Ensure your Chromecast is powered on and ready to receive a Cast signal.
4. Make sure your smartphone and your Chromecast are both connected to the same Wi-Fi network.  
 To quickly check both your smartphone and Chromecast are connected to the same Wi-Fi network, open a cast-enabled app such as YouTube and tap the**Cast** icon. Your Chromecast device should appear. If it's not showing, you may need to reconnect your Chromecast to the network.
5. Open the smartphone app and locate your Chromecast device, then tap the device icon to get an overview of it.
6. Tap the**gear** icon to open device settings.
7. Scroll to the bottom of the page to reveal the Cast firmware version. This is the current firmware your device is running.  
![Living Room TV, Settings Gear icon, Firmware info in Google Home for iOS](https://www.lifewire.com/thmb/kKB8RQrShQtNz7sRkUDHR5T30A8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_how-to-update-chromecast-4628168-8f681ebf21354b27a25dd209fd25fdab.jpg)
8. Compare your device’s firmware with the latest available version on Google’s Chromecast support page (step 1). If the firmware version on the Chromecast support page is newer (a greater number) than the build you have on your device, you can try to encourage an automatic update via the Google Home app.  
 If both versions are the same, you have the latest available firmware and don't need to do anything else.
9. To try and encourage an automatic update, make sure you’re still in the Device settings page (step 5).
10. Tap the**three horizontal dots** icon.
11. A pop-up window will launch with additional options. Tap**Reboot** to[ reset your Chromecast device](https://www.lifewire.com/reset-chromecast-4165369) .  
![Menu dots and Reboot option in Google Home app on iOS](https://www.lifewire.com/thmb/6JkzuC7a6vqCKCMypvLk2zJseHk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-update-chromecast-4628168-9ae7970733f04b3fb4a7ec8ca35414a5.jpg)
12. Your Chromecast dongle will shut itself down and automatically restart. During this process, it will try to download and install the latest available firmware.
13. If the firmware is available, the installation process will show on your connected TV.  
 Unfortunately, there is no audible indicator for a Chromecast Audio dongle
14. Once the update is complete, you'll be able to use your Chromecast as normal.
15. To check your Chromecast is now running the latest firmware, repeat steps 3 through 5.  
 As noted, Google rolls out firmware updates in stages. If the update hasn't yet landed for your device, wait a few days and try the process again.
16. That's it! Your Chromecast should now be automatically updated.

##  How to Force a Chromecast Firmware Update 

 If new Chromecast firmware is available, but your device hasn't updated, you can try to force your Chromecast to download it. 

 This process is a little more complicated than an automatic update, and it’s not guaranteed to work. However, it’s certainly worth trying if you can see the firmware is available but it hasn’t yet pushed to your Chromecast.

##  Force a Chromecast Update on Mac and Linux 

1. Check Google’s Chromecast support page to see the latest available firmware version for your Chromecast device.
2. Ensure your Chromecast is powered on and ready to receive a Cast signal.
3. Be sure you have an iOS or Android device with the Google Home app installed, and make sure it's connected to the same Wi-Fi network as your Chromecast dongle.
4. Launch the Google Home app, then locate and tap the Chromecast you want to update to get a device overview.
5. Tap the**gear** icon to open device settings.
6. Scroll to the bottom of the device settings page to see the Chromecast firmware details and IP address.
7. Check your Chromecast firmware against the latest available version on the Chromecast support page (step 1). If newer firmware is available, you can now try to force a Chromecast update.  
Take note of your Chromecast device's IP address (step 6).
8. To try and force an update via a Mac or Linux PC, power on your machine and ensure it's connected to the same Wi-Fi network as your Chromecast dongle.
9. Launch the Terminal app (macOS, Linux) and type the following command, replacing \[IP ADDRESS\] with your Chromcast's IP address:  
 curl -X POST -H “Content-Type: application/json” -d ‘{“params”: “ota foreground”}’ http://[IP ADDRESS]8008/setup/reboot -v
10. Press**Enter** .
11. Terminal will now check to see if new firmware is available for your specific Chromecast device. If it is, Terminal will instruct the Chromecast to download and install the new firmware.  
 This process can take some time, so leave Terminal running and do not disconnect your Chromecast.
12. Once finished, you will see “Process Completed” at the bottom of the Terminal window. Your Chromecast should now be running the latest firmware.

##  Force a Chromecast Update on Windows 

Follow steps 1-7 above before proceeding.

1. To force a firmware update via Windows PC, turn it on and make sure it’s connected to the same network as your Chromecast.
2. Search for "**Windows Powershell** " and select**Windows PowerShell** to launch it.
3. Type in the following command, replacing \[IP ADDRESS\] with your Chromecast’s IP address:  
 Invoke-WebRequest -Method Post -ContentType “application / json” -Body ‘{“params”: “ota foreground”}’ -Uri “http: // [IP ADDRESS]: 8008 / setup / reboot” -Verbose -UserAgent ” curl “
4. Press**Enter** .
5. Windows PowerShell will now instruct your Chromecast to try and retrieve and install the latest firmware.  
 This process can take some time, so be sure to leave Windows PowerShell running and your Chromecast connected.
6. Once complete, you can cross reference your Chromecast's firmware against the Chromecast support page. If the update was successful, both versions will be the same.  
 This process may take a couple of attempts to work. If your firmware hasn't updated the first time, feel free to try again. Alternatively, leave the dongle connected for a few days to see if it will automatically update.
7. That's it! Your Chromecast should now be running the latest firmware.

 FAQ

* How do I update Chromecast without Wi-Fi?  
 Attach a Chromecast compatible USB cable from the Ethernet adapter to the Chromecast device. Then attach an[ Ethernet cable](https://www.lifewire.com/what-is-an-ethernet-cable-817548) from the router to the Ethernet adapter. After everything is connected and plugged in, you should be able to update.
* Can I update Hulu using Chromecast?  
 Yes. Open the[ Google Home app](https://www.lifewire.com/connect-google-home-to-chromecast-4173604) on your mobile device. Select**Devices** and choose Chromecast. Select**Device Card Menu** \>**Settings** \> look for**Cast firmware version** . To check for Hulu updates, follow the steps for your iOS or Android mobile device.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

Tell us why!

 Other  Not enough details  Hard to understand 

 Submit 

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
