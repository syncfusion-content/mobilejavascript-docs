---
layout: post
title: ejmToggleButton | API Reference | Mobile JS | Syncfusion
description:
documentation: API
platform: Mobilejs
keywords: ejmToggleButton, API, Essential Studio JS Autocomplete (Mobile) 
---

# ejmToggleButton

Custom Design for Html ToggleButton control.

$(element).ejmToggleButton<span class="signature">()</span>


#### Example


{% highlight html %} 
<div id="togglebutton" ></div>
<script> 
// Create ToggleButton  
$("#togglebutton").ejmToggleButton(); 
</script>{% endhighlight %}


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
{% endhighlight %}







#### Requires




* module:jQuery


* module:ej.mobile.application


* module:ej.core


* module:ej.unobtrusive


* module:ej.mobile.core


* module:ej.data


* module:ej.touch




## Members








### animate`boolean`
{:#members:animate}








Specifies the transition effect for state change.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the animate property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-animate=true></div>
{% endhighlight %}


{% highlight html %} 
// Set animate on initialization. 
//To set animate API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ animate:true });  
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton animate, after initialization:
// Get the animate API value.           
$("#togglebutton").ejmToggleButton ("option", "animate");                       
// Set the animate API
$("#togglebutton").ejmToggleButton ("option", "animate", true);            
</script>{% endhighlight %}







### cssClass`string`
{:#members:cssclass}








Sets the root class for ToggleButton theme. This cssClass API helps to use custom skinning option for ToggleButton control. By defining the root class using this API, we need to include this root class in CSS.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-cssclass="customclass"></div>
{% endhighlight %}


{% highlight html %} 
// Set cssClass on initialization. 
//To set cssClass API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ cssClass:"customclass" });  
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton cssClass, after initialization:
// Get the cssClass API value.          
$("#togglebutton").ejmToggleButton ("option", "cssClass");                      
// Set the cssClass API
$("#togglebutton").ejmToggleButton ("option", "cssClass", "customclass");            
</script>{% endhighlight %}







### enabled`boolean`
{:#members:enabled}








Specifies whether to enable or disable the control.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-enabled=true></div>
{% endhighlight %}


{% highlight html %} 
// Set togglebutton enabled on initialization. 
//To set enabled API value 
<div id="togglebutton" ></div>
<script> 
$("#togglebutton").ejmToggleButton ({ enabled:true  }); 
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton enabled, after initialization:
// Get the enabled API value.           
 $("#togglebutton").ejmToggleButton ("option", "enabled");                      
// Set the enabled API
$("#togglebutton").ejmToggleButton ("option", "enabled", true);      
</script>{% endhighlight %}







### enablePersistence`boolean`
{:#members:enablepersistence}








Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-enablePersistence=false></div>
{% endhighlight %}


{% highlight html %} 
// Set togglebutton persistence on initialization. 
//To set enablePersistence API value 
<div id="togglebutton" ></div>
<script> 
$("#togglebutton").ejmToggleButton ({ enablePersistence:false  });
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton persistence, after initialization:
// Get the enablePersistence API value.         
 $("#togglebutton").ejmToggleButton ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#togglebutton").ejmToggleButton ("option", "enablePersistence", false);  
</script>{% endhighlight %}







### renderMode`enum`
{:#members:rendermode}








Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-rendermode="auto"></div>
{% endhighlight %}


{% highlight html %} 
// Set togglebutton rendermode on initialization. 
//To set renderMode API value 
<div id="togglebutton" ></div>
<script>
$(function () {
$("#togglebutton").ejmToggleButton ({ renderMode:ej.mobile.RenderMode.Auto });  
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton rendermode, after initialization:
// Get the renderMode API value.                
 $("#togglebutton").ejmToggleButton ("option", "renderMode");                   
// Set the renderMode API
$("#togglebutton").ejmToggleButton ("option", "renderMode", ej.mobile.RenderMode.Auto);    
</script>{% endhighlight %}







### theme`enum`
{:#members:theme}








Specifies the theme. See <a href="global.html#Theme">Theme</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-theme="auto"></div>
{% endhighlight %}


{% highlight html %} 
// Set togglebutton theme on initialization. 
//To set theme API value 
<div id="togglebutton" ></div>
<script>
$(function () {
$("#togglebutton").ejmToggleButton ({ theme:ej.mobile.Theme.Auto });    
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton theme, after initialization:
// Get the theme API value.             
$("#togglebutton").ejmToggleButton ("option", "theme");                 
// Set the theme API
$("#togglebutton").ejmToggleButton ("option", "theme", ej.mobile.Theme.Auto);       
</script>{% endhighlight %}







### toggleState`boolean`
{:#members:togglestate}








Specifies whether state is on or off.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the togglestate property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-togglestate=true></div>
{% endhighlight %}


{% highlight html %} 
// Set togglebutton togglestate on initialization. 
//To set togglestate API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ toggleState:true  });     
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the togglebutton togglestate, after initialization:
// Get the togglestate API value.               
$("#togglebutton").ejmToggleButton ("option", "toggleState");                   
// Set the togglestate API
$("#togglebutton").ejmToggleButton ("option", "toggleState", true);  
</script>{% endhighlight %}







### windows
{:#members:windows}








Section for windows mode specific functionalities.











### windows.renderDefault`boolean`
{:#members:windows-renderdefault}








Specifies whether to render control based on the windowsphone's current accent color and device theme.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-rendermode="windows" data-ej-windows-renderDefault=false></div>
{% endhighlight %}


{% highlight html %} 
<div id="togglebutton" ></div>
<script>
// To set windows mode renderDefault property API value 
$(function () {
$("#togglebutton").ejmToggleButton({ renderMode:ej.mobile.RenderMode.Windows, windows.renderDefault: false});   
});
</script>{% endhighlight %}


{% highlight html %}<script>
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#togglebutton").ejmToggleButton("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#togglebutton").ejmToggleButton("option", "windows.renderDefault", false); 
</script>{% endhighlight %}





## Methods








### disable`()`
{:#methods:disable}








To disable the togglebutton.





#### Example


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Get the instance of toggle button
var toggle = $("#togglebutton").data("ejmToggleButton");
toggle.disable(); // Disables the toggle button
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Disable togglebutton
$("#togglebutton").ejmToggleButton("disable");  
});
</script>{% endhighlight %}







### enable`()`
{:#methods:enable}








To enable the togglebutton.





#### Example


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton" ></div>
<script>
$(document).ready(function(){
// Get the instance of toggle button
var toggle = $("#togglebutton").data("ejmToggleButton");
toggle.enable(); // Enables the toggle button
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Enable togglebutton
$("#togglebutton").ejmToggleButton("enable");   
});
</script>{% endhighlight %}





## Events








### change
{:#events:change}








Event triggers when the state change occurs.

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
<td class="description last">Event parameters from togglebutton.
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
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name">{% highlight html %}state{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-change="onChange"></div>
<script> 
// Change event for toggleButton 
function onChange(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//change event for toggleButton
<div id="togglebutton"></div>
<script>
$("#togglebutton").ejmToggleButton({
change: function (args) { //handle the event
}
});  
</script>{% endhighlight %}







### touchEnd
{:#events:touchend}








Event triggers when touch end happens on the control.

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
<td class="description last">Event parameters from togglebutton.
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
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name">{% highlight html %}state{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-touchEnd="onTouchEnd"></div>
<script> 
// touchEnd event for ToggleButton  
function onTouchEnd(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//touchEnd event for ToggleButton
<div id="togglebutton"></div>
<script>
$("#togglebutton").ejmToggleButton({
touchEnd: function (args) { //handle the event
}
}); 
</script>                  {% endhighlight %}







### touchStart
{:#events:touchstart}








Event triggers when touch start happens on the control.

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
<td class="description last">Event parameters from togglebutton.
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
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name">{% highlight html %}state{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-touchstart="onTouchStart"></div>
<script> 
// touchStart event to be triggered
function onTouchStart(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="togglebutton"></div>
<script> 
//touchStart event to be triggered
$("#togglebutton").ejmToggleButton({
touchStart: function (args) { //handle the event 
}
});  
</script> {% endhighlight %}




