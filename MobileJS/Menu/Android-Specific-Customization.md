---
layout: post
title: Android-Specific-Customization
description: android specific customization
platform: Mobilejs
control: Menu (Mobile)
documentation: ug
---

## Android Specific Customization

Set the Android Specific properties to the control by accessing “Android” property.

### Type	

When you click a button or target element, the Menu appears in contextual or popup mode. The appearance of the Menu is defined by data-ej-type attribute. 

The possible values are, 

1. Contextual 
2. Popup
3. Optionmenu
4. Optionslist



{% highlight html %}

        <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="android" data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-rendermode="android" data-ej-android-type="contextual">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>



{% endhighlight %}

The following screenshot displays the Android-specific Type:

{{ '![Type-Android](Android-Specific-Customization_images/Android-Specific-Customization_img1.png)' | markdownify }}
{:.image }


