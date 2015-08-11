---
layout: post
title: ejmHeader
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Header control.





$(element).ejmHeader<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="header" ></div>
<script> 
// Create header  
$("#header").ejmHeader(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header" data-role="ejmheader" ></div>
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






### android.backButtonImageClass<span class="type-signature type string">string</span>
{:#members:android-backbuttonimageclass}




Specifies the class name in which URL for the back button image will be set.


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the android mode backButtonImageClass property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-backbuttonimageclass="backimagecssclass" ></div>
 </code>
</pre>



### android.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:android-leftbuttonstyle}




Specifies the style for the left button i.e. back button or normal button button. See AndroidHeaderLeftButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Android.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showleftbutton="true" data-ej-android-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set android leftButtonStyle on initialization. 
//To set android leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"android":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the android leftButtonStyle, after initialization:
// Get the android leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "android.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "android.leftButtonStyle","normal"); </code>
</pre>



### android.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:android-rightbuttonstyle}




Specifies the style for the right button i.e. back button or normal button. See AndroidHeaderRightButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Android.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the android rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-showrightbutton="true" data-ej-android-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set android rightButtonStyle on initialization. 
//To set android rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"android":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the android rightButtonStyle, after initialization:
// Get the android rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "android.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "android.rightButtonStyle","normal"); </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-android-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set android showLeftButton on initialization. 
//To set android showLeftButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({"android":{ "showLeftButton": true }});  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "android.showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "android.showLeftButton", true);                      </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="android" data-ej-android-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set android showRightButton on initialization. 
//To set android showRightButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Android });   
$("#header").ejmHeader({"android":{ "showRightButton": true }});         
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "android.showRightButton");                  
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "android.showRightButton", true);                     </code>
</pre>



### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Header theme. This cssClass API helps to use custom skinning option for Header control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-cssclass="customclass" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set cssClass on initialization. 
//To set cssClass API value 
$("#header").ejmHeader({ cssClass:"customclass" });     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the header cssClass, after initialization:
// Get the cssClass API value.          
 $("#header").ejmHeader ("option", "cssClass");                 
// Set the cssClass API
$("#header").ejmHeader ("option", "cssClass", "customclass");            </code>
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
<div id="header" data-role="ejmheader" data-ej-enablepersistence=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set enablePersistence on initialization. 
//To set enablePersistence API value 
$("#header").ejmHeader({ enablePersistence:true });     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the header enablePersistence, after initialization:
// Get the enablePersistence API value.         
 $("#header").ejmHeader ("option", "enablePersistence");                        
// Set the enablePersistence API
$("#header").ejmHeader ("option", "enablePersistence", false);            </code>
</pre>



### flat
{:#members:flat}




Section for flat rendermode specific functionalities.






### flat.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:flat-leftbuttonstyle}




Specifies the style for the flat left button i.e. back button or normal button or header button. See FlatHeaderLeftButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Flat.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-showleftbutton="true" data-ej-flat-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set flat leftButtonStyle on initialization. 
//To set flat leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"flat":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the flat leftButtonStyle, after initialization:
// Get the flat leftButtonStyle API value.              
 $("#header").ejmHeader ("option", "flat.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "flat.leftButtonStyle","normal");                 </code>
</pre>



### flat.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:flat-rightbuttonstyle}




Specifies the flat style for the right button i.e. back button or normal button. See FlatHeaderRightButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Flat.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the flat rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-showrightbutton="true" data-ej-flat-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set flat rightButtonStyle on initialization. 
//To set flat rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"flat":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the flat rightButtonStyle, after initialization:
// Get the flat rightButtonStyle API value.             
 $("#header").ejmHeader ("option", "flat.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "flat.rightButtonStyle","normal"); </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-flat-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set flat showLeftButton on initialization. 
//To set flat showLeftButton API value 
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({"flat":{ "showLeftButton": true }});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "flat.showLeftButton");                      
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "flat.showLeftButton", true);                 </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="flat" data-ej-flat-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set flat showRightButton on initialization. 
//To set flat showRightButton API value 
$("#header").ejmHeader({ renderMode: "flat" });
$("#header").ejmHeader({"flat":{ "showRightButton": true }});   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "flat.showRightButton");                     
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "flat.showRightButton", true);                        </code>
</pre>



