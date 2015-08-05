---
layout: post
title: customize-watermark-text
description: customize watermark text
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Customize Watermark text

The **data-ej-watermarktext** attribute is used to customize the text that appears in the background of your **Textbox**. It acts like a label for the **Textbox**.

Refer to the following code example.

{% highlight html %}


     <input id="textbox_sample" data-role="ejmtextbox" **data-ej-watermarkText="Textbox**">
     <input id="textbox_sample" data-role="ejmpassword" data-ej-**watermarktext="Password**">
     <textarea id="textbox_sample" data-role="ejmtextarea" data-ej-**watermarkText="Textarea**"></textarea>
          <input id="textbox_sample" data-role="ejmmaskedit" **data-ej-watermarktext="Maskedit"** data-ej-mask="+1 (999) 999-9999" />



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-textbox//customize-watermark-text_images//customize-watermark-text_img1.png" Caption="Textbox - Water Mark Text"%}

