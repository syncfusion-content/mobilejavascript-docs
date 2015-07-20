---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Toggle Button (Mobile)
documentation: ug
---

# Getting Started

Essential Toggle button is used in JS Mobile Widget functions, to switch On/Off functions such as Bluetooth, Airplane Mode, and WiFi. 


{{ '![C:/Users/durga/Pictures/image1.png](Getting-Started_images/Getting-Started_img1.png)' | markdownify }}
{:.image }


## Create the Layout

The following steps help you to add a Toggle button in the “Settings” menu of a mobile and use it to enable or disable a Wi-Fi connection.

Create an HTML file and add the following template to the HTML file. 

{% highlight html %}

 <!DOCTYPE html>

<html>

<head>

    <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

    <title>Toggle button</title>

    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>                

 <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

<scriptsrc="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.js)"></script>

    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

</head>

<body>

    <div data-role="appview">

        <!-- Header control -->

        <div id="header"  data-ej-title="Settings" data-ej-position="normal" 
             data-role="ejmheader"></div>

        <div id="content">

        <div>

        <div id="form" style="margin: 25px 30px;">

        <span>Wi-Fi </span>

        <!-- Add toggle button -->

        </div>

        <!-- Dialog control -->

        <div id="alertdlg" data-role="ejmdialog" data-ej-title="Dialog" `

        data-ej-leftbuttoncaption="OK" data-ej-buttontap="alertClose">

        <div id="dialogContent"></div>

        </div>

        </div>

        </div>

        <!-- Scroll panel control -->

        <div data-role="ejmscrollpanel" data-ej-target="content"></div>

    </div>

</body>

</html>



{% endhighlight %}

## Add Toggle Button

To add a Toggle button, set data-role attribute to ejmtogglebutton for a <div> element. Initially, Mobile Toggle button control is rendered with the default values of all properties and you can customize Mobile Toggle button control by changing its properties according to your requirement.  

Add the following code example to the <div> element.

{% highlight html %}

    <div id="toggle" data-role="ejmtogglebutton" data-ej-togglestate=”true” style="float:right;"></div>




{% endhighlight %}



Run the code and get the following output.



{{ '![C:/Users/durga/Pictures/image1.png](Getting-Started_images/Getting-Started_img2.png)' | markdownify }}
{:.image }


## Change Toggle button to render state

You can customize the initial Toggle button rendering state by data-ej-togglestate attribute that accepts a Boolean value as input. In this scenario, set the value to “False”.

Add the following code to the toggle <div>.



{% highlight html %}


<div id="toggle" data-role="ejmtogglebutton"  data-ej-togglestate=false  style="float:right;"></div>




{% endhighlight %}

Run this code to get the following output.



{{ '![C:/Users/durga/Pictures/image2.png](Getting-Started_images/Getting-Started_img3.png)' | markdownify }}
{:.image }


## Handle events

In this scenario, when the Toggle button state is changed, a Dialog appears saying “Wi-Fi state is enabled,” or, “disabled”. This is achieved by data-ej-change event. Whenever the Toggle button’s state is changed, the change event is raised. This event can be handled by appropriate functions.

Add the code example to the Toggle <div>.

{% highlight html %}


    <div id="toggle" data-role="ejmtogglebutton"  data-ej-togglestate=false data-ej-change="showDialog" style="float:right;"></div>




{% endhighlight %}

Add the following script code to the <body> tag to show the Dialog when you change the Toggle state.



{% highlight js %}



        $(function (args) {

            window.dialogObject = $("#alertdlg").data("ejmDialog"); //To create Dialog object

        });

        //Opens Dialog

        function showDialog(args) {

            (args.state) ? $("#dialogContent").html("Wifi is Enabled") : $("#dialogContent").html("Wifi is Disabled"); //Adds content to the Dialog 

            dialogObject.open(); //Open Dialog

        }

        //Closes Dialog

        function alertClose(args) {

            dialogObject.close(); //Closes Dialog

        }





{% endhighlight %}



Run this code to get the following output. 

{{ '![C:/Users/durga/Pictures/image3.png](Getting-Started_images/Getting-Started_img4.png)' | markdownify }}
{:.image }


{{ '![](Getting-Started_images/Getting-Started_img5.png)' | markdownify }}
{:.image }


