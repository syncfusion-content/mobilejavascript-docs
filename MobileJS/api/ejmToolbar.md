---
layout: post
title: ejmToolbar | API Reference | Mobile JS | Syncfusion
description:
documentation: API
platform: Mobilejs
keywords: ejmToolbar, API, Essential Studio JS Autocomplete (Mobile) 
---

# ejmToolbar

Custom Design for Html toolbar control.

$(element).ejmToolbar<span class="signature">()</span>

#### Example

{% highlight html %} 
<div id="toolbar" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script> 
// Create toolbar  
$("#toolbar").ejmToolbar(); 
</script>{% endhighlight %}


{% highlight html %} 
<div id="toolbar" data-role="ejmtoolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}




#### Requires


* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

* module:ej.mobile.menu

* module:ej.mobile.scrollbar

* module:ej.mobile.scrollpanel


## Members




### android
{:#members:android}




Section for android rendermode specific functionalities.






### android.enableSplitView`boolean`
{:#members:android-enablesplitview}




Specifies the android mode split View mode is enabled or not.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the enableSplitView property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-enablesplitview=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode enableSplitView property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{enableSplitView: false},renderMode:ej.mobile.RenderMode.Android}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode enableSplitView API, after initialization:
<script>
// Gets the android mode enableSplitView value  
$("#toolbar").ejmToolbar("option", "android.enableSplitView");   
// Sets the android mode enableSplitView value 
$("#toolbar").ejmToolbar("option", "android.enableSplitView", false); 
</script>{% endhighlight %}




### android.position`boolean`
{:#members:android-position}




Specifies the android mode position.


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode position property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{position: "normal"},renderMode:ej.mobile.RenderMode.Android}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode position API, after initialization:
<script>
// Gets the android mode position value  
$("#toolbar").ejmToolbar("option", "android.position");   
// Sets the android mode poisition value 
$("#toolbar").ejmToolbar("option", "android.position", false); 
</script>{% endhighlight %}




### android.showBackNavigator`boolean`
{:#members:android-showbacknavigator}




Specifies the android mode Back icon is shown or not.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the showBackNavigator property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-showbacknavigator=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode showBackNavigator property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{showBackNavigator: false},renderMode:ej.mobile.RenderMode.Android}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode showBackNavigator API, after initialization:
<script>
// Gets the android mode showBackNavigator value  
$("#toolbar").ejmToolbar("option", "android.showBackNavigator");   
// Sets the android mode showBackNavigator value 
$("#toolbar").ejmToolbar("option", "android.showBackNavigator", false); 
</script>{% endhighlight %}




### android.showEllipsis`bool`
{:#members:android-showellipsis}




Specifies the android mode Ellipsis icon is shown or not.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the showEllipsis property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-showEllipsis=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode showEllipsis property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{showEllipsis: false},renderMode:ej.mobile.RenderMode.Android });
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode showEllipsis API, after initialization:
<script>
// Gets the android mode showEllipsis value  
$("#toolbar").ejmToolbar("option", "android.showEllipsis");   
// Sets the android mode showEllipsis value 
$("#toolbar").ejmToolbar("option", "android.showEllipsis", false); 
</script>{% endhighlight %}




