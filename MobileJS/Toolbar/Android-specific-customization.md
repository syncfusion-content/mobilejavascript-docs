---
layout: post
title: Android-specific-customization
description: android specific customization
platform: Mobilejs
control: Toolbar (Mobile)
documentation: ug
---

## Android specific customization

You can set the Android specific properties to the control by means of accessing Android property.

### Templating

You can customize the Toolbar left side content by using templating feature. This is achieved by setting data-ej-templateid attribute that specifies the id of the template element.

Refer to the following code example.

{% highlight html %}

    <div data-role="ejmtoolbar" id="toolbar_sample" data-ej-templateid="sample1" data-ej-rendermode="android">

        <ul>

            <li data-ej-iconname="add"></li>

            <li data-ej-iconname="cut"></li>

        </ul>

    </div>

    <span id="sample1">Hi, Welcome</span> 



{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_11.png](Android-specific-customization_images/Android-specific-customization_img1.png) | markdownify }
{:.image }




### EnableSplitView

The data-ej-enablesplitview attribute separates the title and the toolbar items that is displayed at the bottom of the page. You can change the title text by setting the desired title for data-ej-title attribute

Refer to the following code example.

{% highlight html %}

  <div id="toolbar_sample" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-enablesplitview=true>

            <ul>

                <li  data-ej-iconname="add" ></li>

                <li data-ej-iconname="cut" ></li>

                <li data-ej-iconname="copy" ></li>

                <li data-ej-iconname="save" ></li>

                <li data-ej-iconname="search" ></li>

            </ul>

    </div>





{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_12.png](Android-specific-customization_images/Android-specific-customization_img2.png) | markdownify }
{:.image }


### ShowBackNavigator

When you use Android type toolbar, it can be displayed with navigator icon that is used for navigating to the previous page. To enable this, you can use data-ej-showbacknavigator attrubute.

Refer to the following code example.

{% highlight html %}

<div data-role="ejmtoolbar" id="toolbar_sample" data-ej-rendermode="android"  data-ej-android-showbacknavigator="true" >

            <ul>

                <li  data-ej-iconname="add"></li>

                <li data-ej-iconname="cut"></li>

                <li data-ej-iconname="copy"></li>

                <li data-ej-iconname="save"></li>

                <li data-ej-iconname="search"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_13.png](Android-specific-customization_images/Android-specific-customization_img3.png) | markdownify }
{:.image }


### ShowEllipsis

When the number of items is more, the toolbar can’t display all the items. Since it doesn’t fit the device width. Therefore, the over flowed items can be displayed as a menu when you click the ellipsis present in the Toolbar. To display the ellipsis, enable the data-ej-showellipsis attribute. 

Refer to the following code example.

{% highlight html %}

<div data-role="ejmtoolbar" id="toolbar_sample" data-ej-rendermode="android"  data-ej-android-showellipsis=true >

            <ul>

                <li  data-ej-iconname="add"></li>

                <li data-ej-iconname="cut"></li>

                <li data-ej-iconname="copy"></li>

                <li data-ej-iconname="save"></li>

                <li data-ej-iconname="search"></li>

            </ul>

 </div>





{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_14.png](Android-specific-customization_images/Android-specific-customization_img4.png) | markdownify }
{:.image }




### ShowTitleIcon

The android Toolbar can be displayed with a logo or icon specific to the application. The data-ej-showtitleicon is used to display the title logo or icon when it is set to true. The data-ej-titleiconurl is used to provide the URL of the icon or logo that is displayed near the Toolbar title. 

Refer to the following code example.

{% highlight html %}

<div data-role="ejmtoolbar" id="toolbar_sample" data-ej-rendermode="android"  data-ej-android-titleiconurl="http://js.syncfusion.com/UG/Mobile/Content/updates.png" data-ej-android-showtitleicon=true >

            <ul>

                <li  data-ej-iconname="add"></li>

                <li data-ej-iconname="cut"></li>

                <li data-ej-iconname="copy"></li>

                <li data-ej-iconname="save"></li>

                <li data-ej-iconname="search"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot illustrates the output of the above code.

{ ![http://help.syncfusion.com/ug/js/ImagesExt/image124_15.png](Android-specific-customization_images/Android-specific-customization_img5.png) | markdownify }
{:.image }




