---
layout: post
title: ejmTimePicker | API Reference | Mobile JS | Syncfusion
description:
documentation: API
platform: Mobilejs
keywords: ejmTimePicker, API, Essential Studio JS Autocomplete (Mobile) 
---

# ejmTimePicker

Custom Design for Html TimePicker control.

$(element).ejmTimePicker<span class="signature">()</span>


#### Example

{% highlight html %} 
<input id="timepicker" data-role="none" />
<script>  
$(function(){
$("#timepicker").ejmTimePicker(); 
});
</script>{% endhighlight %}







#### Requires




* module:jQuery


* module:ej.mobile.application


* module:ej.core


* module:ej.unobtrusive


* module:ej.mobile.core


* module:ej.data


* module:ej.touch


* module:ej.mobile.menu


* module:ej.mobile.dialog


* module:ej.mobile.button


* module:ej.mobile.toolbar


* module:ej.mobile.scrollbar


* module:ej.mobile.scrollpanel




## Members








### cssClass`string`
{:#members:cssclass}








Sets the root class for TimePicker theme. This cssClass API helps to use custom skinning option for TimePicker control. By defining the root class using this API, we need to include this root class in CSS.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the cssClass property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-cssclass="customclass" />
{% endhighlight %}


{% highlight html %} 
// Set the cssClass on initialization. 
//To set cssClass API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ cssClass: "customclass" });    
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
 $("#TimePicker").ejmTimePicker("option", "cssClass");                  
// Set the cssClass API
$("#TimePicker").ejmTimePicker("option", "cssClass", "customclass");            {% endhighlight %}







### enabled`boolean`
{:#members:enabled}








Specifies whether to enable the control on initialization.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the enabled property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-enabled=true />
{% endhighlight %}


{% highlight html %} 
// Set the enabled on initialization. 
//To set enabled API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ enabled: true });      
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
 $("#timepicker").ejmTimePicker("option", "enabled");                   
// Set the enabled API
$("#timepicker").ejmTimePicker("option", "enabled", true);            {% endhighlight %}







### enablePersistence`boolean`
{:#members:enablepersistence}








Current model value to browser cookies for state maintains. While refresh the page retains the model value apply from browser cookies.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enablePersistence property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-enablepersistence=true />
{% endhighlight %}


{% highlight html %} 
// Set the enablePersistence on initialization. 
//To set enablePersistence API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ enablePersistence: true });    
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#TimePicker").ejmTimePicker("option", "enablePersistence");                 
// Set the enablePersistence API
$("#TimePicker").ejmTimePicker("option", "enablePersistence", true);            {% endhighlight %}







### hourFormat`enum`
{:#members:hourformat}








Specifies the hour format See <a href="global.html#HourFormat">HourFormat</a>.




#### Default Value






* "twentyfour"








#### Example


{% highlight html %} 
//Set the hourFormat property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-hourformat="twentyfour" />
{% endhighlight %}


{% highlight html %} 
// Set the hourFormat on initialization. 
//To set hourFormat API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ hourFormat: "twentyfour" });                   
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the hourFormat, after initialization:
// Get the hourFormat API value.                
 $("#timepicker").ejmTimePicker("option", "hourFormat");                        
// Set the hourFormat API
$("#timepicker").ejmTimePicker("option", "hourFormat", "twentyfour");            {% endhighlight %}







### ios7
{:#members:ios7}








Section for ios7 rendermode specific functionalities.











### ios7.renderDefault`boolean`
{:#members:ios7-renderdefault}








Specifies whether to use ios7 native timepicker or not.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the ios7 mode renderDefault property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="ios7" data-ej-ios7-renderdefault="false" />
{% endhighlight %}


{% highlight html %} 
// To set ios7 mode renderDefault property API value 
<input id="timepicker" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "ios7", ios7: { renderDefault: false } });          
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the ios7 mode renderDefault API, after initialization:
// Get the ios7 mode renderDefault value  
$("#timepicker").ejmTimePicker("option", "ios7.renderDefault");                 
// Set the ios7 mode renderDefault value 
$("#timepicker").ejmTimePicker("option", "ios7.renderDefault", false); {% endhighlight %}







### renderMode`enum`
{:#members:rendermode}








Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the renderMode property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="auto" />
{% endhighlight %}


{% highlight html %} 
// Set the renderMode on initialization. 
//To set renderMode API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "auto" });                 
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
 $("#timepicker").ejmTimePicker("option", "renderMode");                        
// Set the renderMode API
$("#timepicker").ejmTimePicker("option", "renderMode", "auto");            {% endhighlight %}







### theme`enum`
{:#members:theme}








Changes the theme. See <a href="global.html#Theme">Theme</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the theme property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-theme="auto" />
{% endhighlight %}


{% highlight html %} 
// Set the theme on initialization. 
//To set theme API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ theme: "auto" });                      
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#timepicker").ejmTimePicker("option", "theme");                     
// Set the theme API
$("#timepicker").ejmTimePicker("option", "theme", "auto");            {% endhighlight %}







### timeFormat`string`
{:#members:timeformat}








Specifies the time format.




#### Default Value






* null








#### Example


{% highlight html %} 
//Set the timeFormat property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-hourformat="twelve" data-ej-timeformat="hh:mm tt" />
{% endhighlight %}


{% highlight html %} 
// Set the timeFormat on initialization. 
//To set timeFormat API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ hourFormat: "twelve", timeFormat: "hh:mm tt" });                       
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the timeFormat, after initialization:
// Get the timeFormat API value.                
 $("#timepicker").ejmTimePicker("option", "timeFormat");                        
// Set the timeFormat API
$("#timepicker").ejmTimePicker("option", "timeFormat", "hh:mm tt");            {% endhighlight %}







### value`string`
{:#members:value}








Specifies the value.




#### Default Value






* new Date().ToString()








#### Example


{% highlight html %} 
//Set the value property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-value="02:20 PM" />
{% endhighlight %}


{% highlight html %} 
// Set the value on initialization. 
//To set value API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ value: "02:20 PM" });
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the value, after initialization:
// Get the value API value.             
 $("#timepicker").ejmTimePicker("option", "value");                     
// Set the value API
$("#timepicker").ejmTimePicker("option", "value", "02:20 PM");            {% endhighlight %}







### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.renderDefault`boolean`
{:#members:windows-renderdefault}








Specifies whether to render the control based on the windowsphone's current theme or not.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode renderDefault property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="windows" data-ej-windows-renderdefault="false" />
{% endhighlight %}


{% highlight html %} 
// To set windows mode renderDefault property API value 
<input id="timepicker" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "windows", windows: { renderDefault: false } });            
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#timepicker").ejmTimePicker("option", "windows.renderDefault");                      
// Set the windows mode renderDefault value 
$("#timepicker").ejmTimePicker("option", "windows.renderDefault", false); {% endhighlight %}





## Methods








### disable`()`
{:#methods:disable}








To handle the TimePicker control disabled state





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.disable(); 
});
</script>                {% endhighlight %}







### enable`()`
{:#methods:enable}








To handle the TimePicker control enabled state





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.enable(); 
});
</script>        {% endhighlight %}







### getValue`()`
{:#methods:getvalue}








To change the TimePicker control to disabled state





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var dpObj = $("#timepicker").data("ejmTimePicker");
dpObj.getValue();
});
</script>         {% endhighlight %}







### hide`()`
{:#methods:hide}








To hide the TimePicker control





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.hide(); 
});
</script>        {% endhighlight %}







### setCurrentTime`()`
{:#methods:setcurrenttime}








To change the TimePicker control to disabled state





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var dpObj = $("#timepicker").data("ejmTimePicker");
dpObj.setCurrentTime("05:20");
});
</script>        {% endhighlight %}







### show`()`
{:#methods:show}








To show the TimePicker control





#### Example


{% highlight html %} 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.show(); 
});
</script>        {% endhighlight %}





## Events








### change
{:#events:change}








Event triggers when the time is changed.

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
<td class="description last">Event parameters from TimePicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the change event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-change="Change" />
<script>
function Change(args) {}
</script>{% endhighlight %}


{% highlight html %} 
<input id="timepicker" data-role="none" />
//select change for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ change:"Change" });
});
function Change(args) {}                       
</script>                  {% endhighlight %}







