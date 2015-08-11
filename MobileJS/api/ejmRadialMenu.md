---
layout: post
title: ejmRadialMenu
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html radialmenu control.





$(element).ejmRadialMenu<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code> 
//Create radialmenu in unobtrusive way
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu"
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Create radialmenu in obtrusive way
<script> 
$(function(){
$("#defaultradialmenu").ejmRadialMenu(); 
});
</script>
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
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


## Members




### backImageClass<span class="type-signature type string">string</span>
{:#members:backimageclass}




Renders the back button Image for Radial using class.


Default Value:
{:.param}



* e-m-backimage




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the backImageClass property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-backimageclass="e-m-backimage" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu backImageClass on initialization. 
//To set backImageClass API 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "backImageClass":"e-m-backimage" });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu backImageClass, after initialization:
<script>
// Gets the backImageClass API.         
$("#defaultradialmenu").ejmRadialMenu ("option", "backImageClass");                     
// Sets the backImageClass API
$("#defaultradialmenu").ejmRadialMenu ("option", "backImageClass", "e-m-backimage");            
</script></code>
</pre>



### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for RadialMenu theme. This cssClass API helps to use custom skinning option for RadialMenu control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-cssclass="customclass" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu cssClass on initialization. 
//To set cssClass API  
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "cssClass":"customclass" });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu cssClass, after initialization:
<script>
// Gets the cssClass API.               
 $("#radialmenu").ejmRadialMenu ("option", "cssClass");                 
// Sets the cssClass API
$("#radialmenu").ejmRadialMenu ("option", "cssClass", "customclass");            
</script></code>
</pre>



### enableAnimation<span class="type-signature type boolean">boolean</span>
{:#members:enableanimation}




To enable Animation for Radial Menu.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enableAnimation property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-enableanimation="true" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu enableAnimation on initialization. 
//To set enableAnimation API  
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "enableAnimation":true });      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu enableAnimation, after initialization:
<script>
// Gets the enableAnimation API.                
 $("#radialmenu").ejmRadialMenu ("option", "enableAnimation");                  
// Sets the enableAnimation API
$("#radialmenu").ejmRadialMenu ("option", "enableAnimation", true);            
</script></code>
</pre>



### imageClass<span class="type-signature type string">string</span>
{:#members:imageclass}




Renders the image for Radial using Class.


Default Value:
{:.param}



* e-m-radialimage




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the imageClass property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-imagaclass="e-m-radialimage" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu imageClass on initialization. 
//To set imageClass API  
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "imageClass":"e-m-radialimage" });      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu imageClass, after initialization:
<script>
// Gets the imageClass API.             
 $("#radialmenu").ejmRadialMenu ("option", "imageClass");                       
// Sets the imageClass API
$("#radialmenu").ejmRadialMenu ("option", "imageClass", "e-m-radialimage");            
</script></code>
</pre>



