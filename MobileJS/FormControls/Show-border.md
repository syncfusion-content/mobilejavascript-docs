---
layout: post
title: Show-Border
description: show border
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Show Border

The data-ej-showborder attribute is used to decide whether the Textbox border can be visible or hidden. The default value is true.

Refer to the following code example.

{% highlight html %}



  <input id="textbox_sample" data-role="ejmtextbox" data-ej-watermarktext="Textbox" data-ej-showborder="false">

    <input id="textbox_sample" data-role="ejmpassword" data-ej-watermarktext="Password"   data-ej-showborder="false">

    <textarea id="textbox_sample" data-role="ejmtextarea" data-ej-watermarktext="Textarea"  data-ej-showborder="false"></textarea>

    <input id="textbox_sample" data-role="ejmmaskedit" data-ej-showborder="false" data-ej-watermarktext="Maskedit" data-ej-mask="+1 (999) 999-9999" />





{% endhighlight %}



{{ '![C:/Users/isuriyar/AppData/Local/Temp/SNAGHTML8017b82d.PNG](Show-Border_images/Show-Border_img1.png)' | markdownify }}
{:.image }


