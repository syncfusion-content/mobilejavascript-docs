---
layout: post
title: ejmToggleButton
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html ToggleButton control.










$(element).ejmToggleButton<span class="signature">()</span>











Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="togglebutton" ></div>
<script> 
// Create ToggleButton  
$("#togglebutton").ejmToggleButton(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
</code>
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




## Members








### animate<span class="type-signature type boolean">boolean</span>








Specifies the transition effect for state change.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the animate property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-animate=true></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set animate on initialization. 
//To set animate API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ animate:true });  
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton animate, after initialization:
// Get the animate API value.           
$("#togglebutton").ejmToggleButton ("option", "animate");                       
// Set the animate API
$("#togglebutton").ejmToggleButton ("option", "animate", true);            
</script></code>
</pre>






### cssClass<span class="type-signature type string">string</span>








Sets the root class for ToggleButton theme. This cssClass API helps to use custom skinning option for ToggleButton control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-cssclass="customclass"></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set cssClass on initialization. 
//To set cssClass API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ cssClass:"customclass" });  
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton cssClass, after initialization:
// Get the cssClass API value.          
$("#togglebutton").ejmToggleButton ("option", "cssClass");                      
// Set the cssClass API
$("#togglebutton").ejmToggleButton ("option", "cssClass", "customclass");            
</script></code>
</pre>






### enabled<span class="type-signature type boolean">boolean</span>








Specifies whether to enable or disable the control.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enabled property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-enabled=true></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set togglebutton enabled on initialization. 
//To set enabled API value 
<div id="togglebutton" ></div>
<script> 
$("#togglebutton").ejmToggleButton ({ enabled:true  }); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton enabled, after initialization:
// Get the enabled API value.           
 $("#togglebutton").ejmToggleButton ("option", "enabled");                      
// Set the enabled API
$("#togglebutton").ejmToggleButton ("option", "enabled", true);      
</script></code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>








Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enablePersistence property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-enablePersistence=false></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set togglebutton persistence on initialization. 
//To set enablePersistence API value 
<div id="togglebutton" ></div>
<script> 
$("#togglebutton").ejmToggleButton ({ enablePersistence:false  });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton persistence, after initialization:
// Get the enablePersistence API value.         
 $("#togglebutton").ejmToggleButton ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#togglebutton").ejmToggleButton ("option", "enablePersistence", false);  
</script></code>
</pre>






### renderMode<span class="type-signature type enum">enum</span>








Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-rendermode="auto"></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set togglebutton rendermode on initialization. 
//To set renderMode API value 
<div id="togglebutton" ></div>
<script>
$(function () {
$("#togglebutton").ejmToggleButton ({ renderMode:ej.mobile.RenderMode.Auto });  
});
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton rendermode, after initialization:
// Get the renderMode API value.                
 $("#togglebutton").ejmToggleButton ("option", "renderMode");                   
// Set the renderMode API
$("#togglebutton").ejmToggleButton ("option", "renderMode", ej.mobile.RenderMode.Auto);    
</script></code>
</pre>






### theme<span class="type-signature type enum">enum</span>








Specifies the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-theme="auto"></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set togglebutton theme on initialization. 
//To set theme API value 
<div id="togglebutton" ></div>
<script>
$(function () {
$("#togglebutton").ejmToggleButton ({ theme:ej.mobile.Theme.Auto });    
});
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton theme, after initialization:
// Get the theme API value.             
$("#togglebutton").ejmToggleButton ("option", "theme");                 
// Set the theme API
$("#togglebutton").ejmToggleButton ("option", "theme", ej.mobile.Theme.Auto);       
</script></code>
</pre>






### toggleState<span class="type-signature type boolean">boolean</span>








Specifies whether state is on or off.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the togglestate property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-togglestate=true></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set togglebutton togglestate on initialization. 
//To set togglestate API value 
<div id="togglebutton" ></div>
<script>
$("#togglebutton").ejmToggleButton ({ toggleState:true  });     
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the togglebutton togglestate, after initialization:
// Get the togglestate API value.               
$("#togglebutton").ejmToggleButton ("option", "toggleState");                   
// Set the togglestate API
$("#togglebutton").ejmToggleButton ("option", "toggleState", true);  
</script></code>
</pre>






### windows








Section for windows mode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>








Specifies whether to render control based on the windowsphone's current accent color and device theme.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-rendermode="windows" data-ej-windows-renderDefault=false></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="togglebutton" ></div>
<script>
// To set windows mode renderDefault property API value 
$(function () {
$("#togglebutton").ejmToggleButton({ renderMode:ej.mobile.RenderMode.Windows, windows.renderDefault: false});   
});
</script></code>
</pre>
<pre class="prettyprint">
<code><script>
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#togglebutton").ejmToggleButton("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#togglebutton").ejmToggleButton("option", "windows.renderDefault", false); 
</script></code>
</pre>




## Methods








### disable<span class="signature">()</span>








To disable the togglebutton.





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Get the instance of toggle button
var toggle = $("#togglebutton").data("ejmToggleButton");
toggle.disable(); // Disables the toggle button
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Disable togglebutton
$("#togglebutton").ejmToggleButton("disable");  
});
</script></code>
</pre>






### enable<span class="signature">()</span>








To enable the togglebutton.





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="togglebutton" data-role="ejmtogglebutton" ></div>
<script>
$(document).ready(function(){
// Get the instance of toggle button
var toggle = $("#togglebutton").data("ejmToggleButton");
toggle.enable(); // Enables the toggle button
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="togglebutton" data-role="ejmtogglebutton"></div>
<script>
$(document).ready(function(){
// Enable togglebutton
$("#togglebutton").ejmToggleButton("enable");   
});
</script></code>
</pre>




## Events








### change








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name"><code>state</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
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
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-change="onChange"></div>
<script> 
// Change event for toggleButton 
function onChange(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//change event for toggleButton
<div id="togglebutton"></div>
<script>
$("#togglebutton").ejmToggleButton({
change: function (args) { //handle the event
}
});  
</script></code>
</pre>






### touchEnd








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name"><code>state</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
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
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-touchEnd="onTouchEnd"></div>
<script> 
// touchEnd event for ToggleButton  
function onTouchEnd(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//touchEnd event for ToggleButton
<div id="togglebutton"></div>
<script>
$("#togglebutton").ejmToggleButton({
touchEnd: function (args) { //handle the event
}
}); 
</script>                  </code>
</pre>






### touchStart








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
<td class="name"><code>argument</code></td>
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns true if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the model value of the control.</td>
</tr>
<tr>
<td class="name"><code>state</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current state of the control.</td>
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
<div id="togglebutton" data-role="ejmtogglebutton" data-ej-touchstart="onTouchStart"></div>
<script> 
// touchStart event to be triggered
function onTouchStart(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="togglebutton"></div>
<script> 
//touchStart event to be triggered
$("#togglebutton").ejmToggleButton({
touchStart: function (args) { //handle the event 
}
});  
</script> </code>
</pre>



