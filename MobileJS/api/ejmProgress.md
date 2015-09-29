---
layout: post
title: ejmProgress | API Reference | Mobile JS | Syncfusion
description: 
documentation: API
platform: Mobilejs
keywords: ejmProgress, API, Essential Studio JS Autocomplete (Mobile)
---

# ejmProgress

Custom Design for Html Progressbar control.

$(element).ejmProgress<span class="signature">()</span>

#### Example


{% highlight html %} 
<div id="progress" ></div>
<script> 
// Create progressbar  
$("#progress").ejmProgress(); 
</script>{% endhighlight %}


{% highlight html %} 
<div id="progress" data-role="ejmprogress" ></div>
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


### enableCustomText`bool`
{:#members:enablecustomtext}


Specifies whether to accept custom text or not.

#### Default Value

* false


#### Example


{% highlight html %} 
//Set the enableCustomText property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-enablecustomtext=false ></div>
{% endhighlight %}


{% highlight html %} 
// Set enable custom text on initialization. 
//To set enable custom text API value 
<div id="progress" ></div>
<script> 
// Create progressbar  
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ enableCustomText: false });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enable custom text, after initialization:
// Get the enable custom text API value.                
 $("#progress").ejmProgress ("option", "enableCustomText");                     
// Set the enable custom text API
$("#progress").ejmProgress ("option", "enableCustomText", false);            {% endhighlight %}







### enabled`bool`
{:#members:enabled}








Specifies whether the control is enabled or disabled.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-enabled=true ></div>
{% endhighlight %}


{% highlight html %} 
// Set enabled on initialization. 
//To set enabled API value 
<div id="progress" ></div>
<script> 
// Create progressbar  
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ enabled: false});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
 $("#progress").ejmProgress ("option", "enabled");                      
// Set the enabled API
$("#progress").ejmProgress ("option", "enabled", true);            {% endhighlight %}







### enablePersistence`bool`
{:#members:enablepersistence}








Saves current model value to browser cookies for state maintainance. While refreshing the page it retains the model value and applies from browser cookies.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-enablepersistence=false ></div>
{% endhighlight %}


{% highlight html %} 
// Set progressbar enablePersistence on initialization. 
//To set enablePersistence API value 
<div id="progress" ></div>
<script> 
// Create progressbar  
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ enablePersistence: false });
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#progress").ejmProgress ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#progress").ejmProgress ("option", "enablePersistence", false);            {% endhighlight %}







### height`int`
{:#members:height}








Specifies the Height.




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the height property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-height=10 ></div>
{% endhighlight %}


{% highlight html %} 
// Set height on initialization. 
//To set height API value
<div id="progress" ></div>
<script>   
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ height: 10 });
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the height, after initialization:
// Get the height API value.            
 $("#progress").ejmProgress ("option", "height");                       
// Set the height API
$("#progress").ejmProgress ("option", "height", 10);            {% endhighlight %}







### incrementStep`int`
{:#members:incrementstep}








Specifies the value to be added in each step of increment.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the incrementStep property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-incrementstep=2 ></div>
{% endhighlight %}


{% highlight html %} 
// Set incrementStep on initialization. 
//To set incrementStep API value 
<div id="progress" ></div>
<script>             
$("#progress").ejmProgress ({ incrementStep: 2 });
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the incrementStep, after initialization:
// Get the incrementStep API value.             
 $("#progress").ejmProgress ("option", "incrementStep");                        
// Set the incrementStep API
$("#progress").ejmProgress ("option", "incrementStep", 2);            {% endhighlight %}







### maxValue`int`
{:#members:maxvalue}








Specifies the maximum value.




#### Default Value






* 100








#### Example


{% highlight html %} 
//Set the maxValue property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-maxvalue=90 ></div>
{% endhighlight %}


{% highlight html %} 
// Set maxValue on initialization. 
//To set maximum API value 
<div id="progress" ></div>
<script>  
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ maxValue: 90 });
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the maxValue, after initialization:
// Get the maximum API value.           
 $("#progress").ejmProgress ("option", "maxValue");                     
// Set the maxValue API
$("#progress").ejmProgress ("option", "maxValue", 90);            {% endhighlight %}







