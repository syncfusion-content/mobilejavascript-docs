---
layout: post
title: IOS7-Specific-Customization
description: ios7 specific customization
platform: Mobilejs
control: Menu (Mobile)
documentation: ug
---

## IOS7 Specific Customization

You can set the iOS7 specific properties to the control by accessing iOS7 property.

### Cancel Button Customization	

#### Text And Color

The iOS7 Animate Type Menu comes with the Cancel Button at the bottom. The Cancel Button color can be customized by data-ej-ios7-cancelbuttoncolor attribute. The Cancel Button text is changed by using the data-ej-ios7-cancelbuttontext attribute. Set the desired text by using this attribute.

{% highlight html %}

        <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-rendermode="ios7" data-ej-ios7-cancelbuttoncolor="red" data-ej-ios7-cancelbuttontext="Cancel">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot displays the Button Customization:

{{ '![CancelButtonColor](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img1.png)' | markdownify }}
{:.image }


#### Hide Cancel Button	

You can hide or show the Cancel Button by setting false or true to the data-ej-showcancelbutton attribute.

{% highlight html %}

        <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7"

                data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-rendermode="ios7" data-ej-target="menuitem" data-ej-ios7-type="animate" data-ej-ios7-showcancelbutton="false">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot displays the Show Cancel Button:

{{ '![ShowCancelButton](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img2.png)' | markdownify }}
{:.image }


### Title	

When iOS7 Menu is used, it comes up with a Title on the top of the Menu container. You can hide or show the Title by setting false or true by using the data-ej-showtitle attribute. You can also change the Title text by setting the desired Title for data-ej-title attribute.

{% highlight html %}

        <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7"

                data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-rendermode="ios7" data-ej-target="menuitem" data-ej-ios7-type="animate" data-ej-ios7-showtitle="false">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>

        </div>



{% endhighlight %}

The following screenshot displays the Title.

{{ '![ShowTitle](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img3.png)' | markdownify }}
{:.image }


### Type		

When you click a button or a target element, the Menu is displayed. The appearance of the Menu is defined by the data-ej-type attribute. The possible values are,

1. Animate-This Menu is rendered in phone mode.
2. Normal-This Menu is rendered in tablet mode.
3. Auto-This mode automatically updates the MenuType based on the mode of iOS7 device whether it is phone or tablet mode.



{% highlight html %}

         <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7"

                data-ej-text="Menu" />

        </div>

        <div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-rendermode="ios7" data-ej-ios7-type="normal">

            <ul>

                <li data-ej-text="Get info"></li>

                <li data-ej-text="Show in folder"></li>

                <li data-ej-text="Delete"></li>

            </ul>

        </div>



{% endhighlight %}

 The following screenshot displays the Type:

{{ '![def](IOS7-Specific-Customization_images/IOS7-Specific-Customization_img4.png)' | markdownify }}
{:.image }


