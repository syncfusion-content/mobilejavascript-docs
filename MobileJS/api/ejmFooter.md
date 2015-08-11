---
layout: post
title: ejmFooter
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Footer control.










$(element).ejmFooter<span class="signature">()</span>











Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="footer" ></div>
<script> 
// Create footer  
$("#footer").ejmFooter(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer" data-role="ejmfooter" ></div>
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


* module:ej.mobile.button




## Members








### android
{:#members:android}








Section for android rendermode specific functionalities.











### android.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:android-leftbuttonstyle}








Specifies the style for the left button i.e. back button or normal button button. See AndroidFooterLeftButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Android.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android leftButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set android leftButtonStyle on initialization. 
//To set android leftButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Android });   
$("#footer").ejmFooter({ showLeftButton:true});
$("#footer").ejmFooter({"android":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the android leftButtonStyle, after initialization:
// Get the android leftButtonStyle API value.           
 $("#footer").ejmFooter ("option", "android.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#footer").ejmFooter ("option", "android.leftButtonStyle","normal"); </code>
</pre>






### android.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:android-rightbuttonstyle}








Specifies the style for the right button i.e. back button or normal button. See AndroidFooterRightButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Android.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android rightButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="android" data-ej-showrightbutton="true" data-ej-android-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set android rightButtonStyle on initialization. 
//To set android rightButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Android });   
$("#footer").ejmFooter({ showRightButton:true});
$("#footer").ejmFooter({"android":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the android rightButtonStyle, after initialization:
// Get the android rightButtonStyle API value.          
 $("#footer").ejmFooter ("option", "android.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#footer").ejmFooter ("option", "android.rightButtonStyle","normal"); </code>
</pre>






### android.showLeftButton<span class="type-signature type boolean">boolean</span>
{:#members:android-showleftbutton}








Specifies whether to show the android left button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android showLeftButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="android" data-ej-android-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set android showLeftButton on initialization. 
//To set android showLeftButton API value 
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Android });   
$("#footer").ejmFooter({"android":{ "showRightButton": true }});        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "android.showLeftButton");                   
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "android.showLeftButton", true);                      </code>
</pre>






### android.showRightButton<span class="type-signature type boolean">boolean</span>
{:#members:android-showrightbutton}








Specifies whether to show the android right button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android showRightButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="android" data-ej-android-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set android showRightButton on initialization. 
//To set android showRightButton API value 
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Android });   
$("#footer").ejmFooter({"android":{ "showRightButton": true }});        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "android.showRightButton");                  
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "android.showRightButton", true);                     </code>
</pre>






### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}








Sets the root class for Footer theme. This cssClass API helps to use custom skinning option for Footer control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-cssclass="customclass" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set cssClass on initialization. 
//To set cssClass API value 
$("#footer").ejmFooter({ cssClass: "customclass" });    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
//Get the cssClass API value.           
 $("#footer").ejmFooter ("option", "cssClass");                 
//Set the cssClass API
$("#footer").ejmFooter ("option", "cssClass", "customclass");                   </code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}








Current model value to browser cookies for state maintenance. While refreshing the page, the model value applied from browser cookies retains.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enablePersistence property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-enablepersistence=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set enablePersistence on initialization. 
//To set enablePersistence API value 
$("#footer").ejmFooter({ enablePersistence: true });    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
//Get the enablePersistence API value.          
 $("#footer").ejmFooter ("option", "enablePersistence");                        
//Set the enablePersistence API
$("#footer").ejmFooter ("option", "enablePersistence", true);                   </code>
</pre>






