---
title: "Mastering Nested Selectors: Building Related Dropdown Menus in Excel"
date: 2024-08-28T04:35:25.297Z
updated: 2024-08-29T04:35:25.297Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4ac54b51c1cafa3a284440c31d27701c82afd968d6a73268fe3b019a529c7811.jpg
---

## Mastering Nested Selectors: Building Related Dropdown Menus in Excel

### Quick Links

* [Getting Started](https://extra-lessons.techidaily.com/speeding-up-projects-without-compromising-quality/)
* [Adding and Naming Dependent Drop-Down List Items](https://youtube-clips.techidaily.com/new-cutting-edge-editors-scouting-the-ultimate-tools-for-youtube-shorts/)
* [Creating the Dependent Drop-Down List](https://fox-helps.techidaily.com/2024-approved-adding-captions-and-text-a-guide-for-photo-titles-in-microsoft-photos/)

 Does using a drop-down list in Microsoft Excel make data entry easier for you or your co-workers? If you said yes and want to go a step further, you can create a dependent drop-down list just as easily.

 With a dependent drop-down list, you select the item that you want in the first list, and that determines the items that display as choices in the second one. For example, you might select a product, like a shirt, and then pick a size, a food item, like ice cream, and then pick a flavor, or an album, and then pick a song.

##  Getting Started

 Obviously, you'll need your first drop-down list set up and ready to go before you can create the dependent list. We have a complete tutorial with all of the details you need to [create a drop-down list in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) for a refresher, so be sure to check that out.

Related: [How to Add a Drop-Down List to a Cell in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) 

 Since setting up the second list follows the same basic process, we'll start there. Then, we'll move on to the dependency setup.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
##  Adding and Naming Dependent Drop-Down List Items

 For this tutorial, we'll use departments in our company for the first drop-down list, and then employees in each department for the second list.

 Our departments include Marketing, Finance, and Human Resources (HR), and each has three employees. These employees are who we need to add and name.

 List the items for the dependent list, and then select the cells. This places the cells in a group so that you can name the group. With the cells selected, go up to the Name Box on the left side of the Formula Bar and [enter a name for the cell group](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/).

![Name a cell group in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NameCellGroupDependentList-Excel.png) 

 The names for each group should match the list items in your first dropdown.

 Using our example, we'll name our groups with the departments in our first list: Marketing, Finance, and HR.

![Named cell groups](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NamedCellGroupDependentList-Excel.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 You can add the items for your dependent list on the same sheet where the list will reside or on a different one. For the purposes of this how-to, you'll notice that we have everything on the same sheet.

##  Creating the Dependent Drop-Down List

 Once all of your list items are in a sheet and named, it's time to create the second drop-down list. You'll use [the Data Validation feature in Excel](https://extra-lessons.techidaily.com/mastering-iphone-saving-and-utilizing-gifs-effectively/), just like when creating your first list.

 Select the cell where you want the list. Then, go to the Data tab and click "Data Validation" in the Data Tools section of the ribbon.

![Click Data Validation on the Data tab in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataTabValidationDependentList-Excel.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 Choose the Settings tab in the pop-up window. Under Allow, pick "List," and to the right, check the box for In-Cell Dropdown. Optionally, you can check the box to Ignore Blank cells if you like.

![Select List and In-Cell Dropdown](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataValidationDependentList-Excel.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 In the Source box, enter the formula below. Be sure to replace the cell reference in parentheses with the cell containing your first drop-down list.

=INDIRECT($B$6)

![Add INDIRECT as the Source](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/IndirectSourceDependentList-Excel.png) 

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The INDIRECT function "returns the reference specified by a text string." For additional details on this function, check out the [Microsoft Support](https://support.microsoft.com/en-us/office/indirect-function-474b3a3a-8a26-4f44-b491-92b6306fa261) page.

 If you'd like to include an Input Message or Error Alert, select those tabs in the pop-up window and enter the details. When you finish, click "OK" to add the drop-down list to the cell.

 Now, give your list a test. When you select an item in the first drop-down list, you should see the items pertaining to your selection as options in the second list.

![Dependent drop-down list in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DependentDropdownList-Excel.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
 For quicker data entry for yourself or your collaborators, try a dependent drop-down list in Excel!

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-essential-thumbnail-strategies-for-amplifying-viewership-on-youtube/"><u>[New] 2024 Approved  Essential Thumbnail Strategies for Amplifying Viewership on YouTube</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleash-the-power-of-pause-tips-for-slow-motion-video-using-photo-apps/"><u>[New] Unleash the Power of Pause  Tips for Slow-Motion Video Using Photo Apps</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-navigating-the-troubled-waters-of-zombie-army-4-on-your-computer-dead-war-edition/"><u>[SOLVED] Navigating the Troubled Waters of 'Zombie Army 4' On Your Computer - Dead War Edition</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-accelerated-screen-recordings-and-voice-over-assistance/"><u>[Updated] 2024 Approved  Accelerated Screen Recordings & Voice Over Assistance</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-distinguishing-between-youtube-policies-and-cc-clauses/"><u>2024 Approved  Distinguishing Between YouTube Policies and CC Clauses</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-enhancing-your-digital-presence-fb-video-creation-basics/"><u>2024 Approved  Enhancing Your Digital Presence  FB Video Creation Basics</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-rockalldlldll-unavailability-in-pcs/"><u>Addressing Rockalldll.dll Unavailability in PCs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/canon-mf4800-drivers-get-your-free-download-here/"><u>Canon MF4800 Drivers: Get Your Free Download Here!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/connect-and-enjoy-pc-game-control-installing-xbox-360-controllers-compatibility-software/"><u>Connect and Enjoy PC Game Control: Installing Xbox 360 Controllers Compatibility Software</u></a></li>
<li><a href="https://win-amazing.techidaily.com/customer-segmentation-and-target-markets-for-spice-based-chemical-products/"><u>Customer Segmentation and Target Markets for Spice-Based Chemical Products</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-latest-hp-laptop-driver-software-for-windows/"><u>Download & Install Latest HP Laptop Driver Software for Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-official-android-usb-driver-software-on-your-pc/"><u>Download & Install Official Android USB Driver Software on Your PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-microsoft-drivers-seamlessly-in-windows-1087/"><u>Download & Update Microsoft Drivers Seamlessly in Windows 10/8/7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-nvidias-free-3d-vision-drivers-for-windows-easily-step-by-step/"><u>Download Nvidia's Free 3D Vision Drivers for Windows Easily – Step-by-Step</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-updated-gpu-drivers-optimizing-your-pc-with-geforce-rtx-2080-support-on-various-windows-os/"><u>Download Updated GPU Drivers: Optimizing Your PC With GeForce RTX 2080 Support on Various Windows OS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-guide-get-your-acer-wi-fi-drivers-downloaded-today/"><u>Easy Installation Guide: Get Your Acer Wi-Fi Drivers Downloaded Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-setup-secure-your-razer-mamba-drivers-today/"><u>Effortless Setup: Secure Your Razer Mamba Drivers Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/find-and-set-up-the-latest-hp-printer-drivers-for-windows-operating-systems/"><u>Find and Set Up the Latest HP Printer Drivers for Windows Operating Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-drivers-for-realtek-cards-on-windows-10/"><u>Free Download: Compatible Drivers for Realtek Cards on Windows 10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/full-length-video-view-remove-youtube-preview-for-2024/"><u>Full-Length Video View  Remove YouTube Preview for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722969656876-get-your-intel-b560-coffee-lake-motherboard-and-chipset-for-free/"><u>Get Your Intel B560 Coffee Lake Motherboard & Chipset for FREE!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/getting-started-how-to-set-up-brother-dcp-l25nwd-printer-in-windows-using-its-latest-driver-download/"><u>Getting Started: How to Set Up Brother DCP-L25nwd Printer in Windows Using Its Latest Driver Download</u></a></li>
<li><a href="https://win-amazing.techidaily.com/guide-to-updating-and-installing-advanced-micro-devices-drivers-for-blockchain-mining-in-windows-environment/"><u>Guide to Updating & Installing Advanced Micro Devices Drivers for Blockchain Mining in Windows Environment</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-elitebook-x360-laptop-drivers-secure-your-free-latest-version-downloads-today/"><u>HP EliteBook X360 Laptop Drivers: Secure Your Free Latest Version Downloads Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-photosmart-7520-easy-download-of-your-official-printing-software/"><u>HP Photosmart 7520: Easy Download of Your Official Printing Software</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Lava Agni 2 5G? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-honor-magic-6-pro-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Honor Magic 6 Pro Phone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-enhanced-wi-fi-network-drivers-for-windows-versions-win11-10-8-and-7-download-here/"><u>Latest Enhanced Wi-Fi Network Drivers for Windows Versions: Win11, 10, 8 & 7 - Download Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-mp280-printer-driver-installers-compatible-with-windows-1187/"><u>Latest MP280 Printer Driver Installers Compatible with Windows 11/8/7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/msi-z3-pro-motherboard-driver-pack-secure-download-now/"><u>MSI Z3# Pro Motherboard Driver Pack - Secure Download Now</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-simple-guide-downloading-wacom-drivers/"><u>Quick and Simple Guide: Downloading Wacom Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-connectivity-find-download-and-update-drivers-for-netgear-wireless-adapters-today/"><u>Seamless Connectivity: Find, Download & Update Drivers for NETGEAR Wireless Adapters Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722972276062-smooth-and-speedy-samsung-m2070fw-driver-installation-start-today/"><u>Smooth and Speedy Samsung M2070FW Driver Installation – Start Today!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-installing-updated-intel-graphics-drivers-for-win-10win-11-systems/"><u>Step-by-Step Guide: Installing Updated Intel Graphics Drivers for Win 10/Win 11 Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-updating-your-canon-pixma-printer-drivers-with-speed-and-simplicity/"><u>Step-by-Step Guide: Updating Your Canon PIXMA Printer Drivers with Speed and Simplicity</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshoot-with-ease-updating-the-drivers-of-a-standard-sata-ahci-controller/"><u>Troubleshoot with Ease: Updating the Drivers of a Standard SATA AHCI Controller</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-huawei-p60-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Huawei P60 Device</u></a></li>
</ul></div>
