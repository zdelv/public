<meta charset="utf-8">
<style>
      body {
          position: relative;
          max-width: 1000px;
          margin-left: auto;
          margin-right: auto;
          padding-bottom: 500px;
          margin-top: 60px;
          font-size: 14px;
          font-family: Roboto, 'Bitstream Vera Sans', sans-serif;
          font-weight: 100;
          line-height: 150%;
          color: #9CAFB7;
          /*color: #1B6887;*/
      }

      html {
            background: #141518;
          > background: #000E14;
          \*background: #202020;*\
      }

      a:link, a:visited {
          color: rgb(221, 221, 221);
      }

      a:hover {
          color: #FFF;
      }

      h1 {
          margin-top: 40px;
          padding-bottom: 2px;
          border-bottom: 2px solid;
          font-size: 18px;
          color: #fff;
      }

      .md h2 {
          font-size: 17px;
          margin-top: 25px;
          color: #fff;
      }

      .md h3 {
          font-size: 15x;
          margin-top: 20px;
          margin-bottom: -3px;
          color: #fff;
      }
 
      div.view {
         position: absolute;
         width: 268px;
         text-align:center;
      }

      div.window {
         font-family: Tahoma, Arial, sans-serif; 
         text-align:left;
         background: #EEE;
         border: 1px solid #44A;
         color: #000;
         font-size: 11px;
         padding-left: 0px;
         padding-right: 1px;
         padding-bottom: 0px;
         padding-top: 20px;
         position: relative;
         -webkit-box-shadow: 0px 4px 18px 0px rgba(0,0,0,0.42);
         -moz-box-shadow: 0px 4px 18px 0px rgba(0,0,0,0.42);
         box-shadow: 0px 4px 18px 0px rgba(0,0,0,0.42);      
      }

      div.window iframe {
         width: 355px;
         height: 450px;
         background: #FFF;
         border: none;
         margin-bottom: -120px;
         transform-origin: 0 0;
         -ms-transform-origin: 0 0;
         -webkit-transform-origin: 0 0;
         transform: scale(0.75,0.75);
      }

      div.window div.icon {
         position: absolute; 
         top: 1px; 
         padding-left: 3px;
         font-size: 14px;
      }

      div.window div.caption, div.window div.tab {
         position: absolute; 
         top: 2px; 
         width: 100%; 
         text-align: center;
         padding-bottom: 4px; 
         color: #444;
      }

      div.window div.tab {
         text-align: left;
         padding-left: 30px;
      }

      div.window div.menu {
         background: #DDD;
         border-top: 1px solid #555;
         width: 100%;
      }

      div.window div.buttons {
         position: absolute;
         right: 4px;
         top: 0px;
         font-size: 18px;
      }

      code {
         font-size: 11.5px; 
         font-family: Monaco, monospace;
         color: #fff;
      }

      .md pre.tilde {
         background: #25272a;
         border-top: 1px solid #343434;
         border-left: 1px solid #343434;
         border-right: 1px solid #343434;
         border-bottom: 1px solid #343434;
      }

      :not(.code) > code {
        margin-left: -2px;
        margin-right: -2px;
        padding-left: 3px;
        padding-right:3px;
        /*background: rgba(255,255,255,0.1);*/
      }
 
      .code {
         border: 2px solid; 
         background: #678; 
         padding: 10px; 
         margin-bottom: 15px; 
         margin-top: 15px;
      }

      dt {
         font-weight: bold;
      }

      dd {
         margin-top: 5px;
         margin-bottom: 15px;
      }

      .title {
        font-weight: bold;
        font-size: 30px;
        padding-bottom: 3px;
        padding-right: 8px;
        color:#fff;
      }

      .line {
         margin-left: 34px;
         margin-top: -5px;
         width: 180px;
         height: 1px;
         display: inline-block;
         background: linear-gradient(to right, rgba(0, 0, 0, 0), rgb(238, 238, 238) 75%, rgb(238, 238, 238) 100%);
      }

      .md svg.diagram {
          stroke: #fff;
          fill: #fff;
          font-size: 13px;
          font-family: Roboto Mono, IBM Plex Mono, Anonymous Pro;
      }
      
      @import url('https://fonts.googleapis.com/css?family=Yanone+Kaffeesatz:300');
