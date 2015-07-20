---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: Tab (Mobile)
documentation: ug
---

# Getting Started

The Essential JavaScript Mobile Tab provides a way to switch views within a web page. In the following section a Music App is created to explain the features of Mobile Tab widget. 



{{ '![F:/Trunk/work_area/WDT/gettingstartedformobile/JS/Ios_F1.png](Getting-Started_images/Getting-Started_img1.png)' | markdownify }}
{:.image }




The above screenshot illustrates a Mobile Tab in which you can switch through different views from a single webpage and also load tabs on-demand by specifing the URL.

## Create Tabs for Music App

The Essential JavaScript Mobile Tab widget can be rendered by specifying static content or by using on- demand contents by specifying the respective URL. In both the cases Tab control is rendered based on the default values of its properties. You can easily customize Tab control by changing their properties according to your requirement. In this Music App you require three tabs, one for displaying the available music, one for listing out the favorite tracks that you have marked and the other for displaying the updates on the music app. The following code example illustrates how to create a basic Tab for your application. 

Create an HTML file and paste the following template to the HTML file for creating Tab.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

<title>Tab</title>

<link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>                

  <script src="http:// cdn.syncfusion.com/js/assets/external/jsrender.min.js"></script>

<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>



</head>

<body>

    <div id="page" data-role="appview">

        <div id="header" data-role="ejmheader" data-ej-hideforunsupporteddevice="true" data-ej-position="normal">

        </div>

        <div id="content">

            <div>

               <!--Add Tab Elements here. --> 

            </div>

        </div> 

    </div>

</body>

</html>



{% endhighlight %}



Set a title for the header by setting the “data-ej-title” attributes as Music App.

{% highlight html %}



<div id="header" data-ej-title="Music App" data-role="ejmheader"></div>





{% endhighlight %}



To add the scroll panel to a particular content, set the “data-role” attribute to “ejmscrollpanel” and also the value of “data-ej-target” attribute should match with the id of the element to which the scroll panel is added. Add the following code example to the layout to set scroll panel for the content.

{% highlight html %}



<div data-role="ejmscrollpanel" data-ej-target="content"></div>





{% endhighlight %}



To render the Tab control, set the “data-role” attribute to “ejmtab” to a <div> element and include the list of tab items that is added. Add the “data-ej-text” attribute to set text for each item

{% highlight html %}



<!-- Tab control -->

<div data-role="ejmtab" id="tabdefault" data-ej-android-position="normal" data-ej-windows-position="normal">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music'></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites'></li>

    </ul>

</div>

<!-- Tab1 -->

<div data-role="ejmlistview" data-ej-enableheader="false" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab2 -->

<div data-role="ejmlistview" data-ej-enableheader="false" id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>







{% endhighlight %}



To add content for the Tab control, specify the “data-ej-href” to set the content that is loading on each tab and this attribute should match the “id” of the element in which you have specified the Tab content. In this application the Essential JS Mobile ListView control is used with ids “mymusic” and “favorites” that are specified in “data-ej-href” attribute to the respective items and you have a third tab that loads the content dynamically from a given URL. 

> _Note: The third tab is discussed later in the “loading on demand content section”._



{% highlight html %}

<!-- Tab control -->

<div data-role="ejmtab" id="tabdefault" data-ej-android-position="normal" data-ej-windows-position="normal">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music'></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites'></li>

    </ul>

</div>

<!-- Tab1 -->

<div data-role="ejmlistview" data-ej-showheader="false" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab2 -->

<div data-role="ejmlistview" data-ej-showheader="false" id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>





{% endhighlight %}

Run the code example to render the output as follows. 



{{ '![C:/Users/ApoorvahR/Desktop/2.png](Getting-Started_images/Getting-Started_img2.png)' | markdownify }}
{:.image }




The above screenshot illustrates the Mobile Tab widget created for the Music App. 

## Add Images to the Tabs

You have created the Tab that is required for your application. Now you can add images to your Tab. Add images to the Tab by specifying the image class for individual items in the Tab. 

Use the following code sample to add images to your Tab.

{% highlight html %}

 <div data-role="ejmtab" id="tabdefault" data-ej-android-position="normal" data-ej-windows-position="normal">

    <ul>

        <li data-ej-ios7-imageclass="icn-Mymusic" data-ej-href="#mymusic" data-ej-text='My Music'>

        </li>

        <li data-ej-ios7-imageclass="icn-Favorites" data-ej-href="#favorites" data-ej-text='Favorites'>

        </li>

    </ul>

