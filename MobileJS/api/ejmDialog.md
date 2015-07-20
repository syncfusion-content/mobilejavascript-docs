---
layout: post
title: ejmDialog
documentation: API
platform: js
metaname: 
metacontent: 
---

# Custom Design for Html Dialog control.





$(element).ejmDialog<span class="signature">()</span>






Example
{:.example}
<pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true" data-ej-title="Low Battery" >  <div>      10% of battery remaining  </div></div>   </code></pre>



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




Specifies whether to allow scrolling behavior for the contents.


Default Value:
{:.param}



* true




Example
{:.example}
<pre class="prettyprint"><code> //Set the allowScrolling property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-allowscrolling="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set allowScrolling on initialization. //To set allowScrolling API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, allowScrolling: true });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog allowScrolling, after initialization:
// Get the allowScrolling API value.     $("#dlg").ejmDialog ("option", "allowScrolling");                      // Set the allowScrolling API$("#dlg").ejmDialog ("option", "allowScrolling", true);       </script></code></pre>



### checkDOMChanges<span class="type-signature type boolean">boolean</span>




Specifies whether need to refresh scrollpanel rendered in the control when elements are added dynamically.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> //Set the checkDOMChanges property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-checkdomchanges="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set checkDOMChanges on initialization. //To set checkDOMChanges API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, checkDOMChanges: true });});</script> </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog checkDOMChanges, after initialization:
// Get the checkDOMChanges API value.    $("#dlg").ejmDialog ("option", "checkDOMChanges");                     // Set the checkDOMChanges API$("#dlg").ejmDialog ("option", "checkDOMChanges", true); </script></code></pre>



### cssClass<span class="type-signature type string">string</span>




Sets the root class for Dialog theme. This cssClass API helps to use custom skinning option for Dialog control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}
<pre class="prettyprint"><code> //Set the cssClass property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen= "true" data-ej-cssclass="customclass" >  <div>      10% of battery remaining  </div></div></code></pre><pre class="prettyprint"><code> // Set cssClass on initialization.   //To set cssClass API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, cssClass: "customclass" });});</script> </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog cssClass, after initialization:
  // Get the cssClass API value.  $("#dlg").ejmDialog ("option", "cssClass");                     // Set the cssClass API  $("#dlg").ejmDialog ("option", "cssClass", "customclass");        </script></code></pre>



### enableAnimation<span class="type-signature type boolean">boolean</span>




Enables or Disables animation effect on opening or closing the dialog.


Default Value:
{:.param}



* true




Example
{:.example}
<pre class="prettyprint"><code> //Set the enableAnimation property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enableanimation="false" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set enableAnimation on initialization. //To set enableAnimation API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAnimation: false });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog enableAnimation, after initialization:
// Get the enableAnimation API value.    $("#dlg").ejmDialog ("option", "enableAnimation");                     // Set the enableAnimation API$("#dlg").ejmDialog ("option", "enableAnimation", true);    </script></code></pre>



### enableAutoOpen<span class="type-signature type boolean">boolean</span>




Specifies whether to open the dialog on initial loading.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> //Set the enableAutoOpen property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true" >  <div>      10% of battery remaining  </div></div></code></pre><pre class="prettyprint"><code> // Set enableAutoOpen on initialization.   //To set enableAutoOpen API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true });});</script>                 </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog enableAutoOpen, after initialization:
  // Get the enableAutoOpen API value.    $("#dlg").ejmDialog ("option", "enableAutoOpen");                       // Set the enableAutoOpen API  $("#dlg").ejmDialog ("option", "enableAutoOpen", true);   </script></code></pre>



### enableModal<span class="type-signature type boolean">boolean</span>




Specifies whether to enable modal dialog.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> //Set the enableModal property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enableModal="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set enableModal property on initialization.   //To set enableModal API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, enableModal: true });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog enableModal, after initialization:
// Get the enableModal API value. $("#dlg").ejmDialog ("option", "enableModal");                 // Set the enableModal API$("#dlg").ejmDialog ("option", "enableModal", true);    </script></code></pre>



### enableNativeScrolling<span class="type-signature type boolean">boolean</span>




Specifies whether to enable device's native scroll behavior when scrolling is allowed.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> //Set the enableNativeScrolling property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enablenativescrolling="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set enableNativeScrolling on initialization. //To set enableNativeScrolling API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, enableNativeScrolling: true });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog enableNativeScrolling, after initialization:
// Get the enableNativeScrolling API value. $("#dlg").ejmDialog ("option", "enableNativeScrolling");                       // Set the enableNativeScrolling API$("#dlg").ejmDialog ("option", "enableNativeScrolling", true);   </script></code></pre>



