---
layout: post
title: strict-mode
description: strict mode
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Strict Mode

The **data-ej-enablestrictmode** attribute makes Textbox accept only a value between the defined maximum and minimum values when it is set to **true**.

{% highlight html %}

<input type="number" id="textbox_sample" data-role="ejmnumeric" data-ej-minvalue=30 data-ej-maxvalue=100 **data-ej-enablestrictmode="true"** />


{% endhighlight %}



The following screenshot displays the output.

{% include image.html url="strict-mode_images/strict-mode_img1.png" Caption="Numeric Textbox-Enable Strict Mode"%}

