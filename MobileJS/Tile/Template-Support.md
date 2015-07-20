---
layout: post
title: Template-Support
description: template support
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

## Template Support

The “data-ej-imagetemplateid” and “data-ej-captiontemplateid” attributes are used to customize the image and caption/description of a Tile by providing the specific template id respectively. 

Refer to the following code example.

{% highlight html %}



    <div style="margin-top: 45px;">

        <div id="header" data-role="ejmheader" data-ej-title="Tile"></div>

        <div id="tile" data-role="ejmtile" data-ej-imagetemplateid="imageTemplate" data-ej-tilesize="wide" data-ej-captiontemplateid="captionTemplate"></div>

   <div id="imageTemplate">

      <div id="appimage">

        <div class="tileMargin">

          <span class="caption">Google Search</span><br />

          <span class="description">The world’s information</span><br />

          <span class="sub">Free</span>

        </div>

       </div>

    </div>

    <div id="captionTemplate" class="title">Windows Store</div>



    </div>





{% endhighlight %}



The following screenshot illustrates the output of the above code.

{{ '![](Template-Support_images/Template-Support_img1.png)' | markdownify }}
{:.image }


