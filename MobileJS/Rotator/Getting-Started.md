---
layout: post
title: Getting Started | Rotator | Mobilejs | Syncfusion
description: getting started
platform: Mobilejs
control: Rotator (Mobile)
documentation: ug
---

# Getting Started

In this section, you can learn how to create Rotator for your mobile app.

## Create your first Rotator in JavaScript

The Essential JavaScript Mobile Rotator widget is a container (that holds many items) with that you can navigate next and previous items through swipe gestures. Each item in rotator can hold any HTML content. In the following guideline, you can learn the features in mobile rotator widget by creating a Photo Gallery App.

![](Getting-Started_images/Getting-Started_img1.png)


## Create the required layout

Rotator control is rendered based on the default values for all the properties. You can easily customize Rotator control by changing its properties according to your application requirement. The following steps guide you in creating a Photo Gallery App using Rotator.

Create an HTML file and paste the following template to it for Photo Gallery App creation.

{% highlight html %}

<!DOCTYPE html>

<html>

	<head>

		<title>Rotator</title>

		<link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

	</head>

	<body>

		<div id="page" data-role="appview">

			<!-- header control -->

			<div data-role="ejmheader" id="header" data-ej-position="fixed" data-ej-title="Photo Gallery">

			</div>

			<div id="content">

				<div>

					<!--Add Rotator Element here-->

				</div>

			</div>

		</div>

	</body>

</html>

{% endhighlight %}

## Create the Rotator control

To render the Rotator control, set “data-role” attribute to “ejmrotator” to a div element. Also set “data-ej-targetid” attribute with the id of the target element that contains the HTML template for each item. Each first level child div element of the target element acts as an item of Rotator. 

{% highlight html %}

<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent">

</div>    

<div id="rotatorcontent">

	<div><!—  child 1 -->

		<div class="photo photo1">

		</div>

	</div><div><!—  child 2 -->

		<div class="photo photo2">

		</div>

	</div><div><!—  child 3 -->

		<div class="photo photo3">

		</div>

	</div><div><!—  child 4 -->

		<div class="photo photo4">

		</div>

	</div><div><!—  child 5 -->

		<div class="photo photo5">

		</div>

	</div>

</div>	

{% endhighlight %}

Use the following styles to style the Rotator items.

{% highlight css %}

.photo {

	background-position: center center;

	background-repeat: no-repeat;

	height: 100%;

	width: 100%;

	background-size:contain;

}

.photo1 {

	background-image: url(http://js.syncfusion.com/UG/Mobile/Content/rotator/tablet.jpg);

}

.photo2 {

	background-image: url(http://js.syncfusion.com/UG/Mobile/Content/rotator/rose.jpg);

}

.photo3 {

	background-image: url(http://js.syncfusion.com/UG/Mobile/Content/rotator/green.jpg);

}

.photo4 {

	background-image: url(http://js.syncfusion.com/UG/Mobile/Content/rotator/nature.jpg);

}

.photo5 {

	background-image: url(http://js.syncfusion.com/UG/Mobile/Content/rotator/snowfall.jpg);

}

#content{

   height:500px;

   width:300px;

   margin:auto;

}   

{% endhighlight %}

Run this code to render the following output. For more details, refer "Common Getting started” section.

![](Getting-Started_images/Getting-Started_img2.png)


## Hide the Pager

You can see in the above image, the pager is to indicate the item that is currently displayed. You don’t need to show the pager in our use case. To achieve this, make “data-ej-showpager” attribute value as false.


{% highlight html %}

<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-showpager="false">

</div>

{% endhighlight %}

Run this to render the following output. For more details, refer "Common Getting Started" section. 

![](Getting-Started_images/Getting-Started_img3.png)

By swiping left and right, you can view next images from the Photo Gallery.

![](Getting-Started_images/Getting-Started_img4.png)