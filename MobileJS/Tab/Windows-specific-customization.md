---
layout: post
title: Windows-specific-customization
description: windows specific customization
platform: Mobilejs
control: Tab (Mobile)
documentation: ug
---

## Windows specific customization

Set the Windows specific properties to the control by accessing this property.

### EnableCustomText

In the Windows phone, by default the Tab title's text is in the lower case irrespective of whatever case is used for the title. To disable this behavior, set the “data-ej-windows-enablecustomtext” attribute to true. Default value is set to false.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="windows" data-ej-windows-enablecustomtext="true">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music'></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites'></li> 

        <li data-ej-href="#updates" data-ej-text='Updates'></li>         

    </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows"  id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows"  id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows"  id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>

 </ul>

</div>



{% endhighlight %}

The following screenshot displays window specific customization: 

{ ![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab6.png](Windows-specific-customization_images/Windows-specific-customization_img1.png) | markdownify }
{:.image }


### Position

The “data-ej-windows-position” attribute holds fixed and normal values. Normal position allows relative position of the element to the appview and fixed position allows fixed position of the element. Default position is set to fixed.

{% highlight html %}

<div data-role="ejmtab" id="tab" data-ej-rendermode="windows" data-ej-windows-position="normal">

    <ul>

        <li data-ej-href="#mymusic" data-ej-text='My Music'></li>

        <li data-ej-href="#favorites" data-ej-text='Favorites'></li> 

        <li data-ej-href="#updates" data-ej-text='Updates'></li>         

    </ul>

</div>

<!-- Tab first item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows" id="mymusic">

    <ul>

        <li data-ej-text="Not Afraid"></li>

        <li data-ej-text="Get Lucky"></li>

        <li data-ej-text="Roar"></li>

        <li data-ej-text="Till I Collapse"></li>

    </ul>

</div>

<!-- Tab second item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows"  id="favorites">

    <ul>

        <li data-ej-text="Dark Horse"></li>

        <li data-ej-text="Roar"></li>

    </ul>

</div>

<!-- Tab third item -->

<div data-role="ejmlistview" data-ej-showheader="false" data-ej-rendermode="windows"  id="updates">

 <ul>

     <li data-ej-text="New songs available for download"></li>

     <li data-ej-text="1.2.1 update available"></li>     

 </ul>

</div>



{% endhighlight %}

The following screenshot displays the Window Specific Customization Position.

{ ![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/Tab/Tab Complete Doc/Screen shots/tab7.png](Windows-specific-customization_images/Windows-specific-customization_img2.png) | markdownify }
{:.image }


