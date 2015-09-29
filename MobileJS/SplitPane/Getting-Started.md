---
layout: post
title: Getting Started | SplitPane | Mobilejs | Syncfusion
description: getting started
platform: Mobilejs
control: SplitPane (Mobile)
documentation: ug
---

# Getting Started

## Create your first SplitPane in JavaScript

This section enables you to create SplitPane using JavaScript in your mobile app.

The Essential JavaScript Mobile SplitPane divides up a region on the web page.  It can be configured to split up the horizontal view vertically. Right side panes can display the content from an external URL that is specific to the item selected in the left pane. In the following guidelines, you can learn about the features in mobile SplitPane widget by creating a Mail App.

![](Getting-Started_images/Getting-Started_img1.png)

## Create the required layout

The Essential JavaScript Mobile Splitpane widget is rendered based on the default values for all the properties. You can easily customize the Splitpane control by changing their properties according to your need. The following steps guide you to create a Mail App.

Create an HTML file and paste the following template to it for Mail App creation.

{% highlight html %}

<!DOCTYPE html>

<html>

	<head>

		<title>Splitpane</title>

		<link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

		<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"> </script>

	</head>

	<body>

		<div id="page" data-role="appview">

			<div id="content">

				<div>

					<!--Add Splitpane Element here-->

				</div>

			</div>

		</div>

	</body>

</html>

{% endhighlight %}

## Create the SplitPane control

To render the SplitPane control, you need to set data-role attribute to ejmsplitpane to a div element. 

Refer the following code example.

{% highlight html %}

<div id="splitview" data-role="ejmsplitpane" >                                            

    <div data-ej-layout="pane">

        <div>                  

				<!--Left pane content-->

        </div>

    </div>

	<div data-ej-layout="pane">

		<div>

			<!--Right pane content-->				

		</div>

	</div>

</div>

{% endhighlight %}

Run this code and you can see the following output.

![](Getting-Started_images/Getting-Started_img2.png)

## Add left Pane content

To set left pane header title “data-ej-leftheadersettings-title” attribute with the desired title, set it as Inbox. In android mode there is no header for splitpane. Instead, you have toolbar control. To set the toolbar title, add “data-ej-toolbarsettings-android-title” attribute with the desired title for android mode. Use ListView control with template support to display the left pane content (Inbox items).

Refer to the following code example.

{% highlight html %}

<div id="splitview" data-role="ejmsplitpane" data-ej-toolbarsettings-android-title="Messages" data-ej-leftheadersettings-title="Inbox">

	<div data-ej-layout="pane">

		<div>

			<div data-role="ejmlistview" id="templatelist" data-ej-allowscrolling="false" data-ej-datasource="window.dbitem"

				 data-ej-databinding="true" data-ej-showheader="false" data-ej-rendertemplate="true"

				 data-ej-persistselection="true" data-ej-selecteditemindex="0" data-ej-touchend="listItemSelect">

				<div class="cont-bg">

					<span class="templatetext">{{>Name}}</span> <span class="timestyle">{{>Time}}</span>

					<div class="aboutstyle">

						{{>About}}

					</div>

				</div>

			</div>

		</div>

	</div>

	<div data-ej-layout="pane">

		<div>

		</div>

	</div>

</div> 

{% endhighlight %}

{% highlight js %}

// data source for listbox with right pane’s url for each item

window.dbitem =

[{ "Name": "Skype", "Time": "3:06 am", "About": "Password changed successfully", "Url": "load1.html" },

	{ "Name": "Skype", "Time": "3:00 am", "About": "Your password has been changed", "Url": "load2.html" },

	{ "Name": "Skype", "Time": "Yesterday", "About": "Password token", "Url": "load3.html" },

	{ "Name": "Skype", "Time": "Monday", "About": "Hello from Skype", "Url": "load4.html" }];

{% endhighlight %}

Use the following styles to add ListView element.

{% highlight css %}

.cont-bg {
    padding: 6px 0px;
}

.templatetext {
    font-weight: bolder;
    font-size: 17px;
}

#templatelist .timestyle {
    float: right;
    font-size: 12px;
    position: relative;
    padding-right: 2px;
}

