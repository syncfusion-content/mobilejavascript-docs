---
layout: post
title: Scrolling
description: scrolling
platform: Mobilejs
control: ListView (Mobile)
documentation: ug
---

## Scrolling

The data-ej-allowscrolling attribute defines whether to allow the scrolling behavior of the content when it exceeds the target elements’ height.

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-showheader="true" data-ej-headertitle="ListView" data-ej-allowscrolling="true">

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



> _Note:_ _Run this code example and you can see the following output. For more details, refer to the "Common Getting Started" section._

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_10.png](Scrolling_images/Scrolling_img1.png)' | markdownify }}
{:.image }


### EnableNativeScrolling

Even though there is inbuilt mobile JS scroll bar in the ListView, it is also possible to use the Native Scroll Bar based on the device it gets rendered. It is done by adding data-ej-enablenativescrolling attribute to the ListView element. 

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-allowscrolling="true" data-ej-enablenativescrolling="true">

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



### AdjustFixedPosition

data-ej-adjustfixedposition attribute is used to render fixed elements and ListView in the same page. When this attribute is set to true, it automatically calculates and places the ListView without overlaying any element.

The following code example demonstrates how it looks when this attribute is disabled. Default header in the ListView is disabled and a new header is created with Fixed Position. Since the header is fixed, you have to set the data-ej-adjustfixedposition attribute value to true to adjust its content dynamically.

{% highlight html %}



<div id="header" data-role="ejmheader" data-ej-title="ListView" data-ej-position="fixed"></div>

<div id="lb" data-role="ejmListView" data-ej-allowscrolling="true" data-ej-adjustfixedposition="true" data-ej-showheader="false">

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



The following screenshots display the Adjust Fixed Position:

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_15.png](Scrolling_images/Scrolling_img2.png)' | markdownify }}
{:.image }


_Note: You can see here that the first list item is hidden due to fixed header element._

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_16.png](Scrolling_images/Scrolling_img3.png)' | markdownify }}
{:.image }


### CheckDomChanges

data-ej-checkdomchanges attribute specifies the regular updates for scroll bar in the ListView when new item is dynamically added. When this attribute is enabled, scroll height in the ListView is also adjusted as per the number of items.

{% highlight html %}



<div id="lb" data-role="ejmListView" data-ej-allowscrolling="true" data-ej-checkdomchanges="true">

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



