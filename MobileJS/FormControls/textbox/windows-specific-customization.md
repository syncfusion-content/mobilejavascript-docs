---
layout: post
title: windows-specific-customization
description: windows specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Windows specific customization

The **data-ej-allowreset** attribute is used to reset the password value in windows rendermode. The default value is **true.**

Refer to the following code example.

{% highlight html %}


<input id="textbox_sample" data-role="ejmpassword" data-ej-watermarktext="Password" **data**-**ej-rendermode="windows" data-ej-windows-allowreset="true**">



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-textbox//windows-specific-customization_images//windows-specific-customization_img1.png" Caption="Textbox - AllowReset"%}