### android.showTitleIcon`boolean`
{:#members:android-showtitleicon}




Specifies the android mode Title Icon will be shown or not.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the showTitleIcon property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar"  data-ej-rendermode="android" data-ej-android-showTitleIcon=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode showTitleIcon property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{showTitleIcon: false},renderMode: ej.mobile.RenderMode.Android});   
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode showTitleIcon API, after initialization:
<script>
// Gets the android mode showTitleIcon value  
$("#toolbar").ejmToolbar("option", "android.showTitleIcon");   
// Sets the android mode showTitleIcon value 
$("#toolbar").ejmToolbar("option", "android.showTitleIcon", false); 
</script>{% endhighlight %}




### android.title`string`
{:#members:android-title}




Specifies the android mode toolbar's title.


#### Default Value



* Title




#### Example


{% highlight html %} 
//Set the title property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-title="Title" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode title property API value 
<div id="toolbar" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{title: "Title"},renderMode:ej.mobile.RenderMode.Android}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode title API, after initialization:
<script>
// Gets the android mode title value  
$("#toolbar").ejmToolbar("option", "android.title");   
// Sets the android mode title value 
$("#toolbar").ejmToolbar("option", "android.title", "Title"); 
</script>{% endhighlight %}




### android.titleIconUrl`string`
{:#members:android-titleiconurl}




Specifies the android mode title icon path or location.


#### Default Value



* ""




#### Example


{% highlight html %} 
//Set the titleIconUrl property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-titleIconUrl="enter title Icon url here" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set android mode titleIconUrl property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ android:{titleIconUrl: "enter title Icon url here"},renderMode:ej.mobile.RenderMode.Android });   
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode titleIconUrl API, after initialization:
<script>
// Gets the android mode titleIconUrl value  
$("#toolbar").ejmToolbar("option", "android.titleIconUrl");   
// Sets the android mode titleIconUrl value 
$("#toolbar").ejmToolbar("option", "android.titleIconUrl", "enter title Icon url here"); 
</script>{% endhighlight %}




### cssClass`string`
{:#members:cssclass}




Sets the root class for Toolbar theme. This cssClass API helps to use custom skinning option for Toolbar control. By defining the root class using this API, we need to include this root class in CSS.


#### Default Value



* ""




#### Example


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-cssclass="customclass">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar cssClass on initialization. 
//To set cssClass API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar ({ cssClass:"customclass"});   
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar cssClass, after initialization:
<script>
// Gets the cssClass API value.         
 $("#toolbar").ejmToolbar ("option", "cssClass");                       
// Sets the cssClass API
$("#toolbar").ejmToolbar ("option", "cssClass", "customclass");            
</script>{% endhighlight %}




### enabled`bool`
{:#members:enabled}




Specifies whether the control is enabled or not.


#### Default Value



* true




#### Example


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-enabled=true>
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar enabled on initialization. 
//To set enabled API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$("#toolbar").ejmToolbar ({ enabled: true });   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar enabled, after initialization:
<script>
// Gets the enabled API value.          
 $("#toolbar").ejmToolbar ("option", "enabled");                        
// Sets the enabled API
$("#toolbar").ejmToolbar ("option", "enabled", true);            
</script>{% endhighlight %}




### enablePersistence`boolean`
{:#members:enablepersistence}




Current model value to browser cookies for state maintains. While refresh the Header control page retains the model value apply from browser cookies.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-enablepersistence=true >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar enablePersistence on initialization. 
//To set enablePersistence API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$("#toolbar").ejmToolbar ({ enablePersistence: true });         
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar enablePersistence, after initialization:
<script>
// Gets the enablePersistence API value.                
 $("#toolbar").ejmToolbar ("option", "enablePersistence");                      
// Sets the enablePersistence API
$("#toolbar").ejmToolbar ("option", "enablePersistence", true);            
</script>{% endhighlight %}




### flat
{:#members:flat}




Section for Flat rendermode specific functionalities.






### flat.position`boolean`
{:#members:flat-position}




Specifies the flat mode position.


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="flat" data-ej-flat-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set flat mode position property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ flat:{position: "normal"},renderMode:ej.mobile.RenderMode.Flat}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the flat mode position API, after initialization:
<script>
// Gets the flat mode position value  
$("#toolbar").ejmToolbar("option", "flat.position");   
// Sets the android mode position value 
$("#toolbar").ejmToolbar("option", "flat.position", false); 
</script>{% endhighlight %}




### hide`bool`
{:#members:hide}




Specifies whether the control is in hidden state or not.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the hide property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-hide=false>
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar hide on initialization. 
//To set hide API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$("#toolbar").ejmToolbar ({ hide: false });             
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar hide, after initialization:
<script>
// Gets the hide API value.             
 $("#toolbar").ejmToolbar ("option", "hide");                   
// Sets the hide API
$("#toolbar").ejmToolbar ("option", "hide", false);            
</script>{% endhighlight %}




### ios7
{:#members:ios7}




Section for ios7 rendermode specific functionalities.






### ios7.position`boolean`
{:#members:ios7-position}




Specifies the ios7 mode position.


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="ios7" data-ej-ios7-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set ios7 mode position property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ ios7:{position: "normal"},renderMode:ej.mobile.RenderMode.IOS7}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the ios7 mode position API, after initialization:
<script>
// Gets the ios7 mode position value  
$("#toolbar").ejmToolbar("option", "ios7.position");   
// Sets the ios7 mode position value 
$("#toolbar").ejmToolbar("option", "ios7.position", false); 
</script>{% endhighlight %}




### position`enum`
{:#members:position}




Specifies position whether it is in fixed or relative to the page. See <a href="global.html#Position">Position</a>


#### Default Value



* fixed




#### Example


{% highlight html %} 
//Set the toolbarPosition property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-position="fixed">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar toolbarPosition on initialization. 
//To set toolbarPosition API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar ({ position: ej.mobile.Position.Fixed });              
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar toolbarPosition, after initialization:
<script>
// Gets the toolbarPosition API value.          
 $("#toolbar").ejmToolbar ("option", "position");                       
// Sets the toolbarPosition API
$("#toolbar").ejmToolbar ("option", "position", ej.mobile.Position.Fixed);            
</script>{% endhighlight %}




### renderMode`enum`
{:#members:rendermode}




Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="auto">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar renderMode on initialization. 
//To set renderMode API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar ({ renderMode:ej.mobile.RenderMode.Windows});  
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar renderMode, after initialization:
<script>
// Gets the renderMode API value.               
 $("#toolbar").ejmToolbar ("option", "renderMode");                     
// Sets the renderMode API
$("#toolbar").ejmToolbar ("option", "renderMode", ej.mobile.RenderMode.Auto);            
</script>{% endhighlight %}




### templateId`string`
{:#members:templateid}




Specifies the Toolbar template Id.


#### Default Value



* null




#### Example


{% highlight html %} 
//Set the templateId property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-templateid="sample">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<span id="sample" >Hi, SampleSpan </span>{% endhighlight %}


{% highlight html %} 
// Set Toolbar templateId on initialization. 
//To set templateId API value 
<div id="toolbar" data-role="ejmtoolbar" data-ej-templateid="sample">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<span id="sample" >Hi, SampleSpan </span>
<script>
$("#toolbar").ejmToolbar ({ templateId: "sample" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar templateId, after initialization:
<script>
// Gets the templateId API value.               
 $("#toolbar").ejmToolbar ("option", "templateId");                     
// Sets the templateId API
$("#toolbar").ejmToolbar ("option", "templateId", "sample");            
<script>{% endhighlight %}




### theme`enum`
{:#members:theme}




Changes the theme. See <a href="global.html#Theme">Theme</a>


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-theme="auto">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// Set Toolbar theme on initialization. 
//To set theme API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar ({ theme: ej.mobile.Theme.Auto });
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Toolbar theme, after initialization:
<script>
// Gets the theme API value.            
 $("#toolbar").ejmToolbar ("option", "theme");                  
// Sets the theme API
$("#toolbar").ejmToolbar ("option", "theme", ej.mobile.Theme.Auto);            
</script>{% endhighlight %}




### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.position`boolean`
{:#members:windows-position}




Specifies the Windows mode position.


#### Default Value



* auto




#### Example


{% highlight html %} 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="windows" data-ej-windows-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set windows mode position property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ windows:{position: "normal"},renderMode:ej.mobile.RenderMode.Windows}); 
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode position API, after initialization:
<script>
// Gets the windows mode position value  
$("#toolbar").ejmToolbar("option", "windows.position");   
// Sets the windows mode poisition value 
$("#toolbar").ejmToolbar("option", "windows.position", false); 
</script>{% endhighlight %}




### windows.renderDefault`bool`
{:#members:windows-renderdefault}




Specifies whether to render the toolbar based on the windowsphone's current accent color and theme.


#### Default Value



* false




#### Example


{% highlight html %} 
//Set the renderDefault property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar"  data-ej-rendermode="windows" data-ej-windows-renderDefault=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>{% endhighlight %}


{% highlight html %} 
// To set windows mode renderDefault property API value 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$(function () {
$("#toolbar").ejmToolbar({ windows:{renderDefault: false},renderMode:ej.mobile.RenderMode.Windows});
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
<script>
// Gets the windows mode renderDefault value  
$("#toolbar").ejmToolbar("option", "windows.renderDefault");   
// Sets the windows mode renderDefault value 
$("#toolbar").ejmToolbar("option", "windows.renderDefault", false); 
</script>{% endhighlight %}



## Methods




### addItem`()`
{:#methods:additem}




To add new item to the toolbar



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// add new icon to the toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.addItem("paste"); 
</script>{% endhighlight %}




### disableItem`()`
{:#methods:disableitem}




To disable particular toolbar item by name



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// disable particular icon in toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.disableItem("add"); 
</script>{% endhighlight %}




### enableItem`()`
{:#methods:enableitem}




To enable particular toolbar item by name



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// enable particular icon in toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.enableItem("add"); 
</script>{% endhighlight %}




### hideEllipsis`()`
{:#methods:hideellipsis}




To hide ellipsis for android mode toolbar



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// hide ellipsis for android mode toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.hideEllipsis(); 
</script>{% endhighlight %}




### hideItem`()`
{:#methods:hideitem}




To hide particular toolbar item by name



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// hide particular icon in toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.hideItem("add"); 
</script>{% endhighlight %}




### hideMenu`()`
{:#methods:hidemenu}




To hide the overflow menu in android



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// add new icon to the toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.hideMenu(); 
</script>{% endhighlight %}




### removeItem`()`
{:#methods:removeitem}




To remove the toolbar icons by it's index



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// remove the icon by index for toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.removeItem(1); 
</script>{% endhighlight %}




### showEllipsis`()`
{:#methods:showellipsis}




To show ellipsis for android mode toolbar



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// show ellipsis for android mode toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.showEllipsis(); 
</script>{% endhighlight %}




### showItem`()`
{:#methods:showitem}




To show particular toolbar item by name



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// show particular icon in toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.showItem("add"); 
</script>{% endhighlight %}




### showMenu`()`
{:#methods:showmenu}




To show the overflow menu in android



#### Example


{% highlight html %} 
<div id="toolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
// add new icon to the toolbar
$("#toolbar").ejmToolbar();
var toolbar = $("#toolbar").data("ejmToolbar");
toolbar.showMenu(); 
</script>{% endhighlight %}



## Events




### touchEnd
{:#events:touchend}




Event triggers when the touch end happens.

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
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from Toolbar
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
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Toolbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}item{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name">{% highlight html %}itemName{% endhighlight %}</td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
<div id="toolbar" data-role="ejmtoolbar" data-ej-touchend="touchend">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script> 
// TouchEnd event for toolbar  
function touchend(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//TouchEnd event for toolbar
<div id="toolbar" data-role="ejmtoolbar" data-ej-touchend="touchend">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script>
$("#toolbar").ejmToolbar({
  touchend: function (args) { //handle the event
}
});         
</script>{% endhighlight %}




### touchStart
{:#events:touchstart}




Event triggers when the touch start happens.

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
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from Toolbar
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
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Toolbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}item{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
<div id="toolbar" data-role="ejmtoolbar" data-ej-touchstart="touchstart">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<script> 
// TouchStart event for toolbar  
function touchstart(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="toolbar" data-role="ejmtoolbar" data-ej-touchstart="touchstart">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
//touchStart event for toolbar
<script>
$("#toolbar").ejmToolbar({
  touchstart: function (args) { //handle the event
}
});       
</script>{% endhighlight %}