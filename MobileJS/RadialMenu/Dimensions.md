---
layout: post
title: dimensions
description: dimensions
platform: js
control: Control Name undefined
documentation: ug
---

## Dimensions

You can customize Radial Menu width (radius) by using data-ej-radius attribute and its position by using data-ej-position attribute.

The Possible values for Position property are

* leftcenter

* lefttop

* leftbottom

* rightcenter   

* righttop

* rightbottom



{% highlight html %}

  <div id="radialmenu_sample" data-role="ejmradialmenu" data-ej-imageclass="imageclass" data-ej-radius="100" data-ej-position="rightcenter">
        <ul>
            <li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/ios7/light/social.png">
            </li>
            <li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/ios7/light/music.png">
            </li>
            <li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/ios7/light/direction.png">
            </li>
            <li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/ios7/light/message.png">
            </li>
            <li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/ios7/light/browser.png">
            </li>

        </ul>
    </div>



{% endhighlight %}

Refer the below code snippets for css class

{% highlight css %}

        .imageclass {
            background: url("http://js.syncfusion.com/UG/Mobile/Content/radial/radialSettings.png");
            background-position: center;
            background-repeat: no-repeat;
        }



{% endhighlight %}



![](dimensions_images\dimensions_img1.png)

