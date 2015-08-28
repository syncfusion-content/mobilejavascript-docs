---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Radial Menu (Mobile)
documentation: ug
---

# Getting Started

This section explains briefly on how to create a Radial Menu control in your mobile application.

## Create your first Radial Menu control in JavaScript

This section explains briefly on how to create a Radial Menu control in your mobile application.

![](Getting-Started_images/Getting-Started_img1.png)


The following steps guide you to add a Radial Menu control for your mobile application.

## Create basic mobile layout

1. Create an HTML file and paste the following template for mobile layout.     

   ~~~ html
   <!doctype html>
   <html lang="en">
   <head>
   <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />
   <title>Radialmenu</title>
   <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css”](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css) rel="stylesheet" />
   <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>
   <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>
   <script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>
   <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>
   </head>
   <body>
   <div data-role="appview">
   <!--- Adds Header Element Here  --->
   <!--- Adds Page Content Here  --->
   <!--- Adds Radialmenu Element Here  --->
   </div>
   </body>
   </html>
   ~~~ 
   {:.prettyprint}



2. You can create header element with the following code.

   ~~~ html
   <!--- Adds Header Element Here  --->
   <div id="header" data-role="ejmheader" data-ej-title="RadialMenu">
   </div>          
   ~~~ 
   {:.prettyprint}


3. Create the page content as follows.

   ~~~ html
   <div style="padding: 66px 25px; text-align: justify">
   <p>Syncfusion is the enterprise technology partner of choice for Windows development, delivering a broad range of software frameworks and tools. Syncfusion has established itself as the trusted partner worldwide for use in mission-critical applications.
   </p>
   </div>
   ~~~
   {:.prettyprint}

## Add Radial Menu control

1. Create a div element and set its data-role attribute as ejmradialmenu as follows.

{% highlight html %}

<div id="defaultradialmenu" data-role="ejmradialmenu">

     <ul>

          <!--- Add Menu Items Here  --->

     </ul>

</div>  

{% endhighlight %}

You can specify the images for each menu using data-ej-imageurl attribute for the inner list elements as follows. 

{% highlight html %}

<div id="defaultradialmenu" data-role="ejmradialmenu">

  <ul>

      <li data-ej-windows-text="google" data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/google.png"></li>

      <li data-ej-windows-text="music” data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/music.png"></li>

      <li data-ej-windows-text="direction” data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/direction.png"></li>

      <li data-ej-windows-text="message” data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/message.png"></li>

      <li data-ej-windows-text="browser” data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/radial/browser.png"></li>

   </ul>      

</div>



{% endhighlight %}

Run the above code to render the following output. To know how to run the code, refer to this [section](http://docs.syncfusion.com/js).

![](Getting-Started_images/Getting-Started_img2.png)



