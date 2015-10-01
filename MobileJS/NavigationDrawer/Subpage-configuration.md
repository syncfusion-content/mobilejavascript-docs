---
layout: post
title: Subpage configuration | Navigation Drawer | Mobilejs | Syncfusion
description: subpage configuration
platform: Mobilejs
control: Navigation Drawer (Mobile)
documentation: ug
---

# Subpage configuration

By default, Navigation Drawer appends to the Appview (Main page). When you set data-ej-considersubpage attribute as true, then the Navigation Drawer appends to its closest subpage. For example, consider that the Navigation Drawer is rendered as a right pane content of splitpane. While opening the application in tablet resolution, normally the Navigation Drawer appends to the appview that is, it appears over the left pane content. In order to make it append in the right pane subpage, you can set this data-ej-considersubpage attribute value as true.
Refer to the following code example.

{% highlight html %}

<div data-role="ejmnavigationdrawer" id="navpane" data-ej-enablelistview="true" data-ej-listviewsettings-touchend="navListClick" data-ej-considersubpage="true">

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