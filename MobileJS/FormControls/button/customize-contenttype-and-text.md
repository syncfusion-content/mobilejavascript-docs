---
layout: post
title: customize-contenttype-and-text
description: customize contenttype and text
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Customize ContentType and Text

## ContentType

You can make the Button appear as an image or text or combination of both. The **data-ej-contenttype** attribute allows you to choose the content type of the Button in your application. By default, the content type of Button is set to ‘**text**’.

The possible values are, 

* Text

* Image

* Both

You can refer to the following code example.

{% highlight html %}


  <!--specify the button content-type-->               
 <input id="sample_button" type="button" data-role="ejmbutton" data-ej-text="button" **data-ej-contenttype="text"** />



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-button//customize-contenttype-and-text_images//customize-contenttype-and-text_img1.png" Caption="Button – ContentType"%}

## Text

The **data-ej-text** attribute allows you to specify the text to be appeared inside the Button. 

You can refer to the following code example.

{% highlight html %}


<!-- Set the button text-->

<input id="sample_button" data-role="ejmbutton" **data-ej-text="button"** />



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-button//customize-contenttype-and-text_images//customize-contenttype-and-text_img2.png" Caption="Button - Text"%}

