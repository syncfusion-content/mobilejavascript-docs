---
layout: post
title: ejmRadialMenu | API Reference | Mobile JS | Syncfusion
description:  Methods, members, events available in ejmRadialMenu
platform: Mobilejs
control: ejmRadialMenu
documentation: API
keywords: ejmRadialMenu, API, Essential Studio JS RadialMenu (Mobile)
---

# ejmRadialMenu

Essential JavaScript Mobile Radial Menu control is a context that represent the menu items in a circular order with a center button element in it.

Custom Design for HTML RadialMenu control.

$(element).ejmRadialMenu()

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu();
        });
    </script>



{% endhighlight %}



N> Provide proper image path to get images in items of radial menu.

#### Requires

* module:jQuery

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch


## Members

### backImageClass `string`
{:#members:backImageClass} 

Renders the back button Image for Radial using class.

#### Default Value

* “e-m-backimage”

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-backimageclass="e-m-icon-backward">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>      <!-- nested items -->
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>      <!-- nested items -->
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ backImageClass: "e-m-icon-backward" }); 
        });
    </script>



{% endhighlight %}



### cssClass `string`
{:#members:cssClass} 

Sets the root class for RadialMenu theme. This cssClass API helps to use custom skinning option for RadialMenu control. By defining the root class using this API, we need to include this root class in CSS.

#### Default Value

* ””

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-cssclass="customclass">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <style>
        .customclass .e-m-radial {
            background-color: blue;
        }
    </style>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <style>
        .customclass .e-m-radial {
            background-color: blue;
        }
    </style>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ cssClass: "customclass" }); 
        });
    </script>



{% endhighlight %}



### enableAnimation `boolean`
{:#members:enableAnimation} 

To enable Animation for Radial Menu.

#### Default Value

* true

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-enableanimation="false">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ enableAnimation: "false" }); 
        });
    </script>



{% endhighlight %}



### imageClass `string`
{:#members:imageClass} 

Renders the image for Radial using Class.

#### Default Value

* “e-m-radialimage”

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-imageclass="e-m-icon-menu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ imageClass: "e-m-icon-menu" }); 
        });
    </script>



{% endhighlight %}



### items `objectarray`
{:#members:items} 

Renders the Radial menu using datasource which contains array of items.

#### Default Value

* []

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-items="[{ imagename: 'social.png', windows: { text: 'social' } }, { imagename: 'music.png' , windows: { text :'music' } }, { imagename: 'direction.png', windows: { text: 'direction' } }, { imagename: 'message.png', windows: { text: 'message' } }, { imagename: 'browser.png' , windows: { text :'browser' } }]">
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu"></div>
    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ items: [{ imagename: 'social.png', windows: { text: 'social' } }, { imagename: 'music.png', windows: { text: 'music' } }, { imagename: 'direction.png', windows: { text: 'direction' } }, { imagename: 'message.png', windows: { text: 'message' } }, { imagename: 'browser.png', windows: { text: 'browser' } }] });
        });
    </script> 



{% endhighlight %}



### position `enum`
{:#members:position} 

Changes the Position of the control. See [RadialMenuPosition](http://help.syncfusion.com/mobilejs/api/global#RadialMenuPosition)

#### Default Value

* “rightcenter”

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-position="leftcenter">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ position: "leftcenter" }); 
        });
    </script>



{% endhighlight %}



### radius `int`
{:#members:radius} 

Specifies the radius of the radialmenu control.

#### Default Value

* 150

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-radius="100">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ radius: 100 }); 
        });
    </script>



{% endhighlight %}



