---
layout: post
title: ejmRadialSlider | API Reference | Mobile JS | Syncfusion
description:  Methods, members, events available in ejmRadialSlider
platform: Mobilejs
control: ejmRadialSlider
documentation: API
keywords: ejmRadialSlider, API, Essential Studio JS RadialSlider (Mobile)
---

# ejmRadialSlider

Essential JavaScript Mobile Radial Slider control provides support to select a value from a particular range of values aligned in circular diagrammatic manner. The Range Slider has a needle to select the value and it is fixed with a base circle.

Custom Design for HTML RadialSlider control.

$(element).ejmRadialSlider()

#### Example

{% highlight html %}

    &lt;!-- Unobtrusive way of rendering --&gt;

    &lt;div&gt;

        &lt;br /&gt;

        &lt;p&gt;

            Syncfusion is the enterprise technology partner of choice for Windows development

        &lt;/p&gt;

    &lt;/div&gt;

    &lt;div id="defaultradialslider" data-role="ejmradialslider"&gt;&lt;/div&gt;

{% endhighlight %}



{% highlight html %}

    &lt;!-- Obtrusive way of rendering --&gt;

    &lt;div&gt;

        &lt;br /&gt;

        &lt;p&gt;

            Syncfusion is the enterprise technology partner of choice for Windows development

        &lt;/p&gt;

    &lt;/div&gt;

    &lt;div id="defaultradialslider"&gt;&lt;/div&gt;



    &lt;script&gt;

        $("#defaultradialslider").ejmRadialSlider();

    &lt;/script&gt;

{% endhighlight %}



#### Requires

* module:jQuery

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch


## Members

### autoOpen `boolean`
{:#members:autoOpen} 

Specifies whether the radialslider control will be opened initially or not. 

N> If autoOpen property set as false, you need to handle radial slider open manually.

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
        <br />
        <p>
            Click the button to open radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialslideropen" data-ej-text="Open"></button>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-autoopen="false"></div>

    <script>
        function radialslideropen(args) {
            $("#defaultradialslider").ejmRadialSlider("show");
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
        <br />
        <p>
            Click the button to open radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialslideropen" data-ej-text="Open"></button>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ autoOpen: false });
        function radialslideropen(args) {
            $("#defaultradialslider").ejmRadialSlider("show");
        }
    </script>


{% endhighlight %}



### cssClass `string`
{:#members:cssClass} 

Sets the root class for RadialSlider theme. This cssClass API helps to use custom skinning option for RadialSlider control. By defining the root class using this API, we need to include this root class in CSS.

#### Default Value

* null

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-cssclass="customclass"></div>

    <style>
        .customclass .e-m-ticks-text {
            fill: red !important;
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
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ cssClass: "customclass" });
    </script>

    <style>
        .customclass .e-m-ticks-text {
            fill: red !important;
        }
    </style>



{% endhighlight %}



### enableAnimation `boolean`
{:#members:enableAnimation} 

To enable Animation for Radial Slider control.

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
        <br />
        <p>
            Click the button to open radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialslideropen" data-ej-text="Open"></button>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-autoopen="false" data-ej-enableanimation="false"></div>

    <script>
        function radialslideropen(args) {
            $("#defaultradialslider").ejmRadialSlider("show");
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
        <br />
        <p>
            Click the button to open radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialslideropen" data-ej-text="Open"></button>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ autoOpen: false, enableAnimation: false });
        function radialslideropen(args) {
            $("#defaultradialslider").ejmRadialSlider("show");
        }
    </script>



{% endhighlight %}



### enableRoundOff `boolean`
{:#members:enableRoundOff} 

Specifies the result value should be whole number or with decimals for the radialslider control.

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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-enableroundoff="false"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ enableRoundOff: false });
    </script>



{% endhighlight %}



### labelSpace `number`
{:#members:labelSpace} 

Specifies the space between stroke and values in radialslider control.

#### Default Value

* 30

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-labelspace="50"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ labelSpace: 50 });
    </script>



{% endhighlight %}


### position `enum`
{:#members:position} 

Changes the Position of the control. See [RadialSliderPosition](http://help.syncfusion.com/mobilejs/api/global#RadialSliderPosition)

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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-position="bottomleft"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ position: "bottomleft" });
    </script>



{% endhighlight %}



### radius `number`
{:#members:radius} 

Specifies the radius of the radialslider control.

#### Default Value

* 200

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-radius="150"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ radius: 150 });
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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-rendermode="android"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ renderMode: "windows" });
    </script>



