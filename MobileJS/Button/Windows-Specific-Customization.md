---
layout: post
title: Windows-Specific-Customization
description: windows specific customization
platform: Mobilejs
control: Button (Mobile)
documentation: ug
---

## Windows Specific Customization

By using data-ej-windows-style attribute, you can customize the style of the button. 

The possible values are

1. Normal
2. Back

You can refer to the following code example.

{% highlight html %}

<div align="center" style="margin:10px">

        <input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="windows" data-ej-windows-style="normal" /><br /><br />



        <a id="sample_button2" data-role="ejmbutton" data-ej-text="Back" data-ej-rendermode="windows" data-ej-windows-style="back" />

</div>



{% endhighlight %}



{{ '![F:/Work/Testing/release_testing/13.2/Phase-3/btn.PNG](Windows-Specific-Customization_images/Windows-Specific-Customization_img1.png)' | markdownify }}
{:.image }


