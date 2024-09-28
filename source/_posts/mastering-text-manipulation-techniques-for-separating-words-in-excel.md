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