</div>



{% endhighlight %}



To add the images use the following styles.

{% highlight css %}



.icn-Mymusic {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/mymusic.png') no-repeat center center;

}



.icn-Updates {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/updates.png') no-repeat center center;

}



.e-m-tabitem.e-m-state-default .icn-Mymusic {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/mymusic-default.png') no-repeat center center;

}



.e-m-tabitem.e-m-state-default .icn-Updates {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/updates-default.png') no-repeat center center;

}



.icn-Favorites {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/favorites.png') no-repeat center center;

}



.e-m-tabitem.e-m-state-default .icn-Favorites {

    background: url('http://js.syncfusion.com/UG/Mobile/Content/favorites-default.png') no-repeat center center;

}



.e-m-tab.e-m-ios7 .e-m-tab-image {

    width: 26px;

}



.e-m-tab-content .e-m-content {

    padding: 0px;

}



.e-m-lv .e-m-list .e-m-list-text, .e-m-windows.e-m-lv.e-m-mobile .e-m-list-text {

    left: 0px;

}



.e-m-lv.e-m-android .e-m-list .e-m-list-text {

    left: 20px;

}





{% endhighlight %}



Run the code to render the following output.

{{ '![C:/Users/ApoorvahR/Desktop/3.png](Getting-Started_images/Getting-Started_img3.png)' | markdownify }}
{:.image }


The above screenshot illustrates the Tab control rendered with the tab images.

## Add on Demand content for updates Tab

In some applications the content in Tab is loaded only when it is required, in this application the updates Tab are loaded only if you want to check for an update. For loading the content on-demand specify enableAjax property to true and specify the URL to load on demand for individual items in the tab.

Use the following code example to add the contents on-demand in the Tab.

{% highlight html %}

 <div data-role="ejmtab" id="tabdefault" data-ej-android-position="normal" data-ej-windows-position="normal">

    <ul>

        <li data-ej-ios7-imageclass="icn-Mymusic" data-ej-href="#mymusic" data-ej-text='My Music'>

        </li>

        <li data-ej-ios7-imageclass="icn-Favorites" data-ej-href="#favorites" data-ej-text='Favorites'>

        </li>

        <li data-ej-ios7-imageclass="icn-Updates" data-ej-href="updates.html" data-ej-enableajax="true" data-ej-text='Updates'>

        </li>

    </ul>

</div>





{% endhighlight %}



Create an HTML file with the title updates.html and add the following code sample to it.

{% highlight html %}

<div data-role="ejmlistview" data-ej-enableheader="false" id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}



Run the code example to render the following output. 


{{ '![C:/Users/ApoorvahR/Desktop/4.png](Getting-Started_images/Getting-Started_img4.png)' | markdownify }}
{:.image }


The above screenshot illustrates the Mobile Tab with the load on-demand property.

## Set Badge value for updates Tab 

In the real time Music App, the number of available updates is viewed before you decide to view the Tab. For this set the “data-ej-badge-enabled” to true and set the desired badge value in the “data-ej-badge-value” attribute. 

Use the following code example to initialize the badge values.

{% highlight html %}

<div data-role="ejmtab" id="tabdefault" data-ej-android-position="normal" data-ej-windows-position="normal">

    <ul>

        <li data-ej-ios7-imageclass="icn-Mymusic" data-ej-href="#mymusic" data-ej-text='My Music'>

        </li>

        <li data-ej-ios7-imageclass="icn-Favorites" data-ej-href="#favorites" data-ej-text='Favorites'>

        </li>

        <li data-ej-ios7-imageclass="icn-Updates" data-ej-badge-enabled="true" data-ej-badge-value="2"

            data-ej-href="updates.html" data-ej-enableajax="true" data-ej-text='Updates'>

        </li>

    </ul>

</div>





{% endhighlight %}



Run the above code example to render the following output. 



{{ '![C:/Users/ApoorvahR/Desktop/5.png](Getting-Started_images/Getting-Started_img5.png)' | markdownify }}
{:.image }


To dynamically update the badge value whenever a new update is added, use the following code example.

{% highlight js %}



   //Updates the _Badge value_

   $("#tabdefault").ejmTab("updateBadgeValue", 2, 10);





{% endhighlight %}



After running the above script an updated badge renders as shown in the following screenshot. 



{{ '![C:/Users/ApoorvahR/Desktop/6.png](Getting-Started_images/Getting-Started_img6.png)' | markdownify }}
{:.image }


