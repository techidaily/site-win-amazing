---
title: "Mastering Text Manipulation: Techniques for Separating Words in Excel"
date: 2024-08-28T04:35:26.448Z
updated: 2024-08-29T04:35:26.448Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5fe7ecb89bcc6e1487d4d4a1019dead48cda049eb81dcbc464d7190885cdca32.jpg
---

## Mastering Text Manipulation: Techniques for Separating Words in Excel

### Quick Links

* [The TEXTBEFORE Function](https://screen-sharing-recording.techidaily.com/new-2024-approved-expert-routines-for-flawless-webinar-replays/)
* [The TEXTAFTER Function](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a58-4g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [The TEXTSPLIT Function](https://facebook-video-content.techidaily.com/tutorial-transferring-youtube-videos-to-social-media-facebook-edition/)

 Microsoft Excel offers a set of [functions for working with text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/). When you want to extract part of a text string or split a string into rows or columns, there are three particular functions that get the job done.

 With TEXTBEFORE and TEXTAFTER, you can pull out text before or after a certain word or character. This makes these functions more flexible than the [LEFT, RIGHT, and MID functions](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) you might be using. For splitting a string into various cells, you can use TEXTSPLIT.

 These three functions are new to Excel as of August 2022\. They will roll out to Office Insiders and then all Excel users over time.

##  The TEXTBEFORE Function

 The syntax for the function is

        `TEXTBEFORE(text, delimiter, instance, match_mode, match_end, if_not_found)`
    
 . The first two arguments are required with `text` being either the actual text or a cell reference and `delimiter` being the point at which you want the text before.

 Here are descriptions of the three optional arguments:

* **Instance**: Use this argument if there is more than one occurrence of the `delimiter` in the string and you want a particular one.
* **Match\_mode**: Enter a 0 for case sensitive or 1 for not case sensitive. The default is 0.
* **Match\_end**: Enter 0 to not match the delimiter to the end of the text and 1 to match it. The default is 1.
* **If\_not\_found**: Use this argument If you prefer a result rather than an error for values not found.

 Now that you know the arguments, let's look at some example uses for TEXTBEFORE.

 In this first example, we'll extract all text before the word "from" in cell A2 using this formula:

=TEXTBEFORE(A2,"from")

![TEXTBEFORE function for a basic extraction](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFOREbasic-ExcelExtractSplitText.png) 

 Using this next formula, we'll extract all text before the second instance of the word "text."

=TEXTBEFORE(A2,"text",2)

![TEXTBEFORE function using an instance](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFOREinstance-ExcelExtractSplitText.png) 

 For one more example, we'll use the `match_mode` argument for a case-sensitive match.

=TEXTBEFORE(A2,"TEXT",,0)

![TEXTBEFORE function using case sensitive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFORECaseSensitive-ExcelExtractSplitText.png) 

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The TEXTAFTER Function

 TEXTAFTER is the exact opposite of TEXTBEFORE. The syntax for the function is `TEXTAFTER(text, delimiter, instance, match_mode, match_end, if_not_found)`.

 Like its counterpart, the first two arguments are required with `text` being either the actual text or a cell reference and `delimiter` being the point at which you want the text after.

 The three optional arguments described above also work the same as the TEXTBEFORE function.

 In this first example, we'll extract all text after the word "from" in cell A2 using this formula:

=TEXTAFTER(A2,"from")

![TEXTAFTER function for a basic extraction](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERbasic-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Using this next formula, we'll extract all text after the second instance of the word "text."

=TEXTAFTER(A2,"text",2)

![TEXTAFTER function using an instance](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERinstance-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 And finally, we'll use the `match_mode` argument for a case-sensitive match.

=TEXTAFTER(A2,"TEXT",,0)

![TEXTAFTER function using case sensitive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERCaseSensitive-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The TEXTSPLIT Function

 With the TEXTSPLIT function you can [split the text](https://fox-glue.techidaily.com/new-in-2024-navigating-the-essentials-of-av1-coders/) into cells in a row or column based on the delimiter, for example, a space or period.

Related: [How to Split Data Into Multiple Columns in Excel](https://fox-glue.techidaily.com/new-in-2024-navigating-the-essentials-of-av1-coders/) 

 The syntax is `TEXTSPLIT(text, column_delimiter, row_delimiter, ignore, match_mode, pad_with)` where the first argument is required and can be actual text or a cell reference. By default, the formula splits the text into columns, but you can use rows instead with the `row_delimiter` argument.

 Here are descriptions of the remaining arguments:

* **Ignore**: Enter FALSE to create an empty cell when two delimiters are consecutive. The default is TRUE.
* **Match\_mode**: Searches the delimiter for a match with the default as case sensitive.
* **Pad\_with**: To pad the result, enter a value. Otherwise, the #N/A error displays.

 In this example, we'll split the text string in cell A2 across columns with a space as our `column_delimiter` in quotes. Here's the formula:

=TEXTSPLIT(A2," ")

![TEXTSPLIT function across columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITbasic-ExcelExtractSplitText.png) 

 Instead of splitting the string across columns, we'll split it across rows using a space as our `row_delimiter` with this formula:

=TEXTSPLIT(A2,," ")

 Notice in this formula, we leave the `column_delimiter` argument blank and only use the `row_delimiter`.

![TEXTSPLIT function across rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITRows-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For this next example, we'll split only after the semicolon into another column:

=TEXTSPLIT(A2,";")

![TEXTSPLIT function across columns with a single delimiter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITSemicolonColumn-ExcelExtractSplitText.png) 

 Next, we'll split only after the semicolon into a row instead of a column:

=TEXTSPLIT(A2,,";")

![TEXTSPLIT function across rows with a single delimiter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITSemicolonRow-ExcelExtractSplitText.png) 

 The TEXTSPLIT function is a powerful one. If you're looking for more complex examples of using the optional arguments, visit the [Microsoft Support page for the TEXTSPLIT function](https://support.microsoft.com/en-us/office/textsplit-function-b1ca414e-4c21-4ca0-b1b7-bdecace8a6e7).

 The next time you want to extract text from a cell or split a long text string, keep these [Excel functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) in mind. Then, when you need to put strings back together again, learn how to easily [add text to a cell with a formula](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/).

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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-10-ideas-for-making-your-podcast-stand-out-visually/"><u>[New] 2024 Approved  Top 10 Ideas for Making Your Podcast Stand Out Visually</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-ultimate-gaming-adventure-list-ghost-of-tsushimas-allies/"><u>[New] 2024 Approved  Ultimate Gaming Adventure List – Ghost of Tsushima's Allies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-the-ultimate-key-to-capturing-and-preserving-your-favorite-streamed-shows/"><u>[New] In 2024, The Ultimate Key to Capturing and Preserving Your Favorite Streamed Shows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-rotate-for-results-instagram-video-alchemy/"><u>[Updated] 2024 Approved  Rotate for Results  Instagram Video Alchemy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-top-no-cost-virtual-viewer-rendezvous/"><u>[Updated] 2024 Approved  Top No-Cost Virtual Viewer Rendezvous</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-leveraging-the-power-of-movie-maker-in-windows-8-for-professional-results/"><u>[Updated] Leveraging the Power of Movie Maker in Windows 8 for Professional Results</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-navigating-the-essentials-of-av1-coders/"><u>[Updated] Navigating the Essentials of AV1 Coders</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-amplifying-your-impact-voice-customization-in-instagram-media/"><u>2024 Approved  Amplifying Your Impact  Voice Customization in Instagram Media</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-how-to-add-music-to-facebook-videos/"><u>2024 Approved  How to Add Music to Facebook Videos?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-securing-your-digital-dividends-a-no-ads-youtube-money-manual/"><u>2024 Approved  Securing Your Digital Dividends  A No Ads YouTube Money Manual</u></a></li>
<li><a href="https://win-amazing.techidaily.com/asus-z370-e-motherboard-driver-download-fast-and-simple-installation-guide/"><u>ASUS Z370-E Motherboard Driver Download: Fast and Simple Installation Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-guide-amd-radeon-hd-6350-drivers-for-windows/"><u>Download & Update Guide: AMD Radeon HD 6350 Drivers for Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-latest-qualcomm-atheros-ar956x-wifi-card-drivers/"><u>Download the Latest Qualcomm Atheros AR956X WiFi Card Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-latest-version-of-hp-deskjet-3050a-driver-software-for-windows-free-update-available/"><u>Download the Latest Version of HP Deskjet 3050A Driver Software for Windows - Free Update Available</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-asus-dvd-player-drivers-secure-your-media-files-today/"><u>Easy ASUS DVD Player Drivers - Secure Your Media Files Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722974784178-effortless-installation-get-your-hp-officejet-5740-drivers-now/"><u>Effortless Installation - Get Your HP OfficeJet ˈ5740 Drivers Now</u></a></li>
<li><a href="https://some-tips.techidaily.com/enhance-your-site-with-automated-visitor-tracking-the-secrets-in-the-bots/"><u>Enhance Your Site with Automated Visitor Tracking - The Secret's in the Bots!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/externalities-are-costs-or-benefits-incurred-by-third-parties-who-did-not-choose-to-be-affected/"><u>Externalities Are Costs or Benefits Incurred by Third Parties Who Did Not Choose to Be Affected.</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-amd-vega-vega56-drivers-downloading-updating-and-troubleshooting-for-windows-users/"><u>Get the Latest AMD Vega Vega56 Drivers: Downloading, Updating, and Troubleshooting for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-canon-mg3022-driver-software-update-guide-and-download-links/"><u>Get the Latest Canon MG3022 Driver Software - Update Guide & Download Links</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-razer-controller-drivers-for-your-windows-operating-system-10-8-7-xp-vista/"><u>Get the Latest Razer Controller Drivers for Your Windows Operating System (10, 8, 7, XP, Vista)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-brother-dcp-l2540dw-ready-on-pc-free-windows-driver-downloads-and-installation-tutorials/"><u>Get Your Brother DCP-L2540DW Ready on PC: Free Windows Driver Downloads & Installation Tutorials</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-install-updated-nvidia-quadro-graphics-software-on-windows-11/"><u>How to Install Updated NVIDIA Quadro Graphics Software on Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-deskjet-2652-printer-driver-downloads-compatible-with-windows-111087/"><u>HP DeskJet 2652 Printer Driver Downloads Compatible with Windows 11/10/8/7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-laserjet-1018-driver-installation-guide-fast-and-easy-download-options/"><u>HP LaserJet 1018 Driver Installation Guide: Fast & Easy Download Options</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-did-your-apple-iphone-7-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 7 Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-iphone-techniques-for-collage-creation/"><u>In 2024, Innovative iPhone Techniques for Collage Creation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-tips-for-embedding-and-posting-correct-subtitles-on-twitter-instagram/"><u>In 2024, Top Tips for Embedding and Posting Correct Subtitles on Twitter, Instagram</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-through-artificeia-tackling-the-ais-purpose-synchronization-issue/"><u>Navigating Through Artificeia: Tackling the AI's Purpose Synchronization Issue</u></a></li>
<li><a href="https://win-amazing.techidaily.com/optimize-your-gaming-experience-how-to-install-latest-drivers-for-geforce-gtx-1660-super-gpus/"><u>Optimize Your Gaming Experience: How to Install Latest Drivers for GeForce GTX 1660 Super GPUs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/overcoming-known-graphic-drivers-problems-effective-solutions-revealed/"><u>Overcoming 'Known Graphic Drivers Problems': Effective Solutions Revealed</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-setup-how-to-secure-the-latest-nvidia-graphics-card-drivers-for-windows-11-systems/"><u>Seamless Setup: How to Secure the Latest NVIDIA Graphics Card Drivers for Windows 11 Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-to-seamlessly-update-your-windows-scansnap-drivers/"><u>Step-by-Step Guide to Seamlessly Update Your Windows ScanSnap Drivers</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-guide-correcting-kmode-exception-errors-on-microsofts-latest-operating-systems-windows-1110/"><u>Step-by-Step Guide: Correcting KMODE Exception Errors on Microsoft's Latest Operating Systems (Windows 11/10)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-installation-of-updated-dell-d31n-gpu-drivers-for-optimal-performance/"><u>Step-by-Step Installation of Updated Dell D31n GPU Drivers for Optimal Performance</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721267070136-trust-in-these-proven-iphone-data-rescue-solutions-restore-what-was-lost/"><u>Trust in These Proven iPhone Data Rescue Solutions - Restore What Was Lost!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-guide-to-simple-driver-upgrades-on-your-pc/"><u>Ultimate Guide to Simple Driver Upgrades on Your PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-instantly-upgrade-your-sound-with-nahimic-drivers/"><u>Update: Instantly Upgrade Your Sound with Nahimic Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/usb-bluetooth-dongle-driver-update-process-for-windows-operating-system/"><u>USB Bluetooth Dongle Driver Update Process for Windows Operating System</u></a></li>
<li><a href="https://win-amazing.techidaily.com/windows-10-webcam-driver-update-tutorial-easy-fix-for-better-video-quality/"><u>Windows 10 Webcam Driver Update Tutorial - Easy Fix for Better Video Quality</u></a></li>
</ul></div>