#templatelist .aboutstyle {
    font-size: 14px;
}

/* listbox active item color */

.e-m-ios7.e-m-tablet .e-m-state-active .e-m-list-div * {
    color: #FFFFFF;
}

#splitview.e-m-windows.e-m-dark .e-m-sp-left {
    background: black;
}

{% endhighlight %}

Run this code and you can see the following output.

![](Getting-Started_images/Getting-Started_img3.png)

## Add right Pane content

When you click the left pane list item, you can view the content that is specific to the selected item in right pane. Right side panes can display content from an external URL using the loadContent API. You need to pass external URL, right pane title and transition parameters as arguments for loadContent API. The left pane list item selection is handled by listItemSelect function.

Refer to the following code example.

{% highlight js %}


// data source for listbox with right pane’s url for each item

window.dbitem =

[{ "Name": "Skype", "Time": "3:06 am", "About": "Password changed successfully", "Url": "load1.html" },

	{ "Name": "Skype", "Time": "3:00 am", "About": "Your password has been changed", "Url": "load2.html" },

	{ "Name": "Skype", "Time": "Yesterday", "About": "Password token", "Url": "load3.html" },

	{ "Name": "Skype", "Time": "Monday", "About": "Hello from Skype", "Url": "load4.html" }];

// initial loading right pane content



$(document).ready(function () {

	// $("#splitview").data("ejmSplitPane").loadContent(toPage, options)

	var split = $("#splitview").data("ejmSplitPane");

	split.loadContent(dbitem[0].Url, {

		rightHeaderSettings:

		{ title: dbitem[0].About },

		toolbarSettings: { android: { title: dbitem[0].About } }, 

		transition: "none"

	});

});



// loading right pane content by clicking list item selected

function listItemSelect(args) {

	// $("#splitview").data("ejmSplitPane").loadContent(toPage, options)

	var split = $("#splitview").data("ejmSplitPane");

	split.loadContent(dbitem[args.index].Url, {

		rightHeaderSettings:

		{ title: dbitem[args.index].About }, 

		toolbarSettings: { android: { title: dbitem[args.index].About } }, 

		transition: "none"

	});

}

{% endhighlight %}

Create an HTML file with load1.html name and add the following code to the file.

{% highlight html %}

<h2>

    Hi John,</h2>

<br />

<h3>

    Password successfully changed</h3>

<br />

Your new Skype password has been set.

<br />

You can now access your Account, view your call history or change your account settings.

<br />

<br />

<h5>

    Talk soon,</h5>

The people at Skype

{% endhighlight %}

Create an HTML file with load2.html name and add the following code to the file.

{% highlight html %}

<h2>

    Hello John,</h2>

<br />

<h3>

    Your password has been changed</h3>

<br />

Your Skype password has been changed. If you did not change this yourself please

contact one of the administrators of the Skype Manager you belong to.

<br />

<br />

<h5>

    Talk soon,
	
</h5>

The people at Skype

{% endhighlight %}

Create an HTML file with load3.html name and add the following code to the file

{% highlight html %}

<h2>

    Hello John,

</h2>

<br />

<h3>

    Password token</h3>

<br />

Reset your password with this temporary code. Please note that this link is only

active for 6 hours after receipt. After the time limit expires, the code does not

work and you have to resubmit the password change request.<br />

<br />

If the link doesn't work, you can enter the code manually using this token: 45c5chg15ae33c438ch2cc7ehn004hg6

<br />

<br />

<h5>

    Talk soon,

</h5>

The people at Skype

{% endhighlight %}


Create an HTML file with load4.html name and add the following code to the file.

{% highlight html %}

 <h3>

    Hi John,
	
</h3>

<br />

<h2>

    Welcome to Skype</h2>

<br />

Congratulations on joining Skype! Now you can enjoy the magic of free face-to-face

calls, instant messaging, screen sharing and so much more - all with Skype.

<br />

<br />

<h5>

    Talk soon,

</h5>

The people at Skype

{% endhighlight %}

Run this code and you can see the following output.

![](Getting-Started_images/Getting-Started_img4.png)