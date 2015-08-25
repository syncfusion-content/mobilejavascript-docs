---
layout: post
title: Android-Specific-Customization
description: android specific customization
platform: Mobilejs
control: SplitPane (Mobile)
documentation: ug
---

# Android Specific Customization

You can set the android specific properties to the control by using the following settings.



N> In iOS and windows, header control is used to set the title for both left pane and right panel. But in android, toolbar control is used as per the native user interface guideline.



## Customize Toolbar

The “data-ej-showtoolbar” attribute is used to show/hide the toolbar when the control is rendered in android mode. You can customize toolbar title by using this toolbarSettings property.

{% highlight html %}

<div id="splitpane" data-role="ejmsplitpane" data-ej-rendermode="android" data-ej-toolbarsettings-android-title="ToolbarHeader">

        <div data-ej-layout="pane">

            <!--Left pane content-->

            <div id="listview" data-role="ejmlistview" data-ej-touchend="loadContent" data-ej-showheader=false>

                <ul>

                    <li data-ej-text="Item1"></li>

                    <li data-ej-text="Item2"></li>

                    <li data-ej-text="Item3"></li>

                    <li data-ej-text="Item4"></li>

                    <li data-ej-text="Item5"></li>

                    <li data-ej-text="Item6"></li>              

               </ul>

            </div>

        </div>

    </div>



{% endhighlight %}



Refer to the script section and page content section to load the right pane content of appropriate page created. The following screenshot illustrates the output.

![](Android-Specific-Customization_images/Android-Specific-Customization_img2.png)



Likewise, you can customize all other properties of toolbar using this property. Refer to the complete UG of toolbar to know its properties.

