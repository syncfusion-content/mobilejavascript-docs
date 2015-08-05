---
layout: post
title: customize-value
description: customize value
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Customize value

The current value of the Numeric Textbox can be specified by using **data-ej-value** attribute. The range for the Numeric Textbox can be specified by using the **data-ej-maxvalue** and **data-ej-minvalue** attributes. The Numeric Textbox can only accept values within those specified range. The **data-ej-incrementstep** attribute is used to set the step value in each incrementing or decrementing textbox when the spin buttons are clicked or up/down arrows are used.

{% highlight html %}


<input type="number" id="textbox_sample" data-role="ejmnumeric" **data-ej-value="30**" **data-ej-incrementstep="2" data-ej-maxvalue=100 data-ej-minvalue=3** />


{% endhighlight %}



The following screenshot displays the output.

{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-numeric-textbox//customize-value_images//customize-value_img1.png" Caption="Figure 26: Numeric Textbox-Value"%}

{% highlight html %}


<input type="number" id="textbox_sample" data-role="ejmnumeric" **data-ej-decimalPlaces="3"**/>


{% endhighlight %}