### flat
{:#members:flat}








Section for flat rendermode specific functionalities.











### flat.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:flat-leftbuttonstyle}








Specifies the style for the flat left button i.e. back button or normal button or footer button. See FlatFooterLeftButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Flat.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat leftButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="flat" data-ej-showleftbutton="true" data-ej-flat-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set flat leftButtonStyle on initialization. 
//To set flat leftButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: "flat" });
$("#footer").ejmFooter({ showLeftButton:true});
$("#footer").ejmFooter({"flat":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the flat leftButtonStyle, after initialization:
// Get the flat leftButtonStyle API value.              
 $("#footer").ejmFooter ("option", "flat.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#footer").ejmFooter ("option", "flat.leftButtonStyle","normal");                 </code>
</pre>






### flat.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:flat-rightbuttonstyle}








Specifies the flat style for the right button i.e. back button or normal button. See FlatFooterRightButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Flat.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat rightButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="flat" data-ej-showrightbutton="true" data-ej-flat-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set flat rightButtonStyle on initialization. 
//To set flat rightButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: "flat" });
$("#footer").ejmFooter({ showRightButton:true});
$("#footer").ejmFooter({"flat":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the flat rightButtonStyle, after initialization:
// Get the flat rightButtonStyle API value.             
 $("#footer").ejmFooter ("option", "flat.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#footer").ejmFooter ("option", "flat.rightButtonStyle","normal"); </code>
</pre>






### flat.showLeftButton<span class="type-signature type boolean">boolean</span>
{:#members:flat-showleftbutton}








Specifies whether to show the flat left button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat showLeftButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="flat" data-ej-flat-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set flat showLeftButton on initialization. 
//To set flat showLeftButton API value 
$("#footer").ejmFooter({ renderMode: "flat" });
$("#footer").ejmFooter({"flat":{ "showLeftButton": true }});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "flat.showLeftButton");                      
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "flat.showLeftButton", true);                 </code>
</pre>






### flat.showRightButton<span class="type-signature type boolean">boolean</span>
{:#members:flat-showrightbutton}








Specifies whether to show the flat right button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat showRightButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="flat" data-ej-flat-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set flat showRightButton on initialization. 
//To set flat showRightButton API value 
$("#footer").ejmFooter({ renderMode: "flat" });
$("#footer").ejmFooter({"flat":{ "showRightButton": true }});   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "flat.showRightButton");                     
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "flat.showRightButton", true);                        </code>
</pre>






### hideForUnSupportedDevice<span class="type-signature type boolean">boolean</span>
{:#members:hideforunsupporteddevice}








If this property is set to true, footer will be visible for iOS7 rendermode alone.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the hideForUnSupportedDevice property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-hideforunsupporteddevice=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code>//Set hideForUnSupportedDevice on initialization.             
<div id="footer"></div>
<script>
//To set hideForUnSupportedDevice API value 
$(function(){
$("#footer").ejmFooter({ hideForUnSupportedDevice: true });     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the hideForUnSupportedDevice, after initialization:
// Get the hideForUnSupportedDevice API value.          
 $("#footer").ejmFooter ("option", "hideForUnSupportedDevice");                 
// Set the hideForUnSupportedDevice  API
$("#footer").ejmFooter ("option", "hideForUnSupportedDevice", "footer");            </code>
</pre>






### ios7
{:#members:ios7}








Section for ios7 rendermode specific functionalities.











### ios7.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:ios7-leftbuttonstyle}








Specifies the style for the ios7 left button i.e. back button or normal button or footer button. See IOS7FooterLeftButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.IOS7.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 leftButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="ios7" data-ej-showleftbutton="true" data-ej-ios7-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set ios7 leftButtonStyle on initialization. 
//To set ios7 leftButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: "ios7" });
$("#footer").ejmFooter({ showLeftButton:true});
$("#footer").ejmFooter({"ios7":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ios7 leftButtonStyle, after initialization:
// Get the ios7 leftButtonStyle API value.              
 $("#footer").ejmFooter ("option", "ios7.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#footer").ejmFooter ("option", "ios7.leftButtonStyle","normal"); </code>
</pre>






### ios7.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:ios7-rightbuttonstyle}








Specifies the ios7 style for the right button i.e. back button or normal button. See IOS7FooterRightButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.IOS7.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 rightButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="ios7" data-ej-showrightbutton="true" data-ej-ios7-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set ios7 rightButtonStyle on initialization. 
//To set ios7 rightButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: "ios7" });
$("#footer").ejmFooter({ showRightButton:true});
$("#footer").ejmFooter({"ios7":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ios7 rightButtonStyle, after initialization:
// Get the ios7 rightButtonStyle API value.             
 $("#footer").ejmFooter ("option", "ios7.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#footer").ejmFooter ("option", "ios7.rightButtonStyle","normal"); </code>
</pre>






### ios7.showLeftButton<span class="type-signature type boolean">boolean</span>
{:#members:ios7-showleftbutton}








Specifies whether to show the ios7 left button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 showLeftButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="ios7" data-ej-ios7-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set ios7 showLeftButton on initialization. 
//To set ios7 showLeftButton API value 
$("#footer").ejmFooter({ renderMode: "ios7" });
$("#footer").ejmFooter({"ios7":{ "showLeftButton": true }});    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "ios7.showLeftButton");                      
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "ios7.showLeftButton", true);                 </code>
</pre>






### ios7.showRightButton<span class="type-signature type boolean">boolean</span>
{:#members:ios7-showrightbutton}








Specifies whether to show the ios7 right button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 showRightButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="ios7" data-ej-ios7-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set ios7 showRightButton on initialization. 
//To set ios7 showRightButton API value 
$("#footer").ejmFooter({ renderMode: "ios7" });
$("#footer").ejmFooter({"flat":{ "showRightButton": true }});   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "ios7.showRightButton");                     
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "ios7.showRightButton", true);                        </code>
</pre>






### leftButtonCaption<span class="type-signature type string">string</span>
{:#members:leftbuttoncaption}








Specifies the caption for the left button. <a href="ejmFooter.html#showLeftButton">ejmFooter#showLeftButton</a>




Default Value:
{:.param}






* Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonCaption property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttoncaption="Home" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set leftButtonCaption on initialization. 
//To set leftButtonCaption API value 
$("#footer").ejmFooter({ showLeftButton: true });
$("#footer").ejmFooter({ leftButtonCaption: "Home" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the leftButtonCaption, after initialization:
//Get the leftButtonCaption API value.          
 $("#footer").ejmFooter ("option", "leftButtonCaption");                        
//Set the leftButtonCaption API
$("#footer").ejmFooter ("option", "leftButtonCaption", "Home");                 </code>
</pre>






### leftButtonNavigationUrl<span class="type-signature type string">string</span>
{:#members:leftbuttonnavigationurl}








Specifies the navigation url, which the page should go while clicking the left button. <a href="ejmFooter.html#showLeftButton">ejmFooter#showLeftButton</a>




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonNavigationUrl property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttonnavigationurl="" ></div>
</code>
</pre>
<pre class="prettyprint">
<code>//Set leftButtonNavigationUrl on initialization.             
<div id="footer"></div>
<script>
//To set leftButtonNavigationUrl API value 
$(function(){
$("#footer").ejmFooter({ leftButtonNavigationUrl: "" });        
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the leftButtonNavigationUrl, after initialization:
// Get the leftButtonNavigationUrl API value.           
 $("#footer").ejmFooter ("option", "leftButtonNavigationUrl");                  
// Set the leftButtonNavigationUrl  API
$("#footer").ejmFooter ("option", "leftButtonNavigationUrl", "footer");            </code>
</pre>






### leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:leftbuttonstyle}








Specifies the style for the left button i.e. back button or normal button or header buttton. See <a href="global.html#FooterLeftButtonStyle">FooterLeftButtonStyle</a>




Default Value:
{:.param}






* ej.mobile.Footer.FooterLeftButtonStyle.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set leftButtonStyle on initialization. 
//To set leftButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ showLeftButton:true});
$("#footer").ejmFooter({ leftButtonStyle: ej.mobile.Button.IOS7Style.Back });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the leftButtonStyle, after initialization:
// Get the leftButtonStyle API value.           
 $("#footer").ejmFooter ("option", "leftButtonStyle");                  
// Set the leftButtonStyle  API
$("#footer").ejmFooter ("option", "leftButtonStyle","normal"); </code>
</pre>






### position<span class="type-signature type enum">enum</span>
{:#members:position}








Specifies whether to keep the footer in fixed position i.e. bottom or in relative position depends on the other element's position. See <a href="global.html#Position">Position</a>




Default Value:
{:.param}






* ej.mobile.Footer.Position.Fixed








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-position="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set position on initialization. 
//To set position API value 
$(function(){
$("#footer").ejmFooter({ position: ej.mobile.Footer.Position.Fixed });  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the position, after initialization:
//Get the position API value.           
 $("#footer").ejmFooter ("option", "position");                 
//Set the position API
$("#footer").ejmFooter ("option", "position", ej.mobile.Footer.Position.Fixed);                 </code>
</pre>






### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}








Changes the rendering mode of the footer. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="auto" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set rendermode on initialization. 
//To set renderMode API value 
$(function(){
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Auto });      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
//Get the renderMode API value.         
 $("#footer").ejmFooter ("option", "renderMode");                       
//Set the renderMode API
$("#footer").ejmFooter ("option", "renderMode", ej.mobile.RenderMode.Auto);                     </code>
</pre>






### rightButtonCaption<span class="type-signature type string">string</span>
{:#members:rightbuttoncaption}








Specifies the caption for the right button. <a href="ejmFooter.html#showRightButton">ejmFooter#showRightButton</a>




Default Value:
{:.param}






* Right








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonCaption property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttoncaption="Next" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set rightButtonCaption on initialization. 
//To set rightButtonCaption API value 
$("#footer").ejmFooter({ showRightButton: true });      
$("#footer").ejmFooter({ rightButtonCaption: "Next" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rightButtonCaption, after initialization:
//Get the rightButtonCaption API value.         
 $("#footer").ejmFooter ("option", "rightButtonCaption");                       
//Set the rightButtonCaption API
$("#footer").ejmFooter ("option", "rightButtonCaption", "Next");                        </code>
</pre>






### rightButtonNavigationUrl<span class="type-signature type string">string</span>
{:#members:rightbuttonnavigationurl}








Specifies the navigation url, which the page should go while clicking the right button. <a href="ejmFooter.html#showRightButton">ejmFooter#showRightButton</a>




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonNavigationUrl property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttonnavigationurl="" ></div>
</code>
</pre>
<pre class="prettyprint">
<code>//Set rightButtonNavigationUrl on initialization.             
<div id="footer"></div>
<script>
//To set rightButtonNavigationUrl API value 
$(function(){
$("#footer").ejmFooter({ rightButtonNavigationUrl: "" });       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rightButtonNavigationUrl, after initialization:
// Get the rightButtonNavigationUrl API value.          
 $("#footer").ejmFooter ("option", "rightButtonNavigationUrl");                 
// Set the rightButtonNavigationUrl  API
$("#footer").ejmFooter ("option", "rightButtonNavigationUrl", "footer");</code>
</pre>






### rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:rightbuttonstyle}








Specifies the style for the right button i.e. back button or normal button. See <a href="global.html#FooterRightButtonStyle">FooterRightButtonStyle</a> ej.mobile.Footer.FooterRightButtonStyle.Footer





Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set rightButtonStyle on initialization. 
//To set rightButtonStyle API value 
$(function(){
$("#footer").ejmFooter({showRightButton:true});
$("#footer").ejmFooter({ rightButtonStyle: ej.mobile.Button.IOS7.Style.Footer });
});
</script></code>
</pre>
<pre class="prettyprint">
<code>      
//Get or set the rightButtonStyle, after initialization:
// Get the rightButtonStyle API value.          
 $("#footer").ejmFooter ("option", "rightButtonStyle");                 
// Set the rightButtonStyle  API
$("#footer").ejmFooter ("option", "rightButtonStyle","normal");                         </code>
</pre>






### showLeftButton<span class="type-signature type boolean">boolean</span>
{:#members:showleftbutton}








Specifies whether to show the left button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showLeftButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set showLeftButton on initialization. 
//To set showLeftButton API value 
$("#footer").ejmFooter({ showLeftButton: true });       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
//Get the showLeftButton API value.             
 $("#footer").ejmFooter ("option", "showLeftButton");                   
//Set the showLeftButton API
$("#footer").ejmFooter ("option", "showLeftButton", "true");                    </code>
</pre>






### showRightButton<span class="type-signature type boolean">boolean</span>
{:#members:showrightbutton}








Specifies whether to show the right button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showRightButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set showRightButton on initialization. 
//To set showRightButton API value 
$("#footer").ejmFooter({ showRightButton: true });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showRightButton, after initialization:
//Get the showRightButton API value.            
 $("#footer").ejmFooter ("option", "showRightButton");                  
//Set the showRightButton API
$("#footer").ejmFooter ("option", "showRightButton", true);                     </code>
</pre>






### showTitle<span class="type-signature type boolean">boolean</span>
{:#members:showtitle}








Specifies whether to show the title or not. if this property is set to false, title will be hide.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showTitle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-showtitle=false ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set showTitle on initialization. 
//To set showTitle API value 
$("#footer").ejmFooter({ showTitle: false });   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showTitle, after initialization:
//Get the showTitle API value.          
 $("#footer").ejmFooter ("option", "showTitle");                        
//Set the showTitle API
$("#footer").ejmFooter ("option", "showTitle", false);                          </code>
</pre>






### templateId<span class="type-signature type string">string</span>
{:#members:templateid}








Specifies the id of the element which is to be given as template.




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the templateId property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-templateid="footertemplate" ></div>
                        </code>
</pre>






### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Changes the theme of the footer. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-theme="auto" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set theme on initialization. 
//To set theme API value 
$(function(){
$("#footer").ejmFooter({ theme: ej.mobile.Theme.Auto  });       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
//Get the theme API value.              
 $("#footer").ejmFooter ("option", "theme");                    
//Set the leftButtonCaption API
$("#footer").ejmFooter ("option", "theme", ej.mobile.Theme.Auto );                      </code>
</pre>






### title<span class="type-signature type string">string</span>
{:#members:title}








Specifies the title's text.




Default Value:
{:.param}






* Title








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the title property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-title="Footer" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
//Set title on initialization. 
//To set title API value 
$("#footer").ejmFooter({ title: "Title" });     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the title, after initialization:
//Get the title API value.              
 $("#footer").ejmFooter ("option", "title");                    
//Set the title API
$("#footer").ejmFooter ("option", "title", "Footer");                   </code>
</pre>






### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:windows-leftbuttonstyle}








Specifies the style for the windows left button i.e. back button or normal button or footer button. See WindowsFooterLeftButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Windows.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows leftButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="windows" data-ej-showleftbutton="true" data-ej-windows-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set windows leftButtonStyle on initialization. 
//To set windows leftButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Windows });   
$("#footer").ejmFooter({ showLeftButton:true});
$("#footer").ejmFooter({"windows":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the windows leftButtonStyle, after initialization:
// Get the windows leftButtonStyle API value.           
 $("#footer").ejmFooter ("option", "windows.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#footer").ejmFooter ("option", "windows.leftButtonStyle","normal"); </code>
</pre>






### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}








Specifies whether to render the footer based on the windowsphone's current theme or not




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows mode renderDefault property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="windows" data-ej-windows-renderdefault=true ></div>
 </code>
</pre>






### windows.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:windows-rightbuttonstyle}








Specifies the windows style for the right button i.e. back button or normal button. See WindowsFooterRightButtonStyle




Default Value:
{:.param}






* ej.mobile.Button.Windows.Style.Back








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows rightButtonStyle property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="windows" data-ej-showrightbutton="true" data-ej-windows-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set windows rightButtonStyle on initialization. 
//To set windows rightButtonStyle API value 
$(function(){
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Windows });
$("#footer").ejmFooter({ showRightButton:true});
$("#footer").ejmFooter({"windows":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the windows rightButtonStyle, after initialization:
// Get the windows rightButtonStyle API value.          
 $("#footer").ejmFooter ("option", "windows.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#footer").ejmFooter ("option", "windows.rightButtonStyle","normal"); </code>
</pre>






### windows.showLeftButton<span class="type-signature type boolean">boolean</span>
{:#members:windows-showleftbutton}








Specifies whether to show the windows left button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows showLeftButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="windows" data-ej-windows-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set windows showLeftButton on initialization. 
//To set windows showLeftButton API value 
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Windows });
$("#footer").ejmFooter({"windows":{ "showLeftButton": true }}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "windows.showLeftButton");                   
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "windows.showLeftButton", true);                      </code>
</pre>






### windows.showRightButton<span class="type-signature type boolean">boolean</span>
{:#members:windows-showrightbutton}








Specifies whether to show the windows right button or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows showRightButton property in unobtrusive way.
<div id="footer" data-role="ejmfooter" data-ej-rendermode="windows" data-ej-windows-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
// Set windows showRightButton on initialization. 
//To set windows showRightButton API value 
$("#footer").ejmFooter({ renderMode: ej.mobile.RenderMode.Windows });
$("#footer").ejmFooter({"windows":{ "showRightButton": true }});        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#footer").ejmFooter ("option", "windows.showRightButton");                  
// Set the showLeftButton  API
$("#footer").ejmFooter ("option", "windows.showRightButton", true);                     </code>
</pre>




## Methods








### getTitle<span class="signature">()</span>
{:#methods:gettitle}








To get the footer's text





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="footer" data-role="ejmfooter" ></div>
<script>
$(function(){
//To get the instance of the footer
var footer = $("#footer").data("ejmFooter");
footer.getTitle(); //returns the footer's text
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
$(function(){
$("#footer").ejmFooter();       
//get the footer's current value
$("#footer").ejmFooter("getTitle");     
});
</script></code>
</pre>




## Events








### leftButtonTap
{:#events:leftbuttontap}








Event triggers when the left button is tapped. <a href="ejmFooter.html#showLeftButton">ejmFooter#showLeftButton</a>

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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current button text</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="footer" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttontap="onLeftButtonTap"></div>
<script> 
//leftButtonTap event for footer  
function onLeftButtonTap(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
$("#footer").ejmFooter({showLeftButton:true, leftButtonTap:"test"});
//LeftButtonTap event for footer
  function test() { //handle the event 
}
</script>                 </code>
</pre>






### rightButtonTap
{:#events:rightbuttontap}








Event triggers when the right button is tapped. <a href="ejmFooter.html#showRightButton">ejmFooter#showRightButton</a>

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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the groupbutton model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the current button text</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="footer" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttontap="onRightButtonTap"></div>
<script> 
//rightButtonTap event for footer  
function onRightButtonTap(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="footer"></div>
<script>
$("#footer").ejmFooter({showRightButton:true, rightButtonTap:"test"});
//rightButtonTap event for footer
  function test() { //handle the event 
}
</script>                 </code>
</pre>



