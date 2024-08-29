---
title: Enabling & Customizing Auto-Calculate & Parallel Processing
date: 2024-08-28T04:34:27.674Z
updated: 2024-08-29T04:34:27.674Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/00_lead_image_autocalc_multithread_orig.png
---

## Enabling & Customizing Auto-Calculate & Parallel Processing

By default, Excel recalculates all the formulas in your worksheet automatically when you open your worksheet or change any entries, formulas, or names on which your formulas depend. If you worksheet is large, with many formulas, this can take several seconds or minutes.

 While the formulas are being recalculated, the mouse pointer changes to an hourglass and you can’t make any changes to the worksheet.

 You may want to temporarily turn off automatic calculation to save time until you are finished entering and changing the formulas in your worksheet. This is done easily, and we will show you how.

 NOTE: If you don’t want to turn off the automatic calculation feature, and you have multiple processors in your computer, you can turn on the multi-threading feature, which could speed up the recalculation of your formulas by a little bit, depending on how many processors your computer has. We will show you how to turn on this option later in this article.

 To disable the automatic calculation feature, open Excel and click the FILE tab.

![01_clicking_file_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/01_clicking_file_tab1.png) 

 Click the Options item in the menu on the left.

![02_clicking_options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/02_clicking_options.png) 

 On the Excel Options dialog box, click Formulas in the menu on the left.

![03_clicking_formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/03_clicking_formulas.png) 

 Scroll down to the Calculation options section and select Manual to prevent the formulas from being calculated every time you make a change to a value, formula, or name or open a worksheet containing formulas.

 The following list defines the options available in the Calculation options section:

* Automatic - Calculates all dependent formulas and updates open or embedded charts every time you make a change to a value, formula, or name. This is the default setting for each new worksheet.
* Automatic Except for Data Tables - Calculates all dependent formulas and updates open or embedded charts, but it does not calculate data tables created with the Data Table feature. To recalculate data tables when this option button is selected, click the Calculate Now (F9) command button on the Formulas tab of the Ribbon or press F9 in the worksheet.
* Manual - Calculates open worksheets and updates open or embedded charts only when you click the Calculate Now (F9) command button on the Formulas tab of the Ribbon or press F9 or Ctrl+= in the worksheet.
* Recalculate Workbook before Saving - Calculates open worksheets and updates open or embedded charts when you save them even when the Manually option button is selected. If you don’t want to updating dependent formulas and charts every time you save, turn this option off.
* Enable Iterative Calculation - Sets the iterations, that is, the number of times that a worksheet is recalculated, when performing goal seeking or resolving circular references to the number displayed in the Maximum Iterations text box. For more information about goal seeking or resolving circular references, see Excel’s help file.
* Maximum Iterations - Sets the maximum number of iterations (100 by default) when the Enable iterative calculation check box is selected.
* Maximum Change - Sets the maximum amount of change to the values during each iteration (0.001 by default) when the Enable iterative calculation check box is selected.

![04_changing_workbook_calculation](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/04_changing_workbook_calculation.png) 

 You can also switch among the three main calculation options using the Calculation Options button in the Calculation section of the Formulas tab on the Ribbon. However, if you want to set the iteration options, you must use the Formulas page on the Word Options dialog box.

![05_calculation_options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/05_calculation_options.png) 

 Excel 2013 has a multi-threading feature that allows you to reduce the time it takes to calculate complex formulas. If you would rather not turn off automatic calculation, you can try using this feature (if you have multiple processors in your computer) to reduce calculation time.

 To enable the multi-threading feature, click the FILE tab and select Options to open the Excel Options dialog box, as mentioned earlier. Click Advanced in the menu on the left.

![06_clicking_advanced](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/06_clicking_advanced.png) 

 Scroll down to the Formulas section and select the Enable multi-threaded calculation check box so there is a check mark in the box. You can specify manually how many threads to use, or you can tell Excel to Use all processors on this computer.

