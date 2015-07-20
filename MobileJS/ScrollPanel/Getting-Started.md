---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Scroll Panel (Mobile)
documentation: ug
---

# Getting Started

In this section, you can learn how to create Scroll Panel for your mobile app.

Essential Scroll panel for mobile JavaScript is an interactive panel for scrolling. The Scroll panel control wraps its contents in a scrollable area as an object in a GUI with which continuous text, pictures can be scrolled and viewed even if it does not fit into the space of a mobile or computer display.


{{ '![](Getting-Started_images/Getting-Started_img1.png)' | markdownify }}
{:.image }


## Create the Scroll Panel

The following steps will guide you to add Scroll Panel for the required content area.

Create an HTML file and paste the following template to it.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

    <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

    <title>Scroll Panel</title>

    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

    <script type="text/javascript" src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

    <script type="text/javascript" src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

    <script type="text/javascript" src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

</head>

<body>

    <div data-role="appview">

        <div id="header" data-ej-title="Syncfusion" data-ej-position="normal"

            data-role="ejmheader">

        </div>

        <!-- Content that needs to be scrolled-->

        <div id="content" style="text-align: justify;">



            <div>

                <div id="image">

                </div>



                Founded by industry experts in 2001, Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform. With Syncfusion, developers can move beyond simply coding applications to delivering real business innovation—the elegant user interfaces, business intelligence dashboards, and sophisticated reporting that today's business users need, in the formats they demand. Our award-winning .NET components and controls are designed to meet your evolving development needs, whether you're working in Windows Forms, WPF, ASP.NET, ASP.NET MVC, or Silverlight. At Syncfusion, we uncompromisingly strive for excellence in order to offer the very best value to our customers—from small ISVs to Fortune 100 companies. Our most successful product is Essential Studio. For more details about Essential Studio please click the below.

            </div>

        </div>



        <!-- Add scroll panel here-->

    </div>

</body>

</html>





{% endhighlight %}



Add the following styles to display image and align the content.



{% highlight css %}

        #image

        {

            margin: auto;

            width: 150px;

            height: 150px;

            background: url(http://js.syncfusion.com/UG/Mobile/Content/syncfusion.png) center / 150px 150px;

        }

        #content

        {

            margin: 0 auto;

            font-size: 18px;

            text-indent: 2em;

            }





{% endhighlight %}



Run this code for the following output. For more details, refer to "Common Getting Started" section.



{{ '![](Getting-Started_images/Getting-Started_img2.png)' | markdownify }}
{:.image }


## Add Scroll Panel

To set Scroll Panel for a particular content, you need to specify the “data-role” attribute as “ejmScrollPanel” for a <div> element and set the “data-ej-target” attribute with value which should match the “id” (“content” here) of the target element for which you need to add the Scroll Panel.

{% highlight html %}



<div id="ScrollPanel" data-role="ejmScrollPanel" data-ej-target="content">
 </div>




{% endhighlight %}

Refer the following code snippets.

## Set Panel Height and Width	

The “data-ej-targetheight” and “data-ej-targetwidth” describes the height and width of target panel respectively. When height or width of the content exceeds the height or width of target panel, then the content can be scrolled. 

{% highlight html %}

  <div id="ScrollPanel" data-role="ejmScrollPanel" data-ej-target="content"  
   data-ej-targetwidth="300" data-ej-targetheight="400">
   /div>



{% endhighlight %}



Run the above code to render the following output. For more details, refer to "Common Getting Started" section.

{{ '![](Getting-Started_images/Getting-Started_img3.png)' | markdownify }}
{:.image }


By using above steps, you can create scrollable content in a page.

## Enable Horizontal and Vertical ScrollPanel

The target content can be scrolled vertically or horizontally or in both ways. The attribute “data-ej-enablevrscroll” enables vertical scrolling and the attribute “data-ej-enablehrscroll” enables horizontal scrolling.


{% highlight html %}


        <div id="ScrollPanel" data-role="ejmScrollPanel" data-ej-target="content"  
             data-ej-targetwidth="300" data-ej-targetheight="300" 
             data-ej-enablevrscroll="true" data-ej-enablehrscroll="true">
        </div>





{% endhighlight %}

From the above steps, you learnt how to make content scrollable by using EJ mobile Scroll Panel widget with use case sample. You can have more customization properties other than the one used here. To know more about the properties of mobile ScrollPanel widget please refer the complete documentation page for mobile ScrollPanel widget.

