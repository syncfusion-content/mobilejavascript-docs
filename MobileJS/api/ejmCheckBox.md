---
layout: post
title: ejmCheckBox | API Reference | Mobile JS | Syncfusion
description: 
documentation: API
platform: Mobilejs
keywords: ejmCheckBox, API, Essential Studio JS Autocomplete (Mobile)
---

# ejmCheckBox

Custom Design for Html CheckBox control.

$(element).ejmCheckBox<span class="signature">()</span>

#### Example

{% highlight html %} 
// Create checkbox control in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" />
{% endhighlight %}

{% highlight html %} 
// Render checkbox on initialization
<input type="checkbox" id="chkbox" />
<script>  
$("#chkbox").ejmCheckBox(); 
</script>{% endhighlight %}

#### Requires

* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

## Members

### checked`boolean`
{:#members:checked}

Specifies whether to check the control.

#### Default Value

* false

#### Example

{% highlight html %} 
//Set the checked property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-checked=false />
{% endhighlight %}

{% highlight html %} 
// To set checked API value during initialization  
<input type="checkbox" id="chkbox" />
<script>  
 $("#chkbox").ejmCheckBox({ checked:  true });                                  
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the check API, after initialization:
//Get the checked value  
$("#chkbox").ejmCheckBox("option", "checked");
			  
//Set the checked value 
$("#chkbox").ejmCheckBox("option", "checked",  false );  {% endhighlight %}

### checkState`enum`
{:#members:checkstate}

Specifies the check CheckState of the control. See <a href="global.html#CheckState">CheckState</a>

#### Default Value

* ej.mobile.CheckBox.CheckState.Uncheck

#### Example

{% highlight html %} 
//Set the Checkstate property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-enabletristate=true data-ej-checkstate="indeterminate" />
{% endhighlight %}

{% highlight html %} 
//Set the Checkstate property on initialization.
<input type="checkbox" id="chkbox" />
<script>  
// To set Checkstate API value 
  $("#chkbox").ejmCheckBox({ enableTriState : true,checkState: ej.mobile.CheckBox.CheckState.Indeterminate });          
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the CheckState  API, after initialization
//Get the CheckState  value 
  $("#chkbox").ejmCheckBox("option", "checkState");     
// Set the CheckState  value 
  $("#chkbox").ejmCheckBox("option", "checkState", ej.mobile.CheckBox.CheckState.Indeterminate  ); {% endhighlight %}

### cssClass`string`
{:#members:cssclass}

Sets the root class for checkbox theme. This cssClass API helps to use custom skinning option for checkbox control. By defining the root class using this API, we need to include this root class in CSS.

#### Default Value

* ""

#### Example

{% highlight html %} 
// Set the cssClass property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-cssclass="customclass" />
{% endhighlight %}


{% highlight html %}// Set checkbox cssClass on initialization. 
<input type="checkbox" id="chkbox" />
<script>  
// To set cssClass API value 
$("#chkbox").ejmCheckBox ({ cssClass: "customclass"});                  
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the checkbox cssClass, after initialization:
// Get the cssClass API value.          
 $("#chkbox").ejmCheckBox ("option", "cssClass");                       
// Set the cssClass API
$("#chkbox").ejmCheckBox ("option", "cssClass", "customclass");            {% endhighlight %}

### enabled`boolean`
{:#members:enabled}

Specifies whether to enable or disable the control.

#### Default Value

* true

#### Example

{% highlight html %} 
//Set the enabled property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-enabled=true />
{% endhighlight %}

{% highlight html %} 
//Set enabled property checkbox on initialization. 
<input type="checkbox" id="chkbox" />
<script>  
// To set enabled API value 
        $("#chkbox").ejmCheckBox ({ enabled: true });                   
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the checkbox state, after initialization:
// Get the enabled API value.           
        $("#chkbox").ejmCheckBox ("option", "enabled");                 
// Set the enabled API
        $("#chkbox").ejmCheckBox ("option", "enabled", true);{% endhighlight %}

### enablePersistence`boolean`
{:#members:enablepersistence}

Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.

#### Default Value

* false

#### Example

{% highlight html %} 
// Set the enablePersistence property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-enablepersistence=true />
{% endhighlight %}

{% highlight html %} 
// To set enablePersistence API value 
<input type="checkbox" id="chkbox" />
<script>  
  $("#chkbox").ejmCheckBox({ enablePersistence: true});          
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the enablePersistence API, after initialization:
// Get the enablePersistence value  
  $("#chkbox").ejmCheckBox("option", "enablePersistence");                      
// Set the enablePersistence value 
  $("#chkbox").ejmCheckBox("option", "enablePersistence", true ); {% endhighlight %}

### enableTriState`boolean`
{:#members:enabletristate}

Specifies whether to render the control with tri state behavior.

#### Default Value

* false

#### Example

{% highlight html %} 
//Set the enableTriState property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-enabletristate="true" data-ej-checkstate="indeterminate" />
{% endhighlight %}

{% highlight html %} 
//Set the enableTriState property on initialization.
<input type="checkbox" id="chkbox" />
<script>  
// To set enableTriState  API value 
  $("#chkbox").ejmCheckBox({ enableTriState : true, checkState:"indeterminate" });              
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the enableTriState  API, after initialization
//Get the  enableTriState  value 
  $("#chkbox").ejmCheckBox("option", "enableTriState"); 
// Set the  enableTriState  value 
  $("#chkbox").ejmCheckBox("option", "enableTriState", false  ); {% endhighlight %}

### preventDefault`boolean`
{:#members:preventdefault}

Specifies whether to prevent default actions in the control.

#### Default Value

* false

#### Example

{% highlight html %} 
// Set the preventDefault property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-preventdefault="false" />
{% endhighlight %}

{% highlight html %} 
// Set checkbox prevent default on initialization. 
<input type="checkbox" id="chkbox" />
<script>  
// To set preventDefault API value 
$("#chkbox").ejmCheckBox ({ preventDefault: false });                   
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the checkbox prevent default, after initialization:
// Get the preventDefault API value.            
 $("#chkbox").ejmCheckBox ("option", "preventDefault");                 
// Set the preventDefault API
$("#chkbox").ejmCheckBox ("option", "preventDefault", false);{% endhighlight %}

### renderMode`enum`
{:#members:rendermode}

Specifies the rendering mode of the control.See <a href="global.html#RenderMode">RenderMode</a>

#### Default Value

* auto

#### Example

{% highlight html %} 
// Set the renderMode property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-rendermode="auto" />
{% endhighlight %}

{% highlight html %}// Set checkbox rendermode on initialization. 
<input type="checkbox" id="chkbox" />
<script>  
// To set renderMode API value 
$("#chkbox").ejmCheckBox ({ renderMode: ej.mobile.RenderMode.Auto});                    
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the checkbox rendermode, after initialization:
// Get the renderMode API value.                
 $("#chkbox").ejmCheckBox ("option", "renderMode");                     
// Set the renderMode API
$("#chkbox").ejmCheckBox ("option", "renderMode", ej.mobile.RenderMode.Auto);            {% endhighlight %}

### text`string`
{:#members:text}

Specifies the text.

#### Default Value

* ""

#### Example

{% highlight html %} 
// Set the text property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-text="Checkbox" />
{% endhighlight %}

{% highlight html %} 
// To set text API value 
<input type="checkbox" id="chkbox" />
<script>  
  $("#chkbox").ejmCheckBox({ text: "Hello World"});              
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the text API, after initialization:
// Get the text value  
  $("#chkbox").ejmCheckBox("option", "text");                   
// Set the text value 
  $("#chkbox").ejmCheckBox("option", "text", "Hello World" ); {% endhighlight %}

### theme`enum`
{:#members:theme}

Specifies the theme.See <a href="global.html#Theme">Theme</a>

#### Default Value

* auto

#### Example

{% highlight html %} 
//Set the theme property in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-theme="auto" />
{% endhighlight %}

{% highlight html %} 
// Set checkbox theme on initialization. 
<input type="checkbox" id="chkbox" />
<script> 
// To set Theme API value 
  $("#chkbox").ejmCheckBox ({ theme: ej.mobile.Theme.Auto });                   
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the checkbox prevent default, after initialization:
// Get the theme API value.             
  $("#chkbox").ejmCheckBox ("option", "theme");                 
// Set the theme API
  $("#chkbox").ejmCheckBox ("option", "theme", ej.mobile.Theme.Auto);{% endhighlight %}

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
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-windows-renderDefault=false />
{% endhighlight %}

{% highlight html %} 
// To set windows mode renderDefault property API value 
<input type="checkbox" id="chkbox" />
<script>  
$("#chkbox").ejmCheckBox({ windows:{renderDefault: false}});             
</script>{% endhighlight %}

{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#chkbox").ejmCheckBox("option", "windows.renderDefault");                    
// Set the windows mode renderDefault value 
$("#chkbox").ejmCheckBox("option", "windows.renderDefault", false); {% endhighlight %}

## Methods

### isChecked`()`
{:#methods:ischecked}

To change the checked state.

#### Example

{% highlight html %} 
<input type="checkbox" id="chkbox"/>
<script>
// Create checkbox
$("#chkbox").ejmCheckBox();
var chkObj = $("#chkbox").data("ejmCheckBox");
chkObj.isChecked(); // returns the checkbox current state
</script>{% endhighlight %}

{% highlight html %} 
<input type="checkbox" id="chkbox" />
<script>
// get the checkbox current state
$("#chkbox").ejmCheckBox();
$("#chkbox").ejmCheckBox("isChecked");  
</script>{% endhighlight %}

## Events

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
<td class="description last">Event parameters from CheckBox.
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
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current element associated value.</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the status of the control.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>

#### Example

{% highlight html %} 
// Define the touchend event in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-touchend="touchend" />
<script> 
// touchEnd event for checkbox 
function touchend(args){ 
//handle the event
}
</script>{% endhighlight %}

{% highlight html %}  
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" />
// touchEnd event for checkbox
* <script>
$("#chkbox").ejmCheckBox({
  touchEnd: function (args) { 
//handle the event 
}
});           
* </script>{% endhighlight %}

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
<td class="description last">Event parameters from CheckBox.
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
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current element associated value.</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the status of the control.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>

#### Example

{% highlight html %} 
// Define the touchstart event in unobtrusive way.
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" data-ej-touchstart="touchstart" />
<script> 
// touchStart event for checkbox 
function touchstart(args){ 
//handle the event 
}
</script>{% endhighlight %}

{% highlight html %}  
<input type="checkbox" id="chkbox" data-role="ejmcheckbox" />
// touchStart event for checkbox
* <script>
$("#chkbox").ejmCheckBox({
  touchStart: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}