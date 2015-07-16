---
layout: post
title: Android-specific-customization
description: android specific customization
platform: Mobilejs
control: Tab (Mobile)
documentation: ug
---

## Android specific customization

You can set the Android specific properties to the control by accessing the Android property.

### ShowImage

The “data-ej-android-showimage” attribute is used to enable or disable the image to your Tab. Default value is set to false.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="android" data-ej-android-showimage="true">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music' data-ej-android-imageclass="icn-Mymusic"></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites' data-ej-android-imageclass="icn-Favorites"></li> 

        <li data-ej-href="#updates" data-ej-text='Updates' data-ej-android-imageclass="icn-Updates"></li>         

    </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android" id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the Android showImage:

{ ![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab8.png](Android-specific-customization_images/Android-specific-customization_img1.png) | markdownify }
{:.image }


### ImageClass

The “data-ej-android-imageclass” attribute is used to add images to the Tab by specifying the imageClass for individual items in the Tab.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="android" data-ej-android-showimage="true">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music' data-ej-android-imageclass="icn-Mymusic"></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites' data-ej-android-imageclass="icn-Favorites"></li> 

        <li data-ej-href="#updates" data-ej-text='Updates' data-ej-android-imageclass="icn-Updates"></li>         

    </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the Android imageClass:

{ ![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab8.png](Android-specific-customization_images/Android-specific-customization_img2.png) | markdownify }
{:.image }


### Position

The “data-ej-android-position” attribute holds fixed and normal values. Normal position allows relative position of the element to the appview and fixed position allows fixed position of the element. Default position is set to fixed.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="android" data-ej-android-position="normal" data-ej-android-showimage="true">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music' data-ej-android-imageclass="icn-Mymusic"></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites' data-ej-android-imageclass="icn-Favorites"></li> 

        <li data-ej-href="#updates" data-ej-text='Updates' data-ej-android-imageclass="icn-Updates"></li>         

    </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="android"  id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the AndroidPosition:

{ ![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab8.png](Android-specific-customization_images/Android-specific-customization_img3.png) | markdownify }
{:.image }


