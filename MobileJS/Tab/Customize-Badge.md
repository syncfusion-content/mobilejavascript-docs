---
layout: post
title: Customize-Badge
description: customize badge
platform: Mobilejs
control: Tab (Mobile)
documentation: ug
---

# Customize Badge

To know the number of updates available in the specific Tab item before viewing it, it is notified through the Badge support. 

## Enabled

The “data-ej-enabled” attribute is used to enable or disable the badge in the Tab. Default value is set to false.

## Value

The “data-ej-value” attribute is used to set the badge value to a Tab item. Default value is set to 0. You can refer the following code example.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="ios7">

        <ul>

            <li data-ej-href="#mymusic" data-ej-text='My Music' data-ej-ios7-imageclass="icn-Mymusic"></li>

            <li data-ej-href="#favorites" data-ej-text='Favorites' data-ej-ios7-imageclass="icn-Favorites"></li>

            <li data-ej-href="#updates" data-ej-text='Updates' data-ej-ios7-imageclass="icn-Updates" data-ej-badge-enabled="true" data-ej-badge-value="2"></li>

        </ul>

    </div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the Customization of badge:

![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab4.png](Customize-Badge_images/Customize-Badge_img1.png)


## MaxValue

The “data-ej-maxvalue” attribute is used to set the maximum badge value to a Tab item. Default value is set to 100. 

{% highlight html %}



<div data-role="ejmtab" id="tab" data-ej-rendermode="ios7">

        <ul>

            <li data-ej-href="#mymusic" data-ej-text='My Music' data-ej-ios7-imageclass="icn-Mymusic"></li>

            <li data-ej-href="#favorites" data-ej-text='Favorites' data-ej-ios7-imageclass="icn-Favorites"></li>

            <li data-ej-href="#updates" data-ej-text='Updates' data-ej-ios7-imageclass="icn-Updates" data-ej-badge-enabled="true" data-ej-badge-value="3" data-ej-badge-maxvalue="2"></li>

        </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

     <li data-ej-text="1.2.2 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the maxValue

![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab3.png](Customize-Badge_images/Customize-Badge_img2.png)



