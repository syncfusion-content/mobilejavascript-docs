---
layout: post
title: Customize Header Left Button | Header and Footer | Mobilejs | Syncfusion
description: customize header left button
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

# Customize Header Left Button

## LeftButtonCaption

To specify the caption (text) for the Header left button, set the “data-ej-leftbuttoncaption” attribute. By default, the attribute value is set to back.

{% highlight html %}

 <div id="header_sample" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttoncaption="Home" ></div>

{% endhighlight %}

The following screenshot displays the Left Button Caption.

![](Customize-Header-Left-Button_images/Customize-Header-Left-Button_img1.png)

## LeftButtonStyle

The data-ej-leftbuttonstyle attribute specifies the style of the Header left button.

The possible values are, 

* Back
* Header
* Normal

{% highlight html %}

<div id="header_sample" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonstyle="normal" ></div>

{% endhighlight %}

The following screenshot displays the Left Button Style:

![](Customize-Header-Left-Button_images/Customize-Header-Left-Button_img2.png)

## LeftButtonNavigationURL

Specifies the navigation URL of the page while clicking the left button.

{% highlight html %}

<div id="header_sample" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonnavigationurl="navigation.html" ></div>

{% endhighlight %}