---
title: Effective Strategies for Implementing Accessible Labels on Excel Visual Data Representations
date: 2024-08-28T04:35:10.667Z
updated: 2024-08-29T04:35:10.667Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## Effective Strategies for Implementing Accessible Labels on Excel Visual Data Representations

### Quick Links

* [Why Include Captions in Excel Graphs?](https://extra-information.techidaily.com/start-screen-special-free-editing-tools/)
* [Create the Caption Text](https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-vivo-v29e-by-stellar-video-repair-mobile-video-repair/)
* [Add Captions to an Excel Graph](https://screen-video-capture.techidaily.com/new-2024-approved-harvest-hits-roundup-next-gen-farming-game-picks/)

 Include captions in your Microsoft Excel graphs to provide rich and meaningful labels. The labels can be used to display extra information that is not plotted on the graph. By linking them to cell values, you can make these captions dynamic.

##  Why Include Captions in Excel Graphs?

 When you create a chart in Excel, you are provided with label elements. These include the chart title, data labels, and axis titles. These labels can be very useful for displaying extra information in the chart, especially when you [use cell values for Excel chart labels](https://tech-recovery.techidaily.com/top-gaming-console-picks-for-the-year-2024/).

 The following chart uses a link to a cell value to show the total cells in the chart title.

![Dynamic chart title using cell values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/dynamic-chart-title.png) 

 However, you are not limited to these built-in labels. You can include captions in Excel graphs by adding text boxes.

 This chart was created using the following set of data.

![Sample data for the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/chart-data-1.png) 

##  Create the Caption Text

 Let's add a caption to tell more of the story of this data. We will add a caption to convey the top product and its sales total.

 First, we need to calculate the data we want to display. In cell D2, the following formula is used to return the maximum sales value.

=MAX(B2:B7)

![Calculate the maximum value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/max-value-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 We can then use a formula in cell D3 with the [INDEX and MATCH combination](https://support.office.com/en-gb/article/look-up-values-with-vlookup-index-or-match-68297403-7c3c-4150-9e3c-4d348188976b) to return the name of that product.

=INDEX(A2:A7,MATCH(D2,B2:B7,0))

![INDEX and MATCH to return product name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/index-match.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 In cell D4, we can make a creative caption from these calculated values.

=D3&" is the top product with "&D2&" sales."

![Creative text for a caption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/creative-text.png) 

##  Add Captions to an Excel Graph

 Before we add the caption, we need to resize the plot area of this chart to make some space for it.

 Click on the plot area to select it, then drag the resize handle to make room between the chart title and the chart values.

![Resize the plot area](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/resize-plot-area.png) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 We will include the caption by inserting a text box. Click Insert > Text Box and then select the chart to insert it.

![Insert a text box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/text-box.png) 

 Next, click in the Formula Bar, type "=" and then select cell D4 (the cell containing the caption text).

![Refer to the caption text cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/cell-link.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
 Press the Enter key.

 The caption text is shown in the text box and can be moved and resized into an appropriate position on the chart.

![Caption on an Excel chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/inserted-caption.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
 To finish the caption, format it to a light grey so that it is not as impactful as the chart title. Click Home, the list arrow for "Font Color," then select a light grey.

![Formatting with a light grey font colour](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/light-grey.png) 

 This is one example of including captions, but it is up to you to be creative. You can show whatever information you want your chart to convey to go beyond the standard charts.

![Completed Excel chart with caption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/finished-chart.png)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
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


