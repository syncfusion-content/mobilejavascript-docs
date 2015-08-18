---
layout: post
title: ejmDatePicker
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html DatePicker control.










$(element).ejmDatePicker<span class="signature">()</span>











Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script> 
// Create DatePicker  
$("#datepicker").ejmDatePicker(); 
</script>{% endhighlight %}







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


* module:ej.mobile.header


* module:ej.mobile.dialog


* module:ej.mobile.button


* module:ej.mobile.toolbar


* module:ej.mobile.scrollpanel


* module:ej.mobile.scrollbar




## Members








### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}








Sets the root class for DatePicker theme. This cssClass API helps to use custom skinning option for DatePicker control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
//Set the cssClass property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-cssclass="customclass" />
{% endhighlight %}


{% highlight html %} 
// Set the cssClass on initialization. 
//To set cssClass API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ cssClass: "customclass" });            
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
 $("#datepicker").ejmDatePicker("option", "cssClass");                  
// Set the enablePersistence API
$("#datepicker").ejmDatePicker("option", "cssClass", "customclass");            {% endhighlight %}







### culture<span class="type-signature type string">string</span>
{:#members:culture}








Specifies the localization culture to be used.




Default Value:
{:.param}






* "en-US"








Example
{:.example}


{% highlight html %} 
//Set the culture property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-culture="en-US" />
{% endhighlight %}


{% highlight html %} 
// Set the culture on initialization. 
//To set culture API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ culture: "en-US" });           
});
</script>                         {% endhighlight %}


{% highlight html %} 
//Get or set the culture, after initialization:
// Get the culture API value.           
 $("#datepicker").ejmDatePicker("option", "culture");                   
// Set the culture API
$("#datepicker").ejmDatePicker("option", "culture", "en-US");            {% endhighlight %}







### dateFormat<span class="type-signature type string">string</span>
{:#members:dateformat}








Specifies the date format.




Default Value:
{:.param}






* null








Example
{:.example}


{% highlight html %} 
//Set the dateFormat property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-dateformat="MMMM dd, yyyy" />
{% endhighlight %}


{% highlight html %} 
// Set the dateFormat on initialization. 
//To set dateFormat API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ dateFormat: "MMMM dd, yyyy" });                
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the dateFormat, after initialization:
// Get the dateFormat API value.                
 $("#datepicker").ejmDatePicker("option", "dateFormat");                        
// Set the dateFormat API
$("#datepicker").ejmDatePicker("option", "dateFormat", "MM/dd/yyyy");            {% endhighlight %}







### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}








Specifies whether to enable or disbale the control.




Default Value:
{:.param}






* true








Example
{:.example}


{% highlight html %} 
//Set the enabled property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-enabled=false />
{% endhighlight %}


{% highlight html %} 
// Set the enabled on initialization. 
//To set enabled API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ enabled: false });             
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
 $("#datepicker").ejmDatePicker("option", "enabled");                   
// Set the enabled API
$("#datepicker").ejmDatePicker("option", "enabled", false);            {% endhighlight %}







### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}








Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the enablePersistence property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-enablepersistence=true />
{% endhighlight %}


{% highlight html %} 
// Set the enablePersistence on initialization. 
//To set enablePersistence API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ enablePersistence: true });            
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#datepicker").ejmDatePicker("option", "enablePersistence");                 
// Set the enablePersistence API
$("#datepicker").ejmDatePicker("option", "enablePersistence", true);            {% endhighlight %}







### ios7
{:#members:ios7}








Section for ios7 rendermode specific functionalities.











### ios7.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:ios7-renderdefault}








Specifies whether to use ios7 native datepicker or not.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
// Set the ios7 mode renderDefault property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-rendermode="ios7" data-ej-ios7-renderdefault=true />
{% endhighlight %}


{% highlight html %} 
// To set ios7 mode renderDefault property API value
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ renderMode:"ios7", ios: {renderDefault: true }});              
});
</script>                  {% endhighlight %}


