---
layout: post
title: Getting Started | Textbox | Mobilejs | Syncfusion
description: getting started
platform: Mobilejs
control: Textbox (Mobile)
documentation: ug
---

# Getting Started

To create a textbox for the login page in the mobile application, follow the guidelines given. 

![](Getting-Started_images/Getting-Started_img1.png)

## Create the layout

Create a HTML file and add the following template to the HTML file.

{% highlight html %}

<!DOCTYPE html>

<html>

	<head>

		<meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

		<title>Textbox</title>

		<link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

	</head>

	<body>

		 <!--Header Control-->

		<div id="header" data-role="ejmheader" data-ej-title="Login" data-ej-position="normal"></div>

		<div class="sample" style="padding:10px">

			<div class="frame">

				<div class="control">

					<table class="editors">

						<tbody>

							<tr>

								<td>

									<label>

										Name

									</label>

								</td>

								<td>

									<!--Add Textbox control-->                                

								</td>

							</tr>

							<tr>

								<td>

									<label>

										Password

									</label>

								</td>

								<td>

									<!--Password Control-->

									<input id="password" data-role="ejmpassword" data-ej-watermarktext="Password" />

								</td>

							</tr>

						</tbody>

					</table>

					<center>

						<div class="button">

							<!--Button Control-->

							<input type="button" data-role="ejmbutton" data-ej-text="Login" />

						</div>

					</center>

				</div>

			</div>

		</div>

	</body>

</html>

{% endhighlight %}

## Add Textbox Control

To create the Textbox control add the following code.

{% highlight html %}

<input id="textbox_sample" data-role="ejmtextbox" data-ej-watermarktext="User Name" />

{% endhighlight %}

Run the code and get the following output.

![](Getting-Started_images/Getting-Started_img2.png)