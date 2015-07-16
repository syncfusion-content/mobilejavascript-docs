---
layout: post
title: Hide-Header
description: hide header
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

## Hide Header

In some cases (for example, when tab is used in the application), Header control need not be displayed in Android and Windows Platforms. For this scenario, set data-ej-hideforunsupporteddevice attribute. When this attribute is set to true, Header is visible for iOS7 rendermode alone and not visible in Android and Windows rendermode. By default, the attribute value is set to false.

{% highlight html %}



<div id="header_sample" data-role="ejmheader" data-ej-hideforunsupporteddevice=true ></div>



{% endhighlight %}



