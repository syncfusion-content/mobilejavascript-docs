---
layout: post
title: ejmNumeric
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Editor control.










$(element).ejmNumeric<span class="signature">()</span>











Example
{:.example}


{% highlight html %} 
// Create editor control in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" />
{% endhighlight %}


{% highlight html %} 
// Create editor control in obtrusive way.
<input id="editor" type="number"/>
<script>
$("#editor").ejmNumeric();
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




## Members








### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}








Sets the root class for Editor theme. This cssClass API helps to use custom skinning option for Editor control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-cssclass="customclass" />
{% endhighlight %}


{% highlight html %} 
// Set cssClass on initialization. 
//To set cssClass API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ cssClass: "customclass" });
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
 $("#editor").ejmNumeric ("option", "cssClass");                
});
</script>
{% endhighlight %}


{% highlight html %}<script>
// Set the cssClass API
$("#editor").ejmNumeric ("option", "cssClass", "customclass");
</script>{% endhighlight %}







### decimalPlaces<span class="type-signature type number">number</span>
{:#members:decimalplaces}








Specifies the decimal places to set the decimal(floating point) numbers.




Default Value:
{:.param}






* 0








Example
{:.example}


{% highlight html %} 
//Set the decimalPlaces property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-decimalPlaces="2" />
{% endhighlight %}


{% highlight html %} 
// Set decimalPlaces on initialization. 
//To set decimalPlaces API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ decimalPlaces: 2 });
});
</script>
{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the decimalPlaces, after initialization:
// Get the decimalPlaces API value.             
 $("#editor").ejmNumeric ("option", "decimalPlaces");                   
// Set the decimalPlaces API
$("#editor").ejmNumeric ("option", " ", 2);     
</script>{% endhighlight %}







### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}








Specifies whether to enable or disable the control.




Default Value:
{:.param}






* true








Example
{:.example}


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-enabled="true" />
{% endhighlight %}


{% highlight html %} 
// Set enabled on initialization. 
//To set enabled API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ enabled: false });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the enabled, after initialization:
// Get the enabled API value.           
 $("#editor").ejmNumeric ("option", "enabled");                 
// Set the enabled API
$("#editor").ejmNumeric ("option", "enabled", true);
</script>{% endhighlight %}







### enableStrictMode<span class="type-signature type boolean">boolean</span>
{:#members:enablestrictmode}








Specifies whether to restrict entering the values outside the defined range.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the enableStrictMode property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-minValue=0 data-ej-maxValue=100 data-ej-enableStrictMode="true" />
{% endhighlight %}


{% highlight html %} 
// Set enableStrictMode on initialization. 
//To set enableStrictMode API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ maxValue: 100 , minValue: 0 , enableStrictMode: true });
});
</script>
{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the enableStrictMode, after initialization:
// Get the enableStrictMode API value.          
 $("#editor").ejmNumeric ("option", "enableStrictMode");                        
// Set the enableStrictMode API
$("#editor").ejmNumeric ("option", "enableStrictMode", true);
</script>{% endhighlight %}







### incrementStep<span class="type-signature type number">number</span>
{:#members:incrementstep}








Specifies the step value for incrementation.




Default Value:
{:.param}






* 1








Example
{:.example}


{% highlight html %} 
//Set the incrementStep property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-incrementStep="3" />
{% endhighlight %}


{% highlight html %} 
// Set incrementStep on initialization. 
//To set incrementStep API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ incrementStep: 3 });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the incrementStep, after initialization:
// Get the incrementStep API value.             
 $("#editor").ejmNumeric ("option", "incrementStep");                   
// Set the incrementStep API
$("#editor").ejmNumeric ("option", "incrementStep", 3);
</script>{% endhighlight %}







### maxValue<span class="type-signature type number">number</span>
{:#members:maxvalue}








Specify the maximum value of the editor.




Default Value:
{:.param}






* 0








Example
{:.example}


{% highlight html %} 
//Set the maxValue property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-maxValue=500 />
{% endhighlight %}


{% highlight html %} 
// Set maxValue on initialization. 
//To setmaxValue API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ maxValue: 500 });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the maxValue, after initialization:
// Get the maxValue API value.          
 $("#editor").ejmNumeric ("option", "maxValue");                        
// Set the maxValue API
$("#editor").ejmNumeric ("option", "maxValue", 500);
</script>{% endhighlight %}







### minValue<span class="type-signature type number">number</span>
{:#members:minvalue}








Specify the minimum value.




Default Value:
{:.param}






* 0








Example
{:.example}


{% highlight html %} 
//Set the minValue property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-minValue=50 />
{% endhighlight %}


{% highlight html %} 
// Set minValue on initialization. 
//To set minValue API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ minValue: 50 });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the minValue, after initialization:
// Get the minValue API value.          
 $("#editor").ejmNumeric ("option", "minValue");                        
// Set the minValue API
$("#editor").ejmNumeric ("option", "minValue", 50);
</script>{% endhighlight %}







### name<span class="type-signature type string">string</span>
{:#members:name}








Specifies the name of the control.




Default Value:
{:.param}






* Sets id as name if it is null.








Example
{:.example}


{% highlight html %} 
//Set the name property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-name="numeric" />
{% endhighlight %}


{% highlight html %} 
// Set name on initialization. 
//To set name API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ name: "numeric" });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the name, after initialization:
// Get the name API value.              
 $("#editor").ejmNumeric ("option", "name");                    
// Set the name API
$("#editor").ejmNumeric ("option", "name", "numeric");
</script>{% endhighlight %}







### readOnly<span class="type-signature type boolean">boolean</span>
{:#members:readonly}








Specifies whether the control is read only to disable typing the value manually rather than updating by spin button.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the readOnly property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-readOnly="true" />
{% endhighlight %}


{% highlight html %} 
// Set readOnly on initialization. 
//To set readOnly API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ readOnly: false });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the readOnly, after initialization:
// Get the readOnly API value.          
 $("#editor").ejmNumeric ("option", "readOnly");                        
// Set the readOnly API
$("#editor").ejmNumeric ("option", "readOnly", true);
</script>{% endhighlight %}







### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}








Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-renderMode="auto" />
{% endhighlight %}


{% highlight html %} 
// Set rendermode on initialization. 
//To set renderMode API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ renderMode: "auto" });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the rendermode after initialization:
// Get the renderMode API value.                
 $("#editor").ejmNumeric ("option", "renderMode");                      
// Set the renderMode API
$("#editor").ejmNumeric ("option", "renderMode", ej.mobile.RenderMode.Auto);
</script>{% endhighlight %}







### showBorder<span class="type-signature type boolean">boolean</span>
{:#members:showborder}








Specifies whether to show the border in the control.




Default Value:
{:.param}






* true








Example
{:.example}


{% highlight html %} 
//Set the showBorder property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-showborder="true" />
{% endhighlight %}


{% highlight html %} 
// Set showBorder on initialization. 
//To set showBorder API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ showBorder: false });
});
</script>
{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the showBorder, after initialization:
// Get the showBorder API value.                
 $("#editor").ejmNumeric ("option", "showBorder");                      
// Set the showBorder API
$("#editor").ejmNumeric ("option", "showBorder", true);
</script>{% endhighlight %}







### showSpinButton<span class="type-signature type boolean">boolean</span>
{:#members:showspinbutton}








Specifies whether to show the spin button for incremention and decremention of the value.




Default Value:
{:.param}






* true








Example
{:.example}


{% highlight html %} 
//Set the showSpinButton property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-showSpinButton="true" />
{% endhighlight %}


{% highlight html %} 
// Set showSpinButton on initialization. 
//To set showSpinButton API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ showSpinButton: false });
});
</script>
{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the showSpinButton, after initialization:
// Get the showSpinButton API value.            
 $("#editor").ejmNumeric ("option", "showSpinButton");                  
// Set the showSpinButton API
$("#editor").ejmNumeric ("option", "showSpinButton", true);
</script>{% endhighlight %}







### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Specifies the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the theme property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-theme="auto" />
{% endhighlight %}


{% highlight html %} 
// Set theme on initialization. 
//To set theme API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ theme: ej.mobile.Theme.Auto });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#editor").ejmNumeric ("option", "theme");                   
// Set the theme API
$("#editor").ejmNumeric ("option", "theme", ej.mobile.Theme.Auto);
</script>{% endhighlight %}







### value<span class="type-signature type number">number</span>
{:#members:value}








Specifies the value of the editor.




Default Value:
{:.param}






* 0








Example
{:.example}


{% highlight html %} 
//Set the value property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-value="100" />
{% endhighlight %}


{% highlight html %} 
// Set value on initialization. 
//To set value API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ value: 100 });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the value, after initialization:
// Get the value API value.             
 $("#editor").ejmNumeric ("option", "value");                   
// Set the value API
$("#editor").ejmNumeric ("option", "value", 100);
</script>{% endhighlight %}







### watermarkText<span class="type-signature type string">string</span>
{:#members:watermarktext}








Specifies the watermark text of the control.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
//Set the watermarkText property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-watermarkText="Enter the age" />
{% endhighlight %}


{% highlight html %} 
// Set watermarkText on initialization. 
//To set watermarkText API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric ({ watermarkText: "Enter the age" });
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.             
 $("#editor").ejmNumeric ("option", "watermarkText");           
});
</script>
{% endhighlight %}


{% highlight html %}<script>
// Set the watermarkText API
$("#editor").ejmNumeric ("option", "watermarkText", "Enter the age");
</script>{% endhighlight %}







### windows
{:#members:windows}








Section for windows mode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}








Specifies whether to render control based on the windowsphone's current accent color and device theme.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the windows mode renderDefault property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-renderMode="windows" data-ej-windows-renderDefault="true" />
{% endhighlight %}


{% highlight html %} 
// Set windows mode renderDefault on initialization. 
//To set windows mode renderDefault API value 
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric({ renderMode:"windows",windows: { renderDefault: true } });
});
</script>
{% endhighlight %}


{% highlight html %}<script>
//Get or set the windows mode renderDefault, after initialization:
// Get the windows mode renderDefault API value.                
 $("#editor").ejmNumeric ("option", "windows.renderDefault");                   
// Set the windows mode renderDefault API
$("#editor").ejmNumeric ("option", "windows.renderDefault", true);
</script>{% endhighlight %}





## Methods








### disable<span class="signature">()</span>
{:#methods:disable}








To disable the numeric textbox.





Example
{:.example}


{% highlight html %} 
//Change the control status using disable method in obtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" />
<script>
// Call disable method.
$(document).ready(function(){
$("#editor").ejmNumeric("disable");
});
</script>{% endhighlight %}


{% highlight html %}//Change the control status using disable method in obtrusive way.
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric("disable");
});
</script>{% endhighlight %}







### enable<span class="signature">()</span>
{:#methods:enable}








To enable the numeric textbox.





Example
{:.example}


{% highlight html %} 
//Change the control status using enable method in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" />
<script>
// Call enable method.
$(document).ready(function(){
$("#editor").ejmNumeric("enable");
});
</script>{% endhighlight %}


{% highlight html %}//Change the control status using enable method in obtrusive way.
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric("enable");
});
</script>{% endhighlight %}







### getValue<span class="signature">()</span>
{:#methods:getvalue}








To get the current value of the textbox.





Example
{:.example}


{% highlight html %} 
//Get the value using getValue function
<input type="number" id="editor" data-role="ejmnumeric" />
<script>
// Call getValue method.
$(document).ready(function(){
$("#editor").ejmNumeric("getValue");
});
</script>{% endhighlight %}







### setValue<span class="signature">()</span>
{:#methods:setvalue}








Set value of the editor control.





Example
{:.example}


{% highlight html %} 
//Set the value using setValue function 
<input type="number" id="editor" data-role="ejmnumeric" />
<script>
$(document).ready(function(){
// Call setValue method.
$("#editor").ejmNumeric("setValue",50);
});
</script>{% endhighlight %}





## Events








### change
{:#events:change}








Event triggers after the control value gets changed.

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
<td class="description last">Event parameters from editors.
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
<td class="description last">if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the corresponding editor model.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the corresponding editor control value.</td>
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
//Set the windows mode renderDefault property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-change="change" />
{% endhighlight %}


{% highlight html %} 
//Change event for editor
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric({
change: function (args) { //handle the event
}
});           
</script>{% endhighlight %}







### focusIn
{:#events:focusin}








Event triggers after the control gets focused.

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
<td class="description last">Event parameters from editors.
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
<td class="description last">if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the corresponding editor model.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">value</span></td>
<td class="description last">returns the corresponding editor control value.</td>
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
//Set the focusin property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-focusin="focusIn" />
{% endhighlight %}


{% highlight html %} 
//focusIn event for editor
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric({
focusIn: function (args) { //handle the event
}
}); 
</script>{% endhighlight %}







### focusOut
{:#events:focusout}








Event triggers after the control gets focus out.

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
<td class="description last">Event parameters from editors.
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
<td class="description last">if the event should be cancelled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the corresponding editor model.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">value</span></td>
<td class="description last">returns the corresponding editor control value.</td>
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
//Set the focusin property in unobtrusive way.
<input type="number" id="editor" data-role="ejmnumeric" data-ej-focusout="focusOut" />
{% endhighlight %}


{% highlight html %} 
//focusOut event for editor
<input type="number" id="editor" />
<script>
$(document).ready(function(){
$("#editor").ejmNumeric({
focusOut: function (args) { //handle the event
}
});   
</script>{% endhighlight %}




