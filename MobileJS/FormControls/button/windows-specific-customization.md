---
layout: post
title: windows-specific-customization
description: windows specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Windows Specific Customization

You can set the **Windows specific** properties to the control by accessing **Windows** property.

## Style

You can change the style of Windows mode button by accessing **data-ej-windows-style** attribute.

The possible values are

1. Normal

2. Back

You can refer to the following code example.

{% highlight javascript %}


<div align="center" style="margin:10px">
        <input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="windows" **data-ej-windows-style="normal"** /><br /><br />

        <a id="sample_button2" data-role="ejmbutton" data-ej-text="Back" data-ej-rendermode="windows" **data-ej-windows-style="back"** />
    </div>



{% endhighlight %}



{% include image.html url="windows-specific-customization_images/windows-specific-customization_img1.png" Caption="Button - Windows Style"%}

