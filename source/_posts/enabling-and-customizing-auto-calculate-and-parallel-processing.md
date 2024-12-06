---
title: Enabling & Customizing Auto-Calculate & Parallel Processing
date: 2024-12-02T11:20:32.869Z
updated: 2024-12-06T11:49:05.009Z
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
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-the-3-step-approach-to-effective-copywriting-on-facebook/"><u>[Updated] In 2024, The 3-Step Approach to Effective Copywriting on Facebook</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complete-guide-for-downloading-and-installing-epson-wf-2750s-latest-print-drivers/"><u>Complete Guide for Downloading & Installing Epson WF-2750's Latest Print Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-updated-amd-rx-6800-xt-driver-for-optimal-performance-on-windows-platforms/"><u>Download Updated AMD RX 6800 XT Driver for Optimal Performance on Windows Platforms</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-performance-and-features-of-chargetechs-27000mah-mega-capacity-battery-pack/"><u>Evaluating the Performance and Features of ChargeTech's 27000mAh Mega Capacity Battery Pack</u></a></li>
<li><a href="https://win-amazing.techidaily.com/getting-started-with-your-new-steelseries-mouse-download-necessary-drivers-here/"><u>Getting Started with Your New SteelSeries Mouse: Download Necessary Drivers Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-obtain-the-latest-insignia-bluetooth-dongle-driver-on-windows-os/"><u>How to Obtain the Latest Insignia Bluetooth Dongle Driver on Windows OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-realme-12-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Realme 12 5G Fingerprint Lock</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-iphone-13-unavailable-issue-with-ease-by-drfone-ios/"><u>In 2024, How To Fix iPhone 13 Unavailable Issue With Ease</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-iphone-6s-unavailable-issue-with-ease-by-drfone-ios/"><u>In 2024, How To Fix iPhone 6s Unavailable Issue With Ease</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/primer-8-chatgpt-dialogues-to-enhance-attention-span/"><u>Primer 8 ChatGPT Dialogues to Enhance Attention Span</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-downloading-and-installing-latest-drivers-for-your-surface-book-2/"><u>Step-by-Step Tutorial: Downloading and Installing Latest Drivers for Your Surface Book 2</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/stream-your-success-a-step-by-step-guide-to-earning/"><u>Stream Your Success A Step-by-Step Guide to Earning</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshooting-guide-resolving-tl-wn722n-network-adapter-undetectable-on-windows/"><u>Troubleshooting Guide: Resolving 'TL-WN722N' Network Adapter Undetectable on Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

