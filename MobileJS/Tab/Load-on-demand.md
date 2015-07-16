---
layout: post
title: Load-on-demand
description: load on demand
platform: Mobilejs
control: Tab (Mobile)
documentation: ug
---

## Load on demand

In some applications, the content for the specific Tab item is loaded only when it is required. By specifying “data-ej-enableajax” attribute to true and specifying the external URL (via href property), you can load individual items on demand in the Tab. Default value is set to false.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="ios7">

    <ul>

        <li data-ej-href="mymusic.html" data-ej-text='My Music' data-ej-enableajax="true"  data-ej-ios7-imageclass="icn-Mymusic"></li>

        <li data-ej-href="favorites.html" data-ej-text='Favorites' data-ej-enableajax="true" data-ej-ios7-imageclass="icn-Favorites"></li> 

        <li data-ej-href="updates.html" data-ej-text='Updates' data-ej-enableajax="true" data-ej-ios7-imageclass="icn-Updates"></li>         

    </ul>

</div>



{% endhighlight %}



Create a HTML file with title mymusic.html and add the following code example to it.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

<title>Tab-Mymusic</title>

</head>

<body>

<div data-role="ejmlistview" data-ej-showheader="false" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

</body>

</html>



{% endhighlight %}



Create a HTML file with the title favorites.html and add the following code example to it.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

<title>Tab-Favorites</title>

</head>

<body>

<div data-role="ejmlistview" data-ej-showheader="false" id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

</body>

</html>



{% endhighlight %}



Create a HTML file with the title updates.html and add the following code example to it.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

<title>Tab-Updates</title>

</head>

<body>

<div data-role="ejmlistview" data-ej-showheader="false" id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>

</body>

</html>



{% endhighlight %}