### position<span class="type-signature type enum">enum</span>
{:#members:position}




Changes the Position of the control.See <a href="global.html#Position">Position</a>


Default Value:
{:.param}



* rightcenter




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-position="rightcenter" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu position on initialization. 
//To set position API value 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "position":"rightcenter" });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu position, after initialization:
<script>
// Gets the position API value.         
 $("#defaultradialmenu").ejmRadialMenu ("option", "position");                  
// Sets the position API
$("#defaultradialmenu").ejmRadialMenu ("option", "position", "rightcenter");            
</script></code>
</pre>



### radius<span class="type-signature type int">int</span>
{:#members:radius}




Specifies the radius of the radialmenu control.


Default Value:
{:.param}



* 150




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the radius property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-radius="150"
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu radius on initialization. 
//To set radius API value 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "radius":150}); 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu radius, after initialization:
<script>
// Gets the radius API value.           
 $("#defaultradialmenu").ejmRadialMenu ("option", "radius");                    
// Sets the radius API
$("#defaultradialmenu").ejmRadialMenu ("option", "radius", 150);            
</script></code>
</pre>



### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the renderMode property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-rendermode="auto" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu renderMode on initialization. 
//To set renderMode API value 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "renderMode":ej.mobile.RenderMode.Auto });      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu renderMode, after initialization:
<script>
// Gets the renderMode API value.               
 $("#defaultradialmenu").ejmRadialMenu ("option", "renderMode");                        
// Sets the renderMode API
$("#defaultradialmenu").ejmRadialMenu ("option", "renderMode", ej.mobile.RenderMode.Auto);            
</script></code>
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
//Set the theme property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-theme="auto"
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu theme on initialization. 
//To set theme API value 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ "theme":ej.mobile.RenderMode.Auto });   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu renderMode, after initialization:
<script>
// Gets the theme API value.            
 $("#defaultradialmenu").ejmRadialMenu ("option", "theme");                     
// Sets the theme API
$("#defaultradialmenu").ejmRadialMenu ("option", "theme", "ej.mobile.Theme.Auto");            
</script></code>
</pre>



### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}




Specifies whether to render the Radial Menu based on the windowsphone's current accent color and device theme.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the windows renderDefault property in unobtrusive way.
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-windows-renderdefault="true"
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Radialmenu windows renderDefault on initialization. 
//To set windows renderDefault API value 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$(function () {
$("#defaultradialmenu").ejmRadialMenu({ windows:{ renderDefault: true }});      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Radialmenu windows renderDefault, after initialization:
<script>
// Gets the windows renderDefault API value.            
 $("#defaultradialmenu").ejmRadialMenu ("option", "windows.renderDefault");                     
// Sets the windows renderDefault API
$("#defaultradialmenu").ejmRadialMenu ("option", "windows.renderDefault", true);            
</script></code>
</pre>


## Methods




### hide<span class="signature">()</span>
{:#methods:hide}




To hide the redialmenu



Example
{:.example}

<pre class="prettyprint">
<code> 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
$("#defaultradialmenu").ejmRadialMenu ("hide"); 
</script></code>
</pre>



### menuHide<span class="signature">()</span>
{:#methods:menuhide}




To hide the redialmenu items



Example
{:.example}

<pre class="prettyprint">
<code> 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
$("#defaultradialmenu").ejmRadialMenu ("menuHide");
</script></code>
</pre>



### show<span class="signature">()</span>
{:#methods:show}




To Show the redialmenu



Example
{:.example}

<pre class="prettyprint">
<code> 
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
$("#defaultradialmenu").ejmRadialMenu ("show");
</script></code>
</pre>


## Events




### select
{:#events:select}




Event triggers when we select an item.

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
<td class="description last">Event parameters from Radialmenu
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
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Radialmenu model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name"><code>itemName</code></td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
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
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-select="select" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script> 
// select event for Radialmenu  
function select(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//select event for Radialmenu
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$("#defaultradialmenu").ejmRadialMenu({
  select: function (args) { //handle the event
}
});         
</script></code>
</pre>



### touchEnd
{:#events:touchend}




Event triggers when the touch end happens.

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
<td class="description last">Event parameters from Radialmenu
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
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Radialmenu model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name"><code>itemName</code></td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
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
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-touchend="touchend" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script> 
// TouchEnd event for Radialmenu  
function touchend(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//TouchEnd event for Radialmenu
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$("#defaultradialmenu").ejmRadialMenu({
  touchend: function (args) { //handle the event
}
});         
</script></code>
</pre>



### touchStart
{:#events:touchstart}




Event triggers when the touch start happens.

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
<td class="description last">Event parameters from Radialmenu
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
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the Radialmenu model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the item of element</td>
</tr>
<tr>
<td class="name"><code>itemName</code></td>
<td class="type"><span class="param-type">String</span></td>
<td class="description last">returns the name of item</td>
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
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu" data-role="ejmradialmenu" data-ej-touchstart="touchstart" 
>
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script> 
// touchStart event for Radialmenu  
function touchStart(args){ //handle the event
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//touchStart event for Radialmenu
<div >
<br />
<p>
Syncfusion is the enterprise technology partner of choice for Windows development
</p>
</div>  
<div id="defaultradialmenu">
<ul>
<li data-ej-imagename="social.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="social"></li>
<li data-ej-imagename="music.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="music"></li>
<li data-ej-imagename="direction.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="direction"></li>
<li data-ej-imagename="message.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="message"></li>
<li data-ej-imagename="browser.png" data-ej-imagepath="../themes/sample/radialmenu"
data-ej-windows-text="browser"></li>
</ul>
</div>
<script>
$("#defaultradialmenu").ejmRadialMenu({
  touchStart: function (args) { //handle the event
}
});         
</script></code>
</pre>


