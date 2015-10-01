---
layout: post
title: Customize Position | Navigation Drawer | Mobilejs | Syncfusion
description: customize position
platform: Mobilejs
control: Navigation Drawer (Mobile)
documentation: ug
---

# Customize Position

The data-ej-position attribute is used to specify the position whether it is fixed or relative to the container. When you specify its position as normal, it appends within the container otherwise it appends to the appview.

Refer to the following code examples.

{% highlight html %}

<div data-role="ejmnavigationdrawer" id="navpane"  data-ej-position="normal" data-ej-enablelistview="true" data-ej-listviewsettings-touchend="navListClick">

	<ul>

		<li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/drawer/home.png" data-ej-text="Home"

			id="navhome"></li>

		<li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/drawer/profile.png" data-ej-text="Profile"

			id="navprofile"></li>

		<li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/drawer/photo.png" data-ej-text="Photos"

			id="navphotos"></li>

		<li data-ej-imageurl="http://js.syncfusion.com/UG/Mobile/Content/drawer/locations.png" data-ej-text="Location"

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

Refer to the script section to update the page content while clicking the item in the drawer.