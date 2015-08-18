---
layout: post
title: ejmGroupButton
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html GroupButton control.










$(element).ejmGroupButton<span class="signature">()</span>











Example
{:.example}


{% highlight html %} 
//Render groupbutton control by default with button behavior in unobtrusive way
<div data-role="ejmgroupbutton">
<button>ipad</button>
<button>ipod</button>
</div>
{% endhighlight %}


{% highlight html %} 
//Render groupbutton control by default with button behavior in obtrusive way
<div id="grpbtn" >
<button>ipad</button>
<button>ipod</button>
</div>
<script >
$("#grpbtn").ejmGroupButton();
</script >{% endhighlight %}


{% highlight html %} 
//Obtain radiobutton behavior for groupbutton control in unobtrusive way
<div data-role="ejmgroupbutton">
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
//Render groupbutton control by default with radiobutton behavior in obtrusive way
<div id="grpbtn" >
<label >
<input type="radio" data-role="none" />
ipad
</label >
<label >
<input type="radio" data-role="none" />
ipod
</label >
</div >
<script >
$("#grpbtn").ejmGroupButton();
</script >{% endhighlight %}


{% highlight html %} 
//Obtain checkbox behavior for groupbutton control in unobtrusive way
<div data-role="ejmgroupbutton">
<label>
<input type="checkbox"/>ipad
</label>
<label>
<input type="checkbox"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
//Obtain checkbox behavior for groupbutton control in obtrusive way
<div id="grpbtn" >
<label>
<input type="checkbox" data-role="none" />ipad
</label>
<label>
<input type="checkbox" data-role="none" />ipod
</label>
</div>
<script >
$("#grpbtn").ejmGroupButton();
</script >{% endhighlight %}







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








Sets the root class for GroupButton theme. This cssClass API helps to use custom skinning option for GroupButton control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-cssclass="customclass" >
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
//Set the cssClass property in obtrusive way.
// To set cssClass API value 
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton ({ cssClass: "customclass" });
</script>
{% endhighlight %}


{% highlight html %} 
// Get or set the cssClass, after initialization:
// Get the cssClass API value.          
  $("#grpbtn").ejmGroupButton ("option", "cssClass");                   
// Set the cssClass API
  $("#grpbtn").ejmGroupButton ("option", "cssClass", "customclass");{% endhighlight %}







### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}








Current model value to browser cookies for state maintenance. While refreshing the page, the model value applied from browser cookies retains.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-enablepersistence=true >
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
//Set the enablePersistence property in obtrusive way. 
// To set enablePersistence API value 
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton ({ enablePersistence: true });
</script>
{% endhighlight %}


{% highlight html %} 
// Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
  $("#grpbtn").ejmGroupButton ("option", "enablePersistence");                  
// Set the enablePersistence API
  $("#grpbtn").ejmGroupButton ("option", "enablePersistence", true);{% endhighlight %}







