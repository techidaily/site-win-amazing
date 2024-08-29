---
title: "Beyond Databases with VLOOKUP in Excel: Techniques for Efficient Data Retrieval"
date: 2024-08-28T04:34:22.580Z
updated: 2024-08-29T04:34:22.580Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/57a4dd5881ee89a7ccb05cda2bbc7d01f9c197463ce070f6b273e0abf69dbbe5.jpg
---

## Beyond Databases with VLOOKUP in Excel: Techniques for Efficient Data Retrieval

In a recent article, we introduced the Excel function called **VLOOKUP** and explained how it could be used to retrieve information from a database into a cell in a local worksheet. In that article we mentioned that there were two uses for VLOOKUP, and only one of them dealt with querying databases. In this article, the second and final in the VLOOKUP series, we examine this other, lesser known use for the VLOOKUP function. If you haven't already done so, please read [the first VLOOKUP article](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) \- this article will assume that many of the concepts explained in that article are already known to the reader. When working with databases, VLOOKUP is passed a "unique identifier" that serves to identify which data record we wish to find in the database (e.g. a product code or customer ID). This unique identifier must exist in the database, otherwise VLOOKUP returns us an error. In this article, we will examine a way of using VLOOKUP where the identifier doesn't need to exist in the database at all. It's almost as if VLOOKUP can adopt a "near enough is good enough" approach to returning the data we're looking for. In certain circumstances, this is exactly what we need. We will illustrate this article with a real-world example - that of calculating the commissions that are generated on a set of sales figures. We will start with a very simple scenario, and then progressively make it more complex, until the only rational solution to the problem is to use VLOOKUP. The initial scenario in our fictitious company works like this: If a salesperson creates more than $30,000 worth of sales in a given year, the commission they earn on those sales is 30%. Otherwise their commission is only 20%. So far this is a pretty simple worksheet: To use this worksheet, the salesperson enters their sales figures in cell B1, and the formula in cell B2 calculates the correct commission rate they are entitled to receive, which is used in cell B3 to calculate the total commission that the salesperson is owed (which is a simple multiplication of B1 and B2). The cell B2 contains the only interesting part of this worksheet - the formula for deciding which commission rate to use: the one below the threshold of $30,000, or the one above the threshold. This formula makes use of the Excel function called **IF**. For those readers that are not familiar with IF, it works like this: 

> IF(condition,value if true,value if false)

 Where the condition is an expression that evaluates to either **true** or **false**. In the example above, the condition is the expression **B1<B5**, which can be read as "Is B1 less than B5?", or, put another way, "Are the total sales less than the threshold". If the answer to this question is "yes" (true), then we use the value if true parameter of the function, namely **B6** in this case - the commission rate if the sales total was below the threshold. If the answer to the question is "no" (false), then we use the value if false parameter of the function, namely **B7** in this case - the commission rate if the sales total was above the threshold. As you can see, using a sales total of $20,000 gives us a commission rate of 20% in cell B2\. If we enter a value of $40,000, we get a different commission rate: 

![original40k](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/original40k.png) 

 So our spreadsheet is working. Let's make it more complex. Let's introduce a second threshold: If the salesperson earns more than $40,000, then their commission rate increases to 40%: 

![2thresholds](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/2thresholds.png) 

 Easy enough to understand in the real world, but in cell B2 our formula is getting more complex. If you look closely at the formula, you'll see that the third parameter of the original IF function (the value if false) is now an entire IF function in its own right. This is called a nested function (a function within a function). It's perfectly valid in Excel (it even works!), but it's harder to read and understand. We're not going to go into the nuts and bolts of how and why this works, nor will we examine the nuances of nested functions. This is a tutorial on VLOOKUP, not on Excel in general. Anyway, it gets worse! What about when we decide that if they earn more than $50,000 then they're entitled to 50% commission, and if they earn more than $60,000 then they're entitled to 60% commission? 

![4thresholds](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/4thresholds.png) 

 Now the formula in cell B2, while correct, has become virtually unreadable. No-one should have to write formulae where the functions are nested four levels deep! Surely there must be a simpler way? There certainly is. VLOOKUP to the rescue! Let's redesign the worksheet a bit. We'll keep all the same figures, but organize it in a new way, a more tabular way: 

![tableblank](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/tableblank.png) 

 Take a moment and verify for yourself that the new **Rate Table** works exactly the same as the series of thresholds above. Conceptually, what we're about to do is use VLOOKUP to look up the salesperson's sales total (from B1) in the rate table and return to us the corresponding commission rate. Note that the salesperson may have indeed created sales that are not one of the five values in the rate table ($0, $30,000, $40,000, $50,000 or $60,000). They may have created sales of $34,988\. It's important to note that $34,988 does not appear in the rate table. Let's see if VLOOKUP can solve our problem anyway... We select cell B2 (the location we want to put our formula), and then insert the VLOOKUP function from the **Formulas** tab: 

