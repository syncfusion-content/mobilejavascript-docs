---
layout: post
title: Dimensions
description: dimensions
platform: Mobilejs
control: ListView (Mobile)
documentation: ug
---

# Dimensions

To customize the ListView dimensions, data-ej-width and data-ej-height properties are used.

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-allowscrolling="true" data-ej-height="300">

<ul>

<li data-ej-text="Artwork"></li>

<li data-ej-text="Abstract"></li>

<li data-ej-text="2 Acrylic Mediums"></li>

<li data-ej-text="Creative Acrylic"></li>

<li data-ej-text="Modern Painting"></li>

<li data-ej-text="Canvas Art"></li>

<li data-ej-text="Black white"></li>

<li data-ej-text="Children"></li>

<li data-ej-text="Preschool Crafts"></li>

<li data-ej-text="School-age Crafts"></li>

</ul>

</div>



{% endhighlight %}



The following screenshot displays the Dimensions:

![Height z](Dimensions_images/Dimensions_img1.png)


## AutoAdjustScrollHeight

The data-ej-autoadjustscrollheight is a Boolean attribute that lets you adjust the scrolling content height automatically in case you have “ejm” elements with fixed position in your application. Default value is set to true.

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-allowScrolling="true" data-ej-autoadjustscrollheight="true" >

<ul>

<li data-ej-text="Artwork"></li>

<li data-ej-text="Abstract"></li>

<li data-ej-text="2 Acrylic Mediums"></li>

<li data-ej-text="Creative Acrylic"></li>

<li data-ej-text="Modern Painting"></li>

<li data-ej-text="Canvas Art"></li>

<li data-ej-text="Black white"></li>

<li data-ej-text="Children"></li>

<li data-ej-text="Preschool Crafts"></li>

<li data-ej-text="School-age Crafts"></li>

</ul>

</div>



{% endhighlight %}



## AutoAdjustHeight	

When the data-ej-autoadjustheight attribute is set to true, it sets the Height of the list element automatically based on the window height. Default value is set to false.

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-autoadjustheight="true">

<ul>

<li data-ej-text="Artwork"></li>

<li data-ej-text="Abstract"></li>

<li data-ej-text="2 Acrylic Mediums"></li>

<li data-ej-text="Creative Acrylic"></li>

<li data-ej-text="Modern Painting"></li>

<li data-ej-text="Canvas Art"></li>

<li data-ej-text="Black white"></li>

<li data-ej-text="Children"></li>

<li data-ej-text="Preschool Crafts"></li>

<li data-ej-text="School-age Crafts"></li>

</ul>

</div>



{% endhighlight %}



