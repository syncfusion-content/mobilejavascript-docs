---
layout: post
title: Image-Configuration
description: image configuration
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

## Image Configuration

The “data-ej-imageposition” attribute is used to adjust the position of the Tile image. It accepts the following values.

1. center
2. top
3. bottom
4. right
5. left
6. topleft
7. bottomright
8. bottomleft 
9. fill

The “data-ej-backgroundcolor” attribute is used to set the background color of the Tile.

The “data-ej-imageurl” attribute is used to specify the file name for the background image of the Tile. The “data-ej-imagepath” attribute is used to define the root path that should contain the following folder structure to automatically render the background image based on the device/platform it gets rendered. All these three folder should contain the image files (with same name, but different images) that can be specified in the image url property.

* iOS7 - Folder name for ios7 specific images
* Android - Folder name for Android specific images
* Windows - Folder name for Windows specific images

_Note: Both data-ej-imagepath and data-ej-imageurl attribute can be set when you want to specify separate images for each render mode and so it is necessary to specify separate path for iOS, android and windows renderMode. When data-ej-imageurl attribute is alone used, you can provide common images for all render modes. So, you should provide the whole image path for this attribute._



{% highlight html %}

<div style="margin-top:45px;">

<div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

<div id="tile" data-role="ejmtile" data-ej-imageposition="fill" data-ej-text="Weather" data-ej-backgroundcolor="#ae12ae" data-ej-imageurl="Weather_1.png" data-ej-imagepath="../themes/sample/tileview"> </div></div>



{% endhighlight %}



The following screenshot displays the output of the above code.

{ ![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/imagepositionchange.png](Image-Configuration_images/Image-Configuration_img1.png) | markdownify }
{:.image }


Also you can give images for each Tile through CSS classes by using the “data-ej-imageclass” attribute. You can define your desired styles in the specified class.

Refer to the following code example.

{% highlight html %}

<div style="margin-top:45px;">

<div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

<div id="tile" data-role="ejmtile" data-ej-imageclass="picture" data-ej-text="people"> </div>

</div>



{% endhighlight %}



Refer to the following code example for CSS classes.

{% highlight css %}

        .picture {

            background-image: url("../themes/sample/tileview/windows/calculator.png");

            background-color: #ae12ae;

            background-size: 40px 40px;

        }



{% endhighlight %}



The following screenshot illustrates the output of the above code.

{ ![C:/Users/labuser/Desktop/ImagClass.png](Image-Configuration_images/Image-Configuration_img2.png) | markdownify }
{:.image }