### enablePersistence<span class="type-signature type boolean">boolean</span>




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> //Set the enablePersistence property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-enablepersistence="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set enablePersistence on initialization. //To set enablePersistence API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, enablePersistence: true });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog enablePersistence, after initialization:
// Get the enablePersistence API value.  $("#dlg").ejmDialog ("option", "enablePersistence");                   // Set the enablePersistence API$("#dlg").ejmDialog ("option", "enablePersistence", true);    </script></code></pre>



### leftButtonCaption<span class="type-signature type string">string</span>




Specifies the text of left button.


Default Value:
{:.param}



* Cancel




Example
{:.example}
<pre class="prettyprint"><code> //Set the leftButtonCaption property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-leftbuttoncaption="Close" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set leftButtonCaption on initialization. //To set leftButtonCaption API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, leftButtonCaption: "Close" });});</script> </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog leftButtonCaption, after initialization:
// Get the leftButtonCaption API value. $("#dlg").ejmDialog ("option", "leftButtonCaption");                   // Set the leftButtonCaption API$("#dlg").ejmDialog ("option", "leftButtonCaption", "Close");          </script></code></pre>



### mode<span class="type-signature type enum">enum</span>




Specifies the dialog mode to render.See <a href="global.html#Mode">Mode</a>


Default Value:
{:.param}



* ej.mobile.Rating.Mode.Alert.




Example
{:.example}
<pre class="prettyprint"><code> //Set the mode property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-mode="confirm" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set mode on initialization. //To set mode API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, mode: ej.mobile.Dialog.Mode.Confirm });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog mode, after initialization:
// Get the mode API value.       $("#dlg").ejmDialog ("option", "mode");                        // Set the mode API$("#dlg").ejmDialog ("option", "mode", ej.mobile.Dialog.Mode.Confirm);   </script></code></pre>



### renderMode<span class="type-signature type enum">enum</span>




Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}
<pre class="prettyprint"><code> //Set the rendermode property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-rendermode="auto" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set rendermode on initialization. //To set rendermode API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, renderMode: ej.mobile.RenderMode.Auto });});</script>                 </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog rendermode, after initialization:
// Get the rendermode API value.         $("#dlg").ejmDialog ("option", "renderMode");                  // Set the renderMode API$("#dlg").ejmDialog ("option", "renderMode", ej.mobile.RenderMode.Auto);           </script></code></pre>



### rightButtonCaption<span class="type-signature type string">string</span>




Specifies the text of right button.


Default Value:
{:.param}



* Continue




Example
{:.example}
<pre class="prettyprint"><code> //Set the rightButtonCaption property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-mode="confirm" data-ej-rightbuttoncaption="Ok" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set rightButtonCaption on initialization. //To set rightButtonCaption API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, mode:"confirm", rightButtonCaption: "Ok" });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog rightButtonCaption, after initialization:
// Get the rightButtonCaption API value.         $("#dlg").ejmDialog ("option", "rightButtonCaption");                  // Set the rightButtonCaption API$("#dlg").ejmDialog ("option", "rightButtonCaption", "Ok");  </script></code></pre>



### showButtons<span class="type-signature type boolean">boolean</span>




Specifies whether to show the buttons in the dialog.


Default Value:
{:.param}



* true




Example
{:.example}
<pre class="prettyprint"><code> //Set the showButtons property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-showbuttons="true" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set showButtons property on initialization.   //To set showButtons API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, showButtons: false });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog showButtons, after initialization:
// Get the showButtons API value.        $("#dlg").ejmDialog ("option", "showButtons");                 // Set the showButtons API$("#dlg").ejmDialog ("option", "showButtons", false);     </script></code></pre>



### targetHeight<span class="type-signature type string">string</span>




Specifies the target height.


Default Value:
{:.param}



* null




Example
{:.example}
<pre class="prettyprint"><code> //Set the targetHeight property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-targetheight="500" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set targetHeight on initialization. //To set targetHeight API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, targetHeight: 500 });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog targetHeight, after initialization:
// Get the targetHeight API value.       $("#dlg").ejmDialog ("option", "targetHeight");                        // Set the targetHeight API$("#dlg").ejmDialog ("option", "targetHeight", 500);   </script></code></pre>



### templateId<span class="type-signature type string">string</span>




Specifies ID of the element contains template contents.


Default Value:
{:.param}



* null




Example
{:.example}
<pre class="prettyprint"><code> //Set the templateId property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-templateid="temp" data-ej-enableautoopen="true" ></div><div id="temp" >10% of battery remaining</div></code></pre><pre class="prettyprint"><code> // Set templateId on initialization. //To set templateId API value '<div id="dlg" ><script>$(function(){$("#dlg").ejmDialog({ enableAutoOpen:true, templateId: "temp" });});</script> <div id="temp" >10% of battery remaining</div>                    </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog templateId, after initialization:
// Get the templateId API value.         $("#dlg").ejmDialog ("option", "templateId");                  // Set the templateId API$("#dlg").ejmDialog ("option", "templateId", "temp");       </script></code></pre>



