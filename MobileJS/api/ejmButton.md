---
layout: post
title: ejmButton | API Reference | Mobile JS | Syncfusion
description:  Methods, members, events available in ejmButton
platform: Mobilejs
control: ejmButton
documentation: API
keywords: ejmButton, API, Essential Studio JS Button (Mobile)
---

# ejmButton

Custom Design for Html Button control.

$(element).ejmButton();

#### Example

**Button:**

{% highlight html %}

// Create the button control in unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" />


{% endhighlight %}



{% highlight html %}

// Create the button control in obtrusive way.
 <input id="button" type="button" />

    <script>

        $("#button").ejmButton();
    </script>


{% endhighlight %}

**ActionLink:**



{% highlight html %}

// Create the actionlink control in unobtrusive way.
    <a id="button" data-role="ejmactionlink" ></a>


{% endhighlight %}



{% highlight html %}

// Create the actionlink control in obtrusive way.
 <a id="button"></a>

    <script>

        $("#button").ejmActionLink();
    </script>


{% endhighlight %}

#### Requires

* module:jQuery

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.touch

## Members

### color
{:#members:color} 

Section for color specific functionalities.

### color.border `string`
{:#members:colorborder} 

Specifies the color border to button outer border.

#### Default value

* “”

#### Example

{% highlight html %}

    //Set the color border property in Unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" data-ej-color-border="red" />


{% endhighlight %}



{% highlight html %}

//Set the color border property on initialization 

<input id="button" type="button" />
    <script>
        $("#button").ejmButton({ color: { border: "red" } })
    </script>


{% endhighlight %}

### color.fill `string`
{:#members:colorfill} 

Specifies the color fill to button background color.

#### Default value

* “”

#### Example

{% highlight html %}

    //Set the color fill property in Unobtrusive way
<input id="button" type="button" data-role="ejmbutton" data-ej-color-fill="red" />


{% endhighlight %}



{% highlight html %}

//Set the color fill property on initialization 
   <input id="button" type="button" />
    <script>
        $("#button").ejmButton({ color: { fill: "red" } })
    </script>


{% endhighlight %}

### color.text `string`
{:#members:colortext} 

Specifies the color text to button text

#### Default value

* “”

#### Example

{% highlight html %}

    //Set the color text property in Unobtrusive way
    <input id="button" type="button" data-role="ejmbutton" data-ej-color-text="red" />


{% endhighlight %}



{% highlight html %}

//Set the color text property on initialization
<input id="button" type="button" />

    <script>
        $("#button").ejmButton({ color: { text: "red" } })
    </script>


{% endhighlight %}

### contentType `enum`
{:#members:contentType} 

Specifies the contentType of the Button. See [ButtonContentType](http://help.syncfusion.com/mobilejs/api/global#ButtonContentType)

#### Default Value

* ej.mobile.Button.ContentType.Text



#### Example

{% highlight html %}


//Set the contentType property in unobtrusive way.
<button id="button1" type="button" data-role="ejmbutton" data-ej-contenttype="image" data-ej-imageclass="e-m-icon-settings"></button>



{% endhighlight %}



{% highlight html %}

    // Set the contentType on initialization.

<button id="button1" type="button"></button>

    <script>

        // Create Button
        $("#button1").ejmButton({ contentType: ej.mobile.Button.ContentType.Image, imageClass: "e-m-icon-settings" });

    </script>



{% endhighlight %}

### cssClass `string`
{:#members:cssClass} 

The root class for the Button widget to customize the existing theme

#### Default value

“”

#### Example

{% highlight html %}

//Set the cssClass property in Unobtrusive way.
    <style>
        .customize {
            width: 300px;
        }
    </style>
    <input id="button" type="button" data-role="ejmbutton" data-ej-cssclass="customize" />


{% endhighlight %}



{% highlight html %}

//Set the cssClass property on initialization 

    <style>
        .customize {
            width: 300px;
        }
    </style>
    <input id="button" type="button" />
    <script>
        $("#button").ejmButton({ cssClass: "customize" })
    </script>


{% endhighlight %}

### enabled `boolean`
{:#members:enabled} 

Specifies whether to enable or disable the control.

#### Default value

* true

#### Example

{% highlight html %}

    //Set the enabled property in Unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" data-ej-enabled="false" />


{% endhighlight %}





{% highlight html %}

   //Set the enabled property on initialization 

    <input id="button" type="button"/>
    <script>

        $("#button").ejmButton({ enabled: false })
    </script>


{% endhighlight %}

### enablePersistence `boolean`
{:#members:enablePersistence} 

Allows the current model values to be saved in local storage or browser cookies for state maintenance when it is set to true. While refreshing the page, it retains the model value from browser cookies or local storage.

N> [Local storage](http://www.w3schools.com/html/html5_webstorage.asp) is supported only in Html5 supported browsers. If the browsers don’t have support for local storage, browser cookies will be used to maintain the state.

#### Default value

* false



#### Example

{% highlight html %}

    //Set the enablePersistence property in Unobtrusive way.

    <input id="button" type="button" data-role="ejmbutton" data-ej-enablepersistence="true" />


{% endhighlight %}



{% highlight html %}

   //Set the enablePersistence property on initialization.

    <input type="button" id="button" />

    <script>

        $("#button").ejmButton({ enablePersistence: true });

    </script>


{% endhighlight %}

### enableRippleEffect `boolean`
{:#members:enableRippleEffect} 

Specifies whether to enable or disable ripple effect.

#### Default value

* false

#### Example

{% highlight html %}

   //Set the enableRippleEffect property on initialization 

<div style="width:auto;height:auto;position:absolute;">
        <input id="button" type="button" data-role="ejmbutton" data-ej-enablerippleeffect="true" />
    </div>


{% endhighlight %}





{% highlight html %}

//Set the enableRippleEffect property in Unobtrusive way.

    <div style="width:auto;height:auto;position:absolute;">
        <input id="button" type="button" />
    </div>
    <script>

        $("#button").ejmButton({ enableRippleEffect: true })
    </script>


{% endhighlight %}

### href `string`
{:#members:href} 

Specifies the href of action link button

N> This property is only applicable to ejmActionLink

#### Default value

* null

#### Example

{% highlight html %}


//Set the href property in Unobtrusive way.
    <a id="button" data-role="ejmactionlink" data-ej-text="MicroSoft" data-ej-href="https://www.microsoft.com"></a>



{% endhighlight %}



{% highlight html %}

  //Set the href property on initialization.
    <a id="button"></a>

    <script>
        $("#button").ejmActionlink({ href: "https://www.microsoft.com", text: "MicroSoft" })
    </script>


{% endhighlight %}

### imageClass `string`
{:#members:imageClass} 

Specifies the css class of image.

N> This property is only applicable when button control is render with HTML button tag.

#### Default value

* null

#### Example

{% highlight html %}

    //Set the imageClass property in Unobtrusive way.
    <button id="button" data-role="ejmbutton" data-ej-contenttype="image" data-ej-imageclass="e-m-icon-settings"></button>


{% endhighlight %}



{% highlight html %}

  //Set the imageClass property on initialization.

    <button id="button"></button>

    <script>
        $("#button").ejmButton({ contentType: ej.mobile.Button.ContentType.Image, imageClass: "e-m-icon-settings" })
    </script>


{% endhighlight %}

### imagePosition `enum`
{:#members:imagePosition} 

Specifies the position of image. See [ButtonImagePosition](http://help.syncfusion.com/mobilejs/api/global#ButtonImagePosition)


N> This property is only applicable when render the button control with HTML button tag and [contentType] property set as “both”

#### Default value

* ej.mobile.Button.ImagePosition.Left

#### Example

{% highlight html %}


//Set the imagePosition property in Unobtrusive way.

<style>
        .chat {
            background-image: url(chat.png);
        }
    </style>

    <button id="button" data-role="ejmbutton" data-ej-contenttype="both" data-ej-imageclass="chat" data-ej-imageposition="right"></button>


{% endhighlight %}



{% highlight html %}

  //Set the imagePosition property on initialization.
    <style>
        .chat {
            background-image: url(chat.png);
        }
    </style>

    <button id="button"></button>

    <script>
        $("#button").ejmButton({ contentType: ej.mobile.Button.ContentType.Both, imageClass: "chat",imagePosition:ej.mobile.Button.ImagePosition.Right })
    </script>


{% endhighlight %}

### locale `string`
{:#members:locale} 

Set the localization culture for button Widget.

#### Default value

* “en-US”

#### Example

{% highlight html %}

    //Set the locale property in Unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" data-ej-locale="en-US" />


{% endhighlight %}



{% highlight html %}

//Set the locale property on initialization 

    <input id="button" type="button" />
    <script>
        $("#button").ejmButton({ locale: "en-US" })
    </script>



{% endhighlight %}

### renderMode `enum`
{:#members:renderMode} 

Specifies the rendering mode of the control. See [RenderMode](http://help.syncfusion.com/mobilejs/api/global#RenderMode)

#### Default value

* auto

#### Example

{% highlight html %}

    //Set the renderMode property in Unobtrusive way.
    <input id="button" type="button" />
    <script>

        $("#button").ejmButton({ renderMode: "android" })
    </script>


{% endhighlight %}



{% highlight html %}

   //Set the renderMode property on initialization 

 <input id="button" type="button" data-role="ejmbutton" data-ej-rendermode="android" />


{% endhighlight %}

### showBorder `boolean`
{:#members:showBorder} 

Displays the Button with outer border.

#### Default value

* true

#### Example

{% highlight html %}

   //Set the showBorder property in Unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" data-ej-showborder="false" />


{% endhighlight %}



{% highlight html %}

  //Set the showBorder property on initialization
<input id="button" type="button" />

    <script>

        $("#button").ejmButton({ showBorder: false })
    </script>


{% endhighlight %}

### style `enum`
{:#members:style} 

Specifies the style of the control. See [ButtonStyle](http://help.syncfusion.com/mobilejs/api/global#ButtonStyle)


#### Default value

* normal

#### Example

{% highlight html %}

//Set the style property in Unobtrusive way.
    <input id="button" type="button" />
    <script>
        $("#button").ejmButton({ style: "large" })
    </script>


{% endhighlight %}



{% highlight html %}

//Set the style property on initialization
    <input id="button" type="button" data-role="ejmbutton" data-ej-style="large" />


{% endhighlight %}

### text `string`
{:#members:text} 

Specifies the text to button

#### Default value

* null

#### Example

{% highlight html %}


    //Set the text property in Unobtrusive way.
    <input id="button" type="button" data-role="ejmbutton" data-ej-text="Download"/>


{% endhighlight %}



{% highlight html %}

//Set the text property on initialization 

    <input id="button" type="button" />
    <script>

        $("#button").ejmButton({ text: "Download" })
    </script>


{% endhighlight %}

## Methods

### disable()
{:#methods:disable}

To disable the button.

#### Example

{% highlight html %}

<input id="button" type="button" data-role="ejmbutton" />

    <script>

        $(function () {

            var button = $("#button").data("ejmButton");

            button.disable(); // Disables the toggle button

        });

    </script>


{% endhighlight %}



{% highlight html %}

<input id="button" type="button" data-role="ejmbutton" />

    <script>

        $(function () {

            var button = $("#button").ejmButton("disable"); // Disabled the button

        });

    </script>


{% endhighlight %}



### enable()
{:#methods:enable}

To enable the button.

#### Example



{% highlight html %}

<input id="button" type="button" data-role="ejmbutton"  />

    <script>

        $(function () {

            var button = $("#button").data("ejmButton");

            button.enable(); // Enabled the button

        });

    </script>


{% endhighlight %}



{% highlight html %}

<input id="button" type="button" data-role="ejmbutton" />

    <script>

        $(function () {

            var button = $("#button").ejmButton("enable"); // Enabled the button

        });

    </script>


{% endhighlight %}

## Events

### touchEnd
{:#events:touchEnd}

Event triggers when touch end happens on the control.

<table>
<tr>
<td>
Name </td><td>
Type</td><td>
Description</td></tr>
<tr>
<td>
arguments</td><td>
object</td><td>
Event parameters from Button.<table><br><tr><br><td>Name</td><td>
Type</td><td>
Description</td></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
If the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
object</td><td>
Returns the button model. Returns the button model.</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
<br>Returns the name of the event.</td></tr>
<tr>
<td>
status</td><td>
boolean</td><td>
Returns the button state.</td></tr>
</table>


</td></tr>
</table>


#### Example

{% highlight html %}

//Bind the touchEnd event using Unobtrusive way.

    <input id="button" type="button" data-role="ejmbutton" data-ej-touchend="touchend" />

    <script>

        // touchEnd event for Button
        function touchend(args) {
            //handle the event
        }

    </script>


{% endhighlight %}



{% highlight html %}

<input id="button" type="button" />

    <script>

        // touchEnd event for button

        $("#button").ejmButton({

            touchEnd: function (args) {
                //handling the event
            }

        });

    </script>


{% endhighlight %}

### touchStart
{:#events:touchStart}

Event triggers when touch start happens on the control.

<table>
<tr>
<td>
Name </td><td>
Type</td><td>
Description</td></tr>
<tr>
<td>
arguments</td><td>
object</td><td>
Event parameters from Button.<table><br><tr><br><td>Name</td><td>
Type</td><td>
Description</td></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
If the event should be canceled; otherwise, false.</td></tr>
<tr>
<td>
model</td><td>
object</td><td>
Returns the button model. Returns the button model.</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
<br>Returns the name of the event.</td></tr>
<tr>
<td>
status</td><td>
boolean</td><td>
Returns the button state.</td></tr>
</table>


</td></tr>
</table>


#### Example

{% highlight html %}

//Bind the touchStart event using Unobtrusive way.

    <input id="button" type="button" data-role="ejmbutton" data-ej-touchstart="touchstart" />

    <script>

        // touchStart event for Button
        function touchstart(args) {
            //handle the event
        }

    </script>


{% endhighlight %}





{% highlight html %}

<input id="button" type="button" />

    <script>

        // touchEnd event for button

        $("#button").ejmButton({

            touchEnd: function (args) {
                //handling the event
            }

        });
    </script>


{% endhighlight %}