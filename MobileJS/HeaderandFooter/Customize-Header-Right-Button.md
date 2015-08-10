---
layout: post
title: Customize-Header-Right-Button
description: customize header right button
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

# Customize Header Right Button

## RightButtonCaption 

To specify the caption (text) for HeaderRight Button, set “data-ej-rightbuttoncaption” attribute. By default, the value is set to “Right”.

{% highlight html %}



<div id="header_sample" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttoncaption="Next" ></div>



{% endhighlight %}

The following screenshot displays the Right Button Caption:

![](Customize-Header-Right-Button_images/Customize-Header-Right-Button_img1.png)





## RightButtonStyle

The data-ej-rightbuttonstyle attribute is used to specify the style of the Header right button.

The possible values are, 

* Header
* Normal



{% highlight html %}



<div id="header_sample" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonstyle="header" ></div>



{% endhighlight %}

The following screenshot displays the Right Button Style:

![F:/hdr.png](Customize-Header-Right-Button_images/Customize-Header-Right-Button_img2.png)





## RightButtonNavigationURL

This feature specifies the navigation URL of the page while clicking the right button.

{% highlight html %}



<div id="header_sample" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonnavigationurl="" ></div>



{% endhighlight %}



