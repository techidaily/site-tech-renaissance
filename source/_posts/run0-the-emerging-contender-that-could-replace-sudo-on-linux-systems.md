---
title: "Run0: The Emerging Contender That Could Replace Sudo on Linux Systems"
date: 2024-08-27 20:49:33
updated: 2024-08-29 11:49:51
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2c72878e4c5b851b7d621c520b7075b9d80e911d0e1db9a60b0603055e403b62.jpg
---

## Run0: The Emerging Contender That Could Replace Sudo on Linux Systems

### Quick Links

* [What’s Wrong With Sudo?](https://extra-guidance.techidaily.com/updated-metaverse-vs-multimeva-unveiling-their-comparative-features/)
* [What run0 Does Differently](https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-7-plus-with-imei-code-by-drfone-ios/)
* [Using run0](https://apple-account.techidaily.com/how-to-sign-out-of-apple-id-on-iphone-13-mini-without-password-by-drfone-ios/)
* [Will run0 replace sudo?](https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-motorola-moto-e13-device-by-drfone-android/)

### Key Takeaways

* run0 is a new systemd command intended to replace sudo, offering elevated permissions for commands.
* run0 uses systemd-run as a back end, launching processes as transient, short-lived services.
* run0's security benefits are compelling, but it won't replace sudo entirely for a very long time.

 On April 24, 2024, Lennart Poettering posted [a description](https://mastodon.social/@pid%5Feins/112353324518585654) of a new systemd command, called run0\. It’s a replacement for sudo. Here’s what you need to know about the latest systemd controversy.

##  What’s Wrong With Sudo?

 The sudo command seems to have been around forever. It actually dates back to the 1980s. It lets you run commands or programs as though you were either the owner of the command, or a member of the group of the command. Importantly, if the actual owner of the command has elevated permissions and capabilities, the command will run with those elevated permissions. It’s as if their elevated privileges have been bestowed upon you temporarily.

 By default, the user you impersonate is [the superuser, root](https://digital-screen-recording.techidaily.com/updated-2024-approved-entrance-video-analysis-review/). Originally, sudo stood for “superuser, do.” That changed when later developments allowed you to use sudo to impersonate any user. Its name now means “substitute user, do,” but it’s almost always used to impersonate root.

 For a command or app to be able to run with elevated permissions by regular users, either the SUID or GUID bits, or both of them, need to be set on the command. And of course, the user in question must be [permitted to use the sudo command](https://instagram-clips.techidaily.com/new-2024-approved-social-media-momentum-linking-igtv-and-fb/).

 The elevated or privileged code is run in the execution context of the calling user, so it runs in an environment intended to run unprivileged code. That in itself is a security concern. Also, if the command isn’t written to correctly respect its elevated permissions, or it doesn’t clean up after itself thoroughly and correctly, other vulnerabilities can arise. One well-known attack vector [exploits poorly written or poorly configured](https://tbhaxor.com/exploiting-suid-binaries-to-get-root-user-shell/) SUID binaries to obtain a root shell.

##  What run0 Does Differently

 The run0 command isn’t a new command as such, it’s a new way to invoke an existing command. It’s a [symbolic link](https://twitter-videos.techidaily.com/2024-approved-the-quick-guide-to-capturing-and-storing-twitter-animated-content/) to a long-standing [systemd](https://youtube-video-recordings.techidaily.com/customize-your-youtube-view-adjust-speed-settings/) component called systemd-run. As its name suggests, this runs or launches other processes. run0 is a front end to this command.

 Processes launched by run0 run as transient, short-lived services. The moment your command returns to the terminal, you’re back to being a regular user. There’s no “grace period” of authentication like there is with sudo. If you use sudo and enter your password, subsequent uses of sudo in the same terminal and within the sudo timeout period don’t require authentication. The timeout period varies from distro to distro, but values of 5 to 15 minutes are common. With run0, you authenticate every time.

 Another difference is authentication is handled by polkit, the systemd application-level policy toolkit. Where possible, this authentication is off-board from the session that is running the target command. The elevated command is run in a forked pseudo-terminal, so it’s encapsulated and isolated. Virtually nothing of the user’s execution context is available to the launched command, apart from the $TERM [environment variable](https://media-tips.techidaily.com/effortless-format-transformation-how-to-seamlessly-switch-from-mpeg-4-to-mpeg/). Likewise, the authentication credentials are not passed into the execution context of the launched command.

 Commands that are elevated and executed in this way don’t need to have their SUID or GUID bits set, nor to be compliant and thorough regarding their internal clean-up. It’s all handled by run0.

 With sudo, you can make regular users into unrestricted superusers, or you can give them limited superuser powers by [dictating which commands they can use sudo with](https://snapchat-videos.techidaily.com/new-in-2024-advanced-techniques-to-save-snapchat-stories-on-devices/). You can achieve this type of granularity with polkit, too.

##  Using run0

 To use run0 you need to be running systemd version 256, or better yet, the bug-fixed version 256.1\. Version 256.1 is rolling out as an update at the time of writing, and fresh installations of some Linux distributions include 256.1 as standard. You can check your version with this command.

systemctl --version

![Finding the systemd version on the linux command line](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/1.png) 

 Using run0 is almost the same as using sudo. You precede the command you want to launch with “run0”, and provide your password.

run0 ls
                    

 If you’re using a graphical desktop environment, the prompt for your password is a dialog box.

![The run0 authentication dialog in GNOME](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/2.png) 

 The terminal text background changes color to force home the message you’re using escalated privileges. Note that it returns to the usual background colors once the command has been completed.

![Output from a command launched by run0, showing the text's colored background](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/3.png) 

 You can use the --background option to turn off the background color, or change it to an [ANSI color combination](https://en.wikipedia.org/wiki/ANSI%5Fescape%5Fcode#8-bit) of your choice.

 To see white text on a blue background, use this ANSI sequence.

run0 --background=“44;1” ls

![Output from a command launched by run0, with a blue text background](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/4.png) 

 To run the same command with no color highlighting, omit the ANSI sequence, but make sure you leave the “=” sign.

run0 --background= ls

![Output from a command launched by run0, with no colored background on the output text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/5.png) 

 Typing run0 with no command parameters effectively logs you in as root.

run0

![Issuing run0 without command line paramters to effectively log in as root](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/6.png) 

 Note the change in the command prompt. You can return to your regular user status by typing exit and hitting Enter, or hitting Ctrl+D.

![Exiting from the root session and returning to regular user status](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/7.png) 

 If you use run0 on a Linux computer without a desktop environment, the prompt for your password happens in the terminal window.

![Authenticating on the command line on a Linux installtion with no graphical desktop environment](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/8.png) 

##  Will run0 replace sudo?

 Commands do get supplanted over time. In fact, sudo replaced its much older predecessor, [su](https://extra-support.techidaily.com/maximize-your-listening-experience-ios-podcast-mastery-for-2024/), which had been part of Unix-like operating systems since 1971\. But nobody is expecting run0 to swoop in and oust sudo. sudo is too deeply entrenched to go away quickly.

 The security benefits are compelling at first glance, but, without the removal of sudo and SUID binaries from your computer, just adopting run0 isn’t going to make much of a difference to your security stance. That’s like fitting a better door beside your existing, flawed, door.

 The “authenticate every time, all the time” requirements are likely to see some pushback from the user base, even if it is a more secure way to work. Ironically, polkit—the authentication module—uses SUID binaries, and has had [its own security issues](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-4034).

 That seems to be the very definition of something that cuts both ways. It’s a poke in the eye for polkit and a slap in the chops for SUID binaries.

 Even so, I can still see a point in the future where run0 is the new standard and sudo has been, well, not replaced exactly. But maybe relegated to a position of lower standing.

 run0 is arguably the better way to do escalation of privileges, but sudo is baked into the Linux-psyche of its users. Even when I’m thinking of run0, I find myself typing sudo.

 Perhaps we should all alias sudo to point to run0?

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
