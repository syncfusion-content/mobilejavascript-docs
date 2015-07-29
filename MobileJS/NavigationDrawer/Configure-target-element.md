---
layout: post
title: Configure-target-element
description: configure target element
platform: Mobilejs
control: Navigation Drawer (Mobile)
documentation: ug
---

# Configure target element

The data-ej-targetid attribute is used to define the target Id for Navigation Drawer. The drawer opens while you click on the specified target element.

Refer to the following code example.

{% highlight html %}

  <div id="target" class="targeticon"></div>

    <div data-role="ejmnavigationdrawer" id="navpane" data-ej-targetid="target" data-ej-enablelistview="true" data-ej-listviewsettings-touchend="navListClick">



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

Add the following style

{% highlight css %}

.targeticon {

            background: url("http://js.syncfusion.com/UG/Mobile/Content/drawer/sprite.png") no-repeat scroll 0 -344px rgba(0, 0, 0, 0);

            height: 48px;

            left: 10px;

            position: absolute;

            top: 5px;

            width: 48px;

            z-index: 3;

        }

{% endhighlight %}



Refer to the script section to update the page content while clicking the item in the drawer.

![](Configure-target-element_images/Configure-target-element_img1.png)



You can display the drawer either by clicking on the target icon or else by swiping from left. Refer to the following screenshot.



![](Configure-target-element_images/Configure-target-element_img2.png)