</style>
<link href="https://fonts.googleapis.com/css?family=IBM+Plex+Mono|Roboto|Roboto+Mono" rel="stylesheet">

**Imaging Documentation**


Overview
========================= 

Diagram
-------------

***************************************************************************************************************************************
*  .----------.  1. Image     .------.  2. DEP Enrollment    .--------.
* | New Laptop +-----------> | Imaged +-------------------> | Enrolled +----.
*  '----------'  Using USB    '------'  Setup in JSS prior   '--------'     | 3. Naming
*             Drive with macOS          to imaging laptop                   | Laptop is renamed
*                                                                           | following correct naming
*     .---------------------------------------------------------------------' conventions
*     | 
*     v
*  .-----. 4. AD Binding    .-----. 5. Policies     .---------.
* | Named +--------------> | Bound +-------------> | Completed |
*  '-----' Laptop is bound  '-----' Misc policies   '---------'
*               to AD               are installed
***************************************************************************************************************************************


Laptops will follow the diagram above during their imaging procedure. The following is just a rough overview. Find the individual section for more information on each part

1. A new/old laptop that needs to be imaged will be booted into a macOS High Sierra or newer (HFS+ if not already APFS). From there a macOS installer should be set to install onto the target drive.
2. After being imaged the laptop will reboot, install firmware, and begin Setup Assistant. After choosing a language, keyboard type and wireless network, a DEP Configuration pane should appear. This will enroll the laptop into JSS.
3. After enrollment, logging into the laptop with tech will begin the "Policy Cascade". This will begin by reconing the device and going through each step. The first step involves user-intervention for inputting a name for the device. This can be customized for each type of device and allows for easy input and accurate error correction.
4. With a correct name, the laptop will begin to bind itself to AD. Because of macOS and AD rules, the full computer name **MUST** be less than 15 characters and the name is automatically all lowercase, regardless of case.
5. After AD Binding, the laptop is now completely configured for our infrastructure and now can enter into customizable policies. This is where we enter free reign for how we want these devices configured

The main parts with this new DEP imaging path is that every laptop **MUST** be AD Bound (security and ease-of-use reasons) and that the name **MUST** be correct prior to AD Binding.

Goals
-------------
The two main goals with the new imaging procedure are **Modularity** and **Flexibility**

The process is modular in the sense that it:

1. Can be tweaked either in small parts or completely and still retain the shape from the diagram above.
2. Can be expanded upon easily

The process is also flexible as it can:

1. Accept most new additions easily.
2. Change easily with how Apple chooses to allow their devices to be imaged.

Together these two _should_ allow for this to be relatively future proof, in the sense that the main concept and paths taken should be compatible for the next major macOS updates.


!!! note Note
    Please read this **ENTIRE** document prior to going through with imaging a laptop. Some of it is not necessarily out of order, but happens concurrently and needs to be setup at the same time/prior to the other steps.

    This document just follows the chart above, of which it follows a single device through all of the stages of imaging, and not necessarily the same steps needed for setup.

Imaging
=================

USB Drive Preparation
-------------
All imaging is done via an external USB drive running macOS. The following must be met for the process to work

+ If going from HFS+ to APFS on a device that never has had APFS, you must have:
    1. 10.13.3 or higher
    2. HFS+ (**NOT APFS**)
    3. The newest macOS installer (the full installer, not the 50MB stub)

+ If going from APFS to APFS (device currently has APFS), you must have:
    1. 10.13.3 or higher
    2. APFS **OR** HFS+
    3. The newest macOS installer (the full installer, not the 50MB stub)

To setup the USB Drive you must do the following:

!!! note **Note**
    If there are any padlocks in System Preferences that need to be unlocked, it is expected (read: unwritten) for you to unlock them.



