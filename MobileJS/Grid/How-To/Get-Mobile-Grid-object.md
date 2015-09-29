---
layout: post
title: Get Mobile Grid object | Grid | Mobilejs | Syncfusion
description: get mobile grid object
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