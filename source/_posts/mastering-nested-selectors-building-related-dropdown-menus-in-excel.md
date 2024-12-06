---
title: "Mastering Nested Selectors: Building Related Dropdown Menus in Excel"
date: 2024-12-05T01:31:20.553Z
updated: 2024-12-06T07:14:32.899Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4ac54b51c1cafa3a284440c31d27701c82afd968d6a73268fe3b019a529c7811.jpg
---

## Mastering Nested Selectors: Building Related Dropdown Menus in Excel

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Getting Started](https://extra-lessons.techidaily.com/speeding-up-projects-without-compromising-quality/)
* [Adding and Naming Dependent Drop-Down List Items](https://youtube-clips.techidaily.com/new-cutting-edge-editors-scouting-the-ultimate-tools-for-youtube-shorts/)
* [Creating the Dependent Drop-Down List](https://fox-helps.techidaily.com/2024-approved-adding-captions-and-text-a-guide-for-photo-titles-in-microsoft-photos/)

 Does using a drop-down list in Microsoft Excel make data entry easier for you or your co-workers? If you said yes and want to go a step further, you can create a dependent drop-down list just as easily.

 With a dependent drop-down list, you select the item that you want in the first list, and that determines the items that display as choices in the second one. For example, you might select a product, like a shirt, and then pick a size, a food item, like ice cream, and then pick a flavor, or an album, and then pick a song.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Getting Started

 Obviously, you'll need your first drop-down list set up and ready to go before you can create the dependent list. We have a complete tutorial with all of the details you need to [create a drop-down list in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) for a refresher, so be sure to check that out.

Related: [How to Add a Drop-Down List to a Cell in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) 

 Since setting up the second list follows the same basic process, we'll start there. Then, we'll move on to the dependency setup.

##  Adding and Naming Dependent Drop-Down List Items

 For this tutorial, we'll use departments in our company for the first drop-down list, and then employees in each department for the second list.

 Our departments include Marketing, Finance, and Human Resources (HR), and each has three employees. These employees are who we need to add and name.

 List the items for the dependent list, and then select the cells. This places the cells in a group so that you can name the group. With the cells selected, go up to the Name Box on the left side of the Formula Bar and [enter a name for the cell group](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/).

![Name a cell group in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NameCellGroupDependentList-Excel.png) 

 The names for each group should match the list items in your first dropdown.

 Using our example, we'll name our groups with the departments in our first list: Marketing, Finance, and HR.

![Named cell groups](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NamedCellGroupDependentList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can add the items for your dependent list on the same sheet where the list will reside or on a different one. For the purposes of this how-to, you'll notice that we have everything on the same sheet.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Creating the Dependent Drop-Down List

 Once all of your list items are in a sheet and named, it's time to create the second drop-down list. You'll use [the Data Validation feature in Excel](https://extra-lessons.techidaily.com/mastering-iphone-saving-and-utilizing-gifs-effectively/), just like when creating your first list.

 Select the cell where you want the list. Then, go to the Data tab and click "Data Validation" in the Data Tools section of the ribbon.

![Click Data Validation on the Data tab in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataTabValidationDependentList-Excel.png) 

 Choose the Settings tab in the pop-up window. Under Allow, pick "List," and to the right, check the box for In-Cell Dropdown. Optionally, you can check the box to Ignore Blank cells if you like.

![Select List and In-Cell Dropdown](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataValidationDependentList-Excel.png) 

 In the Source box, enter the formula below. Be sure to replace the cell reference in parentheses with the cell containing your first drop-down list.

=INDIRECT($B$6)

![Add INDIRECT as the Source](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/IndirectSourceDependentList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The INDIRECT function "returns the reference specified by a text string." For additional details on this function, check out the [Microsoft Support](https://support.microsoft.com/en-us/office/indirect-function-474b3a3a-8a26-4f44-b491-92b6306fa261) page.

 If you'd like to include an Input Message or Error Alert, select those tabs in the pop-up window and enter the details. When you finish, click "OK" to add the drop-down list to the cell.

 Now, give your list a test. When you select an item in the first drop-down list, you should see the items pertaining to your selection as options in the second list.

![Dependent drop-down list in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DependentDropdownList-Excel.png) 

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
<li><a href="https://fox-http.techidaily.com/new-in-2024-fine-tuning-film-views-through-zoom-adjustment/"><u>[New] In 2024, Fine-Tuning Film Views Through Zoom Adjustment</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-depth-look-at-fraps-screen-capture-for-2024/"><u>[New] In-Depth Look at Fraps Screen Capture for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/alder-lake-intel-core-i5-12400f-processor-a-comprehensive-review-of-the-high-performance-pentium-gold-g7400t-cpu-at-a-record-58ghz-overclock/"><u>Alder Lake Intel Core I5-12400F Processor: A Comprehensive Review of the High-Performance Pentium Gold G7400T CPU at a Record 5.8GHz Overclock</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-latest-amd-radeon-hd-3450-graphics-card-drivers-and-update-guide/"><u>Easy Installation: Latest AMD Radeon HD 3450 Graphics Card Drivers & Update Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-steps-to-fresh-install-or-update-dell-monitor-drivers-for-optimal-performance/"><u>Easy Steps to Fresh Install or Update Dell Monitor Drivers for Optimal Performance</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-hp-officejet-pro-8715-printer-drivers-compatible-with-windows-10-8-and-11/"><u>Free HP OfficeJet Pro 8715 Printer Drivers: Compatible with Windows 10, 8 & 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-logitech-g903-mouse-software-and-drivers-for-windows-pcs/"><u>Free Logitech G903 Mouse Software & Drivers for Windows PCs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-newest-drivers-for-your-epson-wf-372-to-improve-print-quality-install-now/"><u>Get the Newest Drivers for Your Epson WF-372# to Improve Print Quality: Install Now!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-asus-computers-sound-up-and-running-realtek-audio-driver-for-free/"><u>Get Your ASUS Computer's Sound Up and Running: Realtek Audio Driver for FREE!</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-z-fold-5-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-successfully-download-and-install-zexmt-usb-bluetooth-driver-for-multiple-windows-versions/"><u>How to Successfully Download & Install Zexmt USB Bluetooth Driver for Multiple Windows Versions</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-crafting-perfect-youtube-thumbnails-on-macos/"><u>In 2024, Crafting Perfect YouTube Thumbnails on macOS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/mbox-2-drivers-download-and-update-for-windows-solved/"><u>MBox 2 Drivers Download & Update for Windows [SOLVED]</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/revolutionary-softbox-technology-for-artists/"><u>Revolutionary Softbox Technology for Artists</u></a></li>
<li><a href="https://win-updates.techidaily.com/streamlining-your-pc-experience-a-step-by-step-guide-to-disabling-user-login-in-windows-11/"><u>Streamlining Your PC Experience: A Step-by-Step Guide to Disabling User Login in Windows 11</u></a></li>
<li><a href="https://discover-best.techidaily.com/ultimate-guide-to-free-avi-convertors-compare-windows-mac-and-web-based-solutions/"><u>Ultimate Guide to Free AVI Convertors: Compare Windows, Mac and Web-Based Solutions</u></a></li>
</ul></div>

