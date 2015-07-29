---
layout: post
title: Android-specific-customization
description: android specific customization
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

# Android specific customization

You can set the Android Specific properties to the control by accessing Android property.

## BackButtonImageClass

This feature specifies the class name in which an image for the back button is set.  Refer to the following code example.

{% highlight html %}



<div id="header_sample" data-role="ejmheader" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-backbuttonimageclass="img" ></div>



{% endhighlight %}



Add the following styles to the content.

{% highlight css %}



        .img {

            background: url("pin.png") no-repeat;

        }





{% endhighlight %}



The following screenshot displays the Android Specific customization:

![F:/android_phone.png](Android-specific-customization_images/Android-specific-customization_img1.png)





