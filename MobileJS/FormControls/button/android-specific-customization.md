---
layout: post
title: android-specific-customization
description: android specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Android Specific Customization

You can set the **Android specific** properties to the control by accessing **Android** property.

## Style

You can change the style of Android mode button by accessing **data-ej-android-style** attribute. 

The possible values are

1. Normal

2. Small

3. Dialog

You can refer to the following code example.

{% highlight html %}


<div align="center" style="margin:10px">
        <input type="button" id="sample_button" data-role="ejmbutton" data-ej-text="Normal" **data-ej-rendermode="android" data-ej-android-style="normal"** /><br /><br />

        <input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Small" **data-ej-rendermode="android" data-ej-android-style="small"** />

        <input type="button" id="sample_button2" data-role="ejmactionlink" data-ej-text="Dialog" **data-ej-rendermode="android" data-ej-android-style="dialog"** />
    </div>



{% endhighlight %}



{% include image.html url="android-specific-customization_images/android-specific-customization_img1.png" Caption="Button - Android Style"%}

