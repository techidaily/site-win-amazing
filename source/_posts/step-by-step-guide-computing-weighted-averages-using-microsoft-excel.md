---
title: "Step-by-Step Guide: Computing Weighted Averages Using Microsoft Excel"
date: 2024-11-29T06:18:48.188Z
updated: 2024-12-06T03:14:17.007Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What is a Weighted Average?

 A weighted average is an average that takes into account the importance, or weight, of each value. A good example would be calculating a student's final grade based on their performance on a variety of different assignments and tests. Individual assignments usually don't count as much towards a final grade as the final exam---things like quizzes, tests, and final exams will all have different weights. The weighted average is calculated as the sum of all of the values multiplied by their weights divided by the sum of all of the weights.

 The following example will demonstrate how to use Excel's SUMPRODUCT and SUM functions to calculate a weighted average.

##  Let's Look at an Example

 For our example, let's look at a student's quiz and exam scores. There are six quizzes each worth 5% of the total grade, two exams each worth 20% of the total grade, and one final exam worth 30% of the total grade. The student's final grade will be a weighted average, and we will use the SUMPRODUCT and SUM functions to calculate it.

 As you can see in our table below, we've already assigned the relative weights to each quiz and exam in the D column.

![Excel table showing scores and weights assigned to several quizzes and exams](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-01.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Step One: Calculate the SUMPRODUCT

 First, let's look at how the SUMPRODUCT function works. Start by selecting the cell where you want the result to appear (in our example, that's cell D13). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUMPRODUCT" function.

![On the Formulas tab, click Math &amp; Trig, then select SUMPRODUCT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-02.png) 

 The "Function Arguments" window will appear.

![the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-03.png) 

 For the "Array1" box, select the student's scores. Here, we're selecting all the cells with actual scores in the C column.

![In the Array1 box, select the cells with the grades](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-04.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, use the "Array2" box to select the weights of the quizzes and exams. For us, those are in the D column.

![In the Array2 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-05.png) 

 Click "OK" when you're done.

![Click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-06.png) 

 The SUMPRODUCT function will multiply each score by its corresponding weight and then return the sum of all of those products.

![The Excel table now shows the SUMPRODUCT value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-07.png) 

###  Step Two: Calculate the SUM

 Now let's look at how the SUM function works. Select the cell where you want the results to appear (in our example, that's cell D14). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUM" function.

![On the Formulas tab, click Math &amp; Trig, then select SUM](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-08.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The "Function Arguments" window will appear.

![The Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-09.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For the "Number1" box, select all of the weights.

![In the Number1 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-10.png) 

 Click "OK."

![click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-11.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The SUM function will add all of the values together.

![The Excel table now shows the SUM value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-12.png) 

###  Step Three: Combine the SUMPRODUCT and SUM to Calculate the Weighted Average

 Now we can combine the two functions to determine the student's final grade based on their scores and the weights of each score. Select the cell where the weighted average should go (for us that's cell D15) and then type the following formula into the function bar.

=SUMPRODUCT(C3:C11,D3:D11)/SUM(D3:D11)

![select the weighted average cell and then type the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-13.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-a-step-by-step-guide-to-implementing-lut-effects-in-premiere-pro/"><u>[New] 2024 Approved A Step-by-Step Guide to Implementing LUT Effects in Premiere Pro</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-professional-stability-essentials-for-youtube-videographers/"><u>[New] Professional Stability Essentials for YouTube Videographers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-live-recording-analyzer/"><u>[Updated] Live Recording Analyzer</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-youtube-partnership-unlocked-break-through-at-10k-vistas/"><u>2024 Approved YouTube Partnership Unlocked Break Through at 10K Vistas</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complete-tutorial-how-to-rejuvenate-your-computers-motherboard-drivers-in-windows-environments/"><u>Complete Tutorial: How to Rejuvenate Your Computer's Motherboard Drivers in Windows Environments</u></a></li>
<li><a href="https://buynow-info.techidaily.com/diy-guide-to-boosting-performance-of-intel-imachines/"><u>DIY Guide to Boosting Performance of Intel iMachines</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-samsung-m2070fw-driver-download-start-today/"><u>Effortless Samsung M2070FW Driver Download – Start Today</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-surface-book-drivers-quick-simple-and-secure/"><u>Get the Latest Surface Book Drivers - Quick, Simple & Secure!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-install-logitech-g29-driving-force-on-your-computer-windows-10117-compatibility-guide/"><u>How to Install Logitech G29 Driving Force on Your Computer: Windows 10/11/7 Compatibility Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-iphone-11-pro-max-drfone-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/our-picks-for-the-finest-car-dvd-units/"><u>Our Picks for the Finest Car DVD Units</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-to-get-the-new-intel-srt-driver-software/"><u>Step-by-Step Tutorial to Get the New Intel SRT Driver Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-innovators-pathway-advanced-video-editing-techniques-for-instagram/"><u>The Innovator's Pathway Advanced Video Editing Techniques for Instagram</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-apple-watch-models-thoroughly-evaluated-by-tech-gurus-zdnet/"><u>Top-Rated Apple Watch Models - Thoroughly Evaluated by Tech Gurus | ZDNet</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722976277844-up-to-date-nvidia-graphics-drivers-rtx-2nkd-supers-boost-your-pcs-running-win10-or-11/"><u>Up-to-Date Nvidia Graphics Drivers: RTX 2Nkd, Supers, Boost Your PCs Running Win10 or 11!</u></a></li>
</ul></div>