### imageclass<span class="type-signature type string">string</span>
{:#members:imageclass}








Specifies the groupbutton imageclass.




Default Value:
{:.param}






* null








Example
{:.example}


{% highlight html %} 
// Set the imageclass property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton">
<label data-ej-imageclass="class-ipad">
<input type="radio"/>ipad
</label>
<label data-ej-imageclass="class-ipod">
<input type="radio"/>ipod
</label>
</div>                {% endhighlight %}







### imageurl<span class="type-signature type string">string</span>
{:#members:imageurl}








Specifies the groupbutton imageurl.




Default Value:
{:.param}






* null








Example
{:.example}


{% highlight html %} 
// Set the imageurl property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton">
<label data-ej-imageurl="ipad.png">
<input type="radio"/>ipad
</label>
<label data-ej-imageurl="ipod.png">
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}







### items<span class="type-signature type string">string</span>
{:#members:items}








Specifies the groupbutton items in angular JS.




Default Value:
{:.param}






* null








Example
{:.example}


{% highlight html %} 
// Set the items imageurl property in obtrusive way.
<div id="grpbtn">
<script>
</div>
$("#group-button").ejmGroupButton({ items: [{ imageUrl: "style" }, { imageUrl: "image" }});
</script>{% endhighlight %}







### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}








Changes the rendering mode of the groupbutton. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
// Set the renderMode property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-rendermode="auto">
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
// Set the renderMode property in obtrusive way. 
// To set renderMode API value 
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$(function(){
$("#grpbtn").ejmGroupButton ({ renderMode: ej.mobile.RenderMode.Auto });        
});
</script>
{% endhighlight %}


{% highlight html %} 
// Get or set the rendermode, after initialization:
// Get the renderMode API value.                
 $("#grpbtn").ejmGroupButton ("option", "renderMode");                  
// Set the renderMode API
$("#grpbtn").ejmGroupButton ("option", "renderMode", ej.mobile.RenderMode.Auto);            {% endhighlight %}







### selectedItemIndex<span class="type-signature type number">number</span>
{:#members:selecteditemindex}








Specifies the item which one is to be selected initially.




Default Value:
{:.param}






* -1








Example
{:.example}


{% highlight html %} 
//Set the selectedItemIndex property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-selecteditemindex=1>
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
// Set selectedItemIndex on initialization in obtrusive way
// To set selectedItemIndex API value in obtrusive way
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton ({ selectedItemIndex: 1 });
</script>
{% endhighlight %}







### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Changes the theme of the groupbutton. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-theme="auto">
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
//Set the theme property in obtrusive way.
// To set theme API value 
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$(function(){
$("#grpbtn").ejmGroupButton ({ theme: ej.mobile.Theme.Auto });
});
</script>
{% endhighlight %}


{% highlight html %} 
// Get or set the theme, after initialization:
// Get the theme API value.             
  $("#grpbtn").ejmGroupButton ("option", "theme");                      
// Set the theme API
  $("#grpbtn").ejmGroupButton ("option", "theme", ej.mobile.Theme.Auto);{% endhighlight %}







### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}








Specifies whether to render the groupbutton based on the windowsphone's current accent color and device theme.




Default Value:
{:.param}






* false








Example
{:.example}


{% highlight html %} 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-windows-renderdefault=false>
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>{% endhighlight %}


{% highlight html %} 
// Set the windows mode renderDefault property in obtrusive way.
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton({"windows.renderDefault": false});
</script>
{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#grpbtn").ejmGroupButton("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#grpbtn").ejmGroupButton("option", "windows.renderDefault", false); {% endhighlight %}





## Methods








### destroy<span class="signature">()</span>
{:#methods:destroy}








destroy the GroupButton widget all events bound using this._on will be unbind automatically and bring the control to pre-init state.





Example
{:.example}


{% highlight html %} 
<div id="grpbtn" >
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>
<script> 
// Get the instance of the group button
var grpObj = $("#grpbtn").data("ejmGroupButton");
grpObj.destroy();
</script>{% endhighlight %}


{% highlight html %} 
<div id="grpbtn" data-role="ejmgroupbutton">
<label>
<input type="radio" />ipad
</label>
<label>
<input type="radio" />ipod
</label>
</div>
<script>
// destroy the GroupButton
$("#grpbtn").ejmGroupButton("destroy"); 
</script>{% endhighlight %}





## Events








### touchEnd
{:#events:touchend}








Event triggers when the touchend happens in the groupbutton

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
<td class="description last">Event parameters from groupbutton
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
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}text{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the selected button text</td>
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
// Define the touchend event in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-touchend="touchend">
<label>
<input type="radio" />ipad
</label>
<label>
<input type="radio" />ipod
</label>
</div>
<script>
// touchEnd event for groupbutton 
function touchend(args){ //handle the event 
}
</script>{% endhighlight %}


{% highlight html %} 
// Define the touchend event in obtrusive way.
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton({
touchEnd: function (args) { //handle the event 
}
});           
</script>{% endhighlight %}







### touchStart
{:#events:touchstart}








Event triggers when the touchstart happens in the groupbutton

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
<td class="description last">Event parameters from groupbutton
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
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}text{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current button text</td>
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
// Define the touchStart event in unobtrusive way.
<div id="grpbtn" data-role="ejmgroupbutton" data-ej-touchstart="touchstart">
<label>
<input type="radio"/>ipad
</label>
<label>
<input type="radio"/>ipod
</label>
</div>
<script>
// touchStart event for groupbutton 
function touchstart(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
// Define the touchStart event in obtrusive way.
<div id="grpbtn">
<label>
<input type="radio" data-role="none" />ipad
</label>
<label>
<input type="radio" data-role="none" />ipod
</label>
</div>
<script>
$("#grpbtn").ejmGroupButton({
touchStart: function (args) { //handle the event 
}
});     
</script>
{% endhighlight %}




