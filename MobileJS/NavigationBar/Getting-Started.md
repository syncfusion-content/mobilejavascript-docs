---
layout: post
title: Getting Started | Toolbar | Mobilejs | Syncfusion
description: getting started
platform: Mobilejs
control: Toolbar, NavigationBar, Header, Footer (Mobile)
documentation: ug
---

# Getting Started

## Create your first Toolbar in JavaScript

The Essential JavaScript mobile Toolbar provides a single interface to select a command from a collection of commands. It also provides template support. In this example, you can learn how to create a Mail App and through that you can learn the features of Mobile Toolbar Widget.

The Toolbar can also be Mentioned as NavigationBar,Header and Footer.

![](Getting-Started_images/Getting-Started_img1.png)

## Create the necessary layout

The Essential JavaScript Mobile Toolbar Widget is created by using number of <ul> and <li>. Each <li> item performs individual actions. You can customize the Toolbar control by changing its properties according to your requirement. In this scenario, a _back_ toolbar item is used to navigate to previous page, _next_ toolbar item to show the next email in the inbox, _compose_ toolbar item to compose new mail, delete toolbar item to delete current mail, and close toolbar item to close the inbox app. The following steps guide you in creating a basic Toolbar for your application.

Create an HTML file and add the following template to the html file for Toolbar creation.

{% highlight html %}

<!DOCTYPE html>

<html>

	<head>

		<title>Toolbar</title>

		<link href="http://cdn.syncfusion.com/{{ site.releaseversion }}/js/mobile/ej.mobile.all.min.css" rel="stylesheet" />

		<script src="http://cdn.syncfusion.com/js/assets/external/jquery-3.0.0.min.js"></script>

		<script src="http://cdn.syncfusion.com/{{ site.releaseversion }}/js/mobile/ej.mobile.all.min.js"></script>

		<style>

			#mailContent span {

				font-weight: bolder;

			}

		</style>

	</head>

	<body>

		<div id="page" data-role="appview">

			<div id="header" data-ej-title="Inbox" data-role="ejmnavigationbar" data-ej-position="normal"></div>

			<!--Add Toolbar Elements here. -->

			<div id="content">

				<div>

					<!--Adding Inbox sample content-->

					<div id="mailContent" style="padding: 20px;">

						<span>From:</span> websupport@syncfusion.com<br />

						<span>To:</span>john@abc.com<br />

						<span>SUB:</span> Your Syncfusion Metro Studio Order 261234 submitted<br />

						<br />

						<p>

							Dear Customer,<br />

							Thank you for requesting a free license to use Syncfusion Metro Studio. The license provided is perpetual, subject to the terms of our license agreement.

						</p>

					</div>

					<!—Adding dialog control -->

					<div id="alertdlg" data-role="ejmdialog" data-ej-title="Dialog"

						data-ej-leftbuttoncaption="OK" data-ej-buttontap="alertClose">

						<div id="dialogContent">

						</div>

					</div>

				</div>

			</div>

			<div data-role="ejmscrollpanel" data-ej-target="content"></div>

		</div>

</html>

{% endhighlight %}

Execute this code to render the following output.

![](Getting-Started_images/Getting-Started_img1.png)