### minValue`int`
{:#members:minvalue}








specifies the minimum value.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the minValue property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-minvalue=10 ></div>
{% endhighlight %}


{% highlight html %} 
// Set minValue on initialization. 
//To set minimum API value
<div id="progress" ></div>
<script>  
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ minValue: 10 });
</script>                         {% endhighlight %}


{% highlight html %} 
//Get or set the minValue, after initialization:
// Get the minimum API value.
 $("#progress").ejmProgress ("option", "minValue");                     
// Set the minValue API
$("#progress").ejmProgress ("option", "minValue", 10);            {% endhighlight %}







### orientation`enum`
{:#members:orientation}








Specifies the orientation whether it is horizontal or vertical. See <a href="global.html#Orientation">Orientation</a>




#### Default Value






* ej.mobile.Progress.Orientation.Horizontal








#### Example


{% highlight html %}//Set the orientation property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-orientation="horizontal" ></div>
{% endhighlight %}


{% highlight html %} 
// Set orientation on initialization. 
//To set orientation API value 
<div id="progress" ></div>
<script> 
$(function(){
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ orientation: ej.mobile.Progress.Orientation.Horizontal });
});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the orientation, after initialization:
// Get the orientation API value.               
 $("#progress").ejmProgress ("option", "orientation");                  
// Set the orientation API
$("#progress").ejmProgress ("option", "orientation", ej.mobile.Progress.Orientation.Horizontal);            {% endhighlight %}







### percentage`int`
{:#members:percentage}








Specifies the initial value in percentage.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the percentage property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-percentage=35 ></div>
{% endhighlight %}


{% highlight html %} 
// Set percentage on initialization. 
//To set percentage API value
<div id="progress" ></div>
<script>   
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ percentage: 35 });
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the percentage, after initialization:
// Get the percentage API value.                
 $("#progress").ejmProgress ("option", "percentage");                   
// Set the percentage API
$("#progress").ejmProgress ("option", "percentage", 35);            {% endhighlight %}







### renderMode`enum`
{:#members:rendermode}








Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-rendermode="auto" ></div>
{% endhighlight %}


{% highlight html %} 
// Set renderMode on initialization. 
//To set renderMode API value 
<div id="progress" ></div>
<script> 
$(function(){
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ renderMode: ej.mobile.RenderMode.Auto });
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.        
<div id="progress" ></div>
<script> 
 $("#progress").ejmProgress ("option", "renderMode");                   
// Set the renderMode API
$("#progress").ejmProgress ("option", "renderMode", ej.mobile.RenderMode.Auto);            {% endhighlight %}







### text`string`
{:#members:text}








Applies custom text to notify it's current actions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the text property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-enablecustomtext=true data-ej-text="in-progress" ></div>
{% endhighlight %}


{% highlight html %} 
// Set text on initialization. 
//To set text API value 
<div id="progress" ></div>
<script> 
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ enableCustomText: true });
$("#progress").ejmProgress ({ text: "in-progress" });                   
</script> {% endhighlight %}


{% highlight html %} 
//Get or set the text, after initialization:
// Get the text API value.              
 $("#progress").ejmProgress ("option", "text");                 
// Set the text API
$("#progress").ejmProgress ("option", "text", "in-progress");            {% endhighlight %}







### theme`enum`
{:#members:theme}








Specifies the theme.See <a href="global.html#Theme">Theme</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-theme="auto" ></div>
{% endhighlight %}


{% highlight html %} 
// Set progressbar theme on initialization. 
//To set theme API value 
<div id="progress" ></div>
<script> 
// Create progressbar 
$(function(){
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ theme: ej.mobile.Theme.Auto });
});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#progress").ejmProgress ("option", "theme");                        
// Set the theme API
$("#progress").ejmProgress ("option", "theme", ej.mobile.Theme.Auto);            {% endhighlight %}







### value`int`
{:#members:value}








Specifies the initial value.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the value property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-value=35 ></div>
{% endhighlight %}


{% highlight html %} 
// Set value on initialization. 
//To set value API value 
<div id="progress" ></div>
<script>   
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ value: 35 });
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the value, after initialization:
// Get the value API value.                                                
$("#progress").ejmProgress ("option", "value");           
// Set the value API
$("#progress").ejmProgress ("option", "value", 35);            {% endhighlight %}







