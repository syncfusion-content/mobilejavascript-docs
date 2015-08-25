---
layout: post
title: Animations
description: animations
platform: Mobilejs
control: Navigation Drawer (Mobile)
documentation: ug
---

# Animations

You can set the transition type of the Navigation Drawer by using data-ej-type attribute. The possible transition types are slide and overlay. 

Slide – Both navigation panel and content page slides towards left/right direction to view the navigation panel items.

Overlay – Only navigation panel slides over the content page to view the navigation panel items that is, part of the content page is hidden under navigation panel.

N> Transition slide type only working with position fixed.

Refer to the following code example.

{% highlight html %}

<div data-role="ejmnavigationdrawer" id="navpane" data-ej-type="slide" data-ej-enablelistview="true" data-ej-position="fixed"  data-ej-listviewsettings-touchend="navListClick">



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

        <div id="content" style="margin-top: 45px; margin-left: 20px;">

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

