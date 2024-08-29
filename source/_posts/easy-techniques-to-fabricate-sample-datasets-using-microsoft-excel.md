---
title: Easy Techniques to Fabricate Sample Datasets Using Microsoft Excel
date: 2024-08-27 17:18:25
updated: 2024-08-29 10:47:37
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## Easy Techniques to Fabricate Sample Datasets Using Microsoft Excel

### Quick Links

* [Use the Formula Bar](https://ai-editing-video.techidaily.com/new-how-to-create-a-youtube-intro-for-2024/)
* [Adding Random Numbers](https://vp-tips.techidaily.com/new-from-plate-to-screen-perfecting-the-art-of-food-cinema-for-2024/)
* [Adding Dates](https://article-files.techidaily.com/2024-approved-highpoint-masterpiece-suite/)
* [Adding Item Data](https://fox-glue.techidaily.com/2024-approved-elevate-your-interface-mastery-with-these-less-known-windows-11-strategies/)

 Creating random data to fill an Excel workbook is as simple as adding a few little-known formulas. These formulas come in handy when honing your Microsoft Excel skills, as they give you fake data to practice with before you risk mistakes with the real thing.

##  Use the Formula Bar

 To start, we'll enter one of a few formulas in the Formula bar. This is the window below the ribbon, found here.

![Excel formula bar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/formula-bar.png.pagespeed.ce_.8yZx-vULvh-2.png) 

 From there, it's about adding the data you want and then doing a little cleanup.

##  Adding Random Numbers

 To add an integer at random, we’ll use the "RANDBETWEEN" function. Here, we can specify a range of random numerals, in this case, a number from one to 1,000, then copy it to each cell in the column below it.

 Click to select the first cell where you'd like to add your random number.

 Copy the following formula and paste it into Excel’s Formula bar. You can change the number inside the parenthesis to fit your needs. This formula picks a random number between one and 1,000.

        `=RANDBETWEEN(1,1000)`
    
 Press "Enter" on the keyboard or click the "Green" arrow to apply the formula.

![Excel random number formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/random-number-formula-2.png) 

 In the lower-right corner, hover over the cell until the "+" icon appears. Click and drag it to the last cell in the column where you want to apply the formula.

![Excel copy data plus](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/plus-2.png) 

 You can use the same formula for monetary values with a simple tweak. By default, RANDBETWEEN only returns whole numbers, but we can change that by using a slightly modified formula. Just change the dates in parenthesis to meet your needs. In this case, we're choosing a random number between $1 and $1,000.

        `=RANDBETWEEN(1,1000)/100`
    
![Excel random number formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/random-number-formula-copy-1.png) 

 Once done, you'll need to clean up the data just a little. Start by right-clicking inside the cell, and selecting "Format Cells."

![Excel format cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/format-2.png) 

 Next, choose "Currency" under the "Category" menu and then select the second option under the "Negative Numbers" option. Press "Enter" on the keyboard to finish.

![Excel format currency](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/format-currency-2.png) 

##  Adding Dates

 Excel's built-in calendar treats each date as a number, with the number one being January 1, 1900\. Finding the number for the date you need isn't so straightforward, but we've got you covered.

 Select your starting cell and then copy and paste the following formula into Excel's Formula bar. You can change anything in parenthesis to fit your needs. Our sample is set to pick a random date in 2020.

        `=RANDBETWEEN(DATE(2020,1,1),DATE(2020,12,31))`
    
 Press "Enter" on the keyboard or click the "Green" arrow to the left of the Formula bar to apply the formula.

![Excel date formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/date-formula-2.png) 

 You'll notice that this doesn't look anything like a date yet. That's okay. Just like in the previous section, we're going to click the "+" sign at the bottom right of the cell and drag it down as far as needed to add additional randomized data.

 Once done, highlight all of the data in the column.

![Excel highlight column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/date-highlight-2.png) 

 Right-click and select "Format Cells" from the menu.

![Excel format cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/format-3.png) 

 From here, choose the "Date" option and then choose the format you prefer from the available list. Press "OK" once you're done (or "Enter" on the keyboard). Now, all of your random numbers should look like dates.

![Excel data format](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/date-format-2.png) 

##  Adding Item Data

 Randomized data in Excel isn’t limited to just numbers or dates. Using the "VLOOKUP" feature, we can create a list of products, name it, then pull from it to create a randomized list in another column.

 To start, we'll need to create a list of random things. In this example, we'll add pets from an imaginary pet store starting at cell B2 and ending at B11\. You'll need to number each product in the first column, starting at A2 and ending at A11, coinciding with the product to the right. Hamsters, for example, have the product number 10\. The headings in cells A1 and B1 aren't necessary, though the product numbers and names below them are.

![Excel columns and rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/pet-store-2.png) 

 Next, we’ll highlight the entire column, right-click it, and select the “Define Name” option.

![Excel define name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/define-name-2.png) 

 Under "Enter a name for the date range," we'll add a name and then click the "OK" button. We've now created our list from which to pull random data.

![Excel define name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/add-name-pets-2.png) 

 Choose a starting cell and click to highlight it.

![Excel highlight cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/highlight-cell-2.png) 

 Copy and paste the formula into the Formula bar and then press "Enter" on the keyboard or click the "Green" arrow to apply it. You can change the values (1,10) and the name ("products") to fit your needs:

        `=VLOOKUP(RANDBETWEEN(1,10),products,2)`
    
![Excel formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/pets-formula-2.png) 

 Click and drag the "+" sign at the bottom right of the cell to copy the data into additional cells below (or to the side).

![Excel copy data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/more-pets-2.png) 

 Whether learning pivot tables, experimenting with formatting, or learning how to create a chart for your next presentation, this dummy data could prove to be just what you need to get the job done.

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
