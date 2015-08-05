---
layout: post
title: flat-specific-customization
description: flat specific customization
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Flat Specific Customization

You can set the **Flat specific** properties to the control by accessing **Flat** property.

## Style

You can change the style of Flat mode button by accessing **data-ej-flat-style** attribute 

The possible values are

1. Normal

2. Back

3. Header

You can refer to the following code example.

{% highlight html %}


    <div align="center" style="margin:10px">
        <input type="button" id="sample_button" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="flat" **data-ej-flat-style="Normal"** /> <br /><br />

        <input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Back" data-ej-rendermode="flat" **data-ej-flat-style="back"** /><br /><br />

        <input type="button" id="sample_button2" data-role="ejmactionlink" data-ej-text="Header" data-ej-rendermode="flat" **data-ej-flat-style="header"** />
    </div>



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-button//flat-specific-customization_images//flat-specific-customization_img1.png" Caption="Button - Flat Style"%}