{% highlight html %}// Get or set the ios7 mode renderDefault API, after initialization:
// Get the ios7 mode renderDefault value  
$("#datepicker").ejmDatePicker("option", "ios7.renderDefault");                 
// Set the ios7 mode renderDefault value 
$("#datepicker").ejmDatePicker("option", "ios7.renderDefault", true); {% endhighlight %}







### maxDate<span class="type-signature type string">string</span>
{:#members:maxdate}








Specifies the maximum selectable date.




Default Value:
{:.param}






* "12/31/2030"








Example
{:.example}


{% highlight html %} 
//Set the maxDate property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-maxdate="12/31/2030" />
{% endhighlight %}


{% highlight html %} 
// Set the maxDtae on initialization. 
//To set maxDate API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ maxDate: "12/31/2030" });              
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the maxDate, after initialization:
// Get the maxDate API value.           
 $("#datepicker").ejmDatePicker("option", "maxDate");                   
// Set the maxDate API
$("#datepicker").ejmDatePicker("option", "maxDate", "31/12/2030");            {% endhighlight %}







### minDate<span class="type-signature type string">string</span>
{:#members:mindate}








Specifies the minimum selectable date.




Default Value:
{:.param}






* "01/01/2000"








Example
{:.example}


{% highlight html %} 
//Set the minDate property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-mindate="01/01/2000" />
{% endhighlight %}


{% highlight html %} 
// Set the minDate on initialization. 
//To set minDate API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ minDate: "01/01/2000" });              
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the minDate, after initialization:
// Get the minDate API value.           
 $("#datepicker").ejmDatePicker("option", "minDate");                   
// Set the minDate API
$("#datepicker").ejmDatePicker("option", "minDate", "01/01/2000");            {% endhighlight %}







### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}








Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the renderMode property in Unobtrusive way.
<input  id="datepicker" type="date" data-role="ejmdatepicker" data-ej-rendermode="android" />
{% endhighlight %}


{% highlight html %} 
// Set the renderMode on initialization. 
//To set renderMode API value 
<input  id="datepicker" type="date"/>
                 
<script>
$(function(){
$("#datepicker").ejmDatePicker({ renderMode: "android" });              
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
 $("#datepicker").ejmDatePicker("option", "renderMode");                        
// Set the renderMode API
$("#datepicker").ejmDatePicker("option", "renderMode", "android" );            {% endhighlight %}







### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Specifies the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the theme property in Unobtrusive way.
<input  id="datepicker" type="date" data-role="ejmdatepicker" data-ej-theme="auto" />
{% endhighlight %}


{% highlight html %} 
// Set the theme on initialization. 
//To set theme API value 
<input  id="datepicker" type="date"/>
                 
<script>
$(function(){
$("#datepicker").ejmDatePicker({ theme: "auto" });              
});
</script>                                 {% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#datepicker").ejmDatePicker("option", "theme");                     
// Set the theme API
$("#datepicker").ejmDatePicker("option", "theme", "auto" );            {% endhighlight %}







### value<span class="type-signature type string">string</span>
{:#members:value}








Specifies the value.




Default Value:
{:.param}






* new Date().toString()








Example
{:.example}


{% highlight html %} 
//Set the value property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-value="04/23/2010" />
{% endhighlight %}


{% highlight html %} 
// Set the value on initialization. 
//To set value API value 
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ value: "04/23/2010" });                
});
</script>                         {% endhighlight %}


{% highlight html %} 
//Get or set the value, after initialization:
// Get the value API value.             
 $("#datepicker").ejmDatePicker("option", "value");                     
// Set the value API
$("#datepicker").ejmDatePicker("option", "value", "04/23/2010");            {% endhighlight %}







### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}








Specifies whether to render the DatePicker based on the windowsphone's current theme or not.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
// Set the windows mode renderDefault property in Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-rendermode="windows" data-ej-windows-renderdefault=true />
{% endhighlight %}


{% highlight html %} 
// To set windows mode renderDefault property API value
<input id="datepicker" data-role="none"/>
             
<script>
$(function(){
$("#datepicker").ejmDatePicker({ renderMode:"windows", windows: { renderDefault: true }});              
});
</script>                          {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#datepicker").ejmDatePicker("option", "windows.renderDefault");                      
// Set the windows mode renderDefault value 
$("#datepicker").ejmDatePicker("option", "windows.renderDefault", true); {% endhighlight %}





## Methods








### disable<span class="signature">()</span>
{:#methods:disable}








To disable the datpicker





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.disable();
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
// changes the DatePicker current state to disabled     
$(function(){
$("#datepicker").ejmDatePicker("disable");      
});
</script>{% endhighlight %}







### enable<span class="signature">()</span>
{:#methods:enable}








To enable the datepicker





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.enable();
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// change the DatePicker current state to enabled       
$("#datepicker").ejmDatePicker("enable");
});
</script>{% endhighlight %}







### getValue<span class="signature">()</span>
{:#methods:getvalue}








Get the current value.





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.getValue();
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
// get the DatePicker current value             
$(function(){
$("#datepicker").ejmDatePicker("getValue");     
});
</script>{% endhighlight %}







### hide<span class="signature">()</span>
{:#methods:hide}








To hide the DatePicker control





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.hide();
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
$("#datepicker").ejmDatePicker("hide");
});
</script>{% endhighlight %}







### setCurrentDate<span class="signature">()</span>
{:#methods:setcurrentdate}








Set the given date.





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.setCurrentDate("12/31/2000");
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
// get the DatePicker current value             
$(function(){
$("#datepicker").ejmDatePicker("setCurrentDate", "12/31/2000");
});
</script>         {% endhighlight %}







### show<span class="signature">()</span>
{:#methods:show}








To show the DatePicker control





Example
{:.example}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
// Create DatePicker
var dpObj = $("#datepicker").data("ejmDatePicker");
dpObj.show();
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="ejmdatepicker"/>
<script>
$(function(){
$("#datepicker").ejmDatePicker("show"); 
});
</script>{% endhighlight %}





## Events








### change
{:#events:change}








Event triggers when the value is changed while interaction.

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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the change event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-change="change" />
<script>
function change(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//change event for DatePicker
$("#datepicker").ejmDatePicker({
   change: function (args) {* //handle the event 
}
});
</script>                 {% endhighlight %}







### close
{:#events:close}








Event triggers when the control is closed after interaction.

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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the close event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-close="close" />
<script>
function close(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//close event for DatePicker
$("#datepicker").ejmDatePicker({
   close: function (args) {* //handle the event 
}
});
</script>                 {% endhighlight %}







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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the focusin event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-focusin="focusin" />
<script>
function focusin(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//focusIn event for DatePicker
$("#datepicker").ejmDatePicker({
   focusIn: function (args) { * //handle the event 
}
});
</script>                 {% endhighlight %}







### focusOut
{:#events:focusout}








Event triggers when the input element is focusedout or blurred.

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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the focusout event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-focusout="focusout" />
<script>
function focusout(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//focusOut event for DatePicker
$("#datepicker").ejmDatePicker({
   focusOut: function (args) {* //handle the event 
}
}); 
</script>                 {% endhighlight %}







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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the load event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-load="load" />
<script>
function load(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//load event for DatePicker
$("#datepicker").ejmDatePicker({
   load: function (args) {* //handle the event 
}
}); 
</script>                 {% endhighlight %}







### open
{:#events:open}








Event triggers when the control is opened for selection.

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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the open event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-open="open" />
<script>
function open(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//open event for DatePicker
$("#datepicker").ejmDatePicker({
   open: function (args) {* //handle the event 
}
});
</script>                 {% endhighlight %}







### select
{:#events:select}








Event triggers when date value is selected.

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
<td class="description last">Event parameters from datepicker
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
<td class="description last">returns the datepicker model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the datepicker value</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}


{% highlight html %} 
//Bind the select event using Unobtrusive way.
<input id="datepicker" data-role="ejmdatepicker" data-ej-select="select" />
<script>
function select(){}
</script>{% endhighlight %}


{% highlight html %} 
<input id="datepicker" data-role="none"/>
<script>
//select event for DatePicker
$("#datepicker").ejmDatePicker({
   select: function (args) { * //handle the event 
}
}); 
</script>                 {% endhighlight %}




