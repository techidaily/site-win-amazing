---
title: "Building Effective Visual Progress Indicators: Conditional Formatting Techniques in Excel"
date: 2024-08-26 18:52:21
updated: 2024-08-29 10:55:59
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/dc4a82d976964b1f2e7b859f5b2f6939dbc4ceccf4ea97b9d7a6a6bfaea9749c.jpg
---

## Building Effective Visual Progress Indicators: Conditional Formatting Techniques in Excel

Progress bars are pretty much ubiquitous these days; we’ve even seen them on some water coolers. A progress bar provides instant feedback on a given process, so why not bring some of that graphical pizzazz into your spreadsheet, using Excel’s Conditional Formatting feature?

##  Progress Bars in Excel 2010

 “Bar-type” conditional formatting has been around since Excel 2007\. But Excel 2007 would only make bars with a gradient – the bar would get paler and paler towards the end, so even at 100% it wouldn’t really look like 100%. Excel 2010 addresses this by adding Solid Fill bars that maintain one color all throughout. These are ideal for creating progress bars.

##  Creating The Bar

 The first thing you have to do is enter a numeric value into the cell you’d like to format. You can either enter the value directly or use a formula. In our case I’ll just type it in.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/03/image58.png) 

 Note how I made the column wider; you don’t necessarily have to do this, but it does help make the bar look more like a “bar” (and not just a colored cell).

 Now click Conditional Formatting, select Data Bars and click More Rules.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/03/image59.png) 

 In the New Formatting Rule dialog check the box that says Show Bar Only (so the number doesn’t appear in the cell). Under Minimum and Maximum, select Type as Number. Then, set the Value to the minimum (beginning) value of your scale and maximum (the top of your bar, the end of the process). We’ll just go for 0 and 100, but you could set this to anything that works for you.

 Now let’s configure the Bar Appearance. Make sure the Fill is Solid Fill and select the color you’d like to use. When you’re done, the dialog should look similar to this:

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/03/image60.png) 

 Now click OK, and you’re done! At this point you should have a beautiful, crisp progress bar adorning your spreadsheet.

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
