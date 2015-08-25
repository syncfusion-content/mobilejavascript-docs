---
layout: post
title: Text-Configuration
description: text configuration
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

# Text Configuration

The “data-ej-showtext” attribute is used to show or hide the Tile caption. The text property is used to set the caption of a Tile. The “data-ej-textalignment” attribute is used to align the Tile text based on the requirement. The possible position values for textAlignment are as follows.

1. normal
2. left
3. right
4. center

The “data-ej-textposition” attribute wraps the text inside or outside of a Tile. The possible position values of “data-ej-textposition” are inner and outer.

N> TextPosition support is given only to iOS7 and android mode. TextPosition is not supported in small Tiles.

{% highlight html %}

    <div style="margin-top:45px;">

        <div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

        <div id="tile" data-role="ejmtile" data-ej-showtext="true" data-ej-imageurl="weather.png" data-ej-imageposition="fill" data-ej-imagepath="../themes/sample/tileview" data-ej-textalignment="center" data-ej-ios7-textposition="outer" data-ej-text="Weather"> </div>

    </div>

{% endhighlight %}

The following screenshot illustrates the output of the above code.

![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/tiletextchanges.png](Text-Configuration_images/Text-Configuration_img1.png)