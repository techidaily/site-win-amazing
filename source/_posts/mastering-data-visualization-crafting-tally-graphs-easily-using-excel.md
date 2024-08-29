---
title: "Mastering Data Visualization: Crafting Tally Graphs Easily Using Excel"
date: 2024-08-26 20:59:37
updated: 2024-08-29 11:53:46
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

##  Make the Tally Graph with a Formula

 We now know the number of groups of five and also the number of singles to display in the tally graph. We just need to combine them into one row of tally marks.

 To do this, we will use the REPT function to repeat the occurrences of each character the required number of times, and concatenate them.

 In cell F3, enter the following formula:

=REPT($D$1,D3)&REPT($E$1,E3)

![Create a tally graph with REPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-graph-1.png) 

 The REPT function repeats text a specified number of times. We used the function to repeat the tally characters the number of times specified by the groups and singles formulas. We also used the ampersand (&) to concatenate them together.

##  Hide the Helper Columns

 To finish the tally graph, we will hide the helper columns D and E.

 Select columns D and E, right-click, and then choose "Hide."

![Hide the helper columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/hide-columns.png) 

 Our completed tally graph provides a nice visual presentation of the number of votes each person received.

![Completed tally graph in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/completed-tally-graph.png)

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
