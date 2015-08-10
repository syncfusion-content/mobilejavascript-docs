---
layout: post
title: Select-Item
description: select item
platform: Mobilejs
control: Rotator (Mobile)
documentation: ug
---

# Select Item

Rotator control takes a numeric value given in data-ej-currentitemindex attribute and displays the corresponding item that matches the given index. Refer to the following code example.

{% highlight html %}

    <div id="page" data-role="appview">

        <!-- header control -->

        <div data-role="ejmheader" id="header" data-ej-title="Rotator">

        </div>   

        <div id="rotatordefault" data-role="ejmrotator" data-ej- 

              targetid="rotatorcontentdefault" data-ej-currentitemindex=3>

        </div>

    </div>

    <div id="rotatorcontentdefault">

        <div>

            <div class="photo photo1">

            </div>

        </div>

        <div>

            <div class="photo photo2">

            </div>

        </div>

        <div>

            <div class="photo photo3">

            </div>

        </div>

        <div>

            <div class="photo photo4">

            </div>

        </div>

        <div>

            <div class="photo photo5">

            </div>

        </div>

    </div>





{% endhighlight %}


![](Select-Item_images/Select-Item_img1.png)



