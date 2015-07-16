---
layout: post
title: Configure-icons
description: configure icons
platform: Mobilejs
control: Toolbar (Mobile)
documentation: ug
---

## Configure icons

You can use different icons in your Toolbar and also you can customize these icons for each item by using the data-ej-iconname attribute.

The following built-in icons can be used in Toolbar.

* Add
* Back
* Bookmark
* Close
* Compose
* Copy
* Cut
* Delete
* Done
* Edit
* Mail
* Next
* Refresh
* Overflow
* Paste
* Reply
* Save
* Search
* Settings
* Share

Refer to the following code example.

{% highlight html %}

   <div data-role="ejmtoolbar" id="toolbar_sample">

            <ul>

                <li data-ej-iconname="add" li>

                <li data-ej-iconname="cut"></li>

                <li data-ej-iconname="copy"></li>

                <li data-ej-iconname="save"></li>

                <li data-ej-iconname="search"></li>

            </ul>

     </div>



{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_8.png](Configure-icons_images/Configure-icons_img1.png) | markdownify }
{:.image }


You can set the user defined icons using data-ej-iconurl attribute. This property overrides the data-ej-iconname attribute when both properties are set at a time. 

{% highlight html %}

<div data-role="ejmtoolbar" id="sample-toolbar" style="z-index: 100000;">

            <ul>

                <li data-ej-iconurl=" http://js.syncfusion.com/UG/Mobile/Content/toolbar/back.png"></li>

                <li data-ej-iconurl=" http://js.syncfusion.com/UG/Mobile/Content/toolbar/forward.png"></li>

                <li data-ej-iconurl=" http://js.syncfusion.com/UG/Mobile/Content/toolbar/plugin.png"></li>

                <li data-ej-iconurl=" http://js.syncfusion.com/UG/Mobile/Content/toolbar/edit.png"></li>

                <li data-ej-iconurl=" http://js.syncfusion.com/UG/Mobile/Content/toolbar/airoplane_mode.png"></li>

            </ul>

        </div>





{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_9.png](Configure-icons_images/Configure-icons_img2.png) | markdownify }
{:.image }


