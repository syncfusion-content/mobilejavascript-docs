---
layout: post
title: Customize-menu-item-and-its-images
description: customize menu item and its images
platform: Mobilejs
control: Radial Menu (Mobile)
documentation: ug
---

## Customize menu item and its images

You can customize Radial Menu items by using imagepath, imageurl and text properties. The data-ej-imagepath attribute is used to define the path corresponding to the rendermode it get renders. The data-ej-imagename attribute can be used to define the name of image. Refer to the folder name that is required to keep the images for the corresponding render modes.

1. Ios7 – Folder name for ios7 specific images
2. Android – Folder name for Android specific images
3. Windows – Folder name for Windows specific images

Alternatively you can use data-ej-imageurl attribute to directly specify the url of the image for the items. The data-ej-text property is used to specify the item text in windows mode.

{ ![C:/Users/ApoorvahR/Desktop/Note.png](Customize-menu-item-and-its-images_images/Customize-menu-item-and-its-images_img1.png) | markdownify }
{:.image }
_Note: data-ej-imagepath and data-ej-imagename attributes can be used when you want to specify separate images for each render mode. The data-ej-imageurl attribute is used when you want to provide common images for all render modes._

Refer to the following code example.

{% highlight html %}



    <div id="radialmenu_sample" data-role="ejmradialmenu" data-ej-position="rightcenter" data-ej-touchend="click">

        <ul>

            <li data-ej-imagename="social.png" data-ej-imagepath=" http://js.syncfusion.com/UG/Mobile/Content/radial"></li>

            <li data-ej-imagename="music.png" data-ej-imagepath=" http://js.syncfusion.com/UG/Mobile/Content/radial"></li>

            <li data-ej-imageurl=" http://js.syncfusion.com/UG/Mobile/Content/radial /ios7/light/direction.png"></li>

            <li data-ej-imageurl=" http://js.syncfusion.com/UG/Mobile/Content/radial /ios7/light/message.png"></li>

            <li data-ej-imageurl=" http://js.syncfusion.com/UG/Mobile/Content/radial /ios7/light/browser.png"></li>

        </ul>

    </div>





{% endhighlight %}

Refer the following code examples for script section

{% highlight js %}

        function click(e) {

            $("#radialmenu_sample").ejmRadialMenu("menuHide");

        }




{% endhighlight %}