### theme<span class="type-signature type enum">enum</span>




Specifies the theme.See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}
<pre class="prettyprint"><code> //Set the theme property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-theme="auto" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div></code></pre><pre class="prettyprint"><code> // Set theme on initialization. //To set theme API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, theme: ej.mobile.Theme.Auto });});</script>         </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog theme, after initialization:
// Get the theme API value. $("#dlg").ejmDialog ("option", "theme");                       // Set the theme API$("#dlg").ejmDialog ("option", "theme", ej.mobile.Theme.Auto);          </script></code></pre>



### title<span class="type-signature type string">string</span>




Specifies the title text.


Default Value:
{:.param}



* null




Example
{:.example}
<pre class="prettyprint"><code> //Set the title property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-title="Low Battery" data-ej-enableautoopen="true" >  <div>      10% of battery remaining  </div></div></code></pre><pre class="prettyprint"><code> // Set title on initialization.   //To set title API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ enableAutoOpen: true, title: "Low Battery" });});</script> </code></pre><pre class="prettyprint"><code> <script>//Get or set the Dialog title, after initialization:
  // Get the title API value.  $("#dlg").ejmDialog ("option", "title");                        // Set the title API  $("#dlg").ejmDialog ("option", "title", "Low Battery");        </script></code></pre>



### windows




Section for windows mode specific functionalities.






### windows.renderDefault<span class="type-signature type boolean">boolean</span>




Specifies whether to render control based on the windowsphone's current accent color and device theme.


Default Value:
{:.param}



* false




Example
{:.example}
<pre class="prettyprint"><code> // Set the windows mode renderDefault property in unobtrusive way.<div id="dlg" data-role="ejmdialog" data-ej-rendermode="windows" data-ej-windows-renderDefault=true data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div>            </code></pre><pre class="prettyprint"><code> // To set windows mode renderDefault property API value <div id="dlg">  <div>      10% of battery remaining  </div></div><script>$(function(){  $("#dlg").ejmDialog({ renderMode:"windows", enableAutoOpen: true, windows:{renderDefault: true}});});</script></code></pre><pre class="prettyprint"><code> <script>// Get or set the windows mode renderDefault API, after initialization:// Get the windows mode renderDefault value  $("#dlg").ejmDialog("option", "windows.renderDefault");   // Set the windows mode renderDefault value $("#dlg").ejmDialog("option", "windows.renderDefault", true); </script></code></pre>


## Methods




### close<span class="signature">()</span>




To close the dialog.



Example
{:.example}
<pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true"><div>10% of battery remaining</div></div><script>// To check whether the dialog is opened or not  $(function(){  var dialog = $("#dlg").data("ejmDialog");  dialog.close(); });</script></code></pre><pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true"><div>10% of battery remaining</div></div>// To close dialog control<script>$(function(){$("#dlg").ejmDialog("close");});</script></code></pre>



### isOpened<span class="signature">()</span>




To check whether the dialog is opened.



Example
{:.example}
<pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true"><div>10% of battery remaining</div></div><script>// To check whether the dialog is opened or not  $(function(){  var dialog = $("#dlg").data("ejmDialog");  dialog.isOpened(); });</script></code></pre><pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true"><div>10% of battery remaining</div></div>// To check whether the dialog is opened or not<script>$(function(){$("#dlg").ejmDialog("isOpened");});</script></code></pre>



### open<span class="signature">()</span>




To open the dialog



Example
{:.example}
<pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" data-ej-enableautoopen="true"><div>10% of battery remaining</div></div><script>// To check whether the dialog is opened or not  $(function(){  var dialog = $("#dlg").data("ejmDialog");  dialog.open(); });</script></code></pre><pre class="prettyprint"><code> <div id="dlg" data-role="ejmdialog" ><div>10% of battery remaining</div></div>// To open dialog control<script>$(function(){$("#dlg").ejmDialog("open");});</script></code></pre>


## Events




### beforeClose




Event triggers before dialog window get closed.
<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>argument</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">Event parameters from dialog.<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>cancel</code></td><td class="type"><span class="param-type">boolean</span></td><td class="description last">returns true if the event should be cancelled; otherwise, false.</td></tr><tr><td class="name"><code>type</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the name of the event.</td></tr><tr><td class="name"><code>model</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">returns the model value of the control.</td></tr><tr><td class="name"><code>title</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the title of the dialog.</td></tr></tbody></table></td></tr></tbody></table>


