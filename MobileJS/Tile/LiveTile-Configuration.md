---
layout: post
title: LiveTile-Configuration
description: livetile configuration
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

# LiveTile Configuration

Live Tiles are used to display the current or up to date information like scores, stocks, weather, etc. This functionality is supported only in windows rendermode. 

You can enable live Tile by using the “data-ej-livetile-enabled” attribute set to true that is the sub property of live Tile property. The “data-ej-livetile-type” attribute allows you to specify the type of animation while updating the information in the Tile. There are three types of Tile animation supported; flip, slide and carousel.

The “data-ej-livetile-imageurl” attribute sets background image for the Live Tile. This property accepts array values. So, you can specify the image url’s for all the Tiles that are used in the single Live Tile. 

You can specify the time interval for each Tile update/animation by using the “data-ej-livetile-updateinterval” attribute. The Time interval is given in milliseconds. The default value is 2000

Refer to the following code example.

{% highlight html %}

   <div style="margin-top:45px;">

        <div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

        <div id="tile" data-role="ejmtile" data-ej-imagepath="../themes/sample/tileview" data-ej-rendermode="windows" data-ej-livetile-updateinterval="2500" data-ej-livetile-type="slide" data-ej-livetile-enabled="true" data-ej-imageposition="fill" data-ej-livetile-imageurl=["photo1.png","photo2.png"]>

        </div>

    </div>
	
{% endhighlight %}

By using the “data-ej-livetile-imagetemplateid” attribute, you can specify the Live Tile images outside the Tile rendering. To achieve this, you can provide image content inside the element where the path is specified by using the templateid. You can update the imageTemplateId dynamically through the updateTemplateID public method.

{% highlight html %}

<div style="margin-top:45px;">

    <div id="tile" data-role="ejmtile" data-ej-rendermode="windows" data-ej-imageposition="fill" data-ej-livetile-imagetemplateid=["temp1","temp2"] data-ej-livetile-enabled="true">

    </div>

</div>

    <div id="temp1" style="background-image:

            url('../themes/sample/tileview/windows/calendar.png'); width: 100%; height: 100%;">

    </div>

    <div id="temp2" style="background-image:

            url('../themes/sample/tileview/windows/setting.png'); width: 100%; height: 100%;">

    </div>
	
{% endhighlight %}

You can specify the array of images for the Live Tile through CSS classes by using the “data-ej-livetile-imageclass” attribute and you can define the desired styles in the specified class.

{% highlight html %}

   <div style="margin-top:45px;">
   
       <div id="tile" data-role="ejmtile" data-ej-rendermode="windows" data-ej-imageposition="fill" data-ej-livetile-imageclass=["calendar","setting"] data-ej-livetile-enabled="true">

    </div>

</div>

{% endhighlight %}

Refer to the following code example for CSS class.

{% highlight css %}

        .calendar {

            background-image: url('../themes/sample/tileview/windows/calendar.png');

        }

        .setting {

            background-image: url('../themes/sample/tileview/windows/setting.png');

        }

{% endhighlight %}