![07_enable_multi_threaded_calculation](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/04/07_enable_multi_threaded_calculation.png) 

 If you have other programs running on your computer, you may not want to use all the processors on your computers to recalculate the formulas in your Excel spreadsheets.

 Test out different combinations of the Automatic Calculation and Multi-Threaded features to see what works best for you on your computer.

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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-innovators-intertwining-video-with-melodious-images/"><u>[Updated] 2024 Approved  Innovators Intertwining Video with Melodious Images</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-unlocking-the-secrets-behind-youtube-shorts-success/"><u>[Updated] 2024 Approved  Unlocking the Secrets Behind YouTube Shorts Success</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-unleashing-potential-advanced-tiktok-visual-enhancements/"><u>2024 Approved  Unleashing Potential  Advanced TikTok Visual Enhancements</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complete-guide-to-download-and-install-ricoh-printer-drivers-on-pcs-windows-only/"><u>Complete Guide to Download and Install Ricoh Printer Drivers on PCs (Windows Only)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/direct-injection-di-injects-fuel-directly-into-the-combustion-chamber-allowing-for-precise-control-over-timing-and-quantity-of-fuel-delivery/"><u>Direct Injection (DI) Injects Fuel Directly Into the Combustion Chamber, Allowing for Precise Control over Timing and Quantity of Fuel Delivery.</u></a></li>
<li><a href="https://location-social.techidaily.com/does-oneplus-nord-ce-3-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does OnePlus Nord CE 3 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-latest-hp-laptop-driver-software-for-windows/"><u>Download & Install Latest HP Laptop Driver Software for Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-download-latest-intel-uhd-graphics-630-driver-version-for-improved-performance/"><u>Easy Download: Latest Intel UHD Graphics 630 Driver Version for Improved Performance</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-update-your-pl2303-serial-port-emulator-for-windows-os/"><u>Easy Guide: Update Your PL2303 Serial Port Emulator for Windows OS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-guide-get-your-acer-wi-fi-drivers-downloaded-today/"><u>Easy Installation Guide: Get Your Acer Wi-Fi Drivers Downloaded Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-of-wacom-intuos-pro-software-on-windows-10-devices/"><u>Easy Installation of Wacom Intuos Pro Software on Windows 10 Devices</u></a></li>
<li><a href="https://win-amazing.techidaily.com/enhance-performance-with-updated-intel-graphics-control-panel-download-now-on-windows-1011/"><u>Enhance Performance with Updated Intel Graphics Control Panel - Download Now on Windows 10/11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/expert-advice-on-creating-impactful-hdr-portraits-for-2024/"><u>Expert Advice on Creating Impactful HDR Portraits for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/fixing-xbox-accessory-drivers-solutions-for-compatibility-with-windows-10-11-and-8/"><u>Fixing Xbox Accessory Drivers: Solutions for Compatibility with Windows 10, 11, and 8</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-driver-software-for-zexmt-bluetooth-adapter-on-windows-10-7-and-8/"><u>Free Download: Compatible Driver Software for Zexmt Bluetooth Adapter on Windows 10, 7 & 8</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-drivers-for-realtek-cards-on-windows-10/"><u>Free Download: Compatible Drivers for Realtek Cards on Windows 10</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-geforce-rtx-3080-driver-download-for-microsoft-windows-platforms-10-8-and-7/"><u>Free GeForce RTX 3080 Driver Download for Microsoft Windows Platforms (10, 8 & 7)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-canon-imageclass-mf8470-c5560-series-printer-drivers-for-your-pc/"><u>Get the Latest Canon ImageCLASS MF8470 C5560 Series Printer Drivers for Your PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-free-logitech-g29-steering-wheel-drivers-for-win-10-8-and-7/"><u>Get Your Free Logitech G29 Steering Wheel Drivers for Win 10, 8 & 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722969656876-get-your-intel-b560-coffee-lake-motherboard-and-chipset-for-free/"><u>Get Your Intel B560 Coffee Lake Motherboard & Chipset for FREE!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/getting-started-how-to-set-up-brother-dcp-l25nwd-printer-in-windows-using-its-latest-driver-download/"><u>Getting Started: How to Set Up Brother DCP-L25nwd Printer in Windows Using Its Latest Driver Download</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-get-and-set-up-windows-7-bluetooth-driver-download-fast/"><u>How to Get and Set Up Windows 7 Bluetooth Driver Download Fast</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-samsung-galaxy-s24-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Samsung Galaxy S24 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-and-compatible-zebra-printer-software-updates-for-windows-systems/"><u>Latest & Compatible Zebra Printer Software Updates for Windows Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-enhanced-wi-fi-network-drivers-for-windows-versions-win11-10-8-and-7-download-here/"><u>Latest Enhanced Wi-Fi Network Drivers for Windows Versions: Win11, 10, 8 & 7 - Download Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-version-of-asus-pce-ac68-driver-for-immediate-download/"><u>Latest Version of ASUS PCE-AC68 Driver for Immediate Download</u></a></li>
<li><a href="https://win-amazing.techidaily.com/mastering-the-art-of-repairing-issues-with-realtek-high-definition-video-drivers/"><u>Mastering the Art of Repairing Issues With Realtek High Definition Video Drivers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/melodic-memory-bank-save-and-analyze-music-files/"><u>Melodic Memory Bank  Save & Analyze Music Files</u></a></li>
<li><a href="https://win-amazing.techidaily.com/navigating-zebra-technologies-support-for-zp450-drivers-secure-downloads-and-updates-explained/"><u>Navigating Zebra Technologies' Support for ZP450 Drivers - Secure Downloads & Updates Explained</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-mastering-sound-on-your-mac-the-top-8-daws-ranked/"><u>New In 2024, Mastering Sound on Your Mac The Top 8 DAWs Ranked</u></a></li>
<li><a href="https://review-topics.techidaily.com/new-iphone-13-pro-restore-from-icloud-stuck-on-time-remaining-estimating-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>New iPhone 13 Pro Restore from iCloud Stuck on Time Remaining Estimating | Stellar</u></a></li>
<li><a href="https://win-amazing.techidaily.com/new-release-brothers-scanning-device-drivers-on-windows-platform/"><u>New Release: Brother's Scanning Device Drivers on Windows Platform</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-easy-corsair-void-pro-driver-installation-for-windows-users/"><u>Quick & Easy Corsair Void Pro Driver Installation for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-simple-guide-downloading-wacom-drivers/"><u>Quick and Simple Guide: Downloading Wacom Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamlessly-install-hp-envy-5660-device-drivers-a-user-friendly-tutorial/"><u>Seamlessly Install HP ENVY 5660 Device Drivers: A User-Friendly Tutorial</u></a></li>
<li><a href="https://win-amazing.techidaily.com/speedy-installation-of-usb-cam-drivers-download-now-for-seamless-use/"><u>Speedy Installation of USB Cam Drivers - Download Now for Seamless Use</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-updating-your-canon-pixma-printer-drivers-with-speed-and-simplicity/"><u>Step-by-Step Guide: Updating Your Canon PIXMA Printer Drivers with Speed and Simplicity</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722960814452-step-by-step-instructions-downloading-and-installing-steelseries-arctis-5-audio-drivers-today/"><u>Step-by-Step Instructions: Downloading & Installing SteelSeries Arctis 5 Audio Drivers Today</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-non-functioning-laptop-screen-answers-within-reach/"><u>The Non-Functioning Laptop Screen: Answers Within Reach</u></a></li>
<li><a href="https://win-amazing.techidaily.com/thrustmaster-t300-driver-software-free-download-and-installation-guide-for-windows-1110-users/"><u>ThrustMaster T300 Driver Software - Free Download & Installation Guide for Windows 11/10 Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-your-intel-hd-graphics-4400-card-with-new-drivers-free-downloads-available/"><u>Update Your Intel HD Graphics 4400 Card with New Drivers – Free Downloads Available</u></a></li>
<li><a href="https://win-amazing.techidaily.com/updated-canon-pixma-mg490-driver-installation-manual-for-windows-users/"><u>Updated Canon PIXMA MG490 Driver Installation Manual for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-your-nvidia-rtx-2080-driver-version-for-optimal-gaming-experience-in-windows-10-or-11/"><u>Upgrade Your NVIDIA RTX 2080 Driver Version for Optimal Gaming Experience in Windows 10 or 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-your-skills-painlessly-navigating-through-windows-updates/"><u>Upgrade Your Skills: Painlessly Navigating Through Windows Updates</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-tecno-pop-8-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Tecno Pop 8</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->