{% endhighlight %}



### strokeWidth `number`
{:#members:strokeWidth} 

Specifies the radius of the radialslider control.

#### Default Value

* If windows or flat rendering mode, then the value is 12, otherwise 5

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider();
    </script>



{% endhighlight %}



### ticks `numberarray`
{:#members:ticks} 

Specifies the increment steps of radialslider control.

#### Default Value

* [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100]

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-ticks="[0, 25, 50, 75, 100]"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ ticks: [0, 25, 50, 75, 100] });
    </script>



{% endhighlight %}



### value `number`
{:#members:value} 

Specifies the value of the radialslider control need to be set initially.

#### Default Value

* 10

#### Example

{% highlight html %}


    <!-- Unobtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-value="0"></div>



{% endhighlight %}



{% highlight html %}


    <!-- Obtrusive way of rendering -->
    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
    </div>
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider();
    </script>



{% endhighlight %}



## Methods

### hide()
{:#methods:hide} 

To hide the radial slider. You can’t access radial slider after this method called.

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <p>
            Click the button to hide radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialsliderclose" data-ej-text="Hide"></button>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-autoopen="true"></div>

    <script>
        function radialsliderclose(args) {
            $("#defaultradialslider").ejmRadialSlider("hide");
        }
    </script>



{% endhighlight %}



### show()
{:#methods:show} 

To Show the radial slider

#### Example

{% highlight html %}


    <div>
        <br />
        <p>
            Syncfusion is the enterprise technology partner of choice for Windows development
        </p>
        <br />
        <p>
            Click the button to show radial slider
        </p>
        <button id="targetButton" data-role="ejmbutton" data-ej-touchend="radialslideropen" data-ej-text="Show"></button>
    </div>
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-autoopen="false"></div>

    <script>
        function radialslideropen(args) {
            $("#defaultradialslider").ejmRadialSlider("show");
        }
    </script>



{% endhighlight %}



## Events

### change
{:#events:change} 

Event triggers while a value changed to new value in radial slider.

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
Event parameters from Radialslider<table><br><tr><br><th><b>Name</b></th><th>
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
returns the Radialslider model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
oldValue</td><td>
number</td><td>
returns the previous value of radial slider</td></tr>
<tr>
<td>
value</td><td>
number</td><td>
returns the currently selected value</td></tr>
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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-change="change"></div>

    <script>
        function change(args) {
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
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ change: "change" });
        function change(args) {
            //handle the event
        }
    </script> 



{% endhighlight %}



### slide
{:#events:slide} 

Event triggers while user slide the radial menu to change the value.

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
Event parameters from Radial slider<table><br><tr><br><th><b>Name</b></th><th>
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
returns the Radial slider model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
selectedValue</td><td>
number</td><td>
returns the previous selected value of radial slider</td></tr>
<tr>
<td>
value</td><td>
number</td><td>
returns the current value where the cursor in.</td></tr>
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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-slide="slide"></div>

    <script>
        function slide(args) {
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
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ slide: "slide" });
        function slide(args) {
            //handle the event
        }
    </script> 



{% endhighlight %}



### start
{:#events:start} 

Event triggers while user start sliding to change new value in radial slider.

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
Event parameters from Radialslider<table><br><tr><br><th><b>Name</b></th><th>
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
returns the Radialslider model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
value</td><td>
number</td><td>
returns the currently value before slide</td></tr>
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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-start="start"></div>

    <script>
        function start(args) {
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
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ start: "start" });
        function start(args) {
            //handle the event
        }
    </script> 



{% endhighlight %}



### stop
{:#events:stop} 

Event triggers while user stopped sliding to change new value in radial slider.

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
Event parameters from Radialslider<table><br><tr><br><th><b>Name</b></th><th>
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
returns the Radialslider model</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
value</td><td>
number</td><td>
returns the currently selected value after slide stop</td></tr>
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
    <div id="defaultradialslider" data-role="ejmradialslider" data-ej-change="change"></div>

    <script>
        function change(args) {
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
    <div id="defaultradialslider"></div>

    <script>
        $("#defaultradialslider").ejmRadialSlider({ stop: "stop" });
        function stop(args) {
            //handle the event
        }
    </script> 



{% endhighlight %}




