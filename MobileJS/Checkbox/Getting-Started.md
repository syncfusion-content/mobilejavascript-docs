---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Checkbox (Mobile)
documentation: ug
---

# Getting Started

From the following guidelines, you can select Multiple or Single Selection List by using Checkbox. The following screenshot demonstrates the functionality with Checkbox button action.

{{ '![C:/Users/apoorvah.ramanathan/Desktop/1.png](Getting-Started_images/Getting-Started_img1.png)' | markdownify }}
{:.image }


In the above screenshot, you can select multiple search engines as your favorites by using Checkbox, Tri-State Checkbox and perform the action to render the checked values when the button is clicked.

Create Checkbox 

Essential JavaScript Mobile Checkbox widget has built-in features like indeterminate selections. You can easily create the Checkbox widget by using a simple input Checkbox element as follows.

Create an HTML file and add the following template to the HTML file.

{% highlight html %}

<!DOCTYPE html>



<html>



<head>



    <title>Checkbox</title>



    <meta name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />



    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />



    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>



    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>



</head>



<body>



    <div id="header" data-ej-title="Search Engines" data-ej-position="normal" data-role="ejmheader"></div>



    <p id="label">Choose Your Favorite Search Engines</p>



    <!-- Add checkbox elements here -->



    <div class="btnsub">

        <button id="submit" data-role="ejmbutton">SUBMIT</button>

    </div>



</body>

</html>



{% endhighlight %}



To render the Checkbox control, you can set data-role attribute as “ejmcheckbox” for the specific input element as follows.



{% highlight html %}

    <table id="main">

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox1" data-ej-text="Google" data-ej-checked="true" />

            </td>

        </tr>

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox2" data-ej-text="Yahoo" data-ej-checked="true" />

            </td>

        <tr />

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox3" data-ej-text="Bing" />

            </td>

        <tr />

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox4" data-ej-text="Wikipedia" data-ej-checked="true" />

            </td>

        <tr />

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox5" data-ej-text="Amazon" />

            </td>

        <tr />

        <tr>

            <td>

                <input data-role="ejmcheckbox" type="checkbox" id="Checkbox6" data-ej-text="Twitter" />

            </td>

        <tr />

    </table>



{% endhighlight %}

 Add the following styles to show the Checkbox control in an order.

{% highlight css %}



        #main, .btnsub, #label  {

            padding: 20px;

        }



        #label  {

            font-weight: bold;

        }



        .btnsub  {

            text-align: center;

        }





{% endhighlight %}



Run this code example and you can see the following output.

{{ '![C:/Users/apoorvah.ramanathan/Desktop/1.png](Getting-Started_images/Getting-Started_img2.png)' | markdownify }}
{:.image }




