---
layout: post
title: IOS7-Specific-Customization
description: ios7 specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# IOS7 Specific Customization

You can set the IOS7 specific properties to the control by accessing IOS7 property.

## Color

This attribute is specific to IOS7 rendermode that allows you to set the color of the Button when rendered as an action link to indicate the state of the link. 

You can set the text color of the Button using data-ej-ios7-color attribute.

Please refer to the following code example.

{% highlight html %}



<div align="center" style="margin:10px">

        <a id="sample_button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="gray" /> <br /><br />



        <a id="sample_button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="black" /><br /><br />



        <a id="sample_button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="blue" /><br /><br />



        <a id="sample_button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="green"/><br /><br />



        <a id="sample_button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="red" /><br /><br />



    </div>



{% endhighlight %}



{{ '![C:/Users/deepal/AppData/Local/Temp/SNAGHTML1f717c65.PNG](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img1.png)' | markdownify }}
{:.image }


## Style

You can change the style of IOS7 mode button by accessing data-ej-ios7-style attribute. The possible values are:

1. Normal
2. Back
3. Dialog
4. Header

You can refer to the following code example.

{% highlight html %}



<div align="center" style="margin:10px">

        <input type="button" id="sample_button" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="ios7" data-ej-ios7-style="normal" /><br /><br />



        <a id="sample_button1" data-role="ejmbutton" data-ej-text="Back" data-ej-rendermode="ios7" data-ej-ios7-style="back" />



        <input type="button" id="sample_button2" data-role="ejmactionlink" data-ej-text="Dialog" data-ej-rendermode="ios7" data-ej-ios7-style="dialog"/>



        <input type="button" id="sample_button3" data-role="ejmactionlink" data-ej-text="Header" data-ej-rendermode="ios7" data-ej-ios7-style="header"/>



    </div>





{% endhighlight %}



{{ '![C:/Users/deepal/AppData/Local/Temp/SNAGHTML1f700342.PNG](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img2.png)' | markdownify }}
{:.image }


