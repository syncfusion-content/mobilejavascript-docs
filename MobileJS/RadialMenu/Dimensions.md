---
layout: post
title: Dimensions
description: dimensions
platform: Mobilejs
control: Radial Menu (Mobile)
documentation: ug
---

## Dimensions

You can customize Radial Menu width (radius) by using data-ej-radius attribute and its position by using data-ej-position attribute.

The Possible values for Position property are

* Leftcenter
* Lefttop
* Leftbottom
* Rightcenter   
* Righttop
* Rightbottom



{% highlight html %}

  <div id="radialmenu_sample" data-role="ejmradialmenu" data-ej-imageclass="imageclass" data-ej-radius="300" data-ej-position="rightcenter" data-ej-touchend="click">

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

Refer the following code examples for css class

{% highlight css %}

        .imageclass {

            background: url("http://js.syncfusion.com/UG/Mobile/Content/radial/radialSettings.png");

            background-position: center;

            background-repeat: no-repeat;

        }





{% endhighlight %}

Refer the following code examples for script section

{% highlight js %}



        function click(e) {

            $("#radialmenu_sample").ejmRadialMenu("menuHide");

        }





{% endhighlight %}



The following screenshot illustrates the output of the above code.

{ ![](Dimensions_images/Dimensions_img1.png) | markdownify }
{:.image }