### close
{:#events:close}








Event triggers when the control is closed.

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
<td class="description last">Event parameters from TimePicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the close event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-close="Close" />
<script>
function Close(args) {}
</script>{% endhighlight %}


{% highlight html %} 
<input id="timepicker" data-role="none" />
//select close for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ close:"Close" });
});
function Close(args) {}                       
</script>                  {% endhighlight %}







### focusIn
{:#events:focusin}








Event triggers when the input element is focused.

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
<td class="description last">Event parameters from TimePicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the focusin event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-focusin="Focusin" />
<script>
function Focusin(args) {}
</script>{% endhighlight %}


{% highlight html %} 
<input id="timepicker" data-role="none" />
//select focusIn for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ focusin:"Focusin" });
});
function Focusin(args) {}                       
</script>                  {% endhighlight %}







### focusOut
{:#events:focusout}








Event triggers when the input element is blurred.

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
<td class="description last">Event parameters from TimePicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the focusout event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-focusout="Focusout" />
<script>
function Focusout(args) {}
</script>{% endhighlight %}


{% highlight html %} 
<input id="timepicker" data-role="none" />
//select focusOut for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ focusout:"Focusout" });
});
function focusout(args) {}                       
</script>                  {% endhighlight %}







### load
{:#events:load}








Event triggers when the control is loaded.

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
<td class="description last">Event parameters from timepicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Timepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the Timepicker state</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the select event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-load="Load" />
<script>
function Load(args) {}
</script>{% endhighlight %}


{% highlight html %} 
//load event for TimePicker            
<input id="timepicker" data-role="none" />
            
<script>
$(function(){
$("#timepicker").ejmTimePicker({ load:"Load" });
});
function Load(args) {}                       
</script>           {% endhighlight %}







### open
{:#events:open}








Event triggers when the control is opened.

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
<td class="description last">Event parameters from TimePicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the open event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-open="Open" />
<script>
function Open(args) {}
</script>{% endhighlight %}


{% highlight html %} 
<input id="timepicker" data-role="none" />
//select open for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ open:"Open" });
});
function Open(args) {}                       
</script>                  {% endhighlight %}







### select
{:#events:select}








Event triggers when the time is selected.

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
<td class="description last">Event parameters from timepicker
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
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the timepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the timepicker state</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
//Bind the select event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-select="Select" />
<script>
function Select(args) {}
</script>{% endhighlight %}


{% highlight html %} 
//select event for TimePicker
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ select:"Select" });
});
function Select(args) {}                       
</script>            {% endhighlight %}




