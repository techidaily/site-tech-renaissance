---
title: "Step-by-Step Guide: Resolving Mozilla Thunderbird's Launch Failures"
date: 2024-08-03 15:47:45
updated: 2024-08-05 11:33:35
categories:
  - BestProducts
description: "This Article Describes Step-by-Step Guide: Resolving Mozilla Thunderbird's Launch Failures"
excerpt: "This Article Describes Step-by-Step Guide: Resolving Mozilla Thunderbird's Launch Failures"
thumbnail: https://thmb.techidaily.com/d24bf389d1254603d8aad9f86f16f5f0cd9be072e2e5d71e92f6bedcfed5d098.jpg
---

## Why Isn't Mozilla Thunderbird Launching? Find Out How to Rectify It
 Some[Mozilla Thunderbird](https://www.lifewire.com/mozilla-thunderbird-review-1173071) users have noticed an issue where Thunderbird appears to freeze—it's not responding or starting up even though it appears to be running. Thunderbird usually returns the error message:  

 These troubleshooting steps apply to Thunderbird version 68.8.0 and earlier.

## How to Make Thunderbird Start Again

 If Thunderbird is running but not responding, or it's saying that your profile is in use, here are the steps you should try.

1. [Close and reopen Thunderbird](https://support.mozilla.org/bm/questions/1048707) . It's always worth a try to close the application and then reopen it. Select**Thunderbird** \>**Quit Thunderbird** from the menu, and then reopen the application to see if this solves the problem.
2. [Close Thunderbird on another computer](https://support.mozilla.org/en-US/questions/1067045) . If Thunderbird is running with your profile on another computer, close Thunderbird on that machine by selecting**Thunderbird** \>**Quit Thunderbird** from the menu. Then log in again on the computer you're using.
3. [Kill Thunderbird's background processes](https://www.lifewire.com/how-to-force-quit-a-program-in-windows-2625781) . Even if you closed Thunderbird, the application might be running in the background. Ending Thunderbird processes that are running in the background might fix the issue. On a Windows system, do this from the[Task Manager](https://www.lifewire.com/task-manager-2626025) .  
 With macOS, force quit all Thunderbird processes from the[Activity Monitor](https://www.lifewire.com/use-activity-monitor-to-track-mac-memory-usage-2260880) . On a Unix system, use the **killall -9 thunderbird** [command](https://www.lifewire.com/what-is-a-command-2625828) in a terminal.
4. [Restart the computer](https://www.lifewire.com/why-does-restarting-seem-to-fix-most-computer-problems-2624569) . Restarting is an easy fix that often solves many technical issues.
5. [Start Thunderbird in Safe Mode](https://www.lifewire.com/safe-mode-uninstall-extensions-thunderbird-1173165) . This starts the application without certain extensions or add-ons that caused the error message. Open in Safe Mode and see if this solves the problem.
6. [Delete the parentlock file](https://support.mozilla.org/en-US/questions/1139817) . The parentlock file is created every time Thunderbird starts and should automatically clear after you close Thunderbird. If Thunderbird fails to complete the closing process properly, the parentlock file isn't deleted. Manually delete the file to see if this solves the problem.  
 On a Mac, open a terminal window and type **cd** and a space. From the Thunderbird folder in Finder, drag the icon to the terminal window so that the path to the folder immediately follows the cd command. Press**Enter**  to run the command and then enter**rm -f .parentlock** .  
 On Unix, delete**parentlock** and **lock**  from the Thunderbird folder.
7. [Use the LockHunter file-unlocking tool](https://lockhunter.com/download.htm) . Use LockHunter to see what's restricting Thunderbird from opening, and then shut down any holds on the program so that you can use it normally.
8. [Repair Thunderbird folders](https://www.lifewire.com/repair-folders-thunderbird-1173102) . A folder may be corrupted. Repair Thunderbird folders to see if this solves the problem.
9. [Create a new Thunderbird profile](https://support.mozilla.org/en-US/questions/1227161) . There may be something wrong with your Thunderbird profile. Profiles in Thunderbird and Firefox store information about your settings, mail, accounts, and extensions you installed. If something goes wrong,[back up your profile](https://www.lifewire.com/back-up-thunderbird-settings-1173141) and then create a fresh one.
10. [Reinstall Thunderbird](https://support.mozilla.org/en-US/questions/1085697) . If none of these troubleshooting steps solves the problem,[move your profile](https://www.lifewire.com/move-thunderbird-profile-1173159) folder to a different location to back it up. Then, reinstall Thunderbird without a profile present. Everything should start fresh.

## Causes of Thunderbird Not Responding

> Thunderbird is already running, but not responding. To open a new window, you must close the existing Thunderbird process or restart your system.

 Often, closing Thunderbird returns this additional error:

> Your Thunderbird profile cannot be loaded. It may be missing or inaccessible.

 If you have these problems, here's what might be happening and what you can do to fix these issues.

 If Thunderbird refuses to start and returns an error about an existing Thunderbird process, it's because Thunderbird thinks your profile is in use. The cause might be a stale profile lock that was left after Thunderbird crashed. This means Thunderbird didn't close properly or correctly clean up temporary files. Additional processes are running in the background and Thunderbird is confused, frozen, and unable to open.

 Another cause might be that Thunderbird is running on another computer. Thunderbird can't run on more than one computer at the same time with the same profile.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

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
