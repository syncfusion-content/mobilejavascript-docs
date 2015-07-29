---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Button (Mobile)
documentation: ug
---

# Getting Started

From the following guidelines, you can create a Media Player App where you can learn the mobile button features.

The following screenshot illustrates the functionality of a Button control in Media Player.

![C:/Users/labuser/Documents/Documentation_Button/Screenshots/IMG_0534_iphone5s_spacegrey_portrait.png](Getting-Started_images/Getting-Started_img1.png)

## Create the necessary layout

Create an HTML file and paste the following template to it for Button creation.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

    <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

    <title>Button</title>

   <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)"rel="stylesheet" />

	<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>                

  	<script src="http:// cdn.syncfusion.com/js/assets/external/jsrender.min.js"></script>

	<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

</head>

<body>

    <div data-role="appview">

        <div id="header" data-role="ejmheader" data-ej-title="Audio Player" data-ej-position="normal">

        </div>

        <div id="content">

            <div align="center" class="center">

                <!--Mobile Button control  -->

            </div>

        </div>

        <div id="pagescroll" data-role="ejmscrollpanel" data-ej-target="content">

        </div>

    </div>

</body>

</html>

{% endhighlight %}



Add the following styles to add formatting to your page.

{% highlight css %}

       .center {

           padding: 20px;

           top: 20px;

           position: relative;

       }

       td {

           padding: 10px;

       }
	   
{% endhighlight %}

You can add Audio controls in your app by using html audio control. Add the following code example inside the Div element. 

{% highlight html %}

<!--Audio-->

<audio controls id="audio">

     <source src="audio/song.wav" type="audio/wav">

     <source src="audio/song.ogg" type="audio/ogg">

     <source src="audio/song.mp3" type="audio/mp3">

 </audio>

<br />

<br />

{% endhighlight %}

> Note: Make sure you have an audio file in specified location.

Run the above code example to render the following output.

![](Getting-Started_images/Getting-Started_img2.png)


## Create Button Widget

To render the Button control, set “data-role” attribute to “ejmbutton” to an “input” element.

In your Media player, add three buttons for “Play”, “Pause” and “Save” functions.

Add the following code example below the audio control.

{% highlight html %}

<table>

    <tr>

        <td>

            <input type="button" id="play" data-role="ejmbutton" />

        </td>

        <td>

            <input type="button" id="pause" data-role="ejmbutton" />



        </td>

         <td>

            <input type="button" id="save" data-role="ejmbutton" />

        </td>

    </tr>

</table>

{% endhighlight %}

Run the above code example to render the following output.

![C:/Users/labuser/Documents/Documentation_Button/Screenshots/IMG_0533_iphone5s_spacegrey_landscape.png](Getting-Started_images/Getting-Started_img3.png)

## Set text

Now, set text for all the buttons. You can achieve this by using “data-ej-text” attribute. 

{% highlight html %}

<!--Button-->

<table>

    <tr>

        <td>

            <input type="button" id="play" data-role="ejmbutton" data-ej-text="play" />

        </td>

        <td>

            <input type="button" id="pause" data-role="ejmbutton" data-ej-text="pause" />



        </td>

        <td>

            <input type="button" id="stop" data-role="ejmbutton" data-ej-text="save" />

        </td>

    </tr>

</table>

{% endhighlight %}

![C:/Users/labuser/Documents/Documentation_Button/Screenshots/IMG_0534_iphone5s_spacegrey_portrait.png](Getting-Started_images/Getting-Started_img4.png)

## Saving the Audio file

Simply, a Dialog control is added to alert you when the file is saved.

For this purpose, use Mobile dialog control that can be rendered with the code example provided as follows.

{% highlight html %}

<div id="alertdlg" data-role="ejmdialog" data-ej-title="Save" data-ej-mode="alert"

    data-ej-leftbuttoncaption="Ok" data-ej-enablemodal="true" data-ej-enableautoopen="false"

    data-ej-buttontap="alertClose">

    <div>

        Your Audio has been saved. 

    </div>

</div>

{% endhighlight %}

## Binding Events

You can bind Button controls touch events to the html audio control by using the events provided by Button Widget.

You can achieve this by using “data-ej-touchend” attribute.

{% highlight html %}

<!--Button-->

<table>

    <tr>

        <td>

            <input type="button" id="play" data-role="ejmbutton" data-ej-text="play" data-ej-touchend="play" />

        </td>

        <td>

            <input type="button" id="pause" data-role="ejmbutton" data-ej-text="pause" data-ej-touchend="pause" />



        </td>

        <td>

            <input type="button" id="stop" data-role="ejmbutton" data-ej-text="save" data-ej-touchend="save" />

        </td>

    </tr>

</table>



{% endhighlight %}



At this point, you have created all the elements required for a simple Mediaplayer.

Next, write a code for binding button events with Audio control.

You can achieve this by using the following Script.

Add the following Script to your code.

{% highlight js %}



    var v = document.getElementsByTagName("audio")[0];

    v.pause();



    function play() {

        v.play();

    }

    function pause() {

        v.pause();

    }

    function save() {

        App.activePage.find("#alertdlg").ejmDialog("open");

    }

    function alertClose(args) {

        App.activePage.find("#alertdlg").ejmDialog("close");

    }

{% endhighlight %}

Run the above code example to render the following output. 

![C:/Users/Dhinesh R/AppData/Roaming/Skype/My Skype Received Files/Screenshots/Screenshots/IMG_0535_iphone5s_spacegrey_portrait.png](Getting-Started_images/Getting-Started_img5.png)