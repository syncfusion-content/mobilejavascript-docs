---
layout: post
title: Add-Group-Tiles
description: add group tiles
platform: Mobilejs
control: Tile (Mobile)
documentation: ug
---

## Add Group Tiles

You can use the following pre-defined classes to change a Tile as Grouped Tile. By using this, you can achieve the alignment of the Group Tiles automatically instead of writing your own css classes.

<table>
<tr>
<td>
Class Name</td><td>
Explanation</td></tr>
<tr>
<td>
group</td><td>
To group the column elements</td></tr>
<tr>
<td>
column</td><td>
To align the Tile in column manner</td></tr>
<tr>
<td>
small-col-2</td><td>
To align the small size Tiles in windows mode</td></tr>
</table>
Default usage:

{% highlight html %}



<div class="group">

    <div class="column">

           <!— Add tile control here -->

    </div>

</div>





{% endhighlight %}

To render the column grouped Tile, render the number of Tiles inside a div element with the class ‘column’. Then append that column group element to a div with the class ‘group’.                                                            

Refer to the following code example.

{% highlight html %}

<div class="defaultsample" style="margin-top: 45px;">

<div id="head" data-role="ejmheader" data-ej-title="Tileview"></div>

  <div class="group">

            <div class="column">

                <div id="tile1" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='setting.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Settings">

                </div>

                <div id="tile2" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='notes.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Notes">

                </div>

                <div id="tile3" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='clock.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Clock">

                </div>

                <div id="tile4" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='camera.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Camera">

                </div>

                <div id="tile5" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='messaging.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Messages">

                </div>

                <div id="tile6" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='contact.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Contacts">

                </div>

                <div id="tile7" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='map.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Map">

                </div>

                <div id="tile8" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='phone.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Phone">

                </div>

            </div>

            <div class="column">

                <div id="tile9" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='calendar.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Calendar">

                </div>

                <div id="tile10" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='calculator.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Calculator">

                </div>

                <div id="tile11" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='weather.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Weather">

                </div>

                <div id="tile12" data-role="ejmtile" data-ej-theme='dark' data-ej-imageurl='music.png'

                     data-ej-imagepath="../themes/sample/tileview" data-ej-text="Music">

                </div>

            </div>

        </div>

    </div>





{% endhighlight %}

Refer to the following code example for the CSS classes.

{% highlight css %}

        .e-m-ios7 .defaultsample {

            background: url("../themes/sample/tileview/ios7/bg.png") no-repeat scroll 0 0 / 100% 100% rgba(0, 0, 0, 0);

            height: 690px;

            width: 100%;

            position: absolute;

        }

        .e-m-ios7 .e-m-tile.e-m-tile-wrapper-small .e-m-tile-image {

            background-size: 60px 60px;

        }

        .e-m-ios7 .e-m-tile

        {

            margin-left:-3px;

        }

        .e-m-windows .group

        {

            padding:0 2%;

        }



{% endhighlight %}

Refer to the following code example for the script section.

{% highlight js %}

        if (ej.getRenderMode() == "windows")

            $($('.group').find('div[data-role="ejmtile"]')).attr({ 'data-ej-backgroundcolor': 'blue' });

        if (ej.getRenderMode() == "android")

            $($('.group').find('div[data-role="ejmtile"]')).attr({ 'data-ej-theme': 'light' });





{% endhighlight %}



The following screenshots illustrates the output of the above code.

{{ '![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/ios7changes.png](Add-Group-Tiles_images/Add-Group-Tiles_img1.png)' | markdownify }}
{:.image }


{{ '![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/androidchanges.png](Add-Group-Tiles_images/Add-Group-Tiles_img2.png)' | markdownify }}
{:.image }


{{ '![C:/Users/labuser/AppData/Roaming/Skype/My Skype Received Files/windowschange.png](Add-Group-Tiles_images/Add-Group-Tiles_img3.png)' | markdownify }}
{:.image }


To render small-col-2 Grouped Tile, render the number of Tiles inside a div element with the class ‘small-col-2’ and append that small-col-2 group element to a div with the class ‘column’. Now, append those column inside the main group div element. It is used for windows mode only.

Refer to the following code example.

{% highlight html %}

<div class="defaultsample" style="margin-top: 45px;">

<div id="head" data-role="ejmheader" data-ej-title="Tileview"></div> 

<div class="group">

                <div class="column">

                    <div id="tile1" data-role="ejmtile" data-ej-text= "People"data-ej-tilesize="medium" data-ej-imageposition="fill" data-ej-imageurl='setting.png' data-ej-imagepath="themes/sample/tileview" data-ej-backgroundcolor="green">

                    </div>

                    <div class="small-col-2">

                        <div id="tile2" data-role="ejmtile" data-ej-imageurl='notes.png' data-ej-imagepath="themes/sample/tileview" data-ej-text="Notes" data-ej-backgroundcolor="rgb(208, 75, 43)">

                        </div>

                        <div id="tile3" data-role="ejmtile" data-ej-imageurl='clock.png' data-ej-imagepath="themes/sample/tileview" data-ej-text="Clock" data-ej-backgroundcolor="rgb(215, 147, 23)">

                        </div>

                        <div id="tile4" data-role="ejmtile" data-ej-imageurl='camera.png' data-ej-imagepath="themes/sample/tileview" data-ej-text="Camera" data-ej-backgroundcolor="rgb(43, 128, 234)">

                        </div>

                        <div id="tile5" data-role="ejmtile" data-ej-imageurl='messaging.png' data-ej-imagepath="themes/sample/tileview" data-ej-text="Messages" data-ej-backgroundcolor="rgb(94, 58, 179)">

                        </div>

                    </div> 

                </div> 

            </div>

     </div>



{% endhighlight %}



The following screenshot illustrates the output of the above code.

{{ '![](Add-Group-Tiles_images/Add-Group-Tiles_img4.png)' | markdownify }}
{:.image }


