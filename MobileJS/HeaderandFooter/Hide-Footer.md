---
layout: post
title: Hide-Footer
description: hide footer
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

# Hide Footer

In some cases (for example, when toolbar is used in the application), Footer control need not be displayed in Android and Windows Platforms. For this scenario, you can use data-ej-hideforunsupporteddevice attribute. When this attribute is set to true, Footer is visible for IOS7 rendermode alone and is not visible in Android and Windows rendermode. By default, the attribute value is set to false.

{% highlight html %}

<div id="footer_sample" data-role="ejmfooter" data-ej-hideforunsupporteddevice=true ></div>



{% endhighlight %}



