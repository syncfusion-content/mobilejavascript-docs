---
layout: post
title: Flat-Specific-Customization
description: flat specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Flat Specific Customization

You can set the Flat specific properties to the control by accessing Flat property.

## Style

You can change the style of Flat mode button by accessing data-ej-flat-style attribute 

The possible values are

1. Normal
2. Back
3. Header

You can refer to the following code example.

{% highlight html %}



    <div align="center" style="margin:10px">

        <input type="button" id="sample_button" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="flat" data-ej-flat-style="Normal" /> <br /><br />



        <input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Back" data-ej-rendermode="flat" data-ej-flat-style="back" /><br /><br />



        <input type="button" id="sample_button2" data-role="ejmactionlink" data-ej-text="Header" data-ej-rendermode="flat" data-ej-flat-style="header" />

    </div>





{% endhighlight %}



{ ![C:/Users/deepal/AppData/Local/Temp/SNAGHTML2ab540a8.PNG](Flat-Specific-Customization_images/Flat-Specific-Customization_img1.png) | markdownify }
{:.image }


