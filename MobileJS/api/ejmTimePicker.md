---
layout: post
title: ejmTimePicker
documentation: API
platform: js
metaname: 
metacontent: 
---

# Custom Design for Html TimePicker control.










$(element).ejmTimePicker<span class="signature">()</span>











Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
<script>  
$(function(){
$("#timepicker").ejmTimePicker(); 
});
</script></code>
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


* module:ej.mobile.dialog


* module:ej.mobile.button


* module:ej.mobile.toolbar


* module:ej.mobile.scrollbar


* module:ej.mobile.scrollpanel




## Members








### cssClass<span class="type-signature type string">string</span>








Sets the root class for TimePicker theme. This cssClass API helps to use custom skinning option for TimePicker control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-cssclass="customclass" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the cssClass on initialization. 
//To set cssClass API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ cssClass: "customclass" });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
 $("#TimePicker").ejmTimePicker("option", "cssClass");                  
// Set the cssClass API
$("#TimePicker").ejmTimePicker("option", "cssClass", "customclass");            </code>
</pre>






### enabled<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the control on initialization.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enabled property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-enabled=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enabled on initialization. 
//To set enabled API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ enabled: true });      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
 $("#timepicker").ejmTimePicker("option", "enabled");                   
// Set the enabled API
$("#timepicker").ejmTimePicker("option", "enabled", true);            </code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>








Current model value to browser cookies for state maintains. While refresh the page retains the model value apply from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enablePersistence property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-enablepersistence=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
//To set enablePersistence API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ enablePersistence: true });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#TimePicker").ejmTimePicker("option", "enablePersistence");                 
// Set the enablePersistence API
$("#TimePicker").ejmTimePicker("option", "enablePersistence", true);            </code>
</pre>






### hourFormat<span class="type-signature type enum">enum</span>








Specifies the hour format See <a href="global.html#HourFormat">HourFormat</a>.




Default Value:
{:.param}






* "twentyfour"








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the hourFormat property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-hourformat="twentyfour" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the hourFormat on initialization. 
//To set hourFormat API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ hourFormat: "twentyfour" });                   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the hourFormat, after initialization:
// Get the hourFormat API value.                
 $("#timepicker").ejmTimePicker("option", "hourFormat");                        
// Set the hourFormat API
$("#timepicker").ejmTimePicker("option", "hourFormat", "twentyfour");            </code>
</pre>






### ios7








Section for ios7 rendermode specific functionalities.











### ios7.renderDefault<span class="type-signature type boolean">boolean</span>








Specifies whether to use ios7 native timepicker or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the ios7 mode renderDefault property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="ios7" data-ej-ios7-renderdefault="false" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set ios7 mode renderDefault property API value 
<input id="timepicker" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "ios7", ios7: { renderDefault: false } });          
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 mode renderDefault API, after initialization:
// Get the ios7 mode renderDefault value  
$("#timepicker").ejmTimePicker("option", "ios7.renderDefault");                 
// Set the ios7 mode renderDefault value 
$("#timepicker").ejmTimePicker("option", "ios7.renderDefault", false); </code>
</pre>






### renderMode<span class="type-signature type enum">enum</span>








Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="auto" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the renderMode on initialization. 
//To set renderMode API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "auto" });                 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
 $("#timepicker").ejmTimePicker("option", "renderMode");                        
// Set the renderMode API
$("#timepicker").ejmTimePicker("option", "renderMode", "auto");            </code>
</pre>






### theme<span class="type-signature type enum">enum</span>








Changes the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-theme="auto" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
//To set theme API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ theme: "auto" });                      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#timepicker").ejmTimePicker("option", "theme");                     
// Set the theme API
$("#timepicker").ejmTimePicker("option", "theme", "auto");            </code>
</pre>






### timeFormat<span class="type-signature type string">string</span>








Specifies the time format.




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the timeFormat property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-hourformat="twelve" data-ej-timeformat="hh:mm tt" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the timeFormat on initialization. 
//To set timeFormat API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ hourFormat: "twelve", timeFormat: "hh:mm tt" });                       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the timeFormat, after initialization:
// Get the timeFormat API value.                
 $("#timepicker").ejmTimePicker("option", "timeFormat");                        
// Set the timeFormat API
$("#timepicker").ejmTimePicker("option", "timeFormat", "hh:mm tt");            </code>
</pre>