### renderMode `enum`
{:#members:renderMode} 

Changes the rendering mode. See [RenderMode](http://help.syncfusion.com/mobilejs/api/global#RenderMode)

#### Default Value

* “auto”

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-rendermode="android">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $(function () {
            $("#defaultradialmenu").ejmRadialMenu({ renderMode: "windows" }); 
        });
    </script>



{% endhighlight %}



## Methods


### disableItemByIndex()
{:#methods:disableItemByIndex} 

To disable an item of radialmenu by its index

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to disable the item in index 2 <button data-role="ejmbutton" data-ej-touchend="disableItem">Disable Item</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function disableItem() {
            $("#defaultradialmenu").ejmRadialMenu("disableItemByIndex", 2)
        }
    </script>



{% endhighlight %}



### disableItemsByIndices()
{:#methods:disableItemsByIndices} 

To disable a set of radialmenu items by array of indices

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to disable the items in indices 2, 3 <button data-role="ejmbutton" data-ej-touchend="disableItems">Disable Items</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function disableItems() {
            $("#defaultradialmenu").ejmRadialMenu("disableItemsByIndices", [2,3])
        }
    </script>



{% endhighlight %}



### enableItemByIndex()
{:#methods:enableItemByIndex} 

To enable a radialmenu item by its index

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to enable the item in index 2 <button data-role="ejmbutton" data-ej-touchend="enableItem">Enable Item</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-enabled="false" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function enableItem() {
            $("#defaultradialmenu").ejmRadialMenu("enableItemByIndex", 2)
        }
    </script>



{% endhighlight %}



### enableItemsByIndices()
{:#methods:enableItemsByIndices} 

To enable a set of radialmenu items by array of indices

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to enable the items in indices 2, 3 <button data-role="ejmbutton" data-ej-touchend="enableItems">Enable Items</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-enabled="false" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-enabled="false" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function enableItems() {
            $("#defaultradialmenu").ejmRadialMenu("enableItemsByIndices", [2,3])
        }
    </script>



{% endhighlight %}



### hide()

To hide the radialmenu with its target. You can’t access radialmenu after this method called.

Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <button data-role="ejmbutton" data-ej-touchend="hide">Hide Radial Menu</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function hide() {
            $("#defaultradialmenu").ejmRadialMenu("hide");
        }
    </script>


{% endhighlight %}



### hideBadge()
{:#methods:hideBadge} 

To hide the radialmenu item’s badge by its index

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to hide badge value of item in index 2 <button data-role="ejmbutton" data-ej-touchend="hideBadge">Hide Badge</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-badge-value="10" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-badge-value="33" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-badge-value="5" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function hideBadge() {
            $("#defaultradialmenu").ejmRadialMenu("hideBadge", 2)
        }
    </script>



{% endhighlight %}



### hideMenu()
{:#methods:hideMenu} 

To hide the radialmenu when the target clicked

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <button data-role="ejmbutton" data-ej-touchend="hideMenu">Hide Menu</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function hideMenu() {
            $("#defaultradialmenu").ejmRadialMenu("hideMenu");
        }
    </script>



{% endhighlight %}



### show()
{:#methods:show} 

To Show the radialmenu

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <button data-role="ejmbutton" data-ej-touchend="show">Show Radial Menu</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function show() {
            $("#defaultradialmenu").ejmRadialMenu("show");
        }
    </script>



{% endhighlight %}



### showBadge()
{:#methods:showBadge} 

To show the radialmenu item’s badge by its index

N> You can show only the already hidden badge by “hideBadge()” method.

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to hide badge value of item in index 2 <button data-role="ejmbutton" data-ej-touchend="hideBadge">Hide Badge</button><br />
        Click the button to show badge value of item in index 2 <button data-role="ejmbutton" data-ej-touchend="showBadge">Show Badge</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-badge-value="10" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-badge-value="33" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-badge-value="5" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function hideBadge() {
            $("#defaultradialmenu").ejmRadialMenu("hideBadge", 2)
        }

        function showBadge() {
            $("#defaultradialmenu").ejmRadialMenu("showBadge", 2)
        }
    </script>


{% endhighlight %}



### showMenu()
{:#methods:showMenu} 

To Show the radialmenu when the target clicked

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <button data-role="ejmbutton" data-ej-touchend="showMenu">Show Menu</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function showMenu() {
            $("#defaultradialmenu").ejmRadialMenu("showMenu");
        }
    </script>



{% endhighlight %}



### updateBadgeValue()
{:#methods:updateBadgeValue} 

To update badge the radialmenu item. Parameters must be passed are: 1. index of item, 2. new value

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        Click the button to update badge value to 55 of item in index 2 <button data-role="ejmbutton" data-ej-touchend="updateBadge">Update Badge</button>
    </div>
    <div id="defaultradialmenu" data-role="ejmradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-badge-value="10" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-badge-value="33" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-badge-value="5" data-ej-badge-enabled="true" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function updateBadge() {
            $("#defaultradialmenu").ejmRadialMenu("updateBadgeValue", 2, 55)
        }
    </script>



{% endhighlight %}


## Events

### close
{:#events:close} 

Event triggers while radial menu closing.

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument</td><td>
Object</td><td>
Event parameters from Radialmenu<table><br><tr><br><th><b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
if the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
Object</td><td>
returns the Radialmenu model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
currentObj</td><td>
object</td><td>
returns the instance of current control</td></tr>
</table>


</td></tr>
</table>
#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-close="close">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function close(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $("#defaultradialmenu").ejmRadialMenu({ close: "close" });

        function close(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



### open
{:#events:open} 

Event triggers while radial menu opening.

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument</td><td>
Object</td><td>
Event parameters from Radialmenu<table><br><tr><br><th><b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
if the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
Object</td><td>
returns the Radialmenu model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
currentObj</td><td>
object</td><td>
returns the instance of current control</td></tr>
</table>


</td></tr>
</table>
#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-open="open">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function open(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social"></li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $("#defaultradialmenu").ejmRadialMenu({ open: "open" });

        function open(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



### select
{:#events:select} 

[deprecated] Event triggers when we select an item.

N> Since this event deprecated, use [touch] event.

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument</td><td>
Object</td><td>
Event parameters from Radialmenu<table><br><tr><br><th><b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
if the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
Object</td><td>
returns the Radialmenu model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
childIndex</td><td>
number</td><td>
returns the index of selected child item</td></tr>
<tr>
<td>
index</td><td>
number</td><td>
returns the index of selected item</td></tr>
</table>


</td></tr>
</table>
#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-select="select">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function select(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $("#defaultradialmenu").ejmRadialMenu({ select: "select" });

        function select(args) {
            //handle the event
        }
    </script>




{% endhighlight %}



### touch
{:#events:touch} 

Event triggers when the touch happens.

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument</td><td>
Object</td><td>
Event parameters from Radialmenu<table><br><tr><br><th><b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
if the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
Object</td><td>
returns the Radialmenu model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
index </td><td>
number</td><td>
returns the index of selected item </td></tr>
<tr>
<td>
childIndex</td><td>
number</td><td>
returns the index of selected child item</td></tr>
</table>


</td></tr>
</table>


#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>

    <div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-touch="touch">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        function touch(args) {
            //handle the event
        }
    </script>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialmenu">
        <ul>
            <li data-ej-imagename="social.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="social">
                <ul>
                    <li data-ej-imagename="googleplus.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="googleplus" data-ej-flat-text="googleplus"></li>
                    <li data-ej-imagename="facebook.png" data-ej-imagepath="themes/sampleimages/radialmenu"
                        data-ej-windows-text="facebook" data-ej-flat-text="facebook"></li>
                </ul>
            </li>
            <li data-ej-imagename="music.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="music"></li>
            <li data-ej-imagename="direction.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="direction"></li>
            <li data-ej-imagename="message.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="message"></li>
            <li data-ej-imagename="browser.png" data-ej-imagepath="themes/sample/radialmenu"
                data-ej-windows-text="browser"></li>
        </ul>
    </div>

    <script>
        $("#defaultradialmenu").ejmRadialMenu({ touch: "touch" });

        function touch(args) {
            //handle the event
        }
    </script>



{% endhighlight %}





