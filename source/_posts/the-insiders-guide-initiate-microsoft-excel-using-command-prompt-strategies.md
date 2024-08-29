---
title: "The Insider's Guide: Initiate Microsoft Excel Using Command Prompt Strategies"
date: 2024-08-26 22:11:24
updated: 2024-08-29 10:46:10
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ec6b1f1d7d998ce573dd315cc18c0246f2fda616f5f88137d905e138146bac2b.jpg
---

## The Insider's Guide: Initiate Microsoft Excel Using Command Prompt Strategies

### Quick Links

* [Table of Contents](https://program-issues.techidaily.com/enhancing-experience-eliminating-lags-within-the-elder-scrolls-online-blackwood-fixes-applied/)

 You can [open Microsoft Excel](https://ai-vdieo-software.techidaily.com/updated-beyond-quik-exploring-the-best-pc-video-editing-software-for-gopro-users/) from the Command Prompt, and you can also add additional parameters to the command to do things like open Excel with a specific template, or [launch Excel in Safe Mode](https://facebook-video-share.techidaily.com/updated-in-2024-crafting-clearer-communication-the-art-of-adding-text-to-video-media/) for troubleshooting.

##  Table of Contents

* **[Launch Excel Using Command Prompt](https://tech-recovery.techidaily.com/how-to-enjoy-hulu-on-demand-with-your-lg-smart-television-easy-steps/)**
* **[Excel Command Line Switches and Parameters](https://ios-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/)**

### Launch Excel Using Command Prompt

 There are many ways to start Excel using Command Prompt, but if you want to launch Excel in its normal state (that is, the same way that Excel launches when you click the shortcut), then there are two different ways to do that.

 First, there's the simple way. [Open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "cmd" in the Windows Search bar and clicking the Command Prompt app from the search results.

![Type cmd in the Windows Search bar and click Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/Type-cmd-in-the-Windows-Search-bar-and-click-Command-Prompt..png) 

 Command Prompt will open. To launch Excel, type this command and press Enter:

start excel

![Type "start excel" in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/Type-start-excel-in-Command-Prompt.-1.png) 

 Excel should launch immediately.

 Another way to open Excel is by locating the directory that holds the excel.exe file, changing to that directory in Command Prompt, and then running a simple command.

 To locate the excel.exe file, you'll need to be in the Program Files directory in Command Prompt. You can [use the cd command](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) to change the directory. Type this command in Command Prompt, and then press Enter:

cd\"program files"

![Change to the "Program Files" directory in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/Change-to-the-Program-Files-directory-in-Command-Prompt..png) 

 You'll now be in the Program Files directory. Next, you need to find out in which directory the excel.exe file is located. To do so, run this command:

dir excel.exe /s

 The directory of the excel.exe file will be returned.

![The directory of Excel returned in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/The-directory-of-Excel..png) 

 Now that you know the directory where excel.exe is located, navigate to that directory. Since we're already in the Program Files directory, we can omit that from the next command. In our example, we'd run this command:

cd Microsoft Office\root\Office16

![Change to the directory that contains the excel file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/Change-to-the-directory-that-contains-the-excel-file..png) 

 Now that you're in the correct directory, all that's left to do is to type `excel` in Command Prompt and press Enter.

![Type "excel" in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/Type-excel-in-Command-Prompt..png) 

 Excel will now open. However, the main purpose of launching Excel from Command Prompt is so that you can control how it opens, and you do that by appending the various switches and parameters that are available to the command.

### Excel Command Line Switches and Parameters

 Here's a list of command switches provided by the [official Microsoft Office support site](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6#ID0EAABAAA=Excel). Add these to the end of the `start excel` command in Command Prompt.

| **Switch and Parameter**                                                                                   | **Description**                                                                                                                                                         |
| ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| workbook path \| file nameNo switch is required.                                                           | Opens the target file.**Example:**start excel "c:\\Example Folder\\file\_name1.xlsx"orstart excel http://MySite/file\_name1.xlsx                                        |
| **/r** workbook path \| file name                                                                          | Opens the target workbook as read-only.**Example:**start excel /r "c:\\Example Folder\\file\_name1.xlsx"orstart excel /r http://MySite/file\_name1.xlsx                 |
| **/t** _workbook path_ \| _file name_You can also use **/n** instead of **/t** to achieve the same result. | Opens the target file as a template.**Example:**start excel /t "c:\\Example Folder\\file\_name1.xlsx"orstart excel /t http://MySite/file\_name1.xlsx                    |
| **/e** or **/embed**                                                                                       | Prevents the Excel startup screen from appearing and a new blank workbook from opening.                                                                                 |
| **/s** or **/safemode**                                                                                    | Starts Excel in Safe Mode. This launches Excel without any additional add-ins, templates, or other customizations. It's helpful when troubleshooting problems in Excel. |
| **/m**                                                                                                     | Creates a new workbook that contains a single XLM macro sheet.                                                                                                          |
| **/a** _progID_                                                                                            | Loads the Automation add-in specified by the progID of the add-in.**Example:**start excel /a MyProgId.MyProgID2.1                                                       |
| **/x**                                                                                                     | Starts a separate process of Excel.                                                                                                                                     |

 Using these commands, you can open Excel in a number of different ways.

 Excel isn't the only Office program that you can open with Command Prompt---you can also use it to launch [Microsoft Word](https://ai-video-apps.techidaily.com/new-2024-approved-uncover-the-best-green-screen-software-for-mac-video-editing/) and [PowerPoint](https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-vivo-s17-for-parents-drfone-by-drfone-virtual-android/). The commands can differ between applications, so explore which options are available for each one.

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
