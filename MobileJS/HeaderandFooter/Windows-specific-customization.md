---
layout: post
title: Windows-specific-customization
description: windows specific customization
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

## Windows specific customization

You can set the Windows Specific properties to the control by accessing this property.

### WindowsCustomText

In the Windows phones, by default, the Header title's text is in the lower case irrespective of whatever case is provided for the title. To disable this behavior, set the “data-ej-windows-enablecustomtext” attribute to true. By default, the attribute value is set to false.

{% highlight html %}

<div id="header_sample" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-enablecustomtext=true data-ej-title="Custom Text" ></div>



{% endhighlight %}

The following screenshot displays the Windows specific customization:

{{ '![](Windows-specific-customization_images/Windows-specific-customization_img1.png)' | markdownify }}
{:.image }




