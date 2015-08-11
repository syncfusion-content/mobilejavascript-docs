---
layout: post
title: ejmToolbar
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html toolbar control.





$(element).ejmToolbar<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="toolbar" data-role="ejmtoolbar">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>



Requires
{:.require}


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






### android.enableSplitView<span class="type-signature type boolean">boolean</span>
{:#members:android-enablesplitview}




Specifies the android mode split View mode is enabled or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enableSplitView property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-enablesplitview=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode enableSplitView API, after initialization:
<script>
// Gets the android mode enableSplitView value  
$("#toolbar").ejmToolbar("option", "android.enableSplitView");   
// Sets the android mode enableSplitView value 
$("#toolbar").ejmToolbar("option", "android.enableSplitView", false); 
</script></code>
</pre>



### android.position<span class="type-signature type boolean">boolean</span>
{:#members:android-position}




Specifies the android mode position.


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode position API, after initialization:
<script>
// Gets the android mode position value  
$("#toolbar").ejmToolbar("option", "android.position");   
// Sets the android mode poisition value 
$("#toolbar").ejmToolbar("option", "android.position", false); 
</script></code>
</pre>



### android.showBackNavigator<span class="type-signature type boolean">boolean</span>
{:#members:android-showbacknavigator}




Specifies the android mode Back icon is shown or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showBackNavigator property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-showbacknavigator=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode showBackNavigator API, after initialization:
<script>
// Gets the android mode showBackNavigator value  
$("#toolbar").ejmToolbar("option", "android.showBackNavigator");   
// Sets the android mode showBackNavigator value 
$("#toolbar").ejmToolbar("option", "android.showBackNavigator", false); 
</script></code>
</pre>



### android.showEllipsis<span class="type-signature type bool">bool</span>
{:#members:android-showellipsis}




Specifies the android mode Ellipsis icon is shown or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showEllipsis property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-showEllipsis=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode showEllipsis API, after initialization:
<script>
// Gets the android mode showEllipsis value  
$("#toolbar").ejmToolbar("option", "android.showEllipsis");   
// Sets the android mode showEllipsis value 
$("#toolbar").ejmToolbar("option", "android.showEllipsis", false); 
</script></code>
</pre>



### android.showTitleIcon<span class="type-signature type boolean">boolean</span>
{:#members:android-showtitleicon}




Specifies the android mode Title Icon will be shown or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showTitleIcon property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar"  data-ej-rendermode="android" data-ej-android-showTitleIcon=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode showTitleIcon API, after initialization:
<script>
// Gets the android mode showTitleIcon value  
$("#toolbar").ejmToolbar("option", "android.showTitleIcon");   
// Sets the android mode showTitleIcon value 
$("#toolbar").ejmToolbar("option", "android.showTitleIcon", false); 
</script></code>
</pre>



### android.title<span class="type-signature type string">string</span>
{:#members:android-title}




Specifies the android mode toolbar's title.


Default Value:
{:.param}



* Title




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the title property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-title="Title" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode title API, after initialization:
<script>
// Gets the android mode title value  
$("#toolbar").ejmToolbar("option", "android.title");   
// Sets the android mode title value 
$("#toolbar").ejmToolbar("option", "android.title", "Title"); 
</script></code>
</pre>



### android.titleIconUrl<span class="type-signature type string">string</span>
{:#members:android-titleiconurl}




Specifies the android mode title icon path or location.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the titleIconUrl property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="android" data-ej-android-titleIconUrl="enter title Icon url here" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode titleIconUrl API, after initialization:
<script>
// Gets the android mode titleIconUrl value  
$("#toolbar").ejmToolbar("option", "android.titleIconUrl");   
// Sets the android mode titleIconUrl value 
$("#toolbar").ejmToolbar("option", "android.titleIconUrl", "enter title Icon url here"); 
</script></code>
</pre>



### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Toolbar theme. This cssClass API helps to use custom skinning option for Toolbar control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-cssclass="customclass">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar cssClass, after initialization:
<script>
// Gets the cssClass API value.         
 $("#toolbar").ejmToolbar ("option", "cssClass");                       
// Sets the cssClass API
$("#toolbar").ejmToolbar ("option", "cssClass", "customclass");            
</script></code>
</pre>



### enabled<span class="type-signature type bool">bool</span>
{:#members:enabled}




Specifies whether the control is enabled or not.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enabled property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-enabled=true>
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar enabled, after initialization:
<script>
// Gets the enabled API value.          
 $("#toolbar").ejmToolbar ("option", "enabled");                        
// Sets the enabled API
$("#toolbar").ejmToolbar ("option", "enabled", true);            
</script></code>
</pre>



### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}




Current model value to browser cookies for state maintains. While refresh the Header control page retains the model value apply from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enablePersistence property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-enablepersistence=true >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar enablePersistence, after initialization:
<script>
// Gets the enablePersistence API value.                
 $("#toolbar").ejmToolbar ("option", "enablePersistence");                      
// Sets the enablePersistence API
$("#toolbar").ejmToolbar ("option", "enablePersistence", true);            
</script></code>
</pre>



### flat
{:#members:flat}




Section for Flat rendermode specific functionalities.






### flat.position<span class="type-signature type boolean">boolean</span>
{:#members:flat-position}




Specifies the flat mode position.


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="flat" data-ej-flat-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the flat mode position API, after initialization:
<script>
// Gets the flat mode position value  
$("#toolbar").ejmToolbar("option", "flat.position");   
// Sets the android mode position value 
$("#toolbar").ejmToolbar("option", "flat.position", false); 
</script></code>
</pre>



### hide<span class="type-signature type bool">bool</span>
{:#members:hide}




Specifies whether the control is in hidden state or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the hide property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-hide=false>
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar hide, after initialization:
<script>
// Gets the hide API value.             
 $("#toolbar").ejmToolbar ("option", "hide");                   
// Sets the hide API
$("#toolbar").ejmToolbar ("option", "hide", false);            
</script></code>
</pre>



### ios7
{:#members:ios7}




Section for ios7 rendermode specific functionalities.






### ios7.position<span class="type-signature type boolean">boolean</span>
{:#members:ios7-position}




Specifies the ios7 mode position.


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="ios7" data-ej-ios7-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 mode position API, after initialization:
<script>
// Gets the ios7 mode position value  
$("#toolbar").ejmToolbar("option", "ios7.position");   
// Sets the ios7 mode position value 
$("#toolbar").ejmToolbar("option", "ios7.position", false); 
</script></code>
</pre>



### position<span class="type-signature type enum">enum</span>
{:#members:position}




Specifies position whether it is in fixed or relative to the page. See <a href="global.html#Position">Position</a>


Default Value:
{:.param}



* fixed




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the toolbarPosition property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-position="fixed">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar toolbarPosition, after initialization:
<script>
// Gets the toolbarPosition API value.          
 $("#toolbar").ejmToolbar ("option", "position");                       
// Sets the toolbarPosition API
$("#toolbar").ejmToolbar ("option", "position", ej.mobile.Position.Fixed);            
</script></code>
</pre>



### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="auto">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar renderMode, after initialization:
<script>
// Gets the renderMode API value.               
 $("#toolbar").ejmToolbar ("option", "renderMode");                     
// Sets the renderMode API
$("#toolbar").ejmToolbar ("option", "renderMode", ej.mobile.RenderMode.Auto);            
</script></code>
</pre>



### templateId<span class="type-signature type string">string</span>
{:#members:templateid}




Specifies the Toolbar template Id.


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the templateId property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-templateid="sample">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div>
<span id="sample" >Hi, SampleSpan </span></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar templateId, after initialization:
<script>
// Gets the templateId API value.               
 $("#toolbar").ejmToolbar ("option", "templateId");                     
// Sets the templateId API
$("#toolbar").ejmToolbar ("option", "templateId", "sample");            
<script></code>
</pre>



### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Changes the theme. See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-theme="auto">
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Toolbar theme, after initialization:
<script>
// Gets the theme API value.            
 $("#toolbar").ejmToolbar ("option", "theme");                  
// Sets the theme API
$("#toolbar").ejmToolbar ("option", "theme", ej.mobile.Theme.Auto);            
</script></code>
</pre>



### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.position<span class="type-signature type boolean">boolean</span>
{:#members:windows-position}




Specifies the Windows mode position.


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar" data-ej-rendermode="windows" data-ej-windows-position="normal" >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode position API, after initialization:
<script>
// Gets the windows mode position value  
$("#toolbar").ejmToolbar("option", "windows.position");   
// Sets the windows mode poisition value 
$("#toolbar").ejmToolbar("option", "windows.position", false); 
</script></code>
</pre>



### windows.renderDefault<span class="type-signature type bool">bool</span>
{:#members:windows-renderdefault}




Specifies whether to render the toolbar based on the windowsphone's current accent color and theme.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderDefault property in unobtrusive way.
<div id="toolbar" data-role="ejmtoolbar"  data-ej-rendermode="windows" data-ej-windows-renderDefault=false >
<ul>
<li data-ej-iconname="add" ></li>
<li data-ej-iconname="cut" ></li>
<li data-ej-iconname="copy" ></li>
</ul >
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
<script>
// Gets the windows mode renderDefault value  
$("#toolbar").ejmToolbar("option", "windows.renderDefault");   
// Sets the windows mode renderDefault value 
$("#toolbar").ejmToolbar("option", "windows.renderDefault", false); 
</script></code>
</pre>


## Methods




### addItem<span class="signature">()</span>
{:#methods:additem}




To add new item to the toolbar



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### disableItem<span class="signature">()</span>
{:#methods:disableitem}




To disable particular toolbar item by name



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### enableItem<span class="signature">()</span>
{:#methods:enableitem}




To enable particular toolbar item by name



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### hideEllipsis<span class="signature">()</span>
{:#methods:hideellipsis}




To hide ellipsis for android mode toolbar



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### hideItem<span class="signature">()</span>
{:#methods:hideitem}




To hide particular toolbar item by name



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### hideMenu<span class="signature">()</span>
{:#methods:hidemenu}




To hide the overflow menu in android



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### removeItem<span class="signature">()</span>
{:#methods:removeitem}




To remove the toolbar icons by it's index



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### showEllipsis<span class="signature">()</span>
{:#methods:showellipsis}




To show ellipsis for android mode toolbar



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### showItem<span class="signature">()</span>
{:#methods:showitem}




To show particular toolbar item by name



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



### showMenu<span class="signature">()</span>
{:#methods:showmenu}




To show the overflow menu in android



Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>


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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Toolbar model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name"><code>itemName</code></td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>



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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Toolbar model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>


