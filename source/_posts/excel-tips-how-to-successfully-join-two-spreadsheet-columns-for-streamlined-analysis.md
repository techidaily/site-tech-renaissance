---
title: "Excel Tips: How to Successfully Join Two Spreadsheet Columns for Streamlined Analysis"
date: 2024-09-11T16:19:16.821Z
updated: 2024-09-15T17:54:23.759Z
categories:
  - BestProducts
description: "This Article Describes Excel Tips: How to Successfully Join Two Spreadsheet Columns for Streamlined Analysis"
excerpt: "This Article Describes Excel Tips: How to Successfully Join Two Spreadsheet Columns for Streamlined Analysis"
thumbnail: https://thmb.techidaily.com/477c1794ef618005849cb90b5c598de4a419e5c1f80c7ae4dc1f76086ad70935.jpg
---

## Excel Tips: How to Successfully Join Two Spreadsheet Columns for Streamlined Analysis
### What to Know

* Using the concatenate formula in Microsoft Excel you can combine two or more columns of data into one without losing any data.
* Once you've created the CONCATENATE formula in the first cell,**drag the Fill Handle** to duplicate the formula for remaining cells.
* Once combined, you need to change the merged data to values using copy and paste so you can delete or change the original data.

 This article explains how to combine two columns of data in Microsoft Excel into a single column without losing that data.

![A windows laptop sitting on a window sill, displaying Microsoft Excel.](https://www.lifewire.com/thmb/En3iWwF7IcbNVtlTPxk03Lieyas=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dean-pugh-C8NDn4xk9zs-unsplash-f0dd8299f92842af80b9013007ab8630.jpg)

Dean Pugh / Unsplash

## How to Combine Columns in Excel Without Losing Data

 If you just want to merge two empty columns in Excel, that's easy enough to do using the Merge option, but if those columns contain data, you'll lose all the data except what's in the uppermost left cell. If what you're actually trying to do is merge the data from two columns into a single column, the merge command won't work. Instead, you need to use the**CONCATENATE** formula to combine that data.

1. In the Excel worksheet where you want to combine two columns of data, first insert a new column near the data you want to combine. This is where your combined data will be displayed.  
 To insert a new column, right click a column to the right of where you want the new column to appear and select**Insert** from the menu that appears.
2. If your other columns have headers, give the new column a header name. In our example, it's**Full Name** .  
 You can use this same formula to combine the data from several columns. You just need to write it using the same syntax as above: **\=CONCATENATE (Cell1, "Separator", Cell2,"Separator", Cell 3...etc)**
3. Select the the first cell below the heading of the new column (C2 in this example) enter the following into the formula bar:  
**\=CONCATENATE(A2," ",B2)**  
 This tells excel you want to combine the data in cell A2 with the data in cell B2, with a space (" ") between them. In this example, the space between quotation marks is the separator, but if you choose, you can use any other separator you like.  
 For example, if a comma were between the quotation marks, like this:**\=CONCATENATE(A2,","B2)** then the data from cell A would be separated from the data in cell B by a comma.  
![The CONCATENATE formula in Microsoft Excel.](https://www.lifewire.com/thmb/nm_g5q7qFrqjiTG1U2qn2pioUDs=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_01-60e150b9f37a4835862036139397bc3f.jpg)
4. Once you've completed the formula, press**Enter** on your keyboard to activate it. The new data combination should appear in the cell.  
![The results of the CONCATENATE formula in Microsoft Excel.](https://www.lifewire.com/thmb/lrpZXUMOgKEYWsx163xnNjDFz6E=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_02-8b69ebb739dd4721a90babcd0465d135.jpg)
5. Now, you can copy the formula down the length of the column to combine all the desired entries. To do that, place your cursor bac in the previous cell (C2 in the example), grab the green dot (called the**Fill Handle** ) in the lower right corner of the screen and drag down the length of the column you want to use.  
 This will apply the formula to all selected rows.  
![An illustration of how to use the Fill Handle in Microsoft Excel.](https://www.lifewire.com/thmb/jRYAhCFQTgZj888CujHR4w9QvUQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_03-674a233d08ec4ea0bcf80e3bec90d68b.jpg)
6. Now, the data in the new column is part of a formula, and as such, if you delete any of the data used in the formula (in this example, any data in columns A or B) it will cause the combined data in column C to disappear.  
 To prevent this, you need to save all the new entries as a value so they won't disappear. So first, highlight all the combined data you just created and use the keyboard shortcut**Ctrl + C** on Windows or**Command + C** on Mac to copy it.  
![Data selection in Microsoft Excel.](https://www.lifewire.com/thmb/dJvhnrsFHFqq9jYyuvPDvP6vD_8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_04-0f81b1dc8ff5485cb2adf07a5f4262e3.jpg)
7. Then, in the first corresponding cell of the column you copied the data from, right click and select**Paste Value** .  
![The Past Value option in Microsoft Excel.](https://www.lifewire.com/thmb/PZ3_xakgfZ_JtN1mmM00mCW8m7Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_05-054201d683a14effbdab321008554e88.jpg)
8. The combined data will be pasted into the column as a value and you can change or delete the data from the original columns without changing the new, combined data.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

