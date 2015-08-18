---
layout: post
title: ejmRating
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html rating control.





$(element).ejmRating<span class="signature">()</span>






Example
{:.example}


{% highlight html %} 
<div id="rating" ></div>
<script> 
// Create rating control 
$("#rating").ejmRating(); 
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating" data-role="ejmrating" ></div>
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




### enabled<span class="type-signature type bool">bool</span>
{:#members:enabled}




Specifies whether to enable or disable the control.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-enabled=true ></div>
{% endhighlight %}


{% highlight html %} 
// Set enabled on initialization. 
<div id="rating"></div>
<script>
//To set enabled API value 
$("#rating").ejmRating ({ enabled: true });                     
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating enabled, after initialization:
// Get the enabled API value.           
 $("#rating").ejmRating ("option", "enabled");                  
// Set the enabled API
$("#rating").ejmRating ("option", "enabled", true); 
</script>{% endhighlight %}




### enablePersistence<span class="type-signature type bool">bool</span>
{:#members:enablepersistence}




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-enablePersistence=false ></div>
{% endhighlight %}


{% highlight html %} 
// Set enablePersistence on initialization. 
<div id="rating"></div>
<script>
//To set enablePersistence API value 
$(function(){
$("#rating").ejmRating({enablePersistence:false});
});
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#rating").ejmRating ("option", "enablePersistence");                        
// Set the enablePersistence API
$("#rating").ejmRating ("option", "enablePersistence", false);   
</script>{% endhighlight %}




### incrementStep<span class="type-signature type int">int</span>
{:#members:incrementstep}




Specifies the step value for incrementation.


Default Value:
{:.param}



* 1




Example
{:.example}


{% highlight html %} 
//Set the incrementStep property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-incrementstep=1 ></div>
{% endhighlight %}


{% highlight html %} 
// Set incrementStep on initialization. 
<div id="rating"></div>
<script>
//To set incrementStep API value
$("#rating").ejmRating ({ incrementStep: 1 });  
</script>                         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating incrementStep, after initialization:
// Get the incrementStep API value.             
 $("#rating").ejmRating ("option", "incrementStep");                    
// Set the incrementStep API
$("#rating").ejmRating ("option", "incrementStep", 1);      
</script>{% endhighlight %}




### maxValue<span class="type-signature type int">int</span>
{:#members:maxvalue}




Specifies the maximum value.


Default Value:
{:.param}



* 5




Example
{:.example}


{% highlight html %} 
//Set the maxValue property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-maxvalue=5 ></div>
{% endhighlight %}


{% highlight html %} 
// Set rating maxValue on initialization. 
<div id="rating"></div>
<script>
//To set maximum API value
$("#rating").ejmRating ({ maxValue: 5 });       
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating maxValue, after initialization:
// Get the maximum API value.           
 $("#rating").ejmRating ("option", "maxValue");                 
// Set the maximum value API
$("#rating").ejmRating ("option", "maxValue", 5);    
</script>{% endhighlight %}




### minValue<span class="type-signature type int">int</span>
{:#members:minvalue}




Specifies the minimum value.


Default Value:
{:.param}



* 0




Example
{:.example}


{% highlight html %} 
//Set the minValue property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-minvalue=0 ></div>
{% endhighlight %}


{% highlight html %} 
// Set rating minValue on initialization. 
<div id="rating"></div>
<script>
//To set minimum API value 
$("#rating").ejmRating ({ minValue: 0 });               
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating minValue, after initialization:
// Get the minimum API value.           
 $("#rating").ejmRating ("option", "minValue");                 
// Set the minValue API
$("#rating").ejmRating ("option", "minValue", 0);   
</script>{% endhighlight %}




### orientation<span class="type-signature type enum">enum</span>
{:#members:orientation}




Specifies whether the orientation is horizontal or vertical. See <a href="global.html#Orientation">Orientation</a>


Default Value:
{:.param}



* ej.mobile.Rating.Orientation.Horizontal.




Example
{:.example}


{% highlight html %} 
//Set the orientation property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-orientation="horizontal" ></div>
{% endhighlight %}


{% highlight html %} 
// Set orientation on initialization. 
<div id="rating"></div>
<script>
//To set orientation API value 
$(function(){
$("#rating").ejmRating ({ orientation: ej.mobile.Rating.Orientation.Horizontal });
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating orientation, after initialization:
// Get the orientation API value.               
 $("#rating").ejmRating ("option", "orientation");                      
// Set the orientation API
$("#rating").ejmRating ("option", "orientation", ej.mobile.Rating.Orientation.Horizontal);     
</script>{% endhighlight %}




### precision<span class="type-signature type enum">enum</span>
{:#members:precision}




Specifies the precision value. See <a href="global.html#Precision">Precision</a>


Default Value:
{:.param}



* ej.mobile.Rating.Precision.Full.




Example
{:.example}


{% highlight html %} 
//Set the precision property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-precision="full" ></div>
{% endhighlight %}


{% highlight html %} 
// Set precision on initialization. 
//To set precision API value 
<div id="rating"></div>
<script>
$(function(){
$("#rating").ejmRating ({ precision: ej.mobile.Rating.Precision.Full });                
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating precision, after initialization:
// Get the precision API value.         
 $("#rating").ejmRating ("option", "precision");                        
// Set the precision API
$("#rating").ejmRating ("option", "precision", ej.mobile.Rating.Precision.Full);  
</script>{% endhighlight %}




### readOnly<span class="type-signature type bool">bool</span>
{:#members:readonly}




Specifies whether the control is read only.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the read only property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-readonly=false ></div>
{% endhighlight %}


{% highlight html %} 
// Set read only on initialization. 
<div id="rating"></div>
<script>
//To set read only API value 
$("#rating").ejmRating ({ readOnly: false });                   
</script>{% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating read only, after initialization:
// Get the read only API value.         
 $("#rating").ejmRating ("option", "readOnly");                 
// Set the read only API
$("#rating").ejmRating ("option", "readOnly", false);      
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
<div id="rating" data-role="ejmrating" data-ej-rendermode="auto" ></div>
{% endhighlight %}


{% highlight html %} 
// Set rendermode on initialization. 
<div id="rating"></div>
<script>
//To set renderMode API value 
$(function(){
$("#rating").ejmRating ({ renderMode: ej.mobile.RenderMode.Auto });     
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating rendermode, after initialization:
// Get the renderMode API value.                
 $("#rating").ejmRating ("option", "renderMode");                       
// Set the renderMode API
$("#rating").ejmRating ("option", "renderMode", ej.mobile.RenderMode.Auto);   
</script>{% endhighlight %}




### shape<span class="type-signature type enum">enum</span>
{:#members:shape}




Specifies the shape. See <a href="global.html#Shape">Shape</a>


Default Value:
{:.param}



* ej.mobile.Rating.Shape.Star.




Example
{:.example}


{% highlight html %} 
//Set the shape property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-shape="star" ></div>
{% endhighlight %}


{% highlight html %} 
// Set shape on initialization. 
<div id="rating"></div>
<script>
//To set shape API value 
$(function(){
$("#rating").ejmRating ({ shape: ej.mobile.Rating.Shape.Star });
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating shape, after initialization:
// Get the shape API value.             
 $("#rating").ejmRating ("option", "shape");                    
// Set the shape API
$("#rating").ejmRating ("option", "shape", ej.mobile.Rating.Shape.Star);          
</script>{% endhighlight %}




### shapeHeight<span class="type-signature type int">int</span>
{:#members:shapeheight}




Specifies the shape height.


Default Value:
{:.param}



* 25




Example
{:.example}


{% highlight html %} 
//Set the shape height property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-shapeheight=25 ></div>
{% endhighlight %}


{% highlight html %} 
// Set shape height on initialization. 
<div id="rating"></div>
<script>
//To set shape height API value 
$("#rating").ejmRating ({ shapeHeight: 25 });   
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating shape height, after initialization:
// Get the shape height API value.              
 $("#rating").ejmRating ("option", "shapeHeight");                      
// Set the shape height API
$("#rating").ejmRating ("option", "shapeHeight", 25);  
</script>{% endhighlight %}




### shapeWidth<span class="type-signature type int">int</span>
{:#members:shapewidth}




Specifies the shape width.


Default Value:
{:.param}



* 25




Example
{:.example}


{% highlight html %} 
//Set the shape width property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-shapewidth=25 ></div>
{% endhighlight %}


{% highlight html %} 
// Set shape width on initialization. 
<div id="rating"></div>
<script>
//To set shape width API value 
$("#rating").ejmRating ({ shapeWidth: 25 });    
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating shape width, after initialization:
// Get the shape width API value.               
 $("#rating").ejmRating ("option", "shapeWidth");                       
// Set the shape width API
$("#rating").ejmRating ("option", "shapeWidth", 25);       
</script>{% endhighlight %}




### spaceBetweenShapes<span class="type-signature type int">int</span>
{:#members:spacebetweenshapes}




Specifies the space between shapes.


Default Value:
{:.param}



* 25




Example
{:.example}


{% highlight html %} 
//Set the space between shapes property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-spacebetweenshapes=15 ></div>
{% endhighlight %}


{% highlight html %} 
// Set space between shapes on initialization. 
<div id="rating"></div>
<script>
//To set space between shapes API value 
$("#rating").ejmRating ({ spaceBetweenShapes: 15 });            
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating space between shapes, after initialization:
// Get the space between shapes API value.              
 $("#rating").ejmRating ("option", "spaceBetweenShapes");                       
// Set the space between shapes API
$("#rating").ejmRating ("option", "spaceBetweenShapes", 15);            
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
<div id="rating" data-role="ejmrating" data-ej-theme="auto" ></div>
{% endhighlight %}


{% highlight html %} 
// Set theme on initialization. 
<div id="rating"></div>
<script>
//To set theme API value 
$(function(){
$("#rating").ejmRating ({ theme: ej.mobile.Theme.Auto });               
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating theme, after initialization:
// Get the theme API value.             
 $("#rating").ejmRating ("option", "theme");                    
// Set the theme API
$("#rating").ejmRating ("option", "theme", ej.mobile.Theme.Auto);            
</script>{% endhighlight %}




### value<span class="type-signature type int">int</span>
{:#members:value}




Specifies the current value.


Default Value:
{:.param}



* 1




Example
{:.example}


{% highlight html %} 
//Set the current value property in unobtrusive way.
<div id="rating" data-role="ejmrating" data-ej-value=1 ></div>
{% endhighlight %}


{% highlight html %} 
// Set rating current value on initialization. 
<div id="rating"></div>
<script>
//To set current value API value 
$("#rating").ejmRating ({ value: 1 });          
</script>                         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the rating current value, after initialization:
// Get the current value API value.             
 $("#rating").ejmRating ("option", "value");                    
// Set the current value API
$("#rating").ejmRating ("option", "value", 1);   
</script>{% endhighlight %}



## Methods




### disable<span class="signature">()</span>
{:#methods:disable}




To disable the rating.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating" ></div>
<script>
$(function(){
// To get the instance of the rating control
var rating = $("#rating").data("ejmRating");
rating.disable(); // it will disable the rating control
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating" ></div>
<script>
$("#rating").ejmRating();       
$(function(){
// To disable the Rating control
$("#rating").ejmRating("disable");
});   
</script>{% endhighlight %}




### enable<span class="signature">()</span>
{:#methods:enable}




To enable the rating.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating" ></div>
<script>
$(function(){
// To get the instance of the rating control
var rating = $("#rating").data("ejmRating");
rating.enable(); // it will enable the rating control
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating" ></div>
<script>
$("#rating").ejmRating();       
$(function(){
// To enable the Rating control
$("#rating").ejmRating("enable");
});   
</script>{% endhighlight %}




### getValue<span class="signature">()</span>
{:#methods:getvalue}




To get the current value.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating"></div>
<script>
$(function(){
// To get the instance of rating control
var rating = $("#rating").data("ejmRating");
rating.getValue(); // it will return the current value of rating
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script>
// To get the current value of Rating control
$("#rating").ejmRating("getValue");     
</script>{% endhighlight %}




### hide<span class="signature">()</span>
{:#methods:hide}




To hide the rating.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating" ></div>
<script>
$(function(){
// To get the instance of the rating control
var rating = $("#rating").data("ejmRating");
rating.hide(); // it will hide the rating control
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating" ></div>
<script>
$("#rating").ejmRating();       
$(function(){
// To hide the Rating control
$("#rating").ejmRating("hide"); 
});
</script>{% endhighlight %}




### reset<span class="signature">()</span>
{:#methods:reset}




To reset the value.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating"></div>
<script>
$(function(){
// To get the instance of rating control
var rating = $("#rating").data("ejmRating");
rating.reset(); // it will reset the value of rating
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script>
// To reset value of Rating control
$("#rating").ejmRating("reset");        
</script>{% endhighlight %}




### setValue<span class="signature">()</span>
{:#methods:setvalue}




To set the value.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating"></div>
<script>
$(function(){
// To get the instance of rating control
var rating = $("#rating").data("ejmRating");
rating.setValue(3); // it will set the value of rating
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script>
// To set the value of Rating control
$("#rating").ejmRating("setValue",3);   
</script>{% endhighlight %}




### show<span class="signature">()</span>
{:#methods:show}




To show the rating.



Example
{:.example}


{% highlight html %} 
<div id="rating" data-role="ejmrating" ></div>
<script>
$(function(){
// To get the instance of the rating control
var rating = $("#rating").data("ejmRating");
rating.show(); // it will show the rating control
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating" ></div>
<script>
$("#rating").ejmRating();       
$(function(){
// To show the Rating control
$("#rating").ejmRating("show");
});   
</script>{% endhighlight %}



## Events




### change
{:#events:change}




Event triggers when the value changed.

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
<td class="description last">Event parameters from rating.
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
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value.</td>
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
<div id="rating" data-role="ejmrating" data-ej-change="onChange"></div>
<script> 
// change event for Rating  
function onChange(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script>
//change event for Rating
$("#rating").ejmRating({
  change: function (args) { //handle the event 
}
});           
</script>{% endhighlight %}




### tap
{:#events:tap}




Event triggers when touch happens on the control.

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
<td class="description last">Event parameters from rating.
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
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value.</td>
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
<div id="rating" data-role="ejmrating" data-ej-tap="onTap"></div>
<script> 
// Change event for Rating  
function onTap(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script> 
//Change event for Rating
$("#rating").ejmRating({
 tap: function (args) { //handle the event 
}
});     
</script>                 {% endhighlight %}




### touchMove
{:#events:touchmove}




Event triggers when touch move happens on the control.

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
<td class="description last">Event parameters from rating.
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
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the current element associated value.</td>
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
<div id="rating" data-role="ejmrating" data-ej-touchmove="ontouchMove"></div>
<script> 
// Change event for Rating  
function ontouchMove(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
<div id="rating"></div>
<script>
//change event for Rating
$("#rating").ejmRating({
  touchMove: function (args) { //handle the event 
}
});           
</script>{% endhighlight %}



