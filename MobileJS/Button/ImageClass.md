---
layout: post
title: ImageClass | Button | Mobilejs | Syncfusion
description: imageclass
platform: Mobilejs
control: Button (Mobile)
documentation: ug
---

# ImageClass

In your application, you can include image inside the Button. In that case, you can use ImageClass for Button control where you can specify the image as a class to be displayed in the Button. Set the ContentType to ‘image’. 

You can refer to the following code example.

{% highlight html %}

<input id="sample_button" type="button" data-role="ejmbutton" data-ej-contenttype="image" data-ej-imageclass="image" />

{% endhighlight %}

Add the following styles to the content

{% highlight css %}

.image {

	background-image: url("silverlight.jpg");

}
		
{% endhighlight %}

![](ImageClass_images/ImageClass_img1.png)