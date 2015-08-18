---
layout: post
title: ejmRadioButton
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html RadioButton control.










$(element).ejmRadioButton<span class="signature">()</span>











Example
{:.example}


{% highlight html %} 
// Create radiobutton control in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" />
{% endhighlight %}


{% highlight html %} 
<input type="radio" id="radbtn" />
<script> 
  // Create RadioButton  
  $("#radbtn").ejmRadioButton(); 
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








### checked<span class="type-signature type boolean">boolean</span>
{:#members:checked}








Specifies the checked attribute.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the checked property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-checked=false />
{% endhighlight %}


{% highlight html %} 
// To set checked API value during initialization  
<input type="radio" id="radbtn"/>
<script>
 $("#radbtn").ejmRadioButton({ checked:  true });                                       
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the checked API, after initialization:
 //Gets the checked value  
 $("#radbtn").ejmRadioButton("option", "checked");
                  
 //Sets the checked value 
 $("#radbtn").ejmRadioButton("option", "checked",  false );  {% endhighlight %}







### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}








Sets the root class for RadioButton theme. This cssClass API helps to use custom skinning option for RadioButton control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
// Set the cssClass property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-cssclass="customclass" />
{% endhighlight %}


{% highlight html %} 
// Set RadioButton cssClass on initialization. 
// To set renderMode API value 
<input type="radio" id="radbtn"/>
<script>
$(function() {
$("#radbtn").ejmRadioButton ({ cssClass: "customclass" });              
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the cssClass property, after initialization:
  // Gets the cssClass API value.               
  $("#radbtn").ejmRadioButton ("option", "cssClass");                   
  // Sets the cssClass API
  $("#radbtn").ejmRadioButton ("option", "cssClass", "customclass"); {% endhighlight %}







### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}








Specifies whether the control is enabled or not.




Default Value:
{:.param}






* true








Example
{:.example}


{% highlight html %} 
//Set the enabled property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-enabled=true />
{% endhighlight %}


{% highlight html %} 
// Enabled RadioButton on initialization. 
  // To set width API value 
<input type="radio" id="radbtn"/>
<script>
        $("#radbtn").ejmRadioButton ({ enabled: true });                        
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the enabled state, after initialization:
  // Gets the Enabled API value.                
        $("#radbtn").ejmRadioButton ("option", "enabled");                      
  // Sets the Enabled API
        $("#radbtn").ejmRadioButton ("option", "enabled", true);{% endhighlight %}







### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}








Saves current model value to browser cookies for state maintains. While refreshing the page retains the model value apply from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
// Set the enablePersistence property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-enablepersistence=true />
{% endhighlight %}


{% highlight html %} 
// To set enablePersistence API value 
<input type="radio" id="radbtn"/>
<script>
  $("#radbtn").ejmRadioButton({ enablePersistence: true});               
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the enablePersistence API, after initialization:
  // Gets the enablePersistence value  
  $("#radbtn").ejmRadioButton("option", "enablePersistence");                   
  // Sets the enablePersistence value 
  $("#radbtn").ejmRadioButton("option", "enablePersistence", true ); {% endhighlight %}







### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}








Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
// Set the renderMode property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-rendermode="auto" />
{% endhighlight %}


{% highlight html %} 
// Set RadioButton rendermode on initialization. 
// To set renderMode API value 
<input type="radio" id="radbtn"/>
<script>
$(function() {
$("#radbtn").ejmRadioButton ({ renderMode: ej.mobile.RenderMode.Auto });                
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the renderMode property, after initialization:
  // Gets the renderMode API value.             
  $("#radbtn").ejmRadioButton ("option", "renderMode");                 
  // Sets the renderMode API
  $("#radbtn").ejmRadioButton ("option", "renderMode", ej.mobile.RenderMode.Auto); {% endhighlight %}







### text<span class="type-signature type string">string</span>
{:#members:text}








Specifies the text content.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
// Set the text property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-text="RadioButton" />
{% endhighlight %}


{% highlight html %} 
// To set text API value 
<input type="radio" id="radbtn"/>
<script>
  $("#radbtn").ejmRadioButton({ text: "Hello World"});           
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the text API, after initialization:
  // Gets the text value  
  $("#radbtn").ejmRadioButton("option", "text");                        
  // Sets the text value 
  $("#radbtn").ejmRadioButton("option", "text", "Hello World" ); {% endhighlight %}







### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Changes the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the theme property in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-theme="auto" />
{% endhighlight %}


{% highlight html %} 
// Set theme property on initialization. 
  // To set theme API value 
<input type="radio" id="radbtn"/>
<script>
$(function(){
  $("#radbtn").ejmRadioButton ({ theme: ej.mobile.Theme.Auto });                        
});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the theme API value, after initialization:
  // Gets the theme API value.          
  $("#radbtn").ejmRadioButton ("option", "theme");                      
  // Sets the theme API
  $("#radbtn").ejmRadioButton ("option", "theme", ej.mobile.Theme.Auto);{% endhighlight %}





## Methods








### disable<span class="signature">()</span>
{:#methods:disable}








To disable the radio button.





Example
{:.example}


{% highlight html %} 
<input type="radio" id="radbtn" data-role="ejmradiobutton" />
<script>
        $("#radbtn").ejmRadioButton ("disable");                        
</script>{% endhighlight %}







### enable<span class="signature">()</span>
{:#methods:enable}








To enable the radio button





Example
{:.example}


{% highlight html %} 
<input type="radio" id="radbtn" data-role="ejmradiobutton" />
<script>
        $("#radbtn").ejmRadioButton ("enable");                 
</script>{% endhighlight %}





## Events








### change
{:#events:change}








Event triggers when the selection in radiobutton is changed.

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
<td class="description last">Event parameters from RadioButton
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
<td class="description last">returns the RadioButton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the status of the element</td>
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
// Define the change event in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-change="change" />
<script> 
// change event for RadioButton            
function change(args){ 
//handle the event here
}
</script>{% endhighlight %}


{% highlight html %} 
// change event for RadioButton
<input type="radio" id="radbtn" data-role="ejmradiobutton"/>
<script> 
$("#radbtn").ejmRadioButton({
 change: function (args) { 
      //handle the event 
  }
});     
</script> {% endhighlight %}







### touchEnd
{:#events:touchend}








Event triggers when the touch end happens in the RadioButton.

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
<td class="description last">Event parameters from RadioButton
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
<td class="description last">returns the RadioButton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the status of the element</td>
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
// Define the touchend event in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-touchend="touchend" />
<script> 
// touchEnd event for RadioButton            
function touchend(args){ 
//handle the event here
}
</script>{% endhighlight %}


{% highlight html %} 
// touchEnd event for RadioButton
<input type="radio" id="radbtn" data-role="ejmradiobutton"/>
<script> 
$("#radbtn").ejmRadioButton({
  touchEnd: function (args) { 
      //handle the event 
  }
});     
</script> {% endhighlight %}







### touchStart
{:#events:touchstart}








event triggers when the touch start happens in the RadioButton.

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
<td class="description last">Event parameters from RadioButton
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
<td class="description last">returns the RadioButton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}value{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current element associated value</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the status of the element</td>
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
// Define the touchstart event in Unobtrusive way.
<input type="radio" id="radbtn" data-role="ejmradiobutton" data-ej-touchstart="touchstart" />
<script> 
  // touchStart event for RadioButton 
  function touchstart(args){ 
      //handle the event 
  }
</script>{% endhighlight %}


{% highlight html %} 
// touchStart event for RadioButton
<input type="radio" id="radbtn" data-role="ejmradiobutton"/>
<script> 
$("#radbtn").ejmRadioButton({
  touchStart: function (args) { 
        //handle the event 
  }
});           
</script> {% endhighlight %}