### hideForUnSupportedDevice<span class="type-signature type boolean">boolean</span>
{:#members:hideforunsupporteddevice}




If this property is set to true, header will be visible for iOS7 rendermode alone.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the hideForUnSupportedDevice property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-hideforunsupporteddevice=true ></div>
    </code>
</pre>
<pre class="prettyprint">
<code>//Set hideForUnSupportedDevice on initialization.             
<div id="header"></div>
<script>
//To set hideForUnSupportedDevice API value 
$(function(){
$("#header").ejmHeader({ hideForUnSupportedDevice: true });     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the hideForUnSupportedDevice, after initialization:
// Get the hideForUnSupportedDevice API value.          
 $("#header").ejmHeader ("option", "hideForUnSupportedDevice");                 
// Set the hideForUnSupportedDevice  API
$("#header").ejmHeader ("option", "hideForUnSupportedDevice", "Header");</code>
</pre>



### ios7
{:#members:ios7}




Section for ios7 rendermode specific functionalities.






### ios7.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:ios7-leftbuttonstyle}




Specifies the style for the ios7 left button i.e. back button or normal button or header button. See IOS7HeaderLeftButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.IOS7.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-showleftbutton="true" data-ej-ios7-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set ios7 leftButtonStyle on initialization. 
//To set ios7 leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"ios7":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ios7 leftButtonStyle, after initialization:
// Get the ios7 leftButtonStyle API value.              
 $("#header").ejmHeader ("option", "ios7.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "ios7.leftButtonStyle","normal"); </code>
</pre>



### ios7.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:ios7-rightbuttonstyle}




Specifies the ios7 style for the right button i.e. back button or normal button. See IOS7HeaderRightButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.IOS7.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the ios7 rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-showrightbutton="true" data-ej-ios7-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set ios7 rightButtonStyle on initialization. 
//To set ios7 rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"ios7":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ios7 rightButtonStyle, after initialization:
// Get the ios7 rightButtonStyle API value.             
 $("#header").ejmHeader ("option", "ios7.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "ios7.rightButtonStyle","normal"); </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-ios7-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set ios7 showLeftButton on initialization. 
//To set ios7 showLeftButton API value 
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({"ios7":{ "showLeftButton": true }});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "ios7.showLeftButton");                      
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "ios7.showLeftButton", true);                 </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="ios7" data-ej-ios7-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set ios7 showRightButton on initialization. 
//To set ios7 showRightButton API value 
$("#header").ejmHeader({ renderMode: "ios7" });
$("#header").ejmHeader({"ios7":{ "showRightButton": true }});   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "ios7.showRightButton");                     
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "ios7.showRightButton", true);                        </code>
</pre>



### leftButtonCaption<span class="type-signature type string">string</span>
{:#members:leftbuttoncaption}




Specifies the caption of the left button. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>


Default Value:
{:.param}



* Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonCaption property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showLeftbutton="true" data-ej-leftbuttoncaption="Home" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set leftButtonCaption on initialization. 
//To set leftButtonCaption API value 
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({ leftButtonCaption: "Home" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the LeftButtonCaption, after initialization:
// Get the leftButtonCaption API value.         
 $("#header").ejmHeader ("option", "leftButtonCaption");                        
// Set the leftButtonCaption  API
$("#header").ejmHeader ("option", "leftButtonCaption", "Home");                 </code>
</pre>



### leftButtonNavigationUrl<span class="type-signature type string">string</span>
{:#members:leftbuttonnavigationurl}




Specifies the navigation url, which the page should go while clicking the left button. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonNavigationUrl property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonnavigationurl="" ></div>
</code>
</pre>
<pre class="prettyprint">
<code>//Set leftButtonNavigationUrl on initialization.             
<div id="header"></div>
<script>
//To set leftButtonNavigationUrl API value 
$(function(){
$("#header").ejmHeader({ leftButtonNavigationUrl: "" });        
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the leftButtonNavigationUrl, after initialization:
// Get the leftButtonNavigationUrl API value.           
 $("#header").ejmHeader ("option", "leftButtonNavigationUrl");                  
// Set the leftButtonNavigationUrl  API
$("#header").ejmHeader ("option", "leftButtonNavigationUrl", "Header");</code>
</pre>



### leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:leftbuttonstyle}




Specifies the style for the left button i.e. back button or normal button or header buttton. See <a href="global.html#HeaderLeftButtonStyle">HeaderLeftButtonStyle</a>


Default Value:
{:.param}



* ej.mobile.Header.HeaderLeftButtonStyle.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set leftButtonStyle on initialization. 
//To set leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({ leftButtonStyle: ej.mobile.Button.IOS7Style.Back });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the leftButtonStyle, after initialization:
// Get the leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "leftButtonStyle");                  
// Set the leftButtonStyle  API
$("#header").ejmHeader ("option", "leftButtonStyle","normal"); </code>
</pre>



### position<span class="type-signature type enum">enum</span>
{:#members:position}




Specifies whether to keep the header in fixed position. i.e. top or in relative position depends on the other element's position. See <a href="global.html#Position">Position</a>


Default Value:
{:.param}



* ej.mobile.Header.Position.Fixed




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-position="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set position on initialization. 
//To set position API value 
$(function(){
$("#header").ejmHeader({ position: ej.mobile.Header.Position.Fixed });  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the position, after initialization:
// Get the position API value.          
 $("#header").ejmHeader ("option", "position");                 
// Set the position  API
$("#header").ejmHeader ("option", "position", ej.mobile.Header.Position.Fixed);                 </code>
</pre>



### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Changes the rendering mode of the header.See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="auto" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set rendermode on initialization. 
//To set renderMode API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Auto });      
});     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
 $("#header").ejmHeader ("option", "renderMode");                       
// Set the renderMode  API
$("#header").ejmHeader ("option", "renderMode", ej.mobile.RenderMode.Auto);                     </code>
</pre>



### rightButtonCaption<span class="type-signature type string">string</span>
{:#members:rightbuttoncaption}




Specifies the caption of the right button. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>


Default Value:
{:.param}



* Right




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonCaption property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttoncaption="Next" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set rightButtonCaption on initialization. 
//To set rightButtonCaption API value 
$("#header").ejmHeader({showRightButton:true});
$("#header").ejmHeader({ rightButtonCaption: "Next" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rightButtonCaption, after initialization:
// Get the rightButtonCaption API value.                
 $("#header").ejmHeader ("option", "rightButtonCaption");                       
// Set the rightButtonCaption  API
$("#header").ejmHeader ("option", "rightButtonCaption", "Next");                        </code>
</pre>



### rightButtonNavigationUrl<span class="type-signature type string">string</span>
{:#members:rightbuttonnavigationurl}




Specifies the navigation url, which the page should go while clicking the right button. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonNavigationUrl property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonnavigationurl="" ></div>
</code>
</pre>
<pre class="prettyprint">
<code>//Set rightButtonNavigationUrl on initialization.             
<div id="header"></div>
<script>
//To set rightButtonNavigationUrl API value 
$(function(){
$("#header").ejmHeader({ rightButtonNavigationUrl: "" });       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rightButtonNavigationUrl, after initialization:
// Get the rightButtonNavigationUrl API value.          
 $("#header").ejmHeader ("option", "rightButtonNavigationUrl");                 
// Set the rightButtonNavigationUrl  API
$("#header").ejmHeader ("option", "rightButtonNavigationUrl", "Header");</code>
</pre>



### rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:rightbuttonstyle}




Specifies the style for the right button i.e. back button or normal button. See <a href="global.html#HeaderRightButtonStyle">HeaderRightButtonStyle</a> ej.mobile.Header.HeaderRightButtonStyle.Header



Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set rightButtonStyle on initialization. 
//To set rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({showRightButton:true});
$("#header").ejmHeader({ rightButtonStyle: ej.mobile.Button.IOS7.Style.Header });
});
</script></code>
</pre>
<pre class="prettyprint">
<code>      
//Get or set the rightButtonStyle, after initialization:
// Get the rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "rightButtonStyle");                 
// Set the rightButtonStyle  API
$("#header").ejmHeader ("option", "rightButtonStyle","normal");                         </code>
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
<div id="header" data-role="ejmheader" data-ej-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set showLeftButton on initialization. 
//To set showLeftButton API value 
$("#header").ejmHeader({ showLeftButton: true });       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "showLeftButton", true);                      </code>
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
<div id="header" data-role="ejmheader" data-ej-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set showRightButton on initialization. 
//To set showRightButton API value 
$("#header").ejmHeader({ showRightButton: true });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showRightButton, after initialization:
// Get the showRightButton API value.           
 $("#header").ejmHeader ("option", "showRightButton");                  
// Set the showRightButton  API
$("#header").ejmHeader ("option", "showRightButton", true);                     </code>
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
<div id="header" data-role="ejmheader" data-ej-showtitle=false ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set showTitle on initialization. 
//To set showTitle API value 
$("#header").ejmHeader({ showTitle: false });   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showTitle, after initialization:
// Get the showTitle API value.         
 $("#header").ejmHeader ("option", "showTitle");                        
// Set the showTitle  API
$("#header").ejmHeader ("option", "showTitle", false);                          </code>
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
<div id="header" data-role="ejmheader" data-ej-templateid="headertemplate" ></div>
                        </code>
</pre>



### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Changes the theme of the header. See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-theme="auto" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set theme on initialization. 
//To set theme API value 
$(function(){
$("#header").ejmHeader({ theme:  ej.mobile.Theme.Auto });       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.             
 $("#header").ejmHeader ("option", "theme");                    
// Set the leftButtonCaption  API
$("#header").ejmHeader ("option", "theme",  ej.mobile.Theme.Auto);                      </code>
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
<div id="header" data-role="ejmheader" data-ej-title="Header" ></div>
</code>
</pre>
<pre class="prettyprint">
<code>// Set title on initialization.             
<div id="header"></div>
<script>
//To set title API value 
$(function(){
$("#header").ejmHeader({ title: "Title" });     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the title, after initialization:
// Get the title API value.             
 $("#header").ejmHeader ("option", "title");                    
// Set the title  API
$("#header").ejmHeader ("option", "title", "Header");                   </code>
</pre>



### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.enableCustomText<span class="type-signature type boolean">boolean</span>
{:#members:windows-enablecustomtext}




By default windows title's text will be in small case. To override this behavior, set this property to true.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the windows mode enableCustomText property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-enablecustomtext=true data-ej-title="Windows Custom Text" ></div>
 </code>
</pre>



### windows.leftButtonStyle<span class="type-signature type enum">enum</span>
{:#members:windows-leftbuttonstyle}




Specifies the style for the windows left button i.e. back button or normal button or header button. See WindowsHeaderLeftButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Windows.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows leftButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-showleftbutton="true" data-ej-windows-leftbuttonstyle="back" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set windows leftButtonStyle on initialization. 
//To set windows leftButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({ showLeftButton:true});
$("#header").ejmHeader({"windows":{"leftButtonStyle": "back"}})
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the windows leftButtonStyle, after initialization:
// Get the windows leftButtonStyle API value.           
 $("#header").ejmHeader ("option", "windows.leftButtonStyle"); 
// Set the leftButtonStyle  API
 $("#header").ejmHeader ("option", "windows.leftButtonStyle","normal"); </code>
</pre>



### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}




Specifies whether to render the header based on the windowsphone's current theme or not.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-renderdefault=true ></div>
 </code>
</pre>



### windows.rightButtonStyle<span class="type-signature type enum">enum</span>
{:#members:windows-rightbuttonstyle}




Specifies the windows style for the right button i.e. back button or normal button. See WindowsHeaderRightButtonStyle


Default Value:
{:.param}



* ej.mobile.Button.Windows.Style.Back




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows rightButtonStyle property in unobtrusive way.
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-showrightbutton="true" data-ej-windows-rightbuttonstyle="normal" ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set windows rightButtonStyle on initialization. 
//To set windows rightButtonStyle API value 
$(function(){
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({ showRightButton:true});
$("#header").ejmHeader({"windows":{"rightButtonStyle": "normal"}})
}); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the windows rightButtonStyle, after initialization:
// Get the windows rightButtonStyle API value.          
 $("#header").ejmHeader ("option", "windows.rightButtonStyle"); 
// Set the rightButtonStyle  API
 $("#header").ejmHeader ("option", "windows.rightButtonStyle","normal"); </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-showleftbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set windows showLeftButton on initialization. 
//To set windows showLeftButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({"windows":{ "showLeftButton": true }});  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "windows.showLeftButton");                   
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "windows.showLeftButton", true);                      </code>
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
<div id="header" data-role="ejmheader" data-ej-rendermode="windows" data-ej-windows-showrightbutton=true ></div>
</code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
// Set windows showRightButton on initialization. 
//To set windows showRightButton API value 
$("#header").ejmHeader({ renderMode: ej.mobile.RenderMode.Windows });   
$("#header").ejmHeader({"windows":{ "showRightButton": true }});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showLeftButton, after initialization:
// Get the showLeftButton API value.            
 $("#header").ejmHeader ("option", "windows.showRightButton");                  
// Set the showLeftButton  API
$("#header").ejmHeader ("option", "windows.showRightButton", true);                     </code>
</pre>


## Methods




### getTitle<span class="signature">()</span>
{:#methods:gettitle}




To get the header's text



Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="header" data-role="ejmheader" ></div>
<script>
$(function(){
// To get the instance of the Header
var header = $("#header").data("ejmHeader");
header.getTitle(); // returns the header's text
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
$(function(){
$("#header").ejmHeader();       
// get the header's current value
$("#header").ejmHeader("getTitle");     
});
</script></code>
</pre>


## Events




### leftButtonTap
{:#events:leftbuttontap}




Event triggers when the left button is tapped. <a href="ejmHeader.html#showLeftButton">ejmHeader#showLeftButton</a>

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
<div id="header" data-role="ejmheader" data-ej-showleftbutton="true" data-ej-leftbuttontap="onLeftButtonTap"></div>
<script> 
// leftButtonTap event for header  
function onLeftButtonTap(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
//LeftButtonTap event for header
$("#header").ejmHeader({showLeftButton:true, leftButtonTap:"test"});
    function test(){  //handle the event 
}
</script></code>
</pre>



### rightButtonTap
{:#events:rightbuttontap}




Event triggers when the right button is tapped. <a href="ejmHeader.html#showRightButton">ejmHeader#showRightButton</a>

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
<code><div id="header" data-role="ejmheader" data-ej-showrightbutton="true" data-ej-rightbuttontap="onRightButtonTap"></div>
<script> 
// rightButtonTap event for header  
function onRightButtonTap(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="header"></div>
<script>
$("#header").ejmHeader({showRightButton:true, rightButtonTap:"test"});
function test(){ //handle the event 
}
</script>                 </code>
</pre>


