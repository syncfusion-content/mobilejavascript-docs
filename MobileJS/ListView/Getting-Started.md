---
layout: post
title: Getting-Started
description: Getting Started
platform: js
control: Control Name undefined
documentation: ug
---

# Getting Started

This section explains briefly on how to create a ListView control in your application.

## Create your first ListView in JavaScript

Essential JavaScript Mobile ListView widget builds an interactive listview interface. This control allows you to select an item from a list-like interface and provides the infrastructure to display a set of data items in different layouts or views. Lists display data, data navigation, result lists, and data entry.

The following steps help you to add a ListView control for a mobile application that views a list of items such as images, text and navigates to the child item when you click a list item.

## Create a Basic Mobile Layout

Essential JavaScript Mobile ListView widget is rendered, either by specifying static content on a list. The following steps help you create a basic ListView for your application.

1. Create an HTML file and add the following template to the HTML file.

{% highlight html %}

<html>
<head>
    <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />
    <title>ListView</title>
    <link href="http://cdn.syncfusion.com/{{ site.releaseversion }}/js/mobile/ej.mobile.all.min.css" rel="stylesheet" />
    <script src="http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js"></script>
    <script src="http://cdn.syncfusion.com/js/assets/external/jsrender.min.js"></script>
    <script src="http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js"></script>
    <script src="http://cdn.syncfusion.com/{{ site.releaseversion }}/js/mobile/ej.mobile.all.min.js"></script>
</head>
<body>
    <div>
        <!--- Add Header Element Here-->
        <!--Add Listview Element Here-->
    </div>
</body>
</html>



{% endhighlight %}