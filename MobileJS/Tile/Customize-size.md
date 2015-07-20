---
layout: post
title: Customize-size
description: customize size
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

## Customize size

You can customize the size of the Tile by using the “data-ej-tilesize” attribute. The following built-in Tile sizes are supported.

* medium
* small
* large
* wide

Default value: small

Refer to the following code example.

{% highlight html %}

<div style="margin-top:45px;">

<div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

<div id="tile" data-role="ejmtile" data-ej-imageurl="map.png" data-ej-imagepath="themes/sample/tileview" data-ej-text="map" data-ej-tilesize="medium" data-ej-imageposition = "fill" > 

</div>

</div>



{% endhighlight %}



The following screenshot illustrates the output of the above code.

{{ '![](Customize-size_images/Customize-size_img1.png)' | markdownify }}
{:.image }


