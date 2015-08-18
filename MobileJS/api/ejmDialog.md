---
layout: post
title: ejmDialog
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Dialog control.





$(element).ejmDialog<span class="signature">()</span>






Example
{:.example}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true" data-ej-title="Low Battery" >
  <div>
      10% of battery remaining
  </div>
</div>   {% endhighlight %}




Requires
{:.require}


* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

* module:ej.mobile.button

* module:ej.mobile.header

* module:ej.mobile.scrollbar

* module:ej.mobile.scrollpanel


## Members




### allowScrolling<span class="type-signature type boolean">boolean</span>
{:#members:allowscrolling}




Specifies whether to allow scrolling behavior for the contents.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the allowScrolling property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-allowscrolling="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set allowScrolling on initialization. 
//To set allowScrolling API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, allowScrolling: true });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog allowScrolling, after initialization:
// Get the allowScrolling API value.    
 $("#dlg").ejmDialog ("option", "allowScrolling");                      
// Set the allowScrolling API
$("#dlg").ejmDialog ("option", "allowScrolling", true);       
</script>{% endhighlight %}




### checkDOMChanges<span class="type-signature type boolean">boolean</span>
{:#members:checkdomchanges}




Specifies whether need to refresh scrollpanel rendered in the control when elements are added dynamically.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the checkDOMChanges property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-checkdomchanges="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set checkDOMChanges on initialization. 
//To set checkDOMChanges API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, checkDOMChanges: true });
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog checkDOMChanges, after initialization:
// Get the checkDOMChanges API value.   
 $("#dlg").ejmDialog ("option", "checkDOMChanges");                     
// Set the checkDOMChanges API
$("#dlg").ejmDialog ("option", "checkDOMChanges", true); 
</script>{% endhighlight %}




### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Dialog theme. This cssClass API helps to use custom skinning option for Dialog control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen= "true" data-ej-cssclass="customclass" >
  <div>
      10% of battery remaining
  </div>
</div>{% endhighlight %}


{% highlight html %} 
// Set cssClass on initialization. 
  //To set cssClass API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, cssClass: "customclass" });
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog cssClass, after initialization:
  // Get the cssClass API value.
  $("#dlg").ejmDialog ("option", "cssClass");                   
  // Set the cssClass API
  $("#dlg").ejmDialog ("option", "cssClass", "customclass");        
</script>{% endhighlight %}




### enableAnimation<span class="type-signature type boolean">boolean</span>
{:#members:enableanimation}




Enables or Disables animation effect on opening or closing the dialog.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the enableAnimation property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enableanimation="false" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set enableAnimation on initialization. 
//To set enableAnimation API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAnimation: false });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog enableAnimation, after initialization:
// Get the enableAnimation API value.   
 $("#dlg").ejmDialog ("option", "enableAnimation");                     
// Set the enableAnimation API
$("#dlg").ejmDialog ("option", "enableAnimation", true);    
</script>{% endhighlight %}




### enableAutoOpen<span class="type-signature type boolean">boolean</span>
{:#members:enableautoopen}




Specifies whether to open the dialog on initial loading.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableAutoOpen property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true" >
  <div>
      10% of battery remaining
  </div>
</div>{% endhighlight %}


{% highlight html %} 
// Set enableAutoOpen on initialization. 
  //To set enableAutoOpen API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true });
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog enableAutoOpen, after initialization:
  // Get the enableAutoOpen API value.  
  $("#dlg").ejmDialog ("option", "enableAutoOpen");                     
  // Set the enableAutoOpen API
  $("#dlg").ejmDialog ("option", "enableAutoOpen", true);   
</script>{% endhighlight %}




### enableModal<span class="type-signature type boolean">boolean</span>
{:#members:enablemodal}




Specifies whether to enable modal dialog.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableModal property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enableModal="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set enableModal property on initialization. 
  //To set enableModal API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, enableModal: true });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog enableModal, after initialization:
// Get the enableModal API value.
 $("#dlg").ejmDialog ("option", "enableModal");                 
// Set the enableModal API
$("#dlg").ejmDialog ("option", "enableModal", true);    
</script>{% endhighlight %}




### enableNativeScrolling<span class="type-signature type boolean">boolean</span>
{:#members:enablenativescrolling}




Specifies whether to enable device's native scroll behavior when scrolling is allowed.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableNativeScrolling property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enablenativescrolling="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set enableNativeScrolling on initialization. 
//To set enableNativeScrolling API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, enableNativeScrolling: true });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog enableNativeScrolling, after initialization:
// Get the enableNativeScrolling API value.
 $("#dlg").ejmDialog ("option", "enableNativeScrolling");                       
// Set the enableNativeScrolling API
$("#dlg").ejmDialog ("option", "enableNativeScrolling", true);   
</script>{% endhighlight %}




### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-enablepersistence="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set enablePersistence on initialization. 
//To set enablePersistence API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, enablePersistence: true });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog enablePersistence, after initialization:
// Get the enablePersistence API value. 
 $("#dlg").ejmDialog ("option", "enablePersistence");                   
// Set the enablePersistence API
$("#dlg").ejmDialog ("option", "enablePersistence", true);    
</script>{% endhighlight %}




### leftButtonCaption<span class="type-signature type string">string</span>
{:#members:leftbuttoncaption}




Specifies the text of left button.


Default Value:
{:.param}



* Cancel




Example
{:.example}


{% highlight html %} 
//Set the leftButtonCaption property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-leftbuttoncaption="Close" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set leftButtonCaption on initialization. 
//To set leftButtonCaption API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, leftButtonCaption: "Close" });
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog leftButtonCaption, after initialization:
// Get the leftButtonCaption API value.
 $("#dlg").ejmDialog ("option", "leftButtonCaption");                   
// Set the leftButtonCaption API
$("#dlg").ejmDialog ("option", "leftButtonCaption", "Close");          
</script>{% endhighlight %}




### mode<span class="type-signature type enum">enum</span>
{:#members:mode}




Specifies the dialog mode to render.See <a href="global.html#Mode">Mode</a>


Default Value:
{:.param}



* ej.mobile.Rating.Mode.Alert.




Example
{:.example}


{% highlight html %} 
//Set the mode property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-mode="confirm" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set mode on initialization. 
//To set mode API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, mode: ej.mobile.Dialog.Mode.Confirm });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog mode, after initialization:
// Get the mode API value.      
 $("#dlg").ejmDialog ("option", "mode");                        
// Set the mode API
$("#dlg").ejmDialog ("option", "mode", ej.mobile.Dialog.Mode.Confirm);   
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
//Set the rendermode property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-rendermode="auto" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set rendermode on initialization. 
//To set rendermode API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, renderMode: ej.mobile.RenderMode.Auto });
});
</script>                 {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog rendermode, after initialization:
// Get the rendermode API value.        
 $("#dlg").ejmDialog ("option", "renderMode");                  
// Set the renderMode API
$("#dlg").ejmDialog ("option", "renderMode", ej.mobile.RenderMode.Auto);           
</script>{% endhighlight %}




### rightButtonCaption<span class="type-signature type string">string</span>
{:#members:rightbuttoncaption}




Specifies the text of right button.


Default Value:
{:.param}



* Continue




Example
{:.example}


{% highlight html %} 
//Set the rightButtonCaption property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-mode="confirm" data-ej-rightbuttoncaption="Ok" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set rightButtonCaption on initialization. 
//To set rightButtonCaption API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, mode:"confirm", rightButtonCaption: "Ok" });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog rightButtonCaption, after initialization:
// Get the rightButtonCaption API value.        
 $("#dlg").ejmDialog ("option", "rightButtonCaption");                  
// Set the rightButtonCaption API
$("#dlg").ejmDialog ("option", "rightButtonCaption", "Ok");  
</script>{% endhighlight %}




### showButtons<span class="type-signature type boolean">boolean</span>
{:#members:showbuttons}




Specifies whether to show the buttons in the dialog.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the showButtons property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-showbuttons="true" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set showButtons property on initialization. 
  //To set showButtons API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, showButtons: false });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog showButtons, after initialization:
// Get the showButtons API value.       
 $("#dlg").ejmDialog ("option", "showButtons");                 
// Set the showButtons API
$("#dlg").ejmDialog ("option", "showButtons", false);     
</script>{% endhighlight %}




### targetHeight<span class="type-signature type string">string</span>
{:#members:targetheight}




Specifies the target height.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the targetHeight property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-targetheight="500" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set targetHeight on initialization. 
//To set targetHeight API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, targetHeight: 500 });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog targetHeight, after initialization:
// Get the targetHeight API value.      
 $("#dlg").ejmDialog ("option", "targetHeight");                        
// Set the targetHeight API
$("#dlg").ejmDialog ("option", "targetHeight", 500);   
</script>{% endhighlight %}




### templateId<span class="type-signature type string">string</span>
{:#members:templateid}




Specifies ID of the element contains template contents.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the templateId property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-templateid="temp" data-ej-enableautoopen="true" >
</div>
<div id="temp" >
10% of battery remaining
</div>{% endhighlight %}


{% highlight html %} 
// Set templateId on initialization. 
//To set templateId API value '
<div id="dlg" >
<script>
$(function(){
$("#dlg").ejmDialog({ enableAutoOpen:true, templateId: "temp" });
});
</script> 
<div id="temp" >
10% of battery remaining
</div>                    {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog templateId, after initialization:
// Get the templateId API value.        
 $("#dlg").ejmDialog ("option", "templateId");                  
// Set the templateId API
$("#dlg").ejmDialog ("option", "templateId", "temp");       
</script>{% endhighlight %}




### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Specifies the theme.See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-theme="auto" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>{% endhighlight %}


{% highlight html %} 
// Set theme on initialization. 
//To set theme API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, theme: ej.mobile.Theme.Auto });
});
</script>         {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog theme, after initialization:
// Get the theme API value.
 $("#dlg").ejmDialog ("option", "theme");                       
// Set the theme API
$("#dlg").ejmDialog ("option", "theme", ej.mobile.Theme.Auto);          
</script>{% endhighlight %}




### title<span class="type-signature type string">string</span>
{:#members:title}




Specifies the title text.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the title property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-title="Low Battery" data-ej-enableautoopen="true" >
  <div>
      10% of battery remaining
  </div>
</div>{% endhighlight %}


{% highlight html %} 
// Set title on initialization. 
  //To set title API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ enableAutoOpen: true, title: "Low Battery" });
});
</script> {% endhighlight %}


{% highlight html %} 
<script>
//Get or set the Dialog title, after initialization:
  // Get the title API value.
  $("#dlg").ejmDialog ("option", "title");                      
  // Set the title API
  $("#dlg").ejmDialog ("option", "title", "Low Battery");        
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
// Set the windows mode renderDefault property in unobtrusive way.
<div id="dlg" data-role="ejmdialog" data-ej-rendermode="windows" data-ej-windows-renderDefault=true data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>            {% endhighlight %}


{% highlight html %} 
// To set windows mode renderDefault property API value 
<div id="dlg">
  <div>
      10% of battery remaining
  </div>
</div>
<script>
$(function(){
  $("#dlg").ejmDialog({ renderMode:"windows", enableAutoOpen: true, windows:{renderDefault: true}});
});
</script>{% endhighlight %}


{% highlight html %} 
<script>
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#dlg").ejmDialog("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#dlg").ejmDialog("option", "windows.renderDefault", true); 
</script>{% endhighlight %}



## Methods




### close<span class="signature">()</span>
{:#methods:close}




To close the dialog.



Example
{:.example}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true">
<div>
10% of battery remaining
</div>
</div>
<script>
// To check whether the dialog is opened or not
  $(function(){
  var dialog = $("#dlg").data("ejmDialog");
  dialog.close(); 
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true">
<div>
10% of battery remaining
</div>
</div>
// To close dialog control
<script>
$(function(){
$("#dlg").ejmDialog("close");
});
</script>{% endhighlight %}




### isOpened<span class="signature">()</span>
{:#methods:isopened}




To check whether the dialog is opened.



Example
{:.example}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true">
<div>
10% of battery remaining
</div>
</div>
<script>
// To check whether the dialog is opened or not
  $(function(){
  var dialog = $("#dlg").data("ejmDialog");
  dialog.isOpened(); 
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true">
<div>
10% of battery remaining
</div>
</div>
// To check whether the dialog is opened or not
<script>
$(function(){
$("#dlg").ejmDialog("isOpened");
});
</script>{% endhighlight %}




### open<span class="signature">()</span>
{:#methods:open}




To open the dialog



Example
{:.example}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true">
<div>
10% of battery remaining
</div>
</div>
<script>
// To check whether the dialog is opened or not
  $(function(){
  var dialog = $("#dlg").data("ejmDialog");
  dialog.open(); 
});
</script>{% endhighlight %}


{% highlight html %} 
<div id="dlg" data-role="ejmdialog" >
<div>
10% of battery remaining
</div>
</div>
// To open dialog control
<script>
$(function(){
$("#dlg").ejmDialog("open");
});
</script>{% endhighlight %}



## Events




### beforeClose
{:#events:beforeclose}




Event triggers before dialog window get closed.

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
<td class="description last">Event parameters from dialog.
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
<td class="name">{% highlight html %}title{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the title of the dialog.</td>
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
//beforeClose event for Dialog
<div id="dlg" data-role="ejmdialog" data-ej-beforeclose="beforeClose" data-ej-buttontap="alertClose" data-ej-enableautoopen="true" >
 <div>
     10% of battery remaining
 </div>
</div>
<script> 
function alertClose(){
$("#dlg").ejmDialog("close");
}
function beforeClose(){}
</script>{% endhighlight %}


{% highlight html %} 
//beforeClose event for Dialog
<div id="dlg" > 
<div>
   10% of battery remaining
 </div>
</div>
<script> 
$("#dlg").ejmDialog({
enableAutoOpen: true,
buttonTap: function (args) {
   $("#dlg").ejmDialog("close");
},
beforeClose: function (args) {
   //handle the event 
}
});
</script>{% endhighlight %}




### buttonTap
{:#events:buttontap}




Event triggers when tap happens on the button.

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
<td class="description last">Event parameters from dialog.
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
<td class="name">{% highlight html %}text{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the text of the button.</td>
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
//buttonTap event for Dialog
<div id="dlg" data-role="ejmdialog" data-ej-buttontap="buttonTap" data-ej-enableautoopen=true >
  <div>
      10% of battery remaining
  </div>
</div>
<script> 
function buttonTap(){}
</script>{% endhighlight %}


{% highlight html %} 
//buttonTap event for Dialog
<div id="dlg">
<div>
  10% of battery remaining
</div>
</div>
<script>
$(function () {
$("#dlg").ejmDialog({ enableAutoOpen: true, buttonTap: "buttonTap" });
});
function buttonTap(args) { //handle the event
}
</script>{% endhighlight %}




### close
{:#events:close}




Event triggers after dialog window get closed.

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
<td class="description last">Event parameters from dialog.
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
<td class="name">{% highlight html %}title{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the title of the dialog.</td>
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
//Close event for Dialog
<div id="dlg" data-role="ejmdialog" data-ej-close="close" data-ej-buttontap="buttontap" data-ej-enableautoopen="true" >
<div>
10% of battery remaining
</div>
</div>
<script> 
function buttontap(args)
{
$("#dlg").ejmDialog("close");
}
function close(){}
</script>{% endhighlight %}


{% highlight html %} 
//Close event for Dialog
<div id="dlg">
<div>
10% of battery remaining
</div>
</div>
<script> 
$(function(){
$("#dlg").ejmDialog({ enableAutoOpen : true , buttonTap:"buttonTap" , close:"close" });
});
function buttonTap(args) { 
$("#dlg").ejmDialog("close");
} 
function close() { //handle the event 
}               {% endhighlight %}




### open
{:#events:open}




Event triggers after dialog window get opened.

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
<td class="description last">Event parameters from dialog.
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
<td class="name">{% highlight html %}title{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the title of the dialog.</td>
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
//Open event for Dialog
<div > 
<input data-role="ejmbutton" id="btn" data-ej-text="Click here to open dialog" data-ej-enableautoopen="true" data-ej-touchend="openDlg">
</div>
<div id="dlg" data-role="ejmdialog" data-ej-open="open" >
<div>
    10% of battery remaining
  </div>
</div>
<script> 
function openDlg(args) {
$("#dlg").ejmDialog("open");
}
  function open(args) {
       //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//open event for Dialog
<div> 
  <input data-role="ejmbutton" id="btn" data-ej-text="Click here to open dialog" data-ej-enableautoopen="true" data-ej-touchend="openDlg"> 
 </div> 
<div id="dlg"> 
<div> 
10% of battery remaining
</div> 
</div> 
<script> 
$(function () {
$("#dlg").ejmDialog({ open: "open" });
});
function openDlg(args) {
$("#dlg").ejmDialog("open");
}
function open(args) {
    //handle the event
  }
</script> {% endhighlight %}



