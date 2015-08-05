---
layout: post
title: image-support
description: image support
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Image Support

## ImageClass

In your application, you can include **image** inside the Button. In that case, you can use **data-ej-imageclass** attribute for Button control, where you can specify the image to be displayed in the Button. Ensure that you need to set the **data-ej-contenttype** to ‘**image**’. 

You can refer the following code example.

{% highlight html %}


    <!--In head section-->
<style>
     .image {
            background-image: url("silverlight.jpg");
        }
</style>

    <!--In body section-->
 <input id="sample_button" type="button" data-role="ejmbutton" **data-ej-contenttype="image" data-ej-imageclass="image"** />



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-button//image-support_images//image-support_img1.png" Caption="Button - ImageClass"%}

## ImagePosition

You can also set the position of the image in the Button. The **data-ej-imageposition** attribute allows you to specify the position of the image in your Button control. You can set the position of the image in the Button either after the text or before text by setting the image position to ‘**right**’ or ‘**left**’ respectively.

By default this attribute is set to ‘**left**’. Ensure that you need to set the **data-ej-contenttype** to **‘both’**.

You can refer to the following code example.

{% highlight html %}


<!--Set the imagePosition-->
                           <input id="sample_button" type="button" data-role="ejmbutton" **data-ej-contenttype="both"** data-ej-text="button" **data-ej-imageposition="left"** data-ej-imageclass="image" />



{% endhighlight %}



{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-button//image-support_images//image-support_img2.png" Caption="Button – ImagePosition"%}

