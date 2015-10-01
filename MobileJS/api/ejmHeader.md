---
layout: post
title: ejmHeader | API Reference | Mobile JS | Syncfusion
description: 
documentation: API
platform: Mobilejs
keywords: ejmHeader, API, Essential Studio JS Autocomplete (Mobile)
---

# ejmHeader

Custom Design for Html Header control.

$(element).ejmHeader<span class="signature">()</span>


#### Example

{% highlight html %} 
<div id="header" ></div>
<script> 
// Create header  
$("#header").ejmHeader(); 
</script>{% endhighlight %}


{% highlight html %} 
<div id="header" data-role="ejmheader" ></div>
{% endhighlight %}

#### Requires

* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

* module:ej.mobile.button

## Members

### android
{:#members:android}

Section for android rendermode specific functionalities.

### android.backButtonImageClass`string`
{:#members:android-backbuttonimageclass}

Specifies the class name in which URL for the back button image will be set.


#### Default Value



* null



#### Example

{% highlight html %} 
// Set the android mode backButtonImageClass property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-backbuttonimageclass="backimagecssclass" ></div>
 {% endhighlight %}

### android.leftButtonStyle`enum`
{:#members:android-leftbuttonstyle}

Specifies the style for the left button i.e. back button or normal button button. See AndroidHeaderLeftButtonStyle

#### Default Value

* ej.mobile.Button.Android.Style.Back

#### Example


{% highlight html %} 
//Set the android leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-leftbuttonstyle="back" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set android leftButtonStyle on initialization. 
//To set android leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"android":{"leftButtonStyle": "back"}})
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the android leftButtonStyle, after initialization:
// Get the android leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "android.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "android.leftButtonStyle","normal"); {% endhighlight %}

### android.rightButtonStyle`enum`
{:#members:android-rightbuttonstyle}

Specifies the style for the right button i.e. back button or normal button. See AndroidHeaderRightButtonStyle

#### Default Value

* ej.mobile.Button.Android.Style.Back

#### Example


{% highlight html %} 
//Set the android rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showrightbutton="true" data-ej-android-rightbuttonstyle="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set android rightButtonStyle on initialization. 
//To set android rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"android":{"rightButtonStyle": "normal"}})
}); 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the android rightButtonStyle, after initialization:
// Get the android rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "android.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "android.rightButtonStyle","normal"); {% endhighlight %}

### android.showLeftButton`boolean`
{:#members:android-showleftbutton}

Specifies whether to show the android left button or not.

#### Default Value

* false

#### Example


{% highlight html %} 
//Set the android showLeftButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-android-showleftbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set android showLeftButton on initialization. 
//To set android showLeftButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({"android":{ "showLeftButton": true }});  
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "android.showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "android.showLeftButton", true);                      {% endhighlight %}




### android.showRightButton`boolean`
{:#members:android-showrightbutton}

Specifies whether to show the android right button or not.


#### Default Value

* false

#### Example


{% highlight html %} 
//Set the android showRightButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-android-showrightbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set android showRightButton on initialization. 
//To set android showRightButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({"android":{ "showRightButton": true }});         
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "android.showRightButton");                  
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "android.showRightButton", true);                     {% endhighlight %}


### cssClass`string`
{:#members:cssclass}

Sets the root class for Header theme. This cssClass API helps to use custom skinning option for Header control. By defining the root class using this API, we need to include this root class in CSS.

#### Default Value

* ""

#### Example


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-cssclass="customclass" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set cssClass on initialization. 
//To set cssClass API value 
$("#header").ejmHeader({ cssClass:"customclass" });     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the header cssClass, after initialization:
// Get the cssClass API value.          
 $("#header").ejmHeader ("option", "cssClass");                 
// Set the cssClass API
$("#header").ejmHeader ("option", "cssClass", "customclass");            {% endhighlight %}


### enablePersistence`boolean`
{:#members:enablepersistence}

Current model value to browser cookies for state maintenance. While refreshing the page, the model value applied from browser cookies retains.

#### Default Value

* false

#### Example


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-enablepersistence=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set enablePersistence on initialization. 
//To set enablePersistence API value 
$("#header").ejmHeader({ enablePersistence:true });     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the header enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#header").ejmHeader ("option", "enablePersistence");                        
// Set the enablePersistence API
$("#header").ejmHeader ("option", "enablePersistence", false);            {% endhighlight %}

### flat
{:#members:flat}


Section for flat rendermode specific functionalities.

### flat.leftButtonStyle`enum`
{:#members:flat-leftbuttonstyle}




Specifies the style for the flat left button i.e. back button or normal button or header button. See FlatHeaderLeftButtonStyle


#### Default Value

* ej.mobile.Button.Flat.Style.Back

#### Example


{% highlight html %} 
//Set the flat leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-showleftbutton="true" data-ej-flat-leftbuttonstyle="back" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set flat leftButtonStyle on initialization. 
//To set flat leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"flat":{"leftButtonStyle": "back"}})
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the flat leftButtonStyle, after initialization:
// Get the flat leftButtonStyle API value.              
 $("#header").ejmHeader ("option", "flat.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "flat.leftButtonStyle","normal");                 {% endhighlight %}




### flat.rightButtonStyle`enum`
{:#members:flat-rightbuttonstyle}

Specifies the flat style for the right button i.e. back button or normal button. See FlatHeaderRightButtonStyle

#### Default Value

* ej.mobile.Button.Flat.Style.Back

#### Example


{% highlight html %} 
//Set the flat rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-showrightbutton="true" data-ej-flat-rightbuttonstyle="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set flat rightButtonStyle on initialization. 
//To set flat rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"flat":{"rightButtonStyle": "normal"}})
}); 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the flat rightButtonStyle, after initialization:
// Get the flat rightButtonStyle API value.             
 $("#header").ejmHeader ("option", "flat.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "flat.rightButtonStyle","normal"); {% endhighlight %}


### flat.showLeftButton`boolean`
{:#members:flat-showleftbutton}


Specifies whether to show the flat left button or not.

#### Default Value

* false

#### Example

{% highlight html %} 
//Set the flat showLeftButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-flat-showleftbutton=true ></div>
{% endhighlight %}

{% highlight html %} 
<div id="header"></div>
<script>
// Set flat showLeftButton on initialization. 
//To set flat showLeftButton API value 
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({"flat":{ "showLeftButton": true }});
</script>{% endhighlight %}

{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "flat.showLeftButton");                      
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "flat.showLeftButton", true);                 {% endhighlight %}

### flat.showRightButton`boolean`
{:#members:flat-showrightbutton}

Specifies whether to show the flat right button or not.


#### Default Value

* false

#### Example

{% highlight html %} 
//Set the flat showRightButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-flat-showrightbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set flat showRightButton on initialization. 
//To set flat showRightButton API value 
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({"flat":{ "showRightButton": true }});   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "flat.showRightButton");                     
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "flat.showRightButton", true);                        {% endhighlight %}

### hideForUnSupportedDevice`boolean`
{:#members:hideforunsupporteddevice}


If this property is set to true, header will be visible for iOS7 rendermode alone.


#### Default Value

* false

#### Example


{% highlight html %} 
//Set the hideForUnSupportedDevice property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-hideforunsupporteddevice=true ></div>
    {% endhighlight %}


{% highlight html %}//Set hideForUnSupportedDevice on initialization.             
<div id="header"></div>
<script>
//To set hideForUnSupportedDevice API value 
$(function(){
$("#header").ejmHeader({ hideForUnSupportedDevice: true });     
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the hideForUnSupportedDevice, after initialization:
// Get the hideForUnSupportedDevice API value.          
 $("#header").ejmHeader ("option", "hideForUnSupportedDevice");                 
// Set the hideForUnSupportedDevice  API
$("#header").ejmHeader ("option", "hideForUnSupportedDevice", "Header");{% endhighlight %}

### ios7
{:#members:ios7}

Section for ios7 rendermode specific functionalities.

### ios7.leftButtonStyle`enum`
{:#members:ios7-leftbuttonstyle}

Specifies the style for the ios7 left button i.e. back button or normal button or header button. See IOS7HeaderLeftButtonStyle


#### Default Value

* ej.mobile.Button.IOS7.Style.Back

#### Example


{% highlight html %} 
//Set the ios7 leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-showleftbutton="true" data-ej-ios7-leftbuttonstyle="back" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set ios7 leftButtonStyle on initialization. 
//To set ios7 leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"ios7":{"leftButtonStyle": "back"}})
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the ios7 leftButtonStyle, after initialization:
// Get the ios7 leftButtonStyle API value.              
 $("#header").ejmHeader ("option", "ios7.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "ios7.leftButtonStyle","normal"); {% endhighlight %}




### ios7.rightButtonStyle`enum`
{:#members:ios7-rightbuttonstyle}


Specifies the ios7 style for the right button i.e. back button or normal button. See IOS7HeaderRightButtonStyle


#### Default Value

* ej.mobile.Button.IOS7.Style.Back

#### Example


{% highlight html %} 
//Set the ios7 rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-showrightbutton="true" data-ej-ios7-rightbuttonstyle="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set ios7 rightButtonStyle on initialization. 
//To set ios7 rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"ios7":{"rightButtonStyle": "normal"}})
}); 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the ios7 rightButtonStyle, after initialization:
// Get the ios7 rightButtonStyle API value.             
 $("#header").ejmHeader ("option", "ios7.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "ios7.rightButtonStyle","normal"); {% endhighlight %}


### ios7.showLeftButton`boolean`
{:#members:ios7-showleftbutton}

Specifies whether to show the ios7 left button or not.


#### Default Value

* false

#### Example


{% highlight html %} 
//Set the ios7 showLeftButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-ios7-showleftbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set ios7 showLeftButton on initialization. 
//To set ios7 showLeftButton API value 
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({"ios7":{ "showLeftButton": true }});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "ios7.showLeftButton");                      
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "ios7.showLeftButton", true);                 {% endhighlight %}

### ios7.showRightButton`boolean`
{:#members:ios7-showrightbutton}

Specifies whether to show the ios7 right button or not.


#### Default Value

* false

#### Example


{% highlight html %} 
//Set the ios7 showRightButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-ios7-showrightbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set ios7 showRightButton on initialization. 
//To set ios7 showRightButton API value 
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({"ios7":{ "showRightButton": true }});   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "ios7.showRightButton");                     
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "ios7.showRightButton", true);                        {% endhighlight %}

### leftButtonCaption`string`
{:#members:leftbuttoncaption}

Specifies the caption of the left button. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>


#### Default Value

* Back

#### Example

{% highlight html %} 
//Set the leftButtonCaption property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showLeftbutton="true" data-ej-leftbuttoncaption="Home" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set leftButtonCaption on initialization. 
//To set leftButtonCaption API value 
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({ leftButtonCaption: "Home" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the LeftButtonCaption, after initialization:
// Get the leftButtonCaption API value.         
 $("#header").ejmHeader ("option", "leftButtonCaption");                        
// Set the leftButtonCaption  API
$("#header").ejmHeader ("option", "leftButtonCaption", "Home");                 {% endhighlight %}


### leftButtonNavigationUrl`string`
{:#members:leftbuttonnavigationurl}

Specifies the navigation url, which the page should go while clicking the left button. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>

#### Default Value

* null

#### Example


{% highlight html %} 
//Set the leftButtonNavigationUrl property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonnavigationurl="" ></div>
{% endhighlight %}


{% highlight html %}//Set leftButtonNavigationUrl on initialization.             
<div id="header"></div>
<script>
//To set leftButtonNavigationUrl API value 
$(function(){
$("#header").ejmHeader({ leftButtonNavigationUrl: "" });        
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the leftButtonNavigationUrl, after initialization:
// Get the leftButtonNavigationUrl API value.           
 $("#header").ejmHeader ("option", "leftButtonNavigationUrl");                  
// Set the leftButtonNavigationUrl  API
$("#header").ejmHeader ("option", "leftButtonNavigationUrl", "Header");{% endhighlight %}

### leftButtonStyle`enum`
{:#members:leftbuttonstyle}

Specifies the style for the left button i.e. back button or normal button or header buttton. See <a href="global.html#HeaderLeftButtonStyle">HeaderLeftButtonStyle</a>


#### Default Value

* ej.mobile.Header.HeaderLeftButtonStyle.Back

#### Example

{% highlight html %} 
//Set the leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonstyle="back" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set leftButtonStyle on initialization. 
//To set leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({ leftButtonStyle: ej.mobile.Button.IOS7Style.Back });
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the leftButtonStyle, after initialization:
// Get the leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "leftButtonStyle");                  
// Set the leftButtonStyle  API
$("#header").ejmHeader ("option", "leftButtonStyle","normal"); {% endhighlight %}

### position`enum`
{:#members:position}

Specifies whether to keep the header in fixed position. i.e. top or in relative position depends on the other element's position. See <a href="global.html#Position">Position</a>

#### Default Value

* ej.mobile.Header.Position.Fixed

#### Example

{% highlight html %} 
//Set the position property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-position="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set position on initialization. 
//To set position API value 
$(function(){
$("#header").ejmHeader({ position: ej.mobile.Header.Position.Fixed });  
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the position, after initialization:
// Get the position API value.          
 $("#header").ejmHeader ("option", "position");                 
// Set the position  API
$("#header").ejmHeader ("option", "position", ej.mobile.Header.Position.Fixed);                 {% endhighlight %}

### renderMode`enum`
{:#members:rendermode}

Changes the rendering mode of the header.See <a href="global.html#RenderMode">RenderMode</a>

#### Default Value

* auto

#### Example


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="auto" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set rendermode on initialization. 
//To set renderMode API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Auto });      
});     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
 $("#header").ejmHeader ("option", "renderMode");                       
// Set the renderMode  API
$("#header").ejmHeader ("option", "renderMode", ej.mobile.RenderMode.Auto);                     {% endhighlight %}

### rightButtonCaption`string`
{:#members:rightbuttoncaption}

Specifies the caption of the right button. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>

#### Default Value

* Right

#### Example

{% highlight html %} 
//Set the rightButtonCaption property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttoncaption="Next" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set rightButtonCaption on initialization. 
//To set rightButtonCaption API value 
$("#header").ejmHeader({showRightButton:true});
$("#header").ejmHeader({ rightButtonCaption: "Next" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the rightButtonCaption, after initialization:
// Get the rightButtonCaption API value.                
 $("#header").ejmHeader ("option", "rightButtonCaption");                       
// Set the rightButtonCaption  API
$("#header").ejmHeader ("option", "rightButtonCaption", "Next");                        {% endhighlight %}


### rightButtonNavigationUrl`string`
{:#members:rightbuttonnavigationurl}

Specifies the navigation url, which the page should go while clicking the right button. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>

#### Default Value

* null

#### Example


{% highlight html %} 
//Set the rightButtonNavigationUrl property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonnavigationurl="" ></div>
{% endhighlight %}


{% highlight html %}//Set rightButtonNavigationUrl on initialization.             
<div id="header"></div>
<script>
//To set rightButtonNavigationUrl API value 
$(function(){
$("#header").ejmHeader({ rightButtonNavigationUrl: "" });       
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the rightButtonNavigationUrl, after initialization:
// Get the rightButtonNavigationUrl API value.          
 $("#header").ejmHeader ("option", "rightButtonNavigationUrl");                 
// Set the rightButtonNavigationUrl  API
$("#header").ejmHeader ("option", "rightButtonNavigationUrl", "Header");{% endhighlight %}


### rightButtonStyle`enum`
{:#members:rightbuttonstyle}

Specifies the style for the right button i.e. back button or normal button. See <a href="global.html#HeaderRightButtonStyle">HeaderRightButtonStyle</a> ej.mobile.Header.HeaderRightButtonStyle.Header

#### Example


{% highlight html %} 
//Set the rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonstyle="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set rightButtonStyle on initialization. 
//To set rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({showRightButton:true});
$("#header").ejmHeader({ rightButtonStyle: ej.mobile.Button.IOS7.Style.Header });
});
</script>{% endhighlight %}


{% highlight html %}      
//Get or set the rightButtonStyle, after initialization:
// Get the rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "rightButtonStyle");                 
// Set the rightButtonStyle  API
$("#header").ejmHeader ("option", "rightButtonStyle","normal");                         {% endhighlight %}


### showLeftButton`boolean`
{:#members:showleftbutton}

Specifies whether to show the left button or not.


#### Default Value


* false


#### Example


{% highlight html %} 
//Set the showLeftButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showleftbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set showLeftButton on initialization. 
//To set showLeftButton API value 
$("#header").ejmHeader({ showLeftButton: true });       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "showLeftButton", true);                      {% endhighlight %}




### showRightButton`boolean`
{:#members:showrightbutton}

Specifies whether to show the right button or not.


#### Default Value

* false

#### Example

{% highlight html %} 
//Set the showRightButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set showRightButton on initialization. 
//To set showRightButton API value 
$("#header").ejmHeader({ showRightButton: true });      
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showRightButton, after initialization:
// Get the showRightButton API value.           
 $("#header").ejmHeader ("option", "showRightButton");                  
// Set the showRightButton  API
$("#header").ejmHeader ("option", "showRightButton", true);                     {% endhighlight %}

### showTitle`boolean`
{:#members:showtitle}

Specifies whether to show the title or not. if this property is set to false, title will be hide.

#### Default Value

* true

#### Example

{% highlight html %} 
//Set the showTitle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showtitle=false ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set showTitle on initialization. 
//To set showTitle API value 
$("#header").ejmHeader({ showTitle: false });   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showTitle, after initialization:
// Get the showTitle API value.         
 $("#header").ejmHeader ("option", "showTitle");                        
// Set the showTitle  API
$("#header").ejmHeader ("option", "showTitle", false);                          {% endhighlight %}

### templateId`string`
{:#members:templateid}

Specifies the id of the element which is to be given as template.

#### Default Value

* null

#### Example


{% highlight html %} 
//Set the templateId property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-templateid="headertemplate" ></div>
                        {% endhighlight %}

### theme`enum`
{:#members:theme}


Changes the theme of the header. See <a href="global.html#Theme">Theme</a>

#### Default Value

* auto

#### Example

{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-theme="auto" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set theme on initialization. 
//To set theme API value 
$(function(){
$("#header").ejmHeader({ theme:  ej.mobile.Theme.Auto });       
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#header").ejmHeader ("option", "theme");                    
// Set the leftButtonCaption  API
$("#header").ejmHeader ("option", "theme",  ej.mobile.Theme.Auto);                      {% endhighlight %}

### title`string`
{:#members:title}

Specifies the title's text.

#### Default Value

* Title

#### Example


{% highlight html %} 
//Set the title property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-title="Header" ></div>
{% endhighlight %}


{% highlight html %}// Set title on initialization.             
<div id="header"></div>
<script>
//To set title API value 
$(function(){
$("#header").ejmHeader({ title: "Title" });     
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the title, after initialization:
// Get the title API value.             
 $("#header").ejmHeader ("option", "title");                    
// Set the title  API
$("#header").ejmHeader ("option", "title", "Header");                   {% endhighlight %}

### windows
{:#members:windows}

Section for windows rendermode specific functionalities.

### windows.enableCustomText`boolean`
{:#members:windows-enablecustomtext}

By default windows title's text will be in small case. To override this behavior, set this property to true.

#### Default Value

* false


#### Example


{% highlight html %} 
// Set the windows mode enableCustomText property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-enablecustomtext=true data-ej-title="Windows Custom Text" ></div>
 {% endhighlight %}

### windows.leftButtonStyle`enum`
{:#members:windows-leftbuttonstyle}

Specifies the style for the windows left button i.e. back button or normal button or header button. See WindowsHeaderLeftButtonStyle

#### Default Value

* ej.mobile.Button.Windows.Style.Back

#### Example


{% highlight html %} 
//Set the windows leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-showleftbutton="true" data-ej-windows-leftbuttonstyle="back" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set windows leftButtonStyle on initialization. 
//To set windows leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"windows":{"leftButtonStyle": "back"}})
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the windows leftButtonStyle, after initialization:
// Get the windows leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "windows.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "windows.leftButtonStyle","normal"); {% endhighlight %}

### windows.renderDefault`boolean`
{:#members:windows-renderdefault}

Specifies whether to render the header based on the windowsphone's current theme or not.


#### Default Value

* false

#### Example


{% highlight html %} 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-renderdefault=true ></div>
 {% endhighlight %}


### windows.rightButtonStyle`enum`
{:#members:windows-rightbuttonstyle}

Specifies the windows style for the right button i.e. back button or normal button. See WindowsHeaderRightButtonStyle

#### Default Value

* ej.mobile.Button.Windows.Style.Back


#### Example


{% highlight html %} 
//Set the windows rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-showrightbutton="true" data-ej-windows-rightbuttonstyle="normal" ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set windows rightButtonStyle on initialization. 
//To set windows rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"windows":{"rightButtonStyle": "normal"}})
}); 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the windows rightButtonStyle, after initialization:
// Get the windows rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "windows.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "windows.rightButtonStyle","normal"); {% endhighlight %}


### windows.showLeftButton`boolean`
{:#members:windows-showleftbutton}

Specifies whether to show the windows left button or not.

#### Default Value

* false

#### Example


{% highlight html %} 
//Set the windows showLeftButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-showleftbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set windows showLeftButton on initialization. 
//To set windows showLeftButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({"windows":{ "showLeftButton": true }});  
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "windows.showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "windows.showLeftButton", true);                      {% endhighlight %}


### windows.showRightButton`boolean`
{:#members:windows-showrightbutton}

Specifies whether to show the windows right button or not.

#### Default Value

* false

#### Example


{% highlight html %} 
//Set the windows showRightButton property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-showrightbutton=true ></div>
{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
// Set windows showRightButton on initialization. 
//To set windows showRightButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({"windows":{ "showRightButton": true }});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "windows.showRightButton");                  
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "windows.showRightButton", true);                     {% endhighlight %}

## Methods

### getTitle`()`
{:#methods:gettitle}

To get the header's text

#### Example

{% highlight html %} 
<div id="header" data-role="ejmheader" ></div>
<script>
$(function(){
// To get the instance of the Header
var header = $("#header").data("ejmHeader");
header.getTitle(); // returns the header's text
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
$(function(){
$("#header").ejmHeader();       
// get the header's current value
$("#header").ejmHeader("getTitle");     
});
</script>{% endhighlight %}



## Events

### leftButtonTap
{:#events:leftbuttontap}

Event triggers when the left button is tapped. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current button text</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttontap="onLeftButtonTap"></div>
<script> 
// leftButtonTap event for header  
function onLeftButtonTap(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
//LeftButtonTap event for header
$("#header").ejmHeader({showLeftButton:true, leftButtonTap:"test"});
    function test(){  //handle the event 
}
</script>{% endhighlight %}

### rightButtonTap
{:#events:rightbuttontap}

Event triggers when the right button is tapped. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current button text</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %}<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttontap="onRightButtonTap"></div>
<script> 
// rightButtonTap event for header  
function onRightButtonTap(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="header"></div>
<script>
$("#header").ejmHeader({showRightButton:true, rightButtonTap:"test"});
function test(){ //handle the event 
}
</script>                 {% endhighlight %}