+ On an **APFS** formatted macOS 10.13.3 or above device:
    1. Install the newest full macOS installer.
    2. In terminal, run:
        ~~~~~~~~~~~~ bash
        $ sudo /Applications/Install\ macOS\ [NAME OF MACOS].app/Content/Resources/startosinstall \
                --applicationpath /Applications/Install\ [NAME OF MACOS].app \
                --agreetolicense \
                --nointeraction \
                --converttoapfs NO \
                --volume /Volumes/[USB DRIVE NAME]
        ~~~~~~~~~~~~ 
        (The '\' are just line breaks, for readability. You can just leave them)

        This will slowly count up to 100% then reboot repeatedly. It will completely install a fresh copy of macOS onto the target drive. It also makes sure to _not_ convert to apfs, as the to-be imaged laptops can not detect APFS volumes.
    3. Go through Setup Assistant and **DO NOT** go through DEP/Configuration. This is to keep the USB imager out of JSS.
    4. Create the tech account, with the standard password
    5. Log into tech and proceed to copy the macOS installer from the laptop you imaged the USB with (it should have it) into /Applications/
    6. Open System Preferences > Users & Groups > Login Options and click 'Join' next to Network Account Server. Click 'Open Directory Utility' then go to Edit > Enable Root User. Hit enter twice on the dialog (as in no password). This will enable the root user with no password for easy logging in with admin privledges.
    7. Log out of tech then login to root (no password). Go into Users & Groups, then add the macOS Installer that you copied earlier into startup items for 'System Administrator' (root). You can also add Disk Utility here if you don't have a script made to automatically wipe the SSD on login. (I didn't make one)
    8. Also in Users & Groups > Login Options, Set Login Window to be Name & Password. This is kinda nice as it means you can login even faster (no profile bubbles to click into).

!!! tip **Disabling External Accounts**
    + This will remove the dialog on boot to allow an external account (ie one not from the USB drive) to access files on the current device. With sometimes over 30+ accounts this takes awhile to remove the dialog
    + If this USB is going to be used enmass on already-in-use devices with network accounts (see: nearly every student device) this is a 100% necessary step. If not, then skip this.
    + These steps are expecting you to be on the USB drive, but the bulk of them can be done on another device and carried over by another USB drive.



    1. Log into JSS and enter into Computers > Configuration Profiles. In there you will find a profile named "Disable External Accounts" (it might be under AJH - First Boot or something like that). Enter into the profile and click download.
    2. The System Preferences window _might_ see this profile and immediately prompt you to install it, but if it doesn't just click on it and follow the dialogs to install it. It will be unverified, but that is because the USB drive lacks the Root Cert for the JSS Built-In Cert Authority (not a big deal, this isn't being used by a end user)

After the drive is setup, reboot and login to root with no password and verify that the following work/exist:

1. root with no password works 
2. Install macOS automatically opens
3. (optional) Disk Utility automatically opens
4. (optional) External Profiles are disabled (check the profile exists)


On-Site Imaging
------------

With a to-be imaged device on hand, just like how it was tested, boot into the macOS USB drive. After booting in, complete the following steps, in order:

1. Open/Click on Disk Utility and hit Command(⌘)+2 (or go into View > Show all devices). Select the SSD for the device you would like to image, not the volume. It should be named something like Apple SSD.
2. Format the volume and make sure it is **HFS+** and **GUID Partition Map**. This ensures that the macOS Installer will format the drive over to APFS during the installation (it can be flaky with it already APFS for some reason)
3. After the drive is erased, begin the macOS installer and make sure it is pointed at the internal SSD not the USB drive. You may need to hit 'Show all devices' during the prompt.
4. The computer should now begin imaging. For instructions on what to do after it reaches Setup Assistant, go onto DEP Enrollment.


!!! note Troubleshooting
    If you run into problems with the install failing for unknown reasons (goes to recovery with a restart button or something of the sort) try the following:
        + Do what Apple tells you to do and just restart. It should pick back up into the install process and it _might_ make it past the part it got stuck on. I've had this work once for no real reason. Just try it ¯\_(ツ)_/¯
        + Re-image it with the flash drive. This one rarely works, as the issue probably will persist with the same hardware. Still try it, and also throw in a SSD format/wipe to try.
        + Grab/make another USB drive. Honestly this one is the only one that has consistently worked. Some of the drives for some reason refuse to work on some laptops. No real idea why, just that this is the #1 fix I have found.


DEP Enrollment
=================

Device Enrollment Protocol (DEP)
----------
Apple's solution to laptop setup (whether that be imaging or not) is the Device Enrollment Protocol. This is just a fancy name for a tiny payload that can be forced on a laptop during Setup Assistant. Not much can be done with DEP (at least through JSS) but what it does allow is for us to enroll devices into JSS instantly after boot.

The positives of DEP:
+ Apple supports it
+ It isn't scripted (all GUI based in JSS)
+ Automatic: 
    + Profile creation (ie tech or teachers, if we decided to do that)
    + User Approved Mobile Device Management Profiles (see UAMDM)