![findfunc](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/findfunc.png) 

 The **Function Arguments** box for VLOOKUP appears. We fill in the arguments (parameters) one by one, starting with the **Lookup\_value**, which is, in this case, the sales total from cell B1\. We place the cursor in the **Lookup\_value** field and then click once on cell B1: 

![args1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/args1.png) 

 Next we need to specify to VLOOKUP what table to lookup this data in. In this example, it's the rate table, of course. We place the cursor in the **Table\_array** field, and then highlight the entire rate table - excluding the headings: 

![args2](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/args2.png) 

 Next we must specify which column in the table contains the information we want our formula to return to us. In this case we want the commission rate, which is found in the second column in the table, so we therefore enter a **2** into the **Col\_index\_num** field: 

![args3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/args3.png) 

 Finally we enter a value in the **Range\_lookup** field. Important: It is the use of this field that differentiates the two ways of using VLOOKUP. To use VLOOKUP with a database, this final parameter, **Range\_lookup**, must always be set to **FALSE**, but with this other use of VLOOKUP, we must either leave it blank or enter a value of **TRUE**. When using VLOOKUP, it is vital that you make the correct choice for this final parameter. To be explicit, we will enter a value of **true** in the **Range\_lookup** field. It would also be fine to leave it blank, as this is the default value: 

![args4](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/args4.png) 

 We have completed all the parameters. We now click the **OK** button, and Excel builds our VLOOKUP formula for us: 

![vlookupdone](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/04/vlookupdone.png) 

 If we experiment with a few different sales total amounts, we can satisfy ourselves that the formula is working. **Conclusion** In the "database" version of VLOOKUP, where the **Range\_lookup** parameter is **FALSE**, the value passed in the first parameter (**Lookup\_value**) must be present in the database. In other words, we're looking for an exact match. But in this other use of VLOOKUP, we are not necessarily looking for an exact match. In this case, "near enough is good enough". But what do we mean by "near enough"? Let's use an example: When searching for a commission rate on a sales total of $34,988, our VLOOKUP formula will return us a value of 30%, which is the correct answer. Why did it choose the row in the table containing 30% ? What, in fact, does "near enough" mean in this case? Let's be precise: 

