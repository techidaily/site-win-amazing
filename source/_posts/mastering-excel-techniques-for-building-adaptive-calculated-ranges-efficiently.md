---
title: "Mastering Excel: Techniques for Building Adaptive Calculated Ranges Efficiently"
date: 2024-08-28T04:34:33.664Z
updated: 2024-08-29T04:34:33.664Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3d668bfb6eaaff582ac6a3ef0ec269ab4610d6df4de409efc683d784a7434cf5.jpg
---

## Mastering Excel: Techniques for Building Adaptive Calculated Ranges Efficiently

### Quick Links

* [Create a Dynamic Defined Range in Excel](https://screen-activity-recording.techidaily.com/updated-unveiling-the-art-of-smoothing-zoom-screenshots/)
* [Create a Two Way Dynamic Defined Range](https://instagram-video-files.techidaily.com/new-quicken-video-playback-on-instagram-apps-for-2024/)

 Your Excel data changes frequently, so it's useful to create a dynamic defined range that automatically expands and contracts to the size of your data range. Let's see how.

 By using a dynamic defined range, you will not need to manually edit the ranges of your formulas, charts, and PivotTables when data changes. This will happen automatically.

 Two formulas are used to create dynamic ranges: OFFSET and INDEX. This article will focus on using the INDEX function as it is a more efficient approach. OFFSET is a volatile function and can slow down large spreadsheets.

##  Create a Dynamic Defined Range in Excel

 For our first example, we have the single-column list of data seen below.

![Data range to make dynamic](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/one-column-list.png) 

 We need this to be dynamic so that if more countries are added or removed, the range automatically updates.

 For this example, we want to avoid the header cell. As such, we want the range $A$2:$A$6, but dynamic. Do this by clicking Formulas > Define Name.

![Create a defined name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-2.png) 

 Type "countries" in the "Name" box and then enter the formula below in the "Refers to" box.

=$A$2:INDEX($A:$A,COUNTA($A:$A))

 Typing this equation into a spreadsheet cell and then copying it into the New Name box is sometimes quicker and easier.

![Using a formula in a defined name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-details.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
###  How Does This Work?

 The first part of the formula specifies the start cell of the range (A2 in our case) and then the range operator (:) follows.

=$A$2:

 Using the range operator forces the INDEX function to return a range instead of the value of a cell. The INDEX function is then used with the COUNTA function. COUNTA counts the number of non-blank cells in column A (six in our case).

INDEX($A:$A,COUNTA($A:$A))

 This formula asks the INDEX function to return the range of the last non-blank cell in column A ($A$6).

 The final result is $A$2:$A$6, and because of the COUNTA function, it is dynamic, as it will find the last row. You can now use this "countries" defined name inside a Data Validation rule, formula, chart, or wherever we need to reference the names of all the countries.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
##  Create a Two Way Dynamic Defined Range

 The first example was only dynamic in height. However, with a slight modification and another COUNTA function, you can create a range that is dynamic by both height and width.

 In this example, we will be using the data shown below.

![Data for a two way dynamic range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/data-for-two-way-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This time, we will create a dynamic defined range, which includes the headers. Click Formulas > Define Name.

![Create a defined name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-2.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 Type '"sales" in the "Name" box and enter the formula below in the "Refers To" box.

=$A$1:INDEX($1:$1048576,COUNTA($A:$A),COUNTA($1:$1))

![Two way dynamic defined range formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/second-formula.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This formula uses $A$1 as the start cell. The INDEX function then uses a range of the entire worksheet ($1:$1048576) to look in and return from.

 One of the COUNTA functions is used to count the non-blank rows, and another is used for the non-blank columns making it dynamic in both directions. Although this formula started from A1, you could have specified any start cell.

 You can now use this defined name (sales) in a formula or as a chart data series to make them dynamic.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win-amazing.techidaily.com/free-compatible-drivers-to-set-up-your-samsung-printer-on-windows-system/"><u>[Free] Compatible Drivers to Set Up Your Samsung Printer on Windows System</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-achieve-excellence-in-google-meet-hostparticipant-at-no-cost/"><u>[New] 2024 Approved  Achieve Excellence in Google Meet (Host/Participant) at No Cost</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-how-to-optimize-your-youtube-shorts-templates-effectively/"><u>[New] 2024 Approved  How to Optimize Your YouTube Shorts Templates Effectively</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-ultimate-list-of-top-5-mac-streamers-for-2024/"><u>[New] The Ultimate List of Top 5 Mac Streamers for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-mastering-youtube-video-illumination-techniques/"><u>[Updated] 2024 Approved  Mastering YouTube Video Illumination Techniques</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-mastering-the-art-of-caption-placement-in-multimedia-projects-for-youtube/"><u>[Updated] Mastering the Art of Caption Placement in Multimedia Projects for YouTube</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transforming-your-content-delivery-the-power-of-onestream/"><u>[Updated] Transforming Your Content Delivery  The Power of OneStream</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unzipping-subtitles-turning-zip-archives-into-srt-files/"><u>[Updated] Unzipping Subtitles  Turning Zip Archives Into .SRT Files</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-decoding-the-micro-video-phenomenon-on-facebook/"><u>2024 Approved  Decoding the Micro-Video Phenomenon on Facebook</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-how-to-add-titlestext-to-video-on-microsoft-photos-in-windows-10/"><u>2024 Approved  How to Add Titles/Text to Video on Microsoft Photos in Windows 10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-tactics-for-trimming-outside-fb-ads/"><u>2024 Approved  Tactics for Trimming Outside FB Ads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-top-iosandroid-apps-for-creative-photo-captions/"><u>2024 Approved  Top iOS/Android Apps for Creative Photo Captions</u></a></li>
<li><a href="https://win-amazing.techidaily.com/achieve-faster-data-transfer-speeds-download-compatible-intel-usb-30-drivers-for-windows-11-systems/"><u>Achieve Faster Data Transfer Speeds - Download Compatible Intel USB 3.0 Drivers for Windows 11 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advanced-photo-editing-how-to-clean-up-unwanted-space/"><u>Advanced Photo Editing  How to Clean Up Unwanted Space</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-music-from-xiaomi-redmi-note-13-pro-5g-by-fonelab-android-recover-music/"><u>Best Android Data Recovery - Undelete Lost Music from Xiaomi Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://win-amazing.techidaily.com/best-practices-for-updating-hp-deskjet-inkjet-printer-driver-v2700-get-the-new-version-today/"><u>Best Practices for Updating HP Deskjet Inkjet Printer Driver v2700 - Get the New Version Today!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/best-ways-to-screen-record-on-android/"><u>Best Ways to Screen Record on Android</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/blue-screen-blues-clearing-up-error-0x0000001e-on-your-computer/"><u>Blue Screen Blues: Clearing Up Error 0X0000001E on Your Computer</u></a></li>
<li><a href="https://youtube-data.techidaily.com/y-chorus-satirical-song-selections/"><u>Comedy Chorus  Satirical Song Selections</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-samsung-galaxy-a15-4g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Samsung Galaxy A15 4G</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/crafting-tales-leveraging-chatgpt-for-epic-narratives/"><u>Crafting Tales: Leveraging ChatGPT for Epic Narratives</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-hp-officejet-4655-printer-drivers-latest-updates/"><u>Download & Install HP OfficeJet 4655 Printer Drivers: Latest Updates</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-amd-vega-64-graphics-card-drivers-on-windows-solved/"><u>Download & Update AMD Vega 64 Graphics Card Drivers on Windows - Solved</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-latest-hp-officejet-pro-8620-printer-drivers-on-windows/"><u>Download and Install Latest HP OfficeJet Pro 8620 Printer Drivers on Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-asus-pce-ac68-controller-drivers-now-no-hesitation-required/"><u>Download ASUS PCE-AC68 Controller Drivers Now – No Hesitation Required</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-corsair-keyboard-driver-windows-compatible-at-no-cost/"><u>Download Corsair Keyboard Driver (Windows Compatible) at No Cost</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-logitech-steering-wheels-driver-software-for-win7-win8-and-win10/"><u>Download Logitech Steering Wheels Driver Software for Win7, Win8 & Win10</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-roccat-mouse-drivers-for-optimal-compatibility-and-features/"><u>Download Roccat Mouse Drivers for Optimal Compatibility and Features</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-latest-ft232r-usb-to-uart-driver-with-one-click-convenience/"><u>Download the Latest FT232R USB-to-UART Driver with One-Click Convenience</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-trustworthy-and-updated-drivers-for-any-epson-scanner-model/"><u>Download Trustworthy & Updated Drivers For Any Epson Scanner Model</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-and-quick-upgrade-of-pl2303-adapter-drivers-compatible-with-all-windows-versions/"><u>Easy and Quick Upgrade of PL2303 Adapter Drivers - Compatible with All Windows Versions</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-steps-to-repair-and-update-hp-screen-driver-issues-in-windows-11-8-or-7/"><u>Easy Steps to Repair and Update HP Screen Driver Issues in Windows 11, 8 or 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/elevate-your-audio-experience-on-windows-with-the-new-dolby-driver-update-available-here/"><u>Elevate Your Audio Experience on Windows with the New Dolby Driver Update - Available Here!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210904347-error-0x802a1ee9-errconnectionrefused-easy-image-based-solutions-to-get-you-connected-again/"><u>Error 0X802A1EE9 (ERR_CONNECTION_REFUSED): Easy Image-Based Solutions to Get You Connected Again</u></a></li>
<li><a href="https://win-amazing.techidaily.com/find-the-official-ricoh-c4503-printer-software-downloads-fast-latest-version/"><u>Find the Official Ricoh C4503 Printer Software Downloads Fast | Latest Version</u></a></li>
<li><a href="https://win-amazing.techidaily.com/fixing-connection-problems-how-to-update-xbox-one-controller-drivers-for-windows-versions-11-and-below/"><u>Fixing Connection Problems: How to Update Xbox One Controller Drivers for Windows Versions 11 and Below</u></a></li>
<li><a href="https://win-amazing.techidaily.com/fixing-your-usb-problems-in-windows-11-step-by-step-solution/"><u>Fixing Your USB Problems in Windows 11 - Step-by-Step Solution</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722971820763-get-the-latest-acer-display-drivers-instantly-here/"><u>Get the Latest Acer Display Drivers Instantly Here!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-asus-z170-a-motherboard-drivers-for-windows-users-versions-11-8-and-7/"><u>Get the Latest ASUS Z170-A Motherboard Drivers for Windows Users (Versions 11, 8 & 7)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-software-for-your-corsair-h80i-version-2-free-downloads/"><u>Get the Latest Software for Your Corsair H80i Version 2 - Free Downloads</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-toshiba-driver-updates-for-your-windows-based-device-here/"><u>Get the Latest Toshiba Driver Updates for Your Windows-Based Device Here!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722974130395-get-the-new-hp-universal-printing-software-for-windows-installed-today/"><u>Get the New HP Universal Printing Software for Windows Installed Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722965979919-get-your-amd-gpio-driver-now-free-and-ready-for-use/"><u>Get Your AMD GPIO Driver Now – Free & Ready for Use!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-linksys-ae1200-drivers-in-no-time-speedy-download-process-here/"><u>Get Your Linksys AE1200 Drivers in No Time - Speedy Download Process Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-pc-up-to-date-comprehensive-instructions-for-intels-usb-30-drivers-on-win11/"><u>Get Your PC Up-to-Date: Comprehensive Instructions for Intel's USB 3.0 Drivers on Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/gtx-1650-super-graphics-card-driver-download-and-upgrade-for-windows-11/"><u>GTX 1650 Super Graphics Card Driver Download & Upgrade for Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hassle-free-download-and-update-for-hid-keyboard-drivers-available-now/"><u>Hassle-Free Download and Update for HID Keyboard Drivers Available Now</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-honor-x7b-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Honor X7b Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-officejet-4655-driver-downloads-latest-versions-available-now/"><u>HP Officejet 4655 Driver Downloads: Latest Versions Available Now!</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-honor-90-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Honor 90 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-zte-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on ZTE Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sonic-sharing-adding-music-to-your-whatsapp-status/"><u>In 2024, Sonic Sharing  Adding Music to Your WhatsApp Status</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/list-of-pokemon-go-joysticks-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/newest-generic-bluetooth-driver-download-for-windows-pcs/"><u>Newest Generic Bluetooth Driver Download for Windows PCs</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-ssl-certificate-issues-for-a-safe-browsing-experience/"><u>Overcoming SSL Certificate Issues for a Safe Browsing Experience</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prime-picks-best-windows-phone-video-players-list/"><u>Prime Picks  Best Windows Phone Video Players List</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-fixes-how-to-get-and-set-up-epson-xp-830-drivers-instantly/"><u>Quick Fixes: How to Get and Set Up Epson XP-830 Drivers Instantly</u></a></li>
<li><a href="https://win-amazing.techidaily.com/samsung-windows-printer-drivers-free-download/"><u>Samsung Windows Printer Drivers - Free Download</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/sound-sovereign-review-of-high-fidelity-plug-ins/"><u>Sound Sovereign: Review of High-Fidelity Plug Ins</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722976855446-steelseries-engine-download-upgrade-your-pc-gaming-on-windows-10-today/"><u>SteelSeries Engine Download: Upgrade Your PC Gaming on Windows 10 Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-download-of-intel-cpugpu-drivers-instant-access/"><u>Step-by-Step Download of Intel CPU/GPU Drivers - Instant Access!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-process-for-installing-the-latest-audio-technica-sound-card-drivers/"><u>Step-by-Step Process for Installing the Latest Audio-Technica Sound Card Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-solutions-for-realtek-wireless-lan-driver-issues-on-various-windows-versions-fixed/"><u>Step-by-Step Solutions for Realtek Wireless LAN Driver Issues on Various Windows Versions [Fixed]</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-itel-a70-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Itel A70 for Streaming | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-5-obstacles-preventing-idevice-gift-sending/"><u>Top 5 Obstacles Preventing iDevice Gift Sending</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshoot-and-resolve-elgato-hd60-drivers-simple-steps/"><u>Troubleshoot and Resolve Elgato HD60 Drivers: Simple Steps</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-fixes-for-asus-pce-ac56-driver-problems-in-windows-1187-a-step-by-step-tutorial/"><u>Ultimate Fixes for ASUS PCE-AC56 Driver Problems in Windows 11/8/7: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-troubleshooting-upgrading-epson-printer-software-compatibility-with-windows-11/"><u>Ultimate Troubleshooting: Upgrading Epson Printer Software Compatibility with Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-tutorial-how-to-properly-set-up-arduino-software-for-windows-users/"><u>Ultimate Tutorial: How to Properly Set Up Arduino Software for Windows Users</u></a></li>
</ul></div>
