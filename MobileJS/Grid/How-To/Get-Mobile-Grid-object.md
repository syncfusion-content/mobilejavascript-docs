---
layout: post
title: How-To
description: how-to
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

# Get Mobile Grid object

After you initialize Mobile Grid, Grid object is stored in container element of Grid. To access Mobile Grid object refer to the following code example.

{% highlight js %}



var gridObject = $("#MobileGrid").ejmGrid("instance");



                [or]



var gridObject = $("#MobileGrid ").data("ejmGrid");



{% endhighlight %}