### width`int`
{:#members:width}








Specifies the width.




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the width property in unobtrusive way.
<div id="progress" data-role="ejmprogress" data-ej-width=350 ></div>
{% endhighlight %}


{% highlight html %} 
// Set width on initialization. 
//To set width API value 
<div id="progress" ></div>
<script> 
$("#progress").ejmProgress(); 
$("#progress").ejmProgress ({ width: 350 });    
</script> {% endhighlight %}


{% highlight html %} 
//Get or set the width, after initialization:
// Get the width API value.             
 $("#progress").ejmProgress ("option", "width");                        
// Set the width API
$("#progress").ejmProgress ("option", "width", 350);            {% endhighlight %}





## Methods








### getPercentage`()`
{:#methods:getpercentage}








Get current value in percentage





#### Example


{% highlight html %} 
<div id="progress"></div>
<script>
// Create progressbar
var progress = $("#progress").data("ejmProgress");
progress.getPercentage(); // returns the progressbar current percent value
</script>{% endhighlight %}


{% highlight html %} 
<div id="progress"></div>
<script>
// Get the current percent value
$("#progress").ejmProgress("getPercentage");    
</script>{% endhighlight %}







### getValue`()`
{:#methods:getvalue}








Gets the currentvalue.





#### Example


{% highlight html %} 
<div id="progress"></div>
<script>
// Create progressbar
var progress = $("#progress").data("ejmProgress");
progress.getValue(); // returns the progressbar current value
</script>{% endhighlight %}


{% highlight html %} 
<div id="progress"></div>
<script>
// Get the current value
$("#progress").ejmProgress("getValue"); 
</script>{% endhighlight %}







### setCustomText`()`
{:#methods:setcustomtext}








Set the custom text on each action conplete.





#### Example


{% highlight html %} 
<div id="progress"></div>
<script>
// Create progressbar
var progress = $("#progress").data("ejmProgress");
progress.setCustomText("Downloading.."); // Set the progressbar custom text
</script>{% endhighlight %}


{% highlight html %} 
<div id="progress"></div>
<script>
// Set the custom text
$("#progress").ejmProgress("setCustomText", "Downloading..");   
</script>{% endhighlight %}





## Events








### change
{:#events:change}








Event triggers when the value change happens.

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
<td class="description last">event parameters from progressbar
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
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the progressbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="progress" data-role="ejmprogress" data-ej-change="onChange"></div>
<script> 
// change event   
function onChange(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//change event 
<div id="progress"></div>
<script> 
$("#progress").ejmProgress({
  change: function (args) { //handle the event 
}
});  
</script>{% endhighlight %}







### complete
{:#events:complete}








Event triggers when the complete happens.

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
<td class="description last">event parameters from progressbar
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
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the progressbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="progress" data-role="ejmprogress" data-ej-complete="onComplete"></div>
<script> 
// complete event 
function onComplete(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="progress"></div>
<script> 
//complete event 
$("#progress").ejmProgress({
  complete: function (args) { //handle the event
}
}); 
</script>{% endhighlight %}







### create
{:#events:create}








Event triggers when the create happens.

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
<td class="description last">event parameters from progressbar
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
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the progressbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="progress" data-role="ejmprogress" data-ej-create="onCreate"></div>
<script> 
// Create event   
function onCreate(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//create event 
<div id="progress"></div>
<script> 
$("#progress").ejmProgress({
  create: function (args) { //handle the event 
}
}); 
</script>{% endhighlight %}







### start
{:#events:start}








Event triggers when the start happens.

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
<td class="description last">event parameters from progressbar
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
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the progressbar model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %} 
<div id="progress" data-role="ejmprogress" data-ej-start="onStart"></div>
<script> 
// start event 
function onStart(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//start event 
<div id="progress"></div>
<script> 
$("#progress").ejmProgress({
  start: function (args) { //handle the event 
}
});  
</script>{% endhighlight %}