Example
{:.example}
<pre class="prettyprint"><code> //beforeClose event for Dialog<div id="dlg" data-role="ejmdialog" data-ej-beforeclose="beforeClose" data-ej-buttontap="alertClose" data-ej-enableautoopen="true" > <div>     10% of battery remaining </div></div><script> function alertClose(){$("#dlg").ejmDialog("close");}function beforeClose(){}</script></code></pre><pre class="prettyprint"><code> //beforeClose event for Dialog<div id="dlg" > <div>   10% of battery remaining </div></div><script> $("#dlg").ejmDialog({enableAutoOpen: true,buttonTap: function (args) {   $("#dlg").ejmDialog("close");},beforeClose: function (args) {   //handle the event }});</script></code></pre>



### buttonTap




Event triggers when tap happens on the button.
<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>argument</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">Event parameters from dialog.<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>cancel</code></td><td class="type"><span class="param-type">boolean</span></td><td class="description last">returns true if the event should be cancelled; otherwise, false.</td></tr><tr><td class="name"><code>type</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the name of the event.</td></tr><tr><td class="name"><code>model</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">returns the model value of the control.</td></tr><tr><td class="name"><code>text</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">returns the text of the button.</td></tr></tbody></table></td></tr></tbody></table>


Example
{:.example}
<pre class="prettyprint"><code> //buttonTap event for Dialog<div id="dlg" data-role="ejmdialog" data-ej-buttontap="buttonTap" data-ej-enableautoopen=true >  <div>      10% of battery remaining  </div></div><script> function buttonTap(){}</script></code></pre><pre class="prettyprint"><code> //buttonTap event for Dialog<div id="dlg"><div>  10% of battery remaining</div></div><script>$(function () {$("#dlg").ejmDialog({ enableAutoOpen: true, buttonTap: "buttonTap" });});function buttonTap(args) { //handle the event}</script></code></pre>



### close




Event triggers after dialog window get closed.
<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>argument</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">Event parameters from dialog.<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>cancel</code></td><td class="type"><span class="param-type">boolean</span></td><td class="description last">returns true if the event should be cancelled; otherwise, false.</td></tr><tr><td class="name"><code>type</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the name of the event.</td></tr><tr><td class="name"><code>model</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">returns the model value of the control.</td></tr><tr><td class="name"><code>title</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the title of the dialog.</td></tr></tbody></table></td></tr></tbody></table>


Example
{:.example}
<pre class="prettyprint"><code> //Close event for Dialog<div id="dlg" data-role="ejmdialog" data-ej-close="close" data-ej-buttontap="buttontap" data-ej-enableautoopen="true" ><div>10% of battery remaining</div></div><script> function buttontap(args){$("#dlg").ejmDialog("close");}function close(){}</script></code></pre><pre class="prettyprint"><code> //Close event for Dialog<div id="dlg"><div>10% of battery remaining</div></div><script> $(function(){$("#dlg").ejmDialog({ enableAutoOpen : true , buttonTap:"buttonTap" , close:"close" });});function buttonTap(args) { $("#dlg").ejmDialog("close");} function close() { //handle the event }               </code></pre>



### open




Event triggers after dialog window get opened.
<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>argument</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">Event parameters from dialog.<table class="params"><thead><tr><th>Name</th><th>Type</th><th class="last">Description</th></tr></thead><tbody><tr><td class="name"><code>cancel</code></td><td class="type"><span class="param-type">boolean</span></td><td class="description last">returns true if the event should be cancelled; otherwise, false.</td></tr><tr><td class="name"><code>type</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the name of the event.</td></tr><tr><td class="name"><code>model</code></td><td class="type"><span class="param-type">Object</span></td><td class="description last">returns the model value of the control.</td></tr><tr><td class="name"><code>title</code></td><td class="type"><span class="param-type">string</span></td><td class="description last">returns the title of the dialog.</td></tr></tbody></table></td></tr></tbody></table>


Example
{:.example}
<pre class="prettyprint"><code> //Open event for Dialog<div > <input data-role="ejmbutton" id="btn" data-ej-text="Click here to open dialog" data-ej-enableautoopen="true" data-ej-touchend="openDlg"></div><div id="dlg" data-role="ejmdialog" data-ej-open="open" ><div>    10% of battery remaining  </div></div><script> function openDlg(args) {$("#dlg").ejmDialog("open");}  function open(args) {       //handle the event}</script></code></pre><pre class="prettyprint"><code> //open event for Dialog<div>   <input data-role="ejmbutton" id="btn" data-ej-text="Click here to open dialog" data-ej-enableautoopen="true" data-ej-touchend="openDlg">  </div> <div id="dlg"> <div> 10% of battery remaining</div> </div> <script> $(function () {$("#dlg").ejmDialog({ open: "open" });});function openDlg(args) {$("#dlg").ejmDialog("open");}function open(args) {    //handle the event  }</script> </code></pre>