### value<span class="type-signature type string">string</span>








Specifies the value.




Default Value:
{:.param}






* new Date().ToString()








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the value property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-value="02:20 PM" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the value on initialization. 
//To set value API value 
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ value: "02:20 PM" });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the value, after initialization:
// Get the value API value.             
 $("#timepicker").ejmTimePicker("option", "value");                     
// Set the value API
$("#timepicker").ejmTimePicker("option", "value", "02:20 PM");            </code>
</pre>






### windows








Section for windows rendermode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>








Specifies whether to render the control based on the windowsphone's current theme or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the windows mode renderDefault property in Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-rendermode="windows" data-ej-windows-renderdefault="false" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set windows mode renderDefault property API value 
<input id="timepicker" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ renderMode: "windows", windows: { renderDefault: false } });            
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#timepicker").ejmTimePicker("option", "windows.renderDefault");                      
// Set the windows mode renderDefault value 
$("#timepicker").ejmTimePicker("option", "windows.renderDefault", false); </code>
</pre>




## Methods








### disable<span class="signature">()</span>








To handle the TimePicker control disabled state





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.disable(); 
});
</script>                </code>
</pre>






### enable<span class="signature">()</span>








To handle the TimePicker control enabled state





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.enable(); 
});
</script>        </code>
</pre>






### getValue<span class="signature">()</span>








To change the TimePicker control to disabled state





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var dpObj = $("#timepicker").data("ejmTimePicker");
dpObj.getValue();
});
</script>         </code>
</pre>






### hide<span class="signature">()</span>








To hide the TimePicker control





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.hide(); 
});
</script>        </code>
</pre>






### setCurrentTime<span class="signature">()</span>








To change the TimePicker control to disabled state





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
$(function(){
// Create TimePicker instance
var dpObj = $("#timepicker").data("ejmTimePicker");
dpObj.setCurrentTime("05:20");
});
</script>        </code>
</pre>






### show<span class="signature">()</span>








To show the TimePicker control





Example
{:.example}

<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="ejmtimepicker"/>
<script>
// Create TimePicker instance
$(function(){
var tpObj = $("#timepicker").data("ejmTimePicker");
tpObj.show(); 
});
</script>        </code>
</pre>




## Events








### change








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
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
//Bind the change event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-change="Change" />
<script>
function Change(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
//select change for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ change:"Change" });
});
function Change(args) {}                       
</script>                  </code>
</pre>






### close








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
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
//Bind the close event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-close="Close" />
<script>
function Close(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
//select close for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ close:"Close" });
});
function Close(args) {}                       
</script>                  </code>
</pre>






### focusIn








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
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
//Bind the focusin event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-focusin="Focusin" />
<script>
function Focusin(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
//select focusIn for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ focusin:"Focusin" });
});
function Focusin(args) {}                       
</script>                  </code>
</pre>






### focusOut








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
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
//Bind the focusout event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-focusout="Focusout" />
<script>
function Focusout(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
//select focusOut for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ focusout:"Focusout" });
});
function focusout(args) {}                       
</script>                  </code>
</pre>






### load








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Timepicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the Timepicker state</td>
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
//Bind the select event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-load="Load" />
<script>
function Load(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//load event for TimePicker            
<input id="timepicker" data-role="none" />
            
<script>
$(function(){
$("#timepicker").ejmTimePicker({ load:"Load" });
});
function Load(args) {}                       
</script>           </code>
</pre>






### open








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the TimePicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">return the TimePicker value</td>
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
//Bind the open event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-open="Open" />
<script>
function Open(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="timepicker" data-role="none" />
//select open for TimePicker
<script>
$(function(){
$("#timepicker").ejmTimePicker({ open:"Open" });
});
function Open(args) {}                       
</script>                  </code>
</pre>






### select








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the timepicker model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the timepicker state</td>
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
//Bind the select event using Unobtrusive way.
<input id="timepicker" data-role="ejmtimepicker" data-ej-select="Select" />
<script>
function Select(args) {}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//select event for TimePicker
<input id="timepicker" data-role="none" />
<script>
$(function(){
$("#timepicker").ejmTimePicker({ select:"Select" });
});
function Select(args) {}                       
</script>            </code>
</pre>



