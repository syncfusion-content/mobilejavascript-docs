---
layout: post
title: Customize Scrollsettings | Navigation Drawer | Mobilejs | Syncfusion
description: customize scrollsettings 
platform: Mobilejs
control: Navigation Drawer (Mobile)
documentation: ug
---

# Customize Scrollsettings 

Built-in scrolling support is provided to enable scrolling, when the number of items in the navigation panel exceeds the device height. It can be enabled by setting data-ej-allowscrolling attribute as true. You can customize all the properties of scroll panel control to render in Navigation Drawer. For example by setting data-ej-showscrollbars attribute as false, you can hide the scrollbar in Navigation Drawer.

Refer to the following code example.

{% highlight html %}

<div data-role="ejmnavigationdrawer" id="navpane" data-ej-allowscrolling=true data-ej-enablelistview="true" data-ej-listviewsettings-touchend="navListClick" data-ej-scrollsettings-showscrollbars="false">

	<ul>

		<li data-ej-text="Home"

			id="navhome"></li>

		<li data-ej-text="Profile"

			id="navprofile"></li>

		<li data-ej-text="Photos"

			id="navphotos"></li>

		<li data-ej-text="Location"

			id="navlocation"></li>

	</ul>

</div>

<div id="head" data-role="ejmheader" data-ej-title="NavigationDrawer" data-ej-position="normal"></div>

        <div id="content" style="margin-top: 45px;">

            <div id="Home">

                The Home screen allows you to choose the specific content type displayed.

            </div>

            <div id="Profile" style="display: none">

                The Profile page content is displayed.

            </div>



            <div id="Photos" style="display: none">

                The Photos page content is displayed.

            </div>



            <div id="Location" style="display: none">

                The Location page content is displayed.

            </div>

        </div>

{% endhighlight %}

## Script Section

You can update the content and close the Navigation Drawer, once the item is selected from the list.

Refer to the following code example.

{% highlight javascript %}

    function navListClick(args) //To Handle the touch end event

    {

        $('#Home, #Profile, #Photos, #Location').hide(); 

        //Hiding all other contents

        $('#' + args.text).show(); 

        //Displaying the content based on the text of item selected

        $('#navpane').ejmNavigationDrawer('close');

    }

{% endhighlight %}