> When **Range\_lookup** is set to **TRUE** (or omitted), VLOOKUP will look in column 1 and match the highest value that is not greater than the **Lookup\_value** parameter.

 It's also important to note that for this system to work, the table must be sorted in ascending order on column 1! If you would like to practice with VLOOKUP, the sample file illustrated in this article can be downloaded from [here](https://extra-guidance.techidaily.com/new-orchestrating-originality-top-8-schools-for-story-innovation/).

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
<li><a href="https://win-amazing.techidaily.com/new-release-quick-setup-of-intel-ac-3160-wifi-card-update-your-network-adapter-driver-now/"><u>[NEW RELEASE] Quick Setup of Intel AC 3160 WiFi Card - Update Your Network Adapter Driver Now</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-the-comedy-cache-twitters-best-jokes/"><u>[Updated] In 2024, The Comedy Cache  Twitter’s Best Jokes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-ultimate-guide-to-your-unique-tiktok-hash-code/"><u>[Updated] In 2024, The Ultimate Guide to Your Unique TikTok Hash Code</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-creativity-the-ultimate-selection-of-online-jpg-to-gif-tools/"><u>[Updated] Unleash Creativity  The Ultimate Selection of Online JPG to GIF Tools</u></a></li>
<li><a href="https://win-amazing.techidaily.com/acer-wifi-driver-free-download-quickly-and-easily/"><u>Acer WiFi Driver | Free Download | Quickly & Easily</u></a></li>
<li><a href="https://win-amazing.techidaily.com/asus-pce-ac68-usb-30-driver-free-downloads-available/"><u>ASUS PCE-AC68 USB 3.0 Driver - FREE Downloads Available</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-walkthrough-on-downloading-and-installing-linksys-wusb6300-drivers/"><u>Comprehensive Walkthrough on Downloading and Installing Linksys WUSB6300 Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/conquering-connectivity-issues-with-startech-products-on-windows-1087-detailed-fixes/"><u>Conquering Connectivity Issues with StarTech Products on Windows 10/8/7 - Detailed Fixes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-hp-laserjet-pro-m404n-printer-drivers/"><u>Download & Update: HP LaserJet Pro M404n Printer Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-acer-display-drivers-step-by-step-guide/"><u>Download Acer Display Drivers: Step-by-Step Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-epson-wf-2940-printer-drivers-compatible-with-windows-7-81-and-10/"><u>Download Epson WF-2940 Printer Drivers Compatible with Windows 7, 8.1 & 10</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-newest-software-patch-for-hdmi-to-usb-interface/"><u>Download: Newest Software Patch for HDMI to USB Interface</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-updated-netgear-a6100-windows-drivers-to-improve-your-routers-performance/"><u>Easy Installation: Updated Netgear A6100 Windows Drivers to Improve Your Router's Performance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/efficient-techniques-for-saving-online-meeting-transcripts-for-2024/"><u>Efficient Techniques for Saving Online Meeting Transcripts for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-amd-smbus-driver-downloading-and-updating-process/"><u>Effortless AMD SMBus Driver Downloading and Updating Process</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ensure-smooth-printing-with-the-updated-canon-pixma-mg2-222-drivers/"><u>Ensure Smooth Printing with the Updated Canon PIXMA MG2 222 Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-hp-officejet-3830-printing-software-for-windows-users/"><u>Get the Latest HP OfficeJet 3830 Printing Software for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-newest-logitech-t630-driver-updates-for-windows-systems-win-7-8-and-10/"><u>Get the Newest Logitech T630 Driver Updates for Windows Systems (Win 7, 8 & 10)</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-infinix-hot-40i-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Infinix Hot 40i Phone | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-find-and-install-up-to-date-dell-thunderbolt-tb18-drivers-easily/"><u>How to Find and Install Up-to-Date Dell Thunderbolt TB18 Drivers Easily</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722959634646-how-to-get-your-nvidia-quadro-graphic-drivers-for-the-latest-windows-ebx-featuring-enhanced-dch-performance/"><u>How to Get Your NVIDIA Quadro Graphic Drivers for the Latest Windows Ebx, Featuring Enhanced DCH Performance!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-successfully-update-or-download-arduino-drivers-on-a-windows-machine/"><u>How to Successfully Update or Download Arduino Drivers on a Windows Machine</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-update-or-reinstall-drivers-for-your-samsung-evo-850-ssd-step-by-step-instructions/"><u>How to Update or Reinstall Drivers for Your Samsung EVO 850 SSD – Step-by-Step Instructions</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-effortless-ways-to-transfer-data-from-your-apple-iphone-15-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Effortless Ways to Transfer Data from Your Apple iPhone 15 to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-oneplus-11-5g-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for OnePlus 11 5G</u></a></li>
<li><a href="https://win-amazing.techidaily.com/insignia-usb-ethernet-converter-driver-download/"><u>Insignia USB-Ethernet Converter Driver Download</u></a></li>
<li><a href="https://win-amazing.techidaily.com/installing-the-fresh-conexant-driver-a-comprehensive-walkthrough-for-windows-10-20h2-update/"><u>Installing the Fresh Conexant Driver: A Comprehensive Walkthrough for Windows 10 20H2 Update</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/jest-jammer-photo-assembler-for-2024/"><u>Jest Jammer  Photo Assembler for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/lack-of-light-display-disruption/"><u>Lack of Light: Display Disruption</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-nvidia-geforce-rtx-3080-drivers-compatible-with-windows-11-10-and-7/"><u>Latest NVIDIA GeForce RTX 3080 Drivers – Compatible with Windows 11, 10 & 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-nvidia-quadro-graphics-driver-software-for-windows-10-pcs/"><u>Latest Nvidia Quadro Graphics Driver Software for Windows 10 PCs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722964385606-soil-structure-interaction-ssi-evaluates-how-soil-movement-impacts-the-response-of-structures-to-seismic-forces-influencing-design-demands/"><u>Soil-Structure Interaction (SSI) Evaluates How Soil Movement Impacts the Response of Structures to Seismic Forces, Influencing Design Demands</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-on-installing-updated-graphics-drivers-in-windows/"><u>Step-by-Step Tutorial on Installing Updated Graphics Drivers in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-how-to-install-nvme-drivers-for-windows-users/"><u>Step-by-Step Tutorial: How to Install NVMe Drivers for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/take-your-pc-gaming-to-the-next-level-with-freshly-updated-gtx-1660-ti-drivers/"><u>Take Your PC Gaming to the Next Level with Freshly Updated GTX 1660 Ti Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshooting-and-resolving-xbox-controller-driver-problems-in-windows-1087/"><u>Troubleshooting and Resolving Xbox Controller Driver Problems in Windows 10/8/7</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-infinix-zero-30-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Infinix Zero 30 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/whats-new-update-on-your-logitech-extreme-3d-driver/"><u>What’s New: Update on Your Logitech Extreme 지역 3D 프로 마우스 Driver</u></a></li>
<li><a href="https://techtrends.techidaily.com/winning-strategies-for-playing-pokemon-unite-on-a-personal-computer/"><u>Winning Strategies for Playing Pokémon Unite on a Personal Computer</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->