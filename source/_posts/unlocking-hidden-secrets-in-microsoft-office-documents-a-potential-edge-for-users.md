---
title: "Unlocking Hidden Secrets in Microsoft Office Documents: A Potential Edge for Users"
date: 2024-08-28T04:35:46.843Z
updated: 2024-08-29T04:35:46.843Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/72d87bf38b3f988e318217c000305d7e3da283a047b864a8cf5c572968e745b4.jpg
---

## Unlocking Hidden Secrets in Microsoft Office Documents: A Potential Edge for Users

Microsoft Word, Excel, or PowerPoint files can contain images, video, and other embedded files, but it can be annoying to save them. Thankfully, there’s a workaround for that, and it relies on a secret with the modern Office file format.

 Microsoft Office 2007 and later use the [Office Open XML format](https://en.wikipedia.org/wiki/Office%5FOpen%5FXML) for documents, such as .docx for Word, the .pptx format for PowerPoint, and .xlsx for Excel. There are also other file endings for macro-enabled documents or templates, but they all use the same general file format. The same format is used by the Office web apps and mobile apps, and by Google Docs when you export to Office format.

 The fun part is that these Office files are just .zip files in disguise. You can un-zip them to get direct access to all embedded files and data, including any images, videos, audio, or other content. I’ve used this trick countless times when receiving documents that contain lots of images, since unzipping the file is usually faster than looking for each individual image in the document to copy or extract.

 Let’s use an example. I have a PowerPoint presentation with some wallpaper images from Windows, and a copy of the classic CANYON.MID music track included with Windows 3.0 as a video. I could right-click each media file to save it to my files, but that’s annoying and time-consuming if there are more than a few embedded files.

![Screenshot of a PowerPoint with embedded images.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/clipboard-jul-12-2024-at-3-05-pm.png) 

 Instead, I can create a duplicate of the PowerPoint file (just copy and paste the file into the same directory in your file manager), then change the file ending to .zip and open it. Alternatively, archive application like [7-Zip](https://www.7-zip.org/) on Windows or [The Unarchiver](https://theunarchiver.com/) on Mac can usually open the original file directly and recognize them as ZIP format.

 The un-zipped file contains a few XML files with the text and other file information. There’s a main folder, such as “word” for Word files or “ppt” in PowerPoint files, which in turn has a “media” directory with all the embedded files. In this example, all the wallpaper images and the video are in the media folder under the “ppt” folder.

Close 

 The one catch is that media files don’t keep their original names when unzipped, so you won’t be able to search for them by their original file name. However, the original file ending and some other metadata is still present. Also, the files have to be in the modern Office 2007+ format, not the older formats like .doc, .ppt, or .xls.

 Even with the limitations, this trick can still be helpful if you need to get images, videos, and other embedded files out of an Office document, especially on computers without the required applications installed.

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



<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->