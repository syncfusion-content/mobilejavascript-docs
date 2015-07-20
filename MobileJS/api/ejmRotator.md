---
layout: post
title: ejmRotator
documentation: API
platform: js
metaname: 
metacontent: 
---

# Custom Design for Html Rotator control.










$(element).ejmRotator<span class="signature">()</span>











Example
{:.example}

<pre class="prettyprint">
<code>// Render rotator in unobtrusive way
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent">       
</div>
<div id="rotatorcontent">
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code>//Render rotator on initialization
<div id="rotator">        
</div>
<div id="rotatorcontent">
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
// Create rotator  
$("#rotator").ejmRotator({ targetId: "rotatorcontent" }); 
</script></code>
</pre>






Requires
{:.require}




* module:jQuery


* module:ej.mobile.application


* module:ej.core


* module:ej.unobtrusive


* module:ej.mobile.core


* module:ej.mobile.header


* module:ej.data


* module:ej.touch




## Members








### adjustFixedPosition<span class="type-signature type boolean">boolean</span>








Calculates the windows inner height for the Rotator.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the adjustFixedPosition property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-adjustFixedPosition=true >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the adjustFixedPosition on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the adjustFixedPosition API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", adjustFixedPosition: true });                    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the adjustFixedPosition, after initialization:
// Get the adjustFixedPosition API value.       
 $("#rotator").ejmRotator ("option", "adjustFixedPosition");                    
// Set the adjustFixedPosition API
$("#rotator").ejmRotator ("option", "adjustFixedPosition", true);            </code>
</pre>






### cssClass<span class="type-signature type string">string</span>








Sets the root class for Rotator theme. This cssClass API helps to use custom skinning option for Rotator control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the cssClass property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-cssclass="customclass" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the cssClass on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the cssClass API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", cssClass: "customclass" });                      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.  
 $("#rotator").ejmRotator ("option", "cssClass");                       
// Set the cssClass API
$("#rotator").ejmRotator ("option", "cssClass", "customclass");            </code>
</pre>






### currentItemIndex<span class="type-signature type number">number</span>








Specifies the currentItemIndex for select the particular item based on the specified index.




Default Value:
{:.param}






* 0








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the currentItemIndex property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-currentitemindex=0 >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the currentItemIndex on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the currentItemIndex API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", currentItemIndex: 0 });                  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  currentItemIndex, after initialization:
// Get the currentItemIndex API value.  
 $("#rotator").ejmRotator ("option", "currentItemIndex");                       
// Set the currentItemIndex API
$("#rotator").ejmRotator ("option", "currentItemIndex", 0);            </code>
</pre>






### dataBinding<span class="type-signature type boolean">boolean</span>








Specifies whether to enable dataBinding for the items on initilization.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the dataBinding property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-databinding="false" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the dataBinding on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the dataBinding API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", dataBinding: false });                   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the dataBinding, after initialization:
// Get the dataBinding API value.       
 $("#rotator").ejmRotator ("option", "dataBinding");                    
// Set the dataBinding API
$("#rotator").ejmRotator ("option", "dataBinding", false);                      </code>
</pre>






### dataSource<span class="type-signature type data">data</span>








Specifies the dataSource for items .




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the dataSource property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-datasource="window.imgdata" data-ej-databinding=true >
</div>
<div id="rotatorcontent">
<div >
<div style="background-image:url({{:imageurl}});height:350px;width:630px">
</div>
</div>
</div> </code>
</pre>
<pre class="prettyprint">
<code> 
// Set the dataSource on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url{{:imageurl}};height:350px;width:630px" >
</div>
</div>
</div> 
<script> 
//To set the dataSource API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", dataSource: "window.imgdata", dataBinding: true });                      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the dataSource, after initialization:
// Get the dataSource API value.        
 $("#rotator").ejmRotator ("option", "dataSource");                     
// Set the dataSource API
$("#rotator").ejmRotator ("option", "dataSource", "window.imgdata");                    </code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>








Current model value to browser cookies for state maintains. While refresh the Rotator control page retains the model value apply from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the enablePersistence property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-enablepersistence=true >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the enablePersistence API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", enablePersistence: true });                      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value. 
 $("#rotator").ejmRotator ("option", "enablePersistence");                      
// Set the enablePersistence API
$("#rotator").ejmRotator ("option", "enablePersistence", true);            </code>
</pre>






### headerTitle<span class="type-signature type string">string</span>








Specifies the headerTitle on initialization .




Default Value:
{:.param}






* Title








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the headerTitle property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-headertitle="Title" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the headerTitle on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the headerTitle API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", headerTitle: "Title" });                 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the headerTitle, after initialization:
// Get the headerTitle API value.       
 $("#rotator").ejmRotator ("option", "headerTitle");                    
