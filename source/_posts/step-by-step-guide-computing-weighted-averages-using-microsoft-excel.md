---
title: "Step-by-Step Guide: Computing Weighted Averages Using Microsoft Excel"
date: 2024-08-28T04:35:39.480Z
updated: 2024-08-29T04:35:39.480Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3c08a238b64ec62b2aa9f38ae909ae6c80252893c9fb975f46ca921fe1059ab2.jpg
---

## Step-by-Step Guide: Computing Weighted Averages Using Microsoft Excel

### Quick Links

* [What is a Weighted Average?](https://extra-guidance.techidaily.com/new-mastering-the-ritual-of-independent-instagram-sound-creation/)
* [Let's Look at an Example](https://fox-access.techidaily.com/updated-dji-drone-artistry-unlocked-first-20-free-lutts-available/)

 A weighted average is one that takes into account the importance, or weight, of each value. This article will show you how to use Excel's SUMPRODUCT and SUM functions individually and how to combine the two to calculate a weighted average.

##  What is a Weighted Average?

 A weighted average is an average that takes into account the importance, or weight, of each value. A good example would be calculating a student's final grade based on their performance on a variety of different assignments and tests. Individual assignments usually don't count as much towards a final grade as the final exam---things like quizzes, tests, and final exams will all have different weights. The weighted average is calculated as the sum of all of the values multiplied by their weights divided by the sum of all of the weights.

 The following example will demonstrate how to use Excel's SUMPRODUCT and SUM functions to calculate a weighted average.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Let's Look at an Example

 For our example, let's look at a student's quiz and exam scores. There are six quizzes each worth 5% of the total grade, two exams each worth 20% of the total grade, and one final exam worth 30% of the total grade. The student's final grade will be a weighted average, and we will use the SUMPRODUCT and SUM functions to calculate it.

 As you can see in our table below, we've already assigned the relative weights to each quiz and exam in the D column.

![Excel table showing scores and weights assigned to several quizzes and exams](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-01.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step One: Calculate the SUMPRODUCT

 First, let's look at how the SUMPRODUCT function works. Start by selecting the cell where you want the result to appear (in our example, that's cell D13). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUMPRODUCT" function.

![On the Formulas tab, click Math &amp; Trig, then select SUMPRODUCT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-02.png) 

 The "Function Arguments" window will appear.

![the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-03.png) 

 For the "Array1" box, select the student's scores. Here, we're selecting all the cells with actual scores in the C column.

![In the Array1 box, select the cells with the grades](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-04.png) 

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, use the "Array2" box to select the weights of the quizzes and exams. For us, those are in the D column.

![In the Array2 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-05.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 Click "OK" when you're done.

![Click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-06.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 The SUMPRODUCT function will multiply each score by its corresponding weight and then return the sum of all of those products.

![The Excel table now shows the SUMPRODUCT value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-07.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
###  Step Two: Calculate the SUM

 Now let's look at how the SUM function works. Select the cell where you want the results to appear (in our example, that's cell D14). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUM" function.

![On the Formulas tab, click Math &amp; Trig, then select SUM](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-08.png) 

 The "Function Arguments" window will appear.

![The Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-09.png) 

 For the "Number1" box, select all of the weights.

![In the Number1 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-10.png) 

 Click "OK."

![click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-11.png) 

 The SUM function will add all of the values together.

![The Excel table now shows the SUM value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-12.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step Three: Combine the SUMPRODUCT and SUM to Calculate the Weighted Average

 Now we can combine the two functions to determine the student's final grade based on their scores and the weights of each score. Select the cell where the weighted average should go (for us that's cell D15) and then type the following formula into the function bar.

=SUMPRODUCT(C3:C11,D3:D11)/SUM(D3:D11)

![select the weighted average cell and then type the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-13.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Press "Enter" after typing the formula to view the weighted average.

![The table now shows the weighted average](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-14.png) 

 And there you have it. It's a fairly simple example, but it's a good one for showing how weighted averages work.

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
<li><a href="https://youtube-stream.techidaily.com/new-guide-to-avoidable-exposure-hiding-objects-and-faces-online/"><u>[New] Guide to Avoidable Exposure  Hiding Objects and Faces Online</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-muting-background-noise-in-skype-sessions-for-2024/"><u>[New] Muting Background Noise in Skype Sessions for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-premier-camera-drones-10-filmmakers-dream-fleet-for-2024/"><u>[New] Premier Camera Drones #10  Filmmakers' Dream Fleet for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-halt-facebook-ads-in-vids-your-guide/"><u>[Updated] Halt Facebook Ads in Vids  Your Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ideal-ios-tools-2023s-leading-choices-for-psp-gameplay-for-2024/"><u>[Updated] Ideal iOS Tools  2023'S Leading Choices for PSP Gameplay for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-android-audio-archive-a-curated-list-of-top-6-free-music-downloading-apps/"><u>[Updated] In 2024, Android Audio Archive  A Curated List of Top 6 Free Music Downloading Apps</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-top-5-drone-racing-headsets-ultimate-vr-experience/"><u>2024 Approved  Top 5 Drone Racing Headsets  Ultimate VR Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/direct-injection-di-injects-fuel-directly-into-the-combustion-chamber-allowing-for-precise-control-over-timing-and-quantity-of-fuel-delivery/"><u>Direct Injection (DI) Injects Fuel Directly Into the Combustion Chamber, Allowing for Precise Control over Timing and Quantity of Fuel Delivery.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-latest-tools-to-spot-chatgpt-in-your-classroom-or-workplace/"><u>Discover the Latest Tools to Spot ChatGPT in Your Classroom or Workplace</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-latest-hp-laptop-driver-software-for-windows/"><u>Download & Install Latest HP Laptop Driver Software for Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-update-your-pl2303-serial-port-emulator-for-windows-os/"><u>Easy Guide: Update Your PL2303 Serial Port Emulator for Windows OS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-guide-get-your-acer-wi-fi-drivers-downloaded-today/"><u>Easy Installation Guide: Get Your Acer Wi-Fi Drivers Downloaded Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-of-wacom-intuos-pro-software-on-windows-10-devices/"><u>Easy Installation of Wacom Intuos Pro Software on Windows 10 Devices</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-setup-secure-your-razer-mamba-drivers-today/"><u>Effortless Setup: Secure Your Razer Mamba Drivers Today</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/effortless-tips-for-storing-vimeo-videos/"><u>Effortless Tips for Storing Vimeo Videos</u></a></li>
<li><a href="https://win-amazing.techidaily.com/enhance-performance-with-updated-intel-graphics-control-panel-download-now-on-windows-1011/"><u>Enhance Performance with Updated Intel Graphics Control Panel - Download Now on Windows 10/11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/find-and-set-up-the-latest-hp-printer-drivers-for-windows-operating-systems/"><u>Find and Set Up the Latest HP Printer Drivers for Windows Operating Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/fixing-xbox-accessory-drivers-solutions-for-compatibility-with-windows-10-11-and-8/"><u>Fixing Xbox Accessory Drivers: Solutions for Compatibility with Windows 10, 11, and 8</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-7-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 7? Heres the Best Fixes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-driver-software-for-zexmt-bluetooth-adapter-on-windows-10-7-and-8/"><u>Free Download: Compatible Driver Software for Zexmt Bluetooth Adapter on Windows 10, 7 & 8</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-drivers-for-realtek-cards-on-windows-10/"><u>Free Download: Compatible Drivers for Realtek Cards on Windows 10</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-geforce-rtx-3080-driver-download-for-microsoft-windows-platforms-10-8-and-7/"><u>Free GeForce RTX 3080 Driver Download for Microsoft Windows Platforms (10, 8 & 7)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-canon-imageclass-mf8470-c5560-series-printer-drivers-for-your-pc/"><u>Get the Latest Canon ImageCLASS MF8470 C5560 Series Printer Drivers for Your PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-free-logitech-g29-steering-wheel-drivers-for-win-10-8-and-7/"><u>Get Your Free Logitech G29 Steering Wheel Drivers for Win 10, 8 & 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722969656876-get-your-intel-b560-coffee-lake-motherboard-and-chipset-for-free/"><u>Get Your Intel B560 Coffee Lake Motherboard & Chipset for FREE!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/getting-started-how-to-set-up-brother-dcp-l25nwd-printer-in-windows-using-its-latest-driver-download/"><u>Getting Started: How to Set Up Brother DCP-L25nwd Printer in Windows Using Its Latest Driver Download</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-get-and-set-up-windows-7-bluetooth-driver-download-fast/"><u>How to Get and Set Up Windows 7 Bluetooth Driver Download Fast</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-photosmart-7520-easy-download-of-your-official-printing-software/"><u>HP Photosmart 7520: Easy Download of Your Official Printing Software</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-6s-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an iPhone 6s Without Apple ID Password?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivofrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your VivoFRP Lock</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/key-techniques-for-storing-lol-matches/"><u>Key Techniques for Storing LOL Matches</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-and-compatible-zebra-printer-software-updates-for-windows-systems/"><u>Latest & Compatible Zebra Printer Software Updates for Windows Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-enhanced-wi-fi-network-drivers-for-windows-versions-win11-10-8-and-7-download-here/"><u>Latest Enhanced Wi-Fi Network Drivers for Windows Versions: Win11, 10, 8 & 7 - Download Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/mastering-the-art-of-repairing-issues-with-realtek-high-definition-video-drivers/"><u>Mastering the Art of Repairing Issues With Realtek High Definition Video Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/msi-z3-pro-motherboard-driver-pack-secure-download-now/"><u>MSI Z3# Pro Motherboard Driver Pack - Secure Download Now</u></a></li>
<li><a href="https://win-amazing.techidaily.com/navigating-zebra-technologies-support-for-zp450-drivers-secure-downloads-and-updates-explained/"><u>Navigating Zebra Technologies' Support for ZP450 Drivers - Secure Downloads & Updates Explained</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-add-tags-to-your-videos-best-mp4-editors-for-windows-and-macos/"><u>New Add Tags to Your Videos Best MP4 Editors for Windows and macOS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/new-release-brothers-scanning-device-drivers-on-windows-platform/"><u>New Release: Brother's Scanning Device Drivers on Windows Platform</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-easy-corsair-void-pro-driver-installation-for-windows-users/"><u>Quick & Easy Corsair Void Pro Driver Installation for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-simple-guide-downloading-wacom-drivers/"><u>Quick and Simple Guide: Downloading Wacom Drivers</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolve-your-hogwarts-legacy-hiccups-6-expert-fixes-to-stop-the-game-from-stuttering/"><u>Resolve Your Hogwarts Legacy Hiccups: 6 Expert Fixes to Stop the Game From Stuttering</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-connectivity-find-download-and-update-drivers-for-netgear-wireless-adapters-today/"><u>Seamless Connectivity: Find, Download & Update Drivers for NETGEAR Wireless Adapters Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/speedy-installation-of-usb-cam-drivers-download-now-for-seamless-use/"><u>Speedy Installation of USB Cam Drivers - Download Now for Seamless Use</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-installing-updated-intel-graphics-drivers-for-win-10win-11-systems/"><u>Step-by-Step Guide: Installing Updated Intel Graphics Drivers for Win 10/Win 11 Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-updating-your-canon-pixma-printer-drivers-with-speed-and-simplicity/"><u>Step-by-Step Guide: Updating Your Canon PIXMA Printer Drivers with Speed and Simplicity</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722960814452-step-by-step-instructions-downloading-and-installing-steelseries-arctis-5-audio-drivers-today/"><u>Step-by-Step Instructions: Downloading & Installing SteelSeries Arctis 5 Audio Drivers Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/thrustmaster-t300-driver-software-free-download-and-installation-guide-for-windows-1110-users/"><u>ThrustMaster T300 Driver Software - Free Download & Installation Guide for Windows 11/10 Users</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-and-resolving-lg-printer-driver-errors-on-windows-11-8-and-7/"><u>Troubleshooting and Resolving LG Printer Driver Errors on Windows 11, 8 & 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-your-intel-hd-graphics-4400-card-with-new-drivers-free-downloads-available/"><u>Update Your Intel HD Graphics 4400 Card with New Drivers – Free Downloads Available</u></a></li>
<li><a href="https://win-amazing.techidaily.com/updated-canon-pixma-mg490-driver-installation-manual-for-windows-users/"><u>Updated Canon PIXMA MG490 Driver Installation Manual for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-your-nvidia-rtx-2080-driver-version-for-optimal-gaming-experience-in-windows-10-or-11/"><u>Upgrade Your NVIDIA RTX 2080 Driver Version for Optimal Gaming Experience in Windows 10 or 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-your-skills-painlessly-navigating-through-windows-updates/"><u>Upgrade Your Skills: Painlessly Navigating Through Windows Updates</u></a></li>
</ul></div>
