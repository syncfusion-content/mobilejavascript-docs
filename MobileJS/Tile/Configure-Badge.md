---
layout: post
title: Configure-Badge
description: configure badge
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

## Configure Badge

The badge property handles badge specific functionalities like enable or disable the badge and setting badge value for the Tile. The “data-ej-badge-text” property is used to set the text instead of number for Tile badge. The “data-ej-badge-maxvalue” and “data-ej-badge-minvalue” attribute are used to set the maximum and minimum badge value to a Tile respectively. 

Refer to the following code example.

{% highlight html %}

    <div style="margin-top:45px;">

        <div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

        <div id="tile" data-role="ejmtile" data-ej-imageurl="messaging.png" data-ej-imageposition="fill" data-ej-imagepath="../themes/sample/tileview" data-ej-text="Messaging" data-ej-badge-enabled="true" data-ej-badge-minvalue="10" data-ej-badge-maxvalue="80" data-ej-badge-value="88"> </div>

    </div>



{% endhighlight %}

The following screenshot illustrates the output of the above code.

{{ '![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/badgechanges.png](Configure-Badge_images/Configure-Badge_img1.png)' | markdownify }}
{:.image }


