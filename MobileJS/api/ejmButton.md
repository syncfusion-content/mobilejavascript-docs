---
layout: post
title: ejmButton
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Button control.





$(element).ejmButton<span class="signature">()</span>






Example
{:.example}


{% highlight html %} 
<input  id="button" type="button" />
<script> 
// Create Button  
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"}); 
</script>{% endhighlight %}


{% highlight html %} 
<input id="button"  type="button" data-role="ejmbutton"  data-ej-text="button"/>
{% endhighlight %}




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




### android
{:#members:android}




Section for android mode specific functionalities.






### android.style<span class="type-signature type enum">enum</span>
{:#members:android-style}




Specifies the style of the control in android mode.


Default Value:
{:.param}



* ej.mobile.Button.Android.Style.Normal.




Example
{:.example}


{% highlight html %} 
// Set the android mode style property in Unobtrusive way.
<input id="button" type="button"  data-role="ejmbutton" data-ej-rendermode="android" data-ej-android-style="normal" data-ej-text="button"  />
{% endhighlight %}


{% highlight html %} 
// To set android mode style property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: "android" });
$("#button").ejmButton({ "model.android.style":ej.mobile.Button.Android.Style.Normal });                 
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the android mode style API, after initialization:
// Gets the android mode style value  
$("#button").ejmButton("option", "model.android.style");                        
// Sets the android mode style value 
$("#button").ejmButton("option", "model.android.style", ej.mobile.Button.Android.Style.Normal); {% endhighlight %}




### contentType<span class="type-signature type enum">enum</span>
{:#members:contenttype}




Specifies the type of the content. See <a href="global.html#ContentType">ContentType</a>


Default Value:
{:.param}



* ej.mobile.Button.ContentType.Text




Example
{:.example}


{% highlight html %} 
//Set the contentType property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-contentType="text" />
{% endhighlight %}


{% highlight html %} 
// Set contentType property on initialization. 
//To set contentType API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ contentType: "text" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the contentType, after initialization:
// Gets the contentType API value.              
 $("#button").ejmButton("option", "contentType");                       
// Sets the contentType API
$("#button").ejmButton("option", "contentType", ej.mobile.Button.ContentType.Text);            {% endhighlight %}




### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Button theme. This cssClass API helps to use custom skinning option for Button control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}


{% highlight html %} 
//Set the cssClass property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-cssclass="customclass"  />
{% endhighlight %}


{% highlight html %} 
// Set cssClass property on initialization. 
//To set text API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({ cssClass: "customclass" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the cssClass, after initialization:
// Gets the cssClass API value.         
 $("#button").ejmButton("option", "cssClass");                  
// Sets the cssClass API
$("#button").ejmButton("option", "cssClass", "customclass");            {% endhighlight %}




### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}




Specifies whether to enable or disable the control.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the enabled property in Unobtrusive way.
<input id="button"  type="button" data-role="ejmbutton" data-ej-text="button" data-ej-enabled=false />
{% endhighlight %}


{% highlight html %} 
// Set enabled property on initialization. 
//To set enabled API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ enabled: false });     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enabled, after initialization:
// Gets the enabled API value.          
 $("#button").ejmButton("option", "enabled");   
// Sets the enabled API
$("#button").ejmButton("option", "enabled", false);            {% endhighlight %}




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
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-enablepersistence="true" />
{% endhighlight %}


{% highlight html %} 
// Set enablePersistence property on initialization. 
//To set enablePersistence API value 
<input type="button" id="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ enablePersistence: true });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Gets the enablePersistence API value.                
 $("#button").ejmButton("option", "enablePersistence");                 
// Sets the enablePersistence API
$("#button").ejmButton("option", "enablePersistence", true);            {% endhighlight %}




### flat
{:#members:flat}




Section for flat mode specific functionalities.






### flat.style<span class="type-signature type enum">enum</span>
{:#members:flat-style}




Specifies the style of the control in flat mode.


Default Value:
{:.param}



* ej.mobile.Button.Flat.Style.Normal.




Example
{:.example}


{% highlight html %} 
// Set the flat mode style property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="flat" data-ej-flat-style="normal" />
{% endhighlight %}


{% highlight html %} 
// To set flat mode style property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({renderMode: "flat"});
$("#button").ejmButton({ "model.flat.style": ej.mobile.Button.Flat.Style.Normal });              
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the flat mode style API, after initialization:
// Gets the flat mode style value  
$("#button").ejmButton("option", "model.flat.style");                   
// Sets the flat mode style value 
$("#button").ejmButton({"option", "model.flat.style", ej.mobile.Button.Flat.Style.Normal}); {% endhighlight %}




### imageClass<span class="type-signature type string">string</span>
{:#members:imageclass}




Specifies the css class of image.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the imageClass property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-contenttype="image" data-ej-imageClass="imageclass" />
{% endhighlight %}


{% highlight html %} 
// Set imageClass property on initialization. 
//To set imageClass API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({ contentType:"image" });
$("#button").ejmButton({ imageClass: "imageclass" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the imageClass, after initialization:
// Gets the imageClass API value.               
 $("#button").ejmButton("option", "imageClass");                        
// Sets the imageClass API
$("#button").ejmButton("option", "imageClass", "imageclass");            {% endhighlight %}




### imagePosition<span class="type-signature type enum">enum</span>
{:#members:imageposition}




Specifies the position of image. See <a href="global.html#ImagePosition">ImagePosition</a>


Default Value:
{:.param}



* ej.mobile.Button.ImagePosition.Left




Example
{:.example}


{% highlight html %} 
//Set the imagePosition property in Unobtrusive way.
<input id="button" type="button"  data-role="ejmbutton" data-ej-contenttype="both" data-ej-imageclass="imageclass" data-ej-text="button" data-ej-imagePosition="right" />
{% endhighlight %}


{% highlight html %} 
// Set imagePosition property on initialization. 
//To set imagePosition API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({ text:"submit" });
$("#button").ejmButton({ contentType:"both" });
$("#button").ejmButton({ imageClass: "imageclass" });   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the imagePosition, after initialization:
// Gets the imagePosition API value.            
 $("#button").ejmButton("option", "imagePosition");                     
// Sets the imagePosition API
$("#button").ejmButton("option", "imagePosition", ej.mobile.Button.ImagePosition.Right);            {% endhighlight %}




### inline<span class="type-signature type boolean">boolean</span>
{:#members:inline}




Specifies the button is inline or not


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the inline property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-inline="true" />
{% endhighlight %}


{% highlight html %} 
// Set inline on initialization. 
//To set inline API value
<input  id="button" type="button" />
<script> 
$("#button").ejmButton({text:"button", inline:"true"});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the inline, after initialization:
// Gets the inline API value.           
 $("#button").ejmButton("option", "inline");                    
// Sets the inline API
$("#button").ejmButton("option", "inline", "true");            {% endhighlight %}




### ios7
{:#members:ios7}




Section for ios7 mode specific functionalities.






### ios7.color<span class="type-signature type enum">enum</span>
{:#members:ios7-color}




Specifies the color of the control in ios7 mode.


Default Value:
{:.param}



* ej.mobile.Button.IOS7.Color.Blue.




Example
{:.example}


{% highlight html %} 
// Set the ios7 mode buttonColor property in Unobtrusive way.
<a id="button"&#65533;type="button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-color="blue" > </a>
{% endhighlight %}


{% highlight html %} 
// To set ios7 mode buttonColor property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: "ios7" });
$("#button").ejmButton({ "model.ios7.color": ej.mobile.Button.IOS7.Color.Blue });                
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the ios7 mode buttonColor API, after initialization:
// Gets the ios7 mode buttonColor value  
$("#button").ejmButton("option", "model.ios7.color");                   
// Sets the ios7 mode buttonColor value 
$("#button").ejmButton("option", "model.ios7.color", ej.mobile.Button.IOS7.Color.Blue); {% endhighlight %}




### ios7.style<span class="type-signature type enum">enum</span>
{:#members:ios7-style}




Specifies the style of the control in ios7 mode.


Default Value:
{:.param}



* ej.mobile.Button.IOS7.Style.Normal.




Example
{:.example}


{% highlight html %} 
// Set the ios7 mode style property in Unobtrusive way.
<input id="button" type="button"  data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="ios7" data-ej-ios7-style="normal"  />
{% endhighlight %}


{% highlight html %} 
// To set ios7 mode style property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: "ios7" });
$("#button").ejmButton({ "model.ios7.style": ej.mobile.Button.IOS7.Style.Normal});
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the ios7 mode style API, after initialization:
// Gets the ios7 mode style value  
$("#button").ejmButton("option", "model.ios7.style");                   
// Sets the ios7 mode style value 
$("#button").ejmButton("option", "model.ios7.style", ej.mobile.Button.IOS7.Style.Normal); {% endhighlight %}




### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Specifies the rendering mode of the control.See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}


{% highlight html %} 
//Set the renderMode property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="auto" />
{% endhighlight %}


{% highlight html %} 
// Set rendermode property on initialization. 
//To set renderMode API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: ej.mobile.RenderMode.Auto });      
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the Button rendermode, after initialization:
// Gets the renderMode API value.               
 $("#button").ejmButton("option", "renderMode");                        
// Sets the renderMode API
$("#button").ejmButton("option", "renderMode", ej.mobile.RenderMode.Auto);            {% endhighlight %}




### text<span class="type-signature type string">string</span>
{:#members:text}




Specifies the text.


Default Value:
{:.param}



* ""




Example
{:.example}


{% highlight html %} 
//Set the text property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button"  />
{% endhighlight %}


{% highlight html %} 
// Set text property on initialization. 
//To set text API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton(); 
$("#button").ejmButton({ text: "button" });
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the text, after initialization:
// Gets the text API value.             
 $("#button").ejmButton("option", "text");                      
// Sets the text API
$("#button").ejmButton("option", "text", "button");            {% endhighlight %}




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
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-theme="auto" />
{% endhighlight %}


{% highlight html %} 
// Set theme on initialization. 
//To set theme API value
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ theme: ej.mobile.Theme.Auto });        
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Gets the theme API value.            
 $("#button").ejmButton("option", "theme");                     
// Sets the theme API
$("#button").ejmButton("option", "theme", "button");            {% endhighlight %}




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
// Set the windows mode renderDefault property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="windows" data-ej-windows-renderDefault=true />
{% endhighlight %}


{% highlight html %} 
// To set windows mode renderDefault property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: "windows" });
$("#button").ejmButton({ "windows.renderDefault": "true" });             
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Gets the windows mode renderDefault value  
$("#button").ejmButton("option", "windows.renderDefault");                      
// Sets the windows mode renderDefault value 
$("#button").ejmButton("option", "windows.renderDefault", false); {% endhighlight %}




### windows.style<span class="type-signature type enum">enum</span>
{:#members:windows-style}




Specifies the style of the control in windows mode.


Default Value:
{:.param}



* ej.mobile.Button.Windows.Style.Normal.




Example
{:.example}


{% highlight html %} 
// Set the windows mode style property in Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-rendermode="windows" data-ej-windows-style="normal" />
{% endhighlight %}


{% highlight html %} 
// To set windows mode style property API value 
<input  id="button" type="button" />
<script> 
$("#button").ejmButton();
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({ renderMode: "windows" });
$("#button").ejmButton({ "model.windows.style": ej.mobile.Button.Windows.Style.Normal });                
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode style API, after initialization:
// Gets the windows mode style value  
$("#button").ejmButton("option", "model.windows.style");                        
// Sets the windows mode style value 
$("#button").ejmButton("option", "model.windows.style", ej.mobile.Button.Windows.Style.Normal); {% endhighlight %}



## Methods




### destroy<span class="signature">()</span>
{:#methods:destroy}




destroy the Button widget all events bound using this._on will be unbind automatically and bring the control to pre-init state.



Example
{:.example}


{% highlight html %} 
<input&#65533;id="button" type="Button" data-role="ejmbutton" data-ej-text="button"/>
<script> 
var btnObj = $("#button").data("ejmButton");
btnObj.destroy();
</script>{% endhighlight %}


{% highlight html %} 
<input&#65533;id="button" type="button"  />
<script>
// enabled the Button
$("#button").ejmButton({text:"button"});
$("#button").ejmButton("destroy");      
</script>{% endhighlight %}




### disable<span class="signature">()</span>
{:#methods:disable}




To disable the button.



Example
{:.example}


{% highlight html %} 
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button"/>
<script>
$(document).ready(function () {
var button = $("#button").data("ejmButton");
button.disable(); // Disables the toggle button
});
</script>{% endhighlight %}


{% highlight html %} 
<input&#65533;id="button" type="button"  />
<script>
// change the button current state
$("#button").ejmButton({text:"button"});
$("#button").ejmButton(); 
$("#button").ejmButton("disable");      
</script>{% endhighlight %}




### enable<span class="signature">()</span>
{:#methods:enable}




To enable the button.



Example
{:.example}


{% highlight html %} 
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button"/>
<script>
$(document).ready(function () {
var btnObj = $("#button").data("ejmButton");
btnObj.enable(); // changes the button control state
});
</script>{% endhighlight %}


{% highlight html %} 
<input&#65533;id="button" type="button"  />
<script>
// change the button current state
$("#button").ejmButton({text:"button"});
$("#button").ejmButton(); 
$("#button").ejmButton("enable");       
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
<td class="description last">Event parameters from Button.
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
<td class="description last">returns the button model.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}status{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the button state.</td>
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
//Bind the touchEnd event using Unobtrusive way.
<input id="button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-touchEnd="touchEnd" />
<script> 
// touchEnd event for Button
function touchEnd(args){ 
//handle the event
}{% endhighlight %}


{% highlight html %} 
<input  id="button" type="button" />
<script> 
//touchEnd event for button
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({
touchEnd: function (args) {}
});  
</script>{% endhighlight %}




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
<td class="description last">Event parameters from Button.
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
<td class="description last">returns the button model.</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event.</td>
</tr>
<tr>
<td class="name">{% highlight html %}status{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the button state.</td>
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
//Bind the touchStart event using Unobtrusive way.
<input id="button"  type="button"  data-role="ejmbutton" data-ej-touchstart="touchstart" data-ej-text="button"/>
<script> 
// touchStart event for Button
function touchstart(args){ 
//handle the event
}{% endhighlight %}


{% highlight html %} 
<input  id="button" type="button" />
<script>  
//touchStart event for button
$("#button").ejmButton({text:"button"});
$("#button").ejmButton({
   touchStart: function (args) {}
});       
</script>{% endhighlight %}



