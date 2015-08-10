---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Toolbar (Mobile)
documentation: ug
---

# Getting Started

## Create your first Rotator in JavaScript

The Essential JavaScript mobile toolbar provides a single interface to select a command from a collection of commands. It also provides template support. In this example, you can learn how to create a Mail App and through that you can learn the features of Mobile Toolbar Widget.

![1](Getting-Started_images/Getting-Started_img1.png)

## Create the necessary layout

The Essential JavaScript Mobile Toolbar Widget is created by using number of <ul> and <li>. Each <li> item performs individual actions. You can customize the Toolbar control by changing its properties according to your requirement. In this scenario, a _back_ toolbar item is used to navigate to previous page, _next_ toolbar item to show the next email in the inbox, _compose_ toolbar item to compose new mail, delete toolbar item to delete current mail, and close toolbar item to close the inbox app. The following steps guide you in creating a basic Toolbar for your application.

Create an HTML file and add the following template to the html file for Toolbar creation.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

    <title>Toolbar</title>

    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

    <style>

        #mailContent span {

            font-weight: bolder;

        }

    </style>

</head>

<body>

    <div id="page" data-role="appview">

        <div id="header" data-ej-title="Inbox" data-role="ejmheader" data-ej-position="normal"></div>

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

</body>

</html>

{% endhighlight %}

Execute this code to render the following output.

![2](Getting-Started_images/Getting-Started_img2.png)



## Create Toolbar Control

To render the Toolbar control, set data-role attribute to ejmtoolbar in a <div> element and include a list of Toolbar items to be added. There are 20 built-in icons for Toolbar items. This can be achieved by using the data-ej-iconname attribute.  

{% highlight html %}

 <!--Adding toolbar control-->

<div id="toolbar" data-role="ejmtoolbar" data-ej-position="normal"  data-ej-windows-position="fixed" data-ej-android-position="fixed" data-ej-android-title="Inbox">

<ul>

<li data-ej-iconname="back"></li>

<li data-ej-iconname="next"></li>

<li data-ej-iconname="compose"></li>

<li data-ej-iconname="delete"></li>

<li data-ej-iconname="close"></li>

</ul>

</div>

{% endhighlight %}

Use the following styles for content style.

{% highlight css %}

           .e-m-header.e-m-android {

               display: none;

           }

{% endhighlight %}

Run this code to render the following output.

![1](Getting-Started_images/Getting-Started_img3.png)


## Add functionalities for toolbar items 

You can provide functionalities for each Toolbar items and this can be achieved by adding data-ej-touchend attribute. When you click the Toolbar item, its corresponding touchend event triggers, and is handled using the performAction function as shown in the following code example. 

{% highlight html %}

<!--Adds toolbar control-->

<div id="toolbar" data-role="ejmtoolbar" data-ej-touchend="performAction" data-ej-position="normal" data-ej-android-position="fixed" data-ej-android-title="Inbox" data-ej-windows-position="fixed" >

<ul>

<li data-ej-iconname="back"></li>

<li data-ej-iconname="next"></li>

<li data-ej-iconname="compose"></li>

<li data-ej-iconname="delete"></li>

<li data-ej-iconname="close"></li>

</ul>

</div>

{% endhighlight %}



{% highlight js %}

$(document).ready(function (args) {

window.dialogObject = $("#alertdlg").data("ejmDialog"); //creates object for dialog

});

// toolbar touch end event

function performAction(args) {

var itemName = args.itemname;// to get the toolbar item name

$("#dialogContent").append(itemName + " toolbar item selected."); // appends the content to the dialog

window.dialogObject.open();//Shows dialog

}

//closes dialog

function alertClose(args) {

$("#dialogContent").empty(); //empties dialog content

window.dialogObject.close(); //closes dialog

}

{% endhighlight %}

Execute this code to render the following output. 

![3](Getting-Started_images/Getting-Started_img4.png)



