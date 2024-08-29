---
title: "Mastering Data Visualization: Crafting Tally Graphs Easily Using Excel"
date: 2024-08-28T04:34:32.460Z
updated: 2024-08-29T04:34:32.460Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## Mastering Data Visualization: Crafting Tally Graphs Easily Using Excel

### Quick Links

* [Create the Tally system](https://visual-screen-recording.techidaily.com/updated-2024-approved-segmentviewer-study-notes/)
* [Total the Groups of Five](https://tech-recovery.techidaily.com/the-insiders-roadmap-to-online-viewing-how-to-catch-every-moment-of-the-summer-olympics-in-2-groovy-ways/)
* [Total the Leftover Singles](https://facebook-video-share.techidaily.com/scripted-sentiments-for-show-summation-for-2024/)
* [Make the Tally Graph with a Formula](https://extra-tips.techidaily.com/2024-approved-boosting-tiktok-quality-with-smart-zoom-use/)
* [Hide the Helper Columns](https://techidaily.com/best-fixes-for-vivo-y200e-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/)

 A tally graph is a table of tally marks to present the frequency in which something occurred. Microsoft Excel has a large number of built-in chart types available, but it does not have a tally graph option. Fortunately, this can be created using Excel formulas.

 For this example, we want to create a tally graph to visualize the votes received by each person on a list.

![Sample data for the tally graph](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-data.png) 

##  Create the Tally system

 A tally graph is normally presented as four lines followed by a diagonal strikethrough line for the fifth tally. This provides a nice visual grouping.

 It is difficult to replicate this in Excel, so instead, we will group the values by using four pipe symbols and then a hyphen. The pipe symbol is the vertical line above the backslash character on the U.S. or U.K. keyboard.

 So, each group of five will be shown as:

||||-

 And then a single pipe symbol for a single occurrence (1) will appear as:

|

 Type these symbols into cells D1 and E1 on the spreadsheet.

![tally marks in a cell for formula referencing](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-marks.png) 

 We will create the tally graph using formulas and reference these two cells to display the correct tally marks.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Total the Groups of Five

 To total the groups of five, we will round the votes value down to the nearest multiple of five and then divide the result by five. We can use the function named FLOOR.MATH to round the value.

 In cell D3, enter the following formula:

=FLOOR.MATH(C3,5)/5

![Total the groups of five](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/floor.math_-1.png) 

 This rounds the value in C3 (23) down to the nearest multiple of 5 (20) and then divides that result by 5, giving the answer 4.

##  Total the Leftover Singles

 We now need to calculate what is left over after the groups of five. For this, we can use the MOD function. This function returns the remainder after two numbers are divided.

 In cell E3, enter the following formula:

=MOD(C3,5)

![Calculate the remainder with MOD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/singles.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
##  Make the Tally Graph with a Formula

 We now know the number of groups of five and also the number of singles to display in the tally graph. We just need to combine them into one row of tally marks.

 To do this, we will use the REPT function to repeat the occurrences of each character the required number of times, and concatenate them.

 In cell F3, enter the following formula:

=REPT($D$1,D3)&REPT($E$1,E3)

![Create a tally graph with REPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-graph-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 The REPT function repeats text a specified number of times. We used the function to repeat the tally characters the number of times specified by the groups and singles formulas. We also used the ampersand (&) to concatenate them together.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
##  Hide the Helper Columns

 To finish the tally graph, we will hide the helper columns D and E.

 Select columns D and E, right-click, and then choose "Hide."

![Hide the helper columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/hide-columns.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 Our completed tally graph provides a nice visual presentation of the number of votes each person received.

![Completed tally graph in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/completed-tally-graph.png)

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://win-amazing.techidaily.com/latest-release-usb-to-hdmi-compatibility-upgrade-now-available/"><u>[Latest Release]: USB to HDMI Compatibility Upgrade Now Available!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-dive-into-gaming-how-to-build-and-prosper-on-youtube/"><u>[New] 2024 Approved  Dive Into Gaming  How to Build and Prosper on YouTube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-unleash-creativity-with-youtube-studio-editor/"><u>[New] 2024 Approved  Unleash Creativity with YouTube Studio Editor</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-cutting-through-steps-posting-tiktok-videos-on-twitter/"><u>[New] Cutting Through Steps  Posting TikTok Videos on Twitter</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-digital-dreamscape-mapping-vrs-progress-for-2024/"><u>[New] Digital Dreamscape  Mapping VR's Progress for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-how-to-successfully-record-and-manage-internet-radio/"><u>[New] How to Successfully Record and Manage Internet Radio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-spectacular-visuals-the-power-of-tiktok-effects/"><u>[New] Spectacular Visuals  The Power of TikTok Effects</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-7-best-apps-to-go-live-on-youtube-from-iphone-or-android-for-2024/"><u>[Updated] 7 Best Apps to Go Live on YouTube From iPhone or Android for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-7-top-rated-free-mobile-apps-for-video-downloads-for-2024/"><u>[Updated] 7 Top-Rated Free Mobile Apps for Video Downloads for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-creating-immersive-iphone-360-reels-for-social-media/"><u>[Updated] In 2024, Creating Immersive iPhone 360 Reels for Social Media</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-transform-your-presence-advanced-tricks-for-live-video-graphics/"><u>[Updated] Transform Your Presence  Advanced Tricks for Live Video Graphics</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-perfect-video-gear-starting-with-beginner-cameras/"><u>2024 Approved  Perfect Video Gear  Starting with Beginner Cameras</u></a></li>
<li><a href="https://driver-error.techidaily.com/auto-load-not-permitted-by-hardware/"><u>Auto-Load Not Permitted by Hardware</u></a></li>
<li><a href="https://fox-http.techidaily.com/bebops-feathered-wings-unleashed-in-the-parrot-review/"><u>Bebop's Feathered Wings Unleashed in the Parrot Review</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/blur-faces-like-a-pro-top-free-apps-and-tutorials-for-photos-and-videos-for-2024/"><u>Blur Faces Like a Pro Top Free Apps and Tutorials for Photos and Videos for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complete-guide-to-downloading-insignia-ns-pcy5bma2-driver-on-pcs-with-windows-os/"><u>Complete Guide to Downloading Insignia NS-PCY5BMA2 Driver on PCs with Windows OS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complimentary-access-to-top-tier-sound-download-m-audios-fast-track-ultra-drivers-now/"><u>Complimentary Access to Top-Tier Sound: Download M-Audio's Fast Track Ultra Drivers Now</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722978283105-counter-current-flow-maximizes-temperature-change-and-is-highly-efficient/"><u>Counter-Current Flow Maximizes Temperature Change and Is Highly Efficient.</u></a></li>
<li><a href="https://article-files.techidaily.com/craft-impressive-images-with-photoshops-radial-distortion-features/"><u>Craft Impressive Images with Photoshop's Radial Distortion Features</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-hilarious-memes-with-these-10-awesome-apps-2023-edition-for-2024/"><u>Create Hilarious Memes with These 10 Awesome Apps (2023 Edition) for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-installation-process-for-epson-et-3760-printer-software-update-windows/"><u>Download & Installation Process for Epson ET-3760 Printer Software Update (Windows)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-epson-ds-530c89-series-printer-drivers-for-windows-11-x64-compatibility-checked/"><u>Download & Update Epson DS-530/C89 Series Printer Drivers for Windows 11 (X64) - Compatibility Checked</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-amd-ati-radeon-hd-nvidia-geforce-gtx-950-drivers-in-minutes-step-by-step-tutorial/"><u>Download AMD ATI Radeon HD nVidia GeForce GTX 950 Drivers in Minutes – Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-hp-deskjet-2600-printer-drivers-on-windows-7-8-or-10-systems/"><u>Download and Install HP Deskjet 2600 Printer Drivers on Windows 7, 8 or 10 Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-drivers-for-your-acer-aspire-5100-now-available/"><u>Download Drivers for Your Acer Aspire 5100 - Now Available</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722962475899-download-hp-deskjet-2600-printer-drivers-compatible-with-windows-7-8-and-10/"><u>Download HP DeskJet 2600 Printer Drivers Compatible with Windows 7, 8 & 10</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-logitech-g29-racing-wheel-software-compatible-with-windows-10-11-and-7/"><u>Download Logitech G29 Racing Wheel Software Compatible with Windows 10, 11 & 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/enhanced-printing-with-latest-driver-update-for-dell-single-function-lasers-2330d-and-2330dn/"><u>Enhanced Printing with Latest Driver Update for Dell Single-Function Lasers 2330D & 2330DN</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-skills-for-capturing-soundless-videography/"><u>Essential Skills for Capturing Soundless Videography</u></a></li>
<li><a href="https://win-amazing.techidaily.com/first-look-at-the-newly-released-hl-2240-driver-for-seamless-windows-compatibility-and-printing/"><u>First Look at the Newly Released HL-2240 Driver for Seamless Windows Compatibility and Printing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ing-the-script-online-video-reversals-for-2024/"><u>Flipping the Script  Online Video Reversals for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-nvidia-graphics-card-drivers-easy-download-and-update/"><u>Get the Latest NVIDIA Graphics Card Drivers - Easy Download & Update</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-wacom-drivers-in-a-flash-download-steps-unveiled/"><u>Get Your Wacom Drivers in a Flash: Download Steps Unveiled</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722963850257-get-your-wireless-connection-up-to-date-fast-and-simple-ways-to-download-and-update-card-drivers/"><u>Get Your Wireless Connection Up-to-Date: Fast & Simple Ways to Download and Update Card Drivers!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hassle-free-process-to-revamp-your-scansnap-ix5e-driver-compatibility-on-windows-systems/"><u>Hassle-Free Process to Revamp Your ScanSnap iX5e Driver Compatibility on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722977517977-how-to-easily-get-the-latest-linksys-wrt54g-drivers-downloaded-speed-up-your-network/"><u>How to Easily Get the Latest Linksys WRT54G Drivers Downloaded - Speed up Your Network</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-fix-windows-10-usb-detection-issues-a-comprehensive-guide/"><u>How to Fix Windows 10 USB Detection Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-install-ios-drivers-in-windows-10-step-by-step-guide/"><u>How to Install iOS Drivers in Windows 10 - Step by Step Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/how-to-upgrade-from-windows-11-home-to-pro/"><u>How to Upgrade From Windows 11 Home to Pro</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-simplifying-scheduling-a-google-meet-pro-tip/"><u>In 2024, Simplifying Scheduling  A Google Meet Pro Tip</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-complete-beginners-guide-to-creating-impressive-macro-videos/"><u>In 2024, The Complete Beginner's Guide to Creating Impressive Macro Videos</u></a></li>
<li><a href="https://win-amazing.techidaily.com/install-official-aoc-display-drivers-on-your-windows-pc-windows-11108-supported/"><u>Install Official AOC Display Drivers on Your Windows PC: Windows 11/10/8 Supported</u></a></li>
<li><a href="https://win-amazing.techidaily.com/install-updated-realtek-driver-software-on-your-pc-running-windows-11107/"><u>Install Updated Realtek Driver Software on Your PC Running Windows 11/10/7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/installing-creative-sound-blaster-recon3d-drivers-step-by-step-guide/"><u>Installing Creative Sound Blaster Recon3D Drivers – Step-by-Step Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/instant-access-to-your-microsoft-wireless-mouse-5000-easy-and-quick-drivers-inside/"><u>Instant Access to Your Microsoft Wireless Mouse 5000: Easy and Quick Drivers Inside</u></a></li>
<li><a href="https://win-amazing.techidaily.com/intels-xe-series-graphics-card-iris-plus-download-drivers-for-windows-11/"><u>Intel's Xe Series Graphics Card (Iris Plus) - Download Drivers for Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-nvidia-quadro-driver-software-for-enhanced-windows-11-performance/"><u>Latest NVIDIA Quadro Driver Software for Enhanced Windows 11 Performance</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-techkey-bluetooth-driver-software-for-windows-11-7-and-8-systems/"><u>Latest Techkey Bluetooth Driver Software for Windows 11, 7 and 8 Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/lenovo-digital-imaging-device-software-update-for-windows-vista7/"><u>Lenovo Digital Imaging Device Software Update for Windows Vista/7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/lenovo-pc-optimization-seamless-driver-updates-made-easy/"><u>Lenovo PC Optimization: Seamless Driver Updates Made Easy</u></a></li>
<li><a href="https://win-amazing.techidaily.com/microsoft-addresses-and-corrects-battery-driver-flaw-for-acpi-conformance/"><u>Microsoft Addresses and Corrects Battery Driver Flaw for ACPI Conformance</u></a></li>
<li><a href="https://facebook.techidaily.com/mindfulness-in-motion-understanding-instagrams-break-initiative/"><u>Mindfulness in Motion: Understanding Instagram’s Break Initiative</u></a></li>
<li><a href="https://win-amazing.techidaily.com/no-cost-full-access-mastering-with-m-audios-fast-track-for-audio-engineers/"><u>No Cost, Full Access: Mastering with M-Audio's Fast Track for Audio Engineers</u></a></li>
<li><a href="https://review-topics.techidaily.com/poco-video-recovery-recover-deleted-videos-from-poco-by-fonelab-android-recover-video/"><u>Poco Video Recovery - Recover Deleted Videos from Poco</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/premium-ff-downloader-suite-for-efficient-fb-media-grabs/"><u>Premium FF Downloader Suite for Efficient FB Media Grabs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-vector-image-hubs-ranked-1-to-10-for-2024/"><u>Premium Vector Image Hubs Ranked #1 to #10 for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/resolved-why-your-pc-cant-recognize-the-wireless-network-pci-card-tl-wn722n/"><u>Resolved: Why Your PC Can't Recognize the Wireless Network PCI Card (TL-WN722N)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/speed-up-your-creative-workflow-with-fast-wacom-driver-download/"><u>Speed-Up Your Creative Workflow with Fast Wacom Driver Download</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/stellars-top-advice-on-securely-erasing-your-digital-footprint/"><u>Stellar's Top Advice on Securely Erasing Your Digital Footprint</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-downloading-the-latest-surface-book-t-2-drivers/"><u>Step-by-Step Tutorial: Downloading the Latest Surface Book T 2 Drivers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/streamlining-your-zoom-recordings-a-comprehensive-workshop-for-2024/"><u>Streamlining Your Zoom Recordings  A Comprehensive Workshop for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722968172085-the-ideal-gas-law-relates-pressure-volume-temperature-and-the-number-of-moles-of-a-gas/"><u>The Ideal Gas Law Relates Pressure, Volume, Temperature, and the Number of Moles of a Gas</u></a></li>
<li><a href="https://win-amazing.techidaily.com/the-speedy-way-to-get-your-samsung-m2070-up-to-date-with-newest-drivers/"><u>The Speedy Way to Get Your Samsung M2070 Up-to-Date with Newest Drivers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transform-your-content-3-effective-techniques-for-youtube-reaction-magic-for-2024/"><u>Transform Your Content  3 Effective Techniques for YouTube Reaction Magic for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-guide-how-to-update-or-download-new-ricoh-print-driver-for-windows-system/"><u>Ultimate Guide: How To Update or Download New Ricoh Print Driver for Windows System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unleash-efficiency-the-ultimate-list-of-18-ios-shortcut-app-tips-and-tricks/"><u>Unleash Efficiency: The Ultimate List of 18 iOS Shortcut App Tips & Tricks</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-unlock-stunning-bokeh-best-apps-for-iphone-and-android/"><u>Updated 2024 Approved Unlock Stunning Bokeh Best Apps for iPhone and Android</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-your-workflow-seamless-scansnap-driver-setup-and-enhancement-for-windows-computers/"><u>Upgrade Your Workflow: Seamless ScanSnap Driver Setup and Enhancement for Windows Computers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/windows-11-compatible-nvidia-quadro-drivers-download-installation-and-troubleshooting-guide/"><u>Windows 11 Compatible NVIDIA Quadro Drivers – Download, Installation, and Troubleshooting Guide</u></a></li>
</ul></div>
