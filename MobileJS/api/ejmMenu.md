---
layout: post
title: ejmMenu
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Menu control.





$(element).ejmMenu<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code> 
// Create Menu control in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Create Menu control in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function(){
      $("menu").ejmMenu({targetId:"menuitem"});
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

* module:ej.mobile.button

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

<pre class="prettyprint">
<code>       
// Set allowScrolling property in unobtrusive way.      
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem"  data-ej-allowScrolling=true>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set allowScrolling property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div> 
<script>
        // Set allowScrolling on initialization. 
        // To set allowScrolling API value 
        $("#menu").ejmMenu ({targetId: "menuitem" , allowScrolling : true});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set allowScrolling, after initialization:
// Get the allowScrolling API value.            
 $("#menu").ejmMenu("option", "allowScrolling");                        
// Set the allowScrolling API
$("#menu").ejmMenu("option", "allowScrolling", true); 
</script>           </code>
</pre>



### android
{:#members:android}




Section for android mode specific functionalities.






### android.type<span class="type-signature type enum">enum</span>
{:#members:android-type}




Specifies android mode menu type.


Default Value:
{:.param}



* ej.mobile.Menu.Android.Type.Contextual.




Example
{:.example}

<pre class="prettyprint">
<code>   
// Set type in unobtrusive way.          
<div>
   <input id="menuitem" type="button" data-ej-rendermode="android" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode ="android" data-ej-android-type="contextual">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set type in obtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="android" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set type on initialization. 
// To set menu type API value 
$(function() {
$("#menu").ejmMenu ({ android:{type : ej.mobile.Menu.Android.Type.Contextual}, renderMode:"android",targetId:"menuitem"});
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set type, after initialization:
// Get type API value.          
 $("#menu").ejmMenu("option", "android.type");                  
// Set type API
$("#menu").ejmMenu("option", "android.type", ej.mobile.Menu.Android.Type.Contextual);    
</script>        </code>
</pre>



### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Menu theme. This cssClass API helps to use custom skinning option for Menu control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code>            
// Set cssClass in unobtrusive way. 
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-cssclass="customclass">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set cssClass in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu"  >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set cssClass on initialization. 
// To set cssClass API value 
$(function() {
$("#menu").ejmMenu ({ targetId:"menuitem", "cssClass" : "customclass" });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set cssClass, after initialization:
// Get cssClass API value.              
 $("#menu").ejmMenu("option", "cssClass");                      
// Set cssClass API
$("#menu").ejmMenu("option", "cssClass", "customclass"); 
</script>           </code>
</pre>



### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set enablePersistence in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-enablepersistence="true"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-enablepersistence="true">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set enablePersistence in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-enablepersistence="true" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set enablePersistence on initialization. 
        // To set enablePersistence API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , enablePersistence: true });                       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set enablePersistence after initialization:
// Get the enablePersistence API value.         
 $("#menu").ejmMenu("option", "enablePersistence");                     
// Set the enablePersistence API
$("#menu").ejmMenu("option", "enablePersistence", false);
</script>            </code>
</pre>



### height<span class="type-signature type int">int</span>
{:#members:height}




Specifies the height.



Example
{:.example}

<pre class="prettyprint">
<code>   
// Set height in unobtrusive way.          
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-height="100">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
<div>
// Set height in obtrusive way.
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set height on initialization. 
        // To set height API value 
        $("#menu").ejmMenu ({targetId : "menuitem" , height: 100 });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set height, after initialization:
// Get the height API value.            
 $("#menu").ejmMenu("option", "height");                        
// Set the height API
$("#menu").ejmMenu("option", "height", 100);            
</script></code>
</pre>



### ios7
{:#members:ios7}




Section for ios7 mode specific functionalities.






### ios7.cancelButtonColor<span class="type-signature type enum">enum</span>
{:#members:ios7-cancelbuttoncolor}




Specifies cancel button color in ios7 mode.


Default Value:
{:.param}



* ej.mobile.Menu.IOS7.CancelButtonColor.Blue.




Example
{:.example}

<pre class="prettyprint">
<code>            
// Set cancelButtonColor in unobtrusive way. 
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="ios7" data-ej-ios7-cancelButtonColor="blue">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set cancelButtonColor in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu" />
</div> 
<div id="menu"  >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set cancel button color on initialization. 
// To set cancel button color API value 
$(function() {
$("#menu").ejmMenu ({ targetId:"menuitem", renderMode:"ios7", ios7:{cancelButtonColor : ej.mobile.Menu.IOS7.CancelButtonColor.Blue} });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set cancel button color, after initialization:
// Get cancel button color API value.           
 $("#menu").ejmMenu("option", "ios7.cancelButtonColor");                        
// Set cancel button color API
$("#menu").ejmMenu("option", "ios7.cancelButtonColor", ej.mobile.Menu.IOS7.CancelButtonColor.Blue); 
</script>           </code>
</pre>



### ios7.cancelButtonText<span class="type-signature type string">string</span>
{:#members:ios7-cancelbuttontext}




Specifies cancel button text in ios7 mode.


Default Value:
{:.param}



* "Cancel"




Example
{:.example}

<pre class="prettyprint">
<code>      
// Set cancelButtonText in unobtrusive way.       
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menuitem" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="ios7" data-ej-ios7-type="animate" data-ej-ios7-cancelButtonText="Cancel">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set cancelButtonText in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu" />
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set cancel button text on initialization. 
// To set cancel button text API value 
$("#menu").ejmMenu ({ targetId:"menuitem", renderMode:"ios7", ios7:{cancelButtonText : "Cancel", type:"animate"} });    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set cancel button text, after initialization:
// Get cancel button text API value.            
 $("#menu").ejmMenu("option", "ios7.cancelButtonText");                 
// Set cancel button text API
$("#menu").ejmMenu("option", "ios7.cancelButtonText", true);  
</script>          </code>
</pre>



### ios7.showCancelButton<span class="type-signature type boolean">boolean</span>
{:#members:ios7-showcancelbutton}




Specifies whether to show cancel button in ios7 mode.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code>         
// Set showCancelButton in unobtrusive way.    
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu"/>
</div> 
<div id="menuitem" data-role="ejmmenu" data-ej-rendermode="ios7" data-ej-targetid="menuitem" data-ej-ios7-type="animate" data-ej-ios7-showCancelButton=true>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set showCancelButton in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu" />
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set show cancel button on initialization. 
// To set show cancel button  API value 
$("#menu").ejmMenu ({ targetId:"menuitem", renderMode:"ios7", ios7:{showCancelButton : true , type:"animate"}});        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set the show cancel button after initialization:
// Get the show cancel button API value.                
 $("#menu").ejmMenu("option", "ios7.showCancelButton");                 
// Set the show cancel button API
$("#menu").ejmMenu("option", "ios7.showCancelButton", true);
</script>            </code>
</pre>



### ios7.showTitle<span class="type-signature type boolean">boolean</span>
{:#members:ios7-showtitle}




Specifies whether to show title in ios7 mode.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code>             
// Set type in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menuitem" data-role="ejmmenu" data-ej-rendermode="ios7" data-ej-targetid="menuitem" data-ej-ios7-type="animate" data-ej-ios7-showtitle=true>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set type in obtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set showTitle property on initialization. 
// To set showTitle API value 
$("#menu").ejmMenu ({ targetId:"menuitem", renderMode:"ios7", ios7:{showTitle : true} });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set the show menu title, after initialization:
// Get the showTitle API value.         
 $("#menu").ejmMenu("option", "ios7.showTitle");                        
// Set the showTitle API
$("#menu").ejmMenu("option", "ios7.showTitle", true);  
</script>          </code>
</pre>



### ios7.title<span class="type-signature type string">string</span>
{:#members:ios7-title}




Specifies title text in ios7 mode.


Default Value:
{:.param}



* "Title"




Example
{:.example}

<pre class="prettyprint">
<code>      
// Set title for ios7 mode in unobtrusive way.       
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu"/>
</div> 
<div id="menuitem" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="ios7" data-ej-ios7-type="animate" data-ej-ios7-title="Title">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set title for ios7 mode in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-rendermode="ios7" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set menu title on initialization. 
        // To set menu title API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , renderMode : "ios7" , ios7:{title : "Title"} });                  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set title, after initialization:
// Get title API value.         
 $("#menu").ejmMenu("option", "ios7.title");                    
// Set title API
$("#menu").ejmMenu("option", "ios7.title", true);    
</script>        </code>
</pre>



### ios7.type<span class="type-signature type enum">enum</span>
{:#members:ios7-type}




Specifies ios7 mode menu type.


Default Value:
{:.param}



* ej.mobile.Menu.IOS7.Type.Auto.




Example
{:.example}

<pre class="prettyprint">
<code>          
// Set type in unobtrusive way.   
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menuitem" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="ios7" data-ej-ios7-type="animate" data-ej-ios7-type="auto">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
<div>
// Set type in obtrusive way.
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set type on initialization. 
// To set type API value 
$(function(){
$("#menu").ejmMenu ({ targetId:"menuitem", renderMode:"ios7", ios7:{type : ej.mobile.Menu.IOS7.Type.Auto} });
});
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set type, after initialization:
// Get type API value.          
 $("#menu").ejmMenu("option", "ios7.type");                     
// Set type API
$("#menu").ejmMenu("option", "ios7.type", ej.mobile.Menu.IOS7.Type.Auto);    
</script>        </code>
</pre>



### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set renderMode in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="auto"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="auto">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set renderMode in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="auto" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set rendermode on initialization. 
        // To set renderMode API value 
$(function(){
        $("#menu").ejmMenu ({ targetId : "menuitem" , renderMode: ej.mobile.RenderMode.Auto });                 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set rendermode, after initialization:
// Get renderMode API value.            
 $("#menu").ejmMenu("option", "renderMode");                    
// Set renderMode API
$("#menu").ejmMenu("option", "renderMode", ej.mobile.RenderMode.Auto);   
</script>         </code>
</pre>



### renderTemplate<span class="type-signature type boolean">boolean</span>
{:#members:rendertemplate}




Specifies whether need to render the control with the template contents.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code>             
// Set renderTemplate property in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-renderTemplate=false>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set renderTemplate property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set renderTemplate property on initialization. 
        // To set renderTemplate API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , renderTemplate: false});  
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set renderTemplate property, after initialization:
// Get the renderTemplate API value.            
 $("#menu").ejmMenu("option", "renderTemplate");                        
// Set the renderTemplate API
$("#menu").ejmMenu("option", "renderTemplate", false);  
</script>           </code>
</pre>



### showOn<span class="type-signature type string">string</span>
{:#members:showon}




Specifies in which action need to show the menu. See <a href="global.html#ShowOn">ShowOn</a>


Default Value:
{:.param}



* tap




Example
{:.example}

<pre class="prettyprint">
<code>       
// Set showOn property in unobtrusive way.      
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-showOn="taphold">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set showOn property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
&amp;ltscript>
        // Set showOn on initialization. 
        // To set showOn API value 
        $("#menu").ejmMenu ({targetId : "menuitem" , showOn: "taphold"});               
</script></code>
</pre>
<pre class="prettyprint">
<code> 
&amp;ltscript>
// Get or set showOn, after initialization:
// Get the showOn API value.            
 $("#menu").ejmMenu("option", "showOn");                        
// Set the showOn API
$("#menu").ejmMenu("option", "showOn", "taphold");  
</script>          </code>
</pre>



### showScrollbars<span class="type-signature type boolean">boolean</span>
{:#members:showscrollbars}




Specifies whether need to show the scroll bars when scrolling is allowed.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code>             
// Set showScrollbars in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-allowScrolling=true data-ej-showScrollbars=true>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set showScrollbars property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set showScrollbars property on initialization. 
        // To set showScrollbars API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , allowScrolling : true , showScrollbars: true});   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set showScrollbars property, after initialization:
// Get the showScrollbars API value.            
 $("#menu").ejmMenu("option", "showScrollbars");                        
// Set the showScrollbars API
$("#menu").ejmMenu("option", "showScrollbars", true);   
</script>         </code>
</pre>



### targetId<span class="type-signature type string">string</span>
{:#members:targetid}




Specifies ID of target element.



Example
{:.example}

<pre class="prettyprint">
<code>             
// Set target element ID in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set target element ID in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set target element ID on initialization. 
        // To set target element ID value 
        $("#menu").ejmMenu ({ targetId: "menuitem" });  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set target element ID, after initialization:
// Get the target element ID value.             
 $("#menu").ejmMenu("option", "targetId");                      
// Set the target element ID
$("#menu").ejmMenu("option", "targetId", "menu");  
</script>          </code>
</pre>



### templateId<span class="type-signature type string">string</span>
{:#members:templateid}




Specifies ID of the element contains template contents.


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code>             
// Set templateId property in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-templateid="menuTemplate" data-ej-rendertemplate=true></div>
  <div id="menuTemplate"> 
     <li>Get info</li>
     <li>Show in folder</li>
     <li>Delete</li>
  </div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set templateId property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu"></div>
  <div id="menuTemplate"> 
     <li>Get info</li>
     <li>Show in folder</li>
     <li>Delete</li>
  </div>
<script>
        // Set templateId property on initialization. 
        // To set templateId API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , renderTemplate : true , templateId: "menuTemplate"});                     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set templateId property, after initialization:
// Get the templateId API value.                
 $("#menu").ejmMenu("option", "templateId");                    
// Set the templateId API
$("#menu").ejmMenu("option", "templateId", "menuTemplate");   
</script>         </code>
</pre>



### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Specifies the theme. See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set theme in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-theme="auto"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-theme="auto">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set theme in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-theme="auto" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set theme on initialization. 
        // To set theme API value 
$(function(){
        $("#menu").ejmMenu ({ targetId : "menuitem" , theme: ej.mobile.Theme.Auto });           
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set theme, after initialization:
// Get theme API value.         
 $("#menu").ejmMenu("option", "theme");                 
// Set theme API value.
$("#menu").ejmMenu("option", "theme", ej.mobile.Theme.Auto);    
</script>        </code>
</pre>



### width<span class="type-signature type int">int</span>
{:#members:width}




Specifies the width.



Example
{:.example}

<pre class="prettyprint">
<code>        
// Set width in unobtrusive way.     
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-width=200 >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set width in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Set width on initialization. 
        // To set width API value 
        $("#menu").ejmMenu ({ targetId : "menuitem" , width: 200 });    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set width, after initialization:
// Get the width API value.             
 $("#menu").ejmMenu("option", "width");                 
// Set the width API
$("#menu").ejmMenu("option", "width", 200);  
</script>          </code>
</pre>



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

<pre class="prettyprint">
<code>             
// Set the windows mode renderDefault property in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="windows" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode ="windows" data-ej-windows-renderDefault=false>
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the windows mode renderDefault property in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="windows" />
</div> 
<div id="menu">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
        // Get or set the windows mode renderDefault API, after initialization:
        // Get the windows mode renderDefault value  
        $("#menu").ejmMenu ({ targetId : "menuitem" , renderMode : "windows" , windows:{renderDefault : false }});              
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set windows mode renderDefault, after initialization:
// Get the windows mode renderDefault value     
 $("#menu").ejmMenu("option", windows.renderDefault);                   
// Set the windows mode renderDefault value 
$("#menu").ejmMenu("option", "windows.renderDefault", false);
</script>            </code>
</pre>



### windows.type<span class="type-signature type enum">enum</span>
{:#members:windows-type}




Specifies windows mode menu type.


Default Value:
{:.param}



* ej.mobile.Menu.windows.Contextual.




Example
{:.example}

<pre class="prettyprint">
<code>             
// Set type in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="windows" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode ="windows" data-ej-windows-type="contextual">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set type in obtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="windows" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode ="windows" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Set type on initialization. 
// To set menu type API value 
$function(){
$("#menu").ejmMenu ({ windows:{type : ej.mobile.Menu.Windows.Type.Contextual} });                       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
// Get or set type, after initialization:
// Get type API value.          
 $("#menu").ejmMenu("option", "windows.type");                  
// Set type API
$("#menu").ejmMenu("option", "windows.type", ej.mobile.Menu.Windows.Type.Contextual);           
</script>      </code>
</pre>


## Methods




### addItem<span class="signature">()</span>
{:#methods:additem}




To add item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />
</div> 
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        var element = ej.buildTag('li');
        menuObj.addItem(element,3); // Add the given index menu item
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function(){
        // Add the given index menu item
        var element = ej.buildTag('li');
        $("#menu").ejmMenu("addItem", element,3);       
});
</script></code>
</pre>



### disable<span class="signature">()</span>
{:#methods:disable}




To disable the menu.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.disable(); // disable the menu control
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Disable the menu control
$(function (){
        $("#menu").ejmMenu("disable");  
});
</script></code>
</pre>



### disableItem<span class="signature">()</span>
{:#methods:disableitem}




To disable the item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function () {
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.disableItem(1); // disable the given index menu item
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
    
// Create menu control    
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Disable the given index menu item
$(function (){
        $("#menu").ejmMenu("disableItem", "1"); 
});
</script></code>
</pre>



### disableOverFlow<span class="signature">()</span>
{:#methods:disableoverflow}




To disable the overflow menu.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.disableOverflow(); // disableOverFlow menu item.
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
    
// Create menu control    
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Disable the overflow menu control
$(function (){
        $("#menu").ejmMenu("disableOverflow");  
});
</script></code>
</pre>



### disableOverFlowItem<span class="signature">()</span>
{:#methods:disableoverflowitem}




To disable overflow item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.disableOverflowItem(1); // disable the given index menu item in overflow menu
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
    
// Create menu control    
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Disable the given index menu item
$(function (){
        $("#menu").ejmMenu("disableOverflowItem", "1"); 
});
</script></code>
</pre>



### enable<span class="signature">()</span>
{:#methods:enable}




To enable the menu.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
var menuObj = $("#menu").data("ejmMenu");
menuObj.enable(); // enable the menu control
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
// Enable the menu control
$("#menu").ejmMenu("enable");   
</script></code>
</pre>



### enableItem<span class="signature">()</span>
{:#methods:enableitem}




To enable item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
var menuObj = $("#menu").data("ejmMenu");
menuObj.enableItem(1); // enable the given index menu item
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
    
// Create menu control    
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
// Enable the given index menu item
$("#menu").ejmMenu("enableItem", "1");  
</script></code>
</pre>



### enableOverFlow<span class="signature">()</span>
{:#methods:enableoverflow}




To enable the overflow menu.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.enableOverflow(); // enable the overflow menu
});
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
    
// Create menu control    
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Enable the overflow menu control
$(function (){
        $("#menu").ejmMenu("enableOverflow");   
});
</script></code>
</pre>



### enableOverFlowItem<span class="signature">()</span>
{:#methods:enableoverflowitem}




To enable overflow item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
var menuObj = $("#menu").data("ejmMenu");
menuObj.enableOverflowItem(1); // enable the overflow menu item.
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
// Enable the given index menu item
$("#menu").ejmMenu("enableOverflowItem", "1");  
</script></code>
</pre>



### hide<span class="signature">()</span>
{:#methods:hide}




To hide the menu.



Example
{:.example}

<pre class="prettyprint">
<code>      
// Create menu control       
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
var menuObj = $("#menu").data("ejmMenu");
menuObj.hide(); // hide the menu which is already opened
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
// Hide the menu which is already opened
$("#menu").ejmMenu("hide");     
</script></code>
</pre>



### removeItem<span class="signature">()</span>
{:#methods:removeitem}




To remove item in the given index.



Example
{:.example}

<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
// Create menu control
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
$(function (){
        var menuObj = $("#menu").data("ejmMenu");
        menuObj.removeItem(1); // remove the given index menu item
}):
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
// Create menu control
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// Remove the given index menu item
$(function (){
        $("#menu").ejmMenu("removeItem", "1");  
});
</script></code>
</pre>



### show<span class="signature">()</span>
{:#methods:show}




To show the menu.



Example
{:.example}

<pre class="prettyprint">
<code>     
// Create menu control        
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
var menuObj = $("#menu").data("ejmMenu");
menuObj.show(); // Show/Open the menu which is in hide state.
</script></code>
</pre>
<pre class="prettyprint">
<code>             
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
        
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script>
// Show/Open the menu which is in hide state.
$("#menu").ejmMenu("show");     
</script></code>
</pre>


## Events




### cancelButtonTouchEnd
{:#events:cancelbuttontouchend}




Event triggers when touch end happens on the cancel button in ios7 mode.

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
<td class="description last">Event parameters from menu.
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
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current menu list element.</td>
</tr>
<tr>
<td class="name"><code>text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current menu list element associated text.</td>
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
// Set hide method in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-rendermode="ios7" data-ej-ios7-type="animate" data-ej-ios7-cancelbuttontouchend="cancelbuttontouchend">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// hide event for menu&#65533;
function cancelbuttontouchend(args){ //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Set hide method in obtrusive way.
<div>
   <input id="menuitem" type="button" data-ej-rendermode="ios7" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// hide event for menu
$("#menu").ejmMenu({ targetId:"menuitem",renderMode:"ios7",ios7:{type:"animate",cancelButtonTouchEnd: function (args) { 
//handle the event
}}
});           </code>
</pre>



### hide
{:#events:hide}




Event triggers when the control get hided.

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
<td class="description last">Event parameters from menu.
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
// Set hide event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-hide="hide">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// hide event for menu
function hide(args){ 
       //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Set hide event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// hide event for menu
$("#menu").ejmMenu({ targetId:"menuitem", 
        hide: function (args) { 
        //handle the event 
  }
 });          
</script> </code>
</pre>



### load
{:#events:load}




Event triggers before the items loaded.

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
<td class="description last">Event parameters from menu.
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
// Set load event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="auto"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-load="load">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// load event for menu
function load(args){ 
                //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code>  
// Set load event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="auto"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script>
// load event for menu
$("#menu").ejmMenu({ targetId:"menuitem",
        load: function (args) { 
                        //handle the event 
                }
 });         
</script>  </code>
</pre>



### loadComplete
{:#events:loadcomplete}




Event triggers after the items loaded.

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
<td class="description last">Event parameters from menu.
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
// Set loadcomplete event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-loadcomplete="loadcomplete">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script> 
// loadcomplete event for menu
function loadcomplete(args){ 
        //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code>  
// Set loadcomplete event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script> 
// loadcomplete event for menu
$("#menu").ejmMenu({ targetId:"menuitem",
  loadComplete: function (args) { 
                //handle the event 
        }
 });           </code>
</pre>



### show
{:#events:show}




Event triggers when the control get shown.

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
<td class="description last">Event parameters from menu.
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
// Set show event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-show="show">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// show event for menu
function show(args){ 
        //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Set show event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// show event for menu
$("#menu").ejmMenu({ targetId:"menuitem", 
        show: function (args) { 
                //handle the event 
  }
 });      
</script>     </code>
</pre>



### touchEnd
{:#events:touchend}




Event triggers when touch end happens on the item.

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
<td class="description last">Event parameters from menu.
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
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current menu list element</td>
</tr>
<tr>
<td class="name"><code>text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current menu list element associated text</td>
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
// Set touchend event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-touchend="touchend">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script> 
// touchend event for menu
function touchend(args){ 
        //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Set touchend event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>

<script> 
// touchend event for menu
$("#menu").ejmMenu({ targetId:"menuitem",
  touchEnd: function (args) { 
     //handle the event 
  }
 });      
</script>     </code>
</pre>



### touchStart
{:#events:touchstart}




Event triggers when touch start happens on the item.

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
<td class="description last">Event parameters from menu.
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
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current menu list element</td>
</tr>
<tr>
<td class="name"><code>text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current menu list element associated text</td>
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
// Set touchstart event in unobtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" data-role="ejmmenu" data-ej-targetid="menuitem" data-ej-touchstart="touchstart">
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// touchStart event for menu
function touchstart(args){ 
        //handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Set touchstart event in obtrusive way.
<div>
   <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu"/>
</div> 
<div id="menu" >
  <ul> 
     <li data-ej-text="Get info"></li>
     <li data-ej-text="Show in folder"></li>
     <li data-ej-text="Delete"></li>
  </ul>
</div>
<script> 
// touchStart event for menu
$("#menu").ejmMenu({targetId:"menuitem" ,
  touchStart: function (args) { 
     //handle the event 
   }
 });           
</script></code>
</pre>