// Set the headerTitle API
$("#rotator").ejmRotator ("option", "headerTitle", "Title");            </code>
</pre>






### orientation<span class="type-signature type enum">enum</span>








Specifies the rotator orientation to the horizontal or vertical. See <a href="global.html#Orientation">Orientation</a>




Default Value:
{:.param}






* ej.mobile.Rotator.Orientation.Horizontal








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the orientation property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-orientation="horizontal" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the orientation on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$(function(){
//To set the orientation API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", orientation: ej.mobile.Rotator.Orientation.Horizontal  });                       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the orientation, after initialization:
// Get the orientation API value.       
 $("#rotator").ejmRotator ("option", "orientation");                    
// Set the orientation API
$("#rotator").ejmRotator ("option", "orientation", ej.mobile.Rotator.Orientation.Horizontal);            </code>
</pre>






### pagerPosition








Section for pagerPosition specific functionalities.











### pagerPosition.horizontal<span class="type-signature type enum">enum</span>








Specifies the PagerPosition Horizontal to the top or bottom position. See <a href="global.html#PagerPositionHorizontal">PagerPositionHorizontal</a>




Default Value:
{:.param}






* ej.mobile.Rotator.PagerPositionHorizontal.Bottom








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the pagerPosition horizontal property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-pagerposition-horizontal="bottom" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the pagerPosition horizontal on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$(function(){
//To set the pagerPosition horizontal API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", pagerPosition: { horizontal: ej.mobile.Rotator.PagerPositionHorizontal.Bottom }});                       
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the pagerPosition horizontal, after initialization:
// Get the pagerPosition horizontal API value.  
 $("#rotator").ejmRotator ("option", "pagerPosition.horizontal");                       
// Set the pagerPosition horizontal API
$("#rotator").ejmRotator ("option", "pagerPosition.horizontal", ej.mobile.Rotator.PagerPositionHorizontal.Bottom);            </code>
</pre>






### pagerPosition.vertical<span class="type-signature type enum">enum</span>








Specifies the PagerPosition Vertical to the top or bottom position. See <a href="global.html#PagerPositionVertical">PagerPositionVertical</a>




Default Value:
{:.param}






* ej.mobile.Rotator.PagerPositionVertical.Right








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the pagerPosition vertical property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-orientation="vertical" data-ej-pagerposition-vertical="right" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the pagerPosition vertical on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$(function(){
//To set the pagerPosition vertical API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", orientation: "vertical", pagerPosition: { vertical: ej.mobile.Rotator.PagerPositionVertical.Right }});           
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the pagerPosition vertical, after initialization:
// Get the pagerPosition vertical API value.    
 $("#rotator").ejmRotator ("option", "pagerPosition.vertical");                 
// Set the pagerPosition vertical API
$("#rotator").ejmRotator ("option", "pagerPosition.vertical", ej.mobile.Rotator.PagerPositionVertical.Right);            </code>
</pre>






### renderMode<span class="type-signature type enum">enum</span>








Changes the rendering mode for rotator. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the rendermode property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-rendermode="auto" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the rendermode on initialization.
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$(function(){
//To set the rendermode API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", renderMode: ej.mobile.RenderMode.Auto});                 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rendermode, after initialization:
// Get the rendermode API value.        
 $("#rotator").ejmRotator ("option", "renderMode");                     
// Set the renderMode API
$("#rotator").ejmRotator ("option", "renderMode", ej.mobile.RenderMode.Auto);            </code>
</pre>






### showHeader<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the header on initialization.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showHeader property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-showheader=false >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showHeader on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the showHeader API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", showHeader: false });                    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  showHeader, after initialization:
// Get the showHeader API value.        
 $("#rotator").ejmRotator ("option", "showHeader");                     
// Set the showHeader API
$("#rotator").ejmRotator ("option", "showHeader", false);            </code>
</pre>






### showPager<span class="type-signature type boolean">boolean</span>








Specifies whether to show the Pager on initialization.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the showPager property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-showpager=true >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showPager on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the showPager API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", showPager: true });                      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showPager, after initialization:
// Get the showPager API value. 
 $("#rotator").ejmRotator ("option", "showPager");                      
// Set the showPager API
$("#rotator").ejmRotator ("option", "showPager", true);            </code>
</pre>






### targetHeight<span class="type-signature type string">string</span>








Specifies the targetHeight on initialization.




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the targetHeight property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-targetheight="100px" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the targetHeight on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the targetHeight API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", targetHeight: "100px" });                        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  targetHeight, after initialization:
// Get the targetHeight API value.      
 $("#rotator").ejmRotator ("option", "targetHeight");                   
// Set the targetHeight API
$("#rotator").ejmRotator ("option", "targetHeight", "auto");            </code>
</pre>






### targetId<span class="type-signature type string">string</span>








Specifies the targetId to the content .




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the targetId property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent">
</div>
<div id="rotatorcontent">
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div>         
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div>         
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div>         
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set the targetId on initialization. 
<div id="rotator">        
</div>
<div id="rotatorcontent">
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div> 
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the targetId API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent" });
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the targetId, after initialization:
// Get the targetId API value.  
 $("#rotator").ejmRotator ("option", "targetId");                       
// Set the targetId API
$("#rotator").ejmRotator ("option", "targetId", "rotatorcontent");            </code>
</pre>






### targetWidth<span class="type-signature type string">string</span>








Specifies the targetWidth on initialization.




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the targetWidth property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-targetwidth="auto" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the targetWidth on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
//To set the targetWidth API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", targetWidth: "auto" });                  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the rotator targetWidth, after initialization:
// Get the targetWidth API value.       
 $("#rotator").ejmRotator ("option", "targetWidth");                    
// Set the targetWidth API
$("#rotator").ejmRotator ("option", "targetWidth", "auto");            </code>
</pre>






### theme<span class="type-signature type enum">enum</span>








Changes the theme of the Rotator. See<a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the theme property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-theme="auto" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$(function(){
//To set the theme API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", theme: ej.mobile.Theme.Light });                 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.     
 $("#rotator").ejmRotator ("option", "theme");                  
// Set the theme API
$("#rotator").ejmRotator ("option", "theme", ej.mobile.Theme.Light);            </code>
</pre>






### windows








Section for windows rendermode specific functionalities.











### windows.renderDefault<span class="type-signature type boolean">boolean</span>








Specifies whether to render the rotator based on the windowsphone's current accent color and device theme.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-windows-renderdefault="true" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set the windows renderDefault on initialization. 
<div id="rotator" >       
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
                
<script> 
//To set the windows renderDefault API value 
$("#rotator").ejmRotator({ targetId: "rotatorcontent", windows:{ renderDefault: true} });                       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the windows renderDefault, after initialization:
// Get the windows renderDefault API value.     
 $("#rotator").ejmRotator ("option", "windows.renderDefault");                  
// Set the windows renderDefault API
$("#rotator").ejmRotator ("option", "windows.renderDefault", true);            </code>
</pre>




## Methods








### renderDatasource<span class="signature">()</span>








To handle the rotator datasource





Example
{:.example}

<pre class="prettyprint">
<code>             
<div id="rotator" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url{{:imageurl}};height:350px;width:630px" >
</div>
</div>
</div>            
//To set the dataSource API value
<script >
$("#rotator").ejmRotator({ targetId: "rotatorcontent", dataBinding: true });
var rotObj = $("#rotator").data("ejmRotator");
rotObj.renderDatasource(imgdata); 
</script ></code>
</pre>
<pre class="prettyprint">
<code>             
<div id="rotator" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url{{:imageurl}};height:350px;width:630px" >
</div>
</div>
</div>            
//To set the dataSource API value
<script >
$("#rotator").ejmRotator({ targetId: "rotatorcontent", dataBinding: true });
$("#rotator").ejmRotator("renderDatasource", imgdata);
</script ></code>
</pre>




## Events








### change








Event triggers when the rotator changes from one slide to another slide

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//change event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-change="onChange" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function onChange(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//change event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  change: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>






### pagerSelect








Event triggers when the rotator's pager clicked

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//pagerSelect event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-pagerselect="onUpdate" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function onUpdate(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//pagerSelect event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  pagerSelect: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>






### swipeDown








Event triggers when the swipeDown happens in the Rotator

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//SwipeDown event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipedown="swipeDown" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function swipeDown(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//SwipeDown event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  swipeDown: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>






### swipeLeft








Event triggers when the swipeLeft happens.

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the Rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//SwipeLeft event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipeleft="swipeLeft" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function swipeLeft(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//SwipeLeft event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  swipeLeft: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>






### swipeRight








Event triggers when the swipeRight happens in the Rotator

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//SwipeRight event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swiperight="swipeRight" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function swipeRight(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//SwipeRight event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  swipeRight: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>






### swipeUp








Event triggers when the swipeUp happens in the Rotator

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
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Rotator model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.targetElement</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the targetElement of the rotator</td>
</tr>
<tr>
<td class="name"><code>argument.value</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current slide index.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
//SwipeUp event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipeup="swipeUp" >
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >                
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script>
function swipeUp(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//SwipeUp event for rotator
<div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" >      
</div>
<div id="rotatorcontent" >
<div >
<div style="background-image:url(nature.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(bird.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(snowfall.jpg);height:350px;width:630px">
</div>
</div><div >        
<div style="background-image:url(sculpture.jpg);height:350px;width:630px">
</div>
</div>
</div>
<script> 
$("#rotator").ejmRotator({
  swipeUp: function (args) { 
//handle the event 
}
});           
</script></code>
</pre>