The negatives of DEP:
+ For it to be worth it, the laptop must be imaged, or a fresh unbox
+ For what Apple plays it up to be, it honestly does not do that much. There is very little ability to do arbitrary commands/installations/policies off of it. This means that the overwhelming majority of the "imaging" is just policy cascading through specific smart grouping.
+ Depending on your PoV, the lack of scripting is a nightmare
+ It is slow
+ Overly dependent on external servers (DEP is 100% external, minus the setup to JSS)
+ JSS seems to be lacking some of the abilities that DEP has (that being computer naming prior to enrollment)

DEP works through [Apple School](school.apple.com) (previously known as dep.apple.com) where a device is enrolled via serial number. For iPads this gives us both Supervision and Management over the device. For MacBooks, all we get is just a list of the devices we own, and a tie into the Setup Assistant. This list of devices is then hooked up to our local JSS server via a token, which allows JSS to pull all of the devices into a 'PreStage Enrollment'. 

**PreStage Enrollments** are what allow us to select specific devices and place them into a group to be enrolled after being picked up by DEP during Setup. There are also a few other settings that are modifiable, like AD Binding, Local Users, Purchasing Info, and a few others. No option allows for an arbitrary script to be run after it finishes though, leaving us with a bit of a problem when it comes to automating the entire imaging process. To put it simply, PreStage Enrollments are just JAMF's implementation of the client side part of DEP. Nothing special exists with it. If Apple decides to give or remove the ability to do something then JAMF is at their will. Because of the lack of scripting and command input, we have to use what is called (or I call) Policy Cascading. See Naming for more info on this.

To say that DEP is woefully underwhelming is an understatement. For what it's worth, DEP is a solution to a problem, and that's about it. Its not pretty nor is it fast, but it (sometimes) works and until Apple creates another solution for imaging/setup, we're stuck with it.



User Approved Mobile Device Management (UAMDM)
----------

User Approved Mobile Device Management (UAMDM) is Apple's new form of MDM profile, that is given more permissions than a standard profile. Currently (as of 10.13.6) UAMDM profiles give you the ability to apply Kernel Extensions (kexts) to a device. They do not have any other permissions that are different from a standard MDM profile. They were introduced into macOS in 10.13.3.

To get a UAMDM profile you must do one of the following:
+ Enroll a device through DEP, whether it be before or after imaging (profiles -N)
+ Be grandfathered into it by upgrading from 10.13.2 or below to 10.13.3 or higher.
+ Manually approve the profile by opening profiles in System Preferences and clicking approve.

While UAMDM profiles may seem kinda useless for our infrastructure currently, as we do not use any kexts, Apple did announce during WWDC 2018 that testing applications can soon require that an MDM profile be User Approved for them to accept the testing environment. Since we plan on using almost all of our devices for testing, we need to make sure that any imaging or repairs we do to a laptop leave it with a UAMDM profile. JSS has the ability to detect when a profile is not User Approved, and we can scope to that to check that every laptop has the correct profile.


The best explanation for UAMDM that I have read would be a problem that Apple created where its only real solution is DEP.

Setup
------------

Setting up DEP is sometimes easy and other times an absolute nightmare. JAMF's implementation of the MDM side of DEP is definitely buggy and has its issues, so you will need to probably fight through them.

To go from nothing to a work PreStage Enrollment do the following:
1. Start by going to JSS > Computers > PreStage Enrollments and create a new PreStage.
2. Give it a reasonable name (you will need it later)
3. Make sure the Device Enrollment Program Instance is set to Amherst Mobile Devices



Naming
=================
For AD Binding to be organized, the name must be sanitized _prior_ to binding. This means that the most important step out of all of this is the naming of the laptop, and because of this, the bulk of the customized scripting was spent there.

Scripts
------------


AD Binding
=================

Policies
------------


Policies
=================

Setup
------------

<!-- Markdeep: --><style class="fallback">body{visibility:hidden;white-space:pre;font-family:monospace}</style><script src="markdeep.min.js"></script><script src="https://casual-effects.com/markdeep/latest/markdeep.min.js?" type="text/javascript"></script><script>window.alreadyProcessedMarkdeep||(document.body.style.visibility="visible")</script>
