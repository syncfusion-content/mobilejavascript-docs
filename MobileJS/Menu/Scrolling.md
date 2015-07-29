---
layout: post
title: Scrolling
description: scrolling 	
platform: Mobilejs
control: Menu (Mobile)
documentation: ug
---

# Scrolling 	

The data-ej-allowscrolling attribute defines whether to allow the scrolling behavior or not when the number of Menu items exceed the specified Menu height. To display the scrollbars when data-ej-allowscrolling is enabled, set the data-ej-showscrollbars attribute to true. You can customize the height and width of the Menu control by setting the desired value to data-ej-height and data-ej-width attributes respectively.

{% highlight html %}

        <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-allowscrolling="true" data-ej-height=200 data-ej-allowscrolling="true" data-ej-showscrollbars="true">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot displays Scrolling:

![ShowScrollBars](Scrolling_images/Scrolling_img1.png)



