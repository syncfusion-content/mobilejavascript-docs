---
layout: post
title: ejmScrollPanel | API Reference | Mobile JS | Syncfusion
description:
documentation: API
platform: Mobilejs
keywords: ejmScrollPanel, API, Essential Studio JS Autocomplete (Mobile) 
---

# ejmScrollPanel

Custom Design for Html Scrollpanel control.

$(element).ejmScrollPanel<span class="signature">()</span>

#### Example

{% highlight html %} 
// Create scrollpanel control in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" />{% endhighlight %}




#### Requires


* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

* module:ej.mobile.scrollbar


## Members




### adjustFixedPosition`boolean`
{:#members:adjustfixedposition}




Specifies whether need to adjust the scrolling content height for fixed position elements.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the adjustFixedPosition property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-adjustfixedposition="true" />               {% endhighlight %}


{% highlight html %}// Set the adjustFixedPosition property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", adjustFixedPosition:true});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel adjustFixedPosition property, after initialization:
<script>
// Get the adjustFixedPosition API value.               
 $("#scrollpanel").ejmScrollPanel("option", "adjustFixedPosition");                     
// Set the adjustFixedPosition API
$("#scrollpanel").ejmScrollPanel("option", "adjustFixedPosition", true);            
</script>{% endhighlight %}




### autoAdjustHeight`boolean`
{:#members:autoadjustheight}




Specifies whether need to calculate the scroll content height.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the autoAdjustHeight property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-autoadjustheight="true" />          {% endhighlight %}


{% highlight html %}// Set the autoAdjustHeight property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", autoAdjustHeight:true});                
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel autoAdjustHeight property, after initialization:
<script>
// Get the autoAdjustHeight API value.          
 $("#scrollpanel").ejmScrollPanel("option", "autoAdjustHeight");                        
// Set the autoAdjustHeight API
$("#scrollpanel").ejmScrollPanel("option", "autoAdjustHeight", true);            
</script>{% endhighlight %}




### bounceTime`int`
{:#members:bouncetime}




Specifies the bouncing time when bouncing behavior is enabled.


#### Default Value



* 450




#### Example


{% highlight html %} 
// Set the bounceTime property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-bouncetime=450/>    {% endhighlight %}


{% highlight html %}// Set the bounceTime property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", bounceTime:500});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel bounceTime property, after initialization:
<script>
// Get the bounceTime API value.                
 $("#scrollpanel").ejmScrollPanel("option", "bounceTime");                      
// Set the bounceTime API
$("#scrollpanel").ejmScrollPanel("option", "bounceTime", "500");            
</script>{% endhighlight %}




### checkDOMChanges`boolean`
{:#members:checkdomchanges}




Specifies whether need to refresh scrollpanel when elements are added dynamically.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the checkDOMChanges property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-checkdomchanges=false/>             {% endhighlight %}


{% highlight html %}// Set the checkDOMChanges property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", checkDOMChanges:"200"});                
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel checkDOMChanges property, after initialization:
<script>
// Get the checkDOMChanges API value.           
 $("#scrollpanel").ejmScrollPanel("option", "checkDOMChanges");                 
// Set the checkDOMChanges API
$("#scrollpanel").ejmScrollPanel("option", "checkDOMChanges", true);            
</script>{% endhighlight %}




### directionLockThreshold`int`
{:#members:directionlockthreshold}




Specifies the value for direction lock threshold.


#### Default Value



* 5




#### Example


{% highlight html %} 
// Set the directionLockThreshold property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-directionlockthreshold=12/>         {% endhighlight %}


{% highlight html %}// Set the directionLockThreshold property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", directionLockThreshold:12});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel directionLockThreshold property, after initialization:
<script>
// Get the directionLockThreshold API value.            
 $("#scrollpanel").ejmScrollPanel("option", "directionLockThreshold ");                 
// Set the directionLockThreshold  API
$("#scrollpanel").ejmScrollPanel("option", "directionLockThreshold ", 12);            
</script>{% endhighlight %}




### disableMouse`bool`
{:#members:disablemouse}




Specifies whether to disable mouse.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the disableMouse, property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-disablemouse="true" />      {% endhighlight %}


{% highlight html %}// Set the disableMouse property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", disableMouse:true});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel disableMouse property, after initialization:
<script>
// Get the disableMouse API value.              
 $("#scrollpanel").ejmScrollPanel("option", "disableMouse");                    
// Set the disableMouse API
$("#scrollpanel").ejmScrollPanel("option", "disableMouse", true);            
</script>{% endhighlight %}




### disablePointer`bool`
{:#members:disablepointer}




Specifies whether to disable pointer.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the disablePointer, property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-disablepointer="true" />            {% endhighlight %}


{% highlight html %}// Set the disablePointer property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", disablePointer:true});          
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel disablePointer property, after initialization:
<script>
// Get the disablePointer API value.            
 $("#scrollpanel").ejmScrollPanel("option", "disablePointer");                  
// Set the disablePointer API
$("#scrollpanel").ejmScrollPanel("option", "disablePointer", true);            
</script>{% endhighlight %}




### disableTouch`bool`
{:#members:disabletouch}




Specifies whether to disable touch.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the disableTouch, property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-disabletouch="true" />              {% endhighlight %}


{% highlight html %}// Set the disableTouch property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", disableTouch:true});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel disableTouch property, after initialization:
<script>
// Get the disableTouch API value.              
 $("#scrollpanel").ejmScrollPanel("option", "disableTouch");                    
// Set the disableTouch API
$("#scrollpanel").ejmScrollPanel("option", "disableTouch", true);            
</script>{% endhighlight %}




### enableBounce`boolean`
{:#members:enablebounce}




Specifies whether to enable bouncing behavior.


#### Default Value



* true

Note: For Android platform this property is false




#### Example


{% highlight html %} 
// Set the enableBounce property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablebounce="true" />      {% endhighlight %}


{% highlight html %}// Set the enableBounce property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableBounce:true});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableBounce property, after initialization:
<script>
// Get the enableBounce API value.              
 $("#scrollpanel").ejmScrollpanel("option", "enableBounce");                    
// Set the enableBounce API
$("#scrollpanel").ejmScrollpanel("option", "enableBounce", true);            
</script>{% endhighlight %}




### enabled`boolean`
{:#members:enabled}




Specifies whether to enable or disable the control.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enabled property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enabled="true" />   {% endhighlight %}


{% highlight html %}// Set the enabled property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enabled:true});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel interactiveScrollbars property, after initialization:
<script>
// Get the enabled API value.           
 $("#scrollpanel").ejmScrollPanel("option", "enabled");                 
// Set the enabled API
$("#scrollpanel").ejmScrollPanel("option", "enabled", true);            
</script>{% endhighlight %}




### enableFade`boolean`
{:#members:enablefade}




Specifies whether need to fade the scrollbars.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableFade property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablefade="true" />                
// Set the enableFade property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableFade:true});              
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableFade property, after initialization:
<script>
// Get the enableFade API value.                
 $("#scrollpanel").ejmScrollPanel("option", "enableFade");                      
// Set the enableFade API
$("#scrollpanel").ejmScrollPanel("option", "enableFade", true);            
</script>{% endhighlight %}




### enableHrScroll`boolean`
{:#members:enablehrscroll}




Specifies whether need to enable the horizontal scrolling.


#### Default Value



* false

Note: For windows tablet horizontal scrolling is true




#### Example


{% highlight html %} 
// Set the enableHrScroll property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablehrscroll=false/>              {% endhighlight %}


{% highlight html %}// Set the enableHrScroll property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableHrScroll:true});          
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableHrScroll property, after initialization:
<script>
// Get the enableHrScroll API value.            
 $("#scrollpanel").ejmScrollPanel("option", "enableHrScroll");                  
// Set the enableHrScroll API
$("#scrollpanel").ejmScrollPanel("option", "enableHrScroll", true);            
</script>{% endhighlight %}




### enableInteraction`boolean`
{:#members:enableinteraction}




Specifies whether need to enable the interactive scrollbars.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableInteraction property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enableinteraction="true" />         {% endhighlight %}


{% highlight html %}// Set the enableInteraction property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableInteraction:true});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableInteraction property, after initialization:
<script>
// Get the enableInteraction API value.         
 $("#scrollpanel").ejmScrollPanel("option", "enableInteraction");                       
// Set the enableInteraction API
$("#scrollpanel").ejmScrollPanel("option", "enableInteraction", true);            
</script>{% endhighlight %}




### enableKeys`boolean`
{:#members:enablekeys}




Specifies whether to enable keys.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableKeys property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablekeys=false/>          
// Set the enableKeys property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableKeys:false});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableKeys property, after initialization:
<script>
// Get the enableKeys API value.                
 $("#scrollpanel").ejmScrollpanel("option", "enableKeys");                      
// Set the enableKeys API
$("#scrollpanel").ejmScrollpanel("option", "enableKeys", false);            
</script>{% endhighlight %}




### enableMouseWheel`boolean`
{:#members:enablemousewheel}




Specifies whether to enable mouse wheel scrolling.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableMouseWheel property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablemousewheel=false/>    
// Set the enableMouseWheel property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableMouseWheel:false});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableMouseWheel property, after initialization:
<script>
// Get the enableMouseWheel API value.          
 $("#scrollpanel").ejmScrollPanel("option", "enableMouseWheel");                        
// Set the enableMouseWheel API
$("#scrollpanel").ejmScrollPnel("option", "enableMouseWheel", false);            
</script>{% endhighlight %}




### enableNativeScrolling`boolean`
{:#members:enablenativescrolling}




Specifies whether to enable device's native scroll behavior.


#### Default Value



* false

Note: For Windows tablet, this property is true




#### Example


{% highlight html %} 
// Set the enableNativeScrolling property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablenativescrolling="true" />             {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableNativeScrolling property, after initialization:
<script>
// Get the enableNativeScrolling API value.             
 $("#scrollpanel").ejmScrollPanel("option", "enableNativeScrolling");                   
// Set the enableNativeScrolling API
$("#scrollpanel").ejmScrollPanel("option", "enableNativeScrolling", true);            
</script>{% endhighlight %}




### enablePersistence`boolean`
{:#members:enablepersistence}




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the enablePersistence property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablepersistence="true" />{% endhighlight %}


{% highlight html %}// Set the enablePersistence property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enablePersistence:true});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enablePersistence property, after initialization:
<script>
// Get the enablePersistence API value.         
 $("#scrollpanel").ejmScrollpanel("option", "enablePersistence");                       
// Set the enablePersistence API
$("#scrollpanel").ejmScrollpanel("option", "enablePersistence", true);            
</script>{% endhighlight %}




### enableResize`boolean`
{:#members:enableresize}




Specifies whether need to resize the scrollbar.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the enableResize property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enableresize="true" />              {% endhighlight %}


{% highlight html %}// Set the enableResize property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableResize:true});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableResize property, after initialization:
<script>
// Get the enableResize API value.              
 $("#scrollpanel").ejmScrollPanel("option", "enableResize");                    
// Set the enableResize API
$("#scrollpanel").ejmScrollPanel("option", "enableResize", true);            
</script>{% endhighlight %}




### enableShrink`boolean`
{:#members:enableshrink}




Specifies whether need to shrink the scrollbars.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the enableShrink property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enableshrink="true" />              
// Set the enableShrink property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableShrink:"scale"});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableShrink property, after initialization:
<script>
// Get the enableShrink API value.              
 $("#scrollpanel").ejmScrollPanel("option", "enableShrink");                    
// Set the enableShrink API
$("#scrollpanel").ejmScrollPanel("option", "enableShrink", true);            
</script>{% endhighlight %}




### enableTransform`boolean`
{:#members:enabletransform}




Specifies whether to enable transform style for the control.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableTransform property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enabletransform=false/>             {% endhighlight %}


{% highlight html %}// Set the enableTransform property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableTransform:false});                
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableTransform property, after initialization:
<script>
// Get the enableTransform API value.           
 $("#scrollpanel").ejmScrollPanel("option", "enableTransform");                 
// Set the enableTransform API
$("#scrollpanel").ejmScrollPanel("option", "enableTransform", false);            
</script>{% endhighlight %}




### enableTransition`boolean`
{:#members:enabletransition}




Specifies whether to enable transition effect for the control.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableTransition property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enabletransition=false/>            {% endhighlight %}


{% highlight html %}// Set the enableTransition property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableTransition:false});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableTransition property, after initialization:
<script>
// Get the enableTransition API value.          
 $("#scrollpanel").ejmScrollPanel("option", "enableTransition");                        
// Set the enableTransition API
$("#scrollpanel").ejmScrollPanel("option", "enableTransition", false);            
</script>{% endhighlight %}




### enableVrScroll`boolean`
{:#members:enablevrscroll}




Specifies whether need to enable the vertical scrolling.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the enableVrScroll property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablevrscroll="true" />            {% endhighlight %}


{% highlight html %}// Set the enableVrScroll property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableVrScroll:true});          
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableVrScroll property, after initialization:
<script>
// Get the enableVrScroll API value.            
 $("#scrollpanel").ejmScrollPanel("option", "enableVrScroll");                  
// Set the enableVrScroll API
$("#scrollpanel").ejmScrollPanel("option", "enableVrScroll", true);            
</script>{% endhighlight %}




### enableZoom`boolean`
{:#members:enablezoom}




Specifies whether to enable zooming.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the enableZoom property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablezoom="true" />{% endhighlight %}


{% highlight html %}// Set the enableZoom property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableZoom:true});              
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel enableZoom property, after initialization:
<script>
// Get the enableZoom API value.                
 $("#scrollpanel").ejmScrollpanel("option", "enableZoom");                      
// Set the enableZoom API
$("#scrollpanel").ejmScrollpanel("option", "enableZoom", true);            
</script>{% endhighlight %}




### invertWheel`boolean`
{:#members:invertwheel}




Specifies whether to enable invert wheel.


#### Default Value



* false




#### Example


{% highlight html %} 
// Set the invertWheel property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-invertwheel="true" />{% endhighlight %}


{% highlight html %}// Set the invertWheel property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", invertWheel:true});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel invertWheel property, after initialization:
<script>
// Get the invertWheel API value.               
 $("#scrollpanel").ejmScrollpanel("option", "invertWheel");                     
// Set the invertWheel API
$("#scrollpanel").ejmScrollpanel("option", "invertWheel", true);            
<script>{% endhighlight %}




### isRelative`boolean`
{:#members:isrelative}




Specifies whether need to style the target element with relative position.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the isRelative property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-isrelative="true" />{% endhighlight %}


{% highlight html %}// Set the isRelative property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", isRelative:true});              
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel isRelative property, after initialization:
<script>
// Get the isRelative API value.                
 $("#scrollpanel").ejmScrollPanel("option", "isRelative");                      
// Set the isRelative API
$("#scrollpanel").ejmScrollPanel("option", "isRelative", true);            
</script>{% endhighlight %}




### preventDefault`bool`
{:#members:preventdefault}




Specifies whether to prevent default events.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the preventDefault property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-preventdefault=false/>{% endhighlight %}


{% highlight html %}// Set the preventDefault property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", preventDefault:false});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel preventDefault property, after initialization:
<script>
// Get the preventDefault API value.            
 $("#scrollpanel").ejmScrollPanel("option", "preventDefault");                  
// Set the preventDefault API
$("#scrollpanel").ejmScrollPanel("option", "preventDefault", false);            
</script>{% endhighlight %}




### renderMode`enum`
{:#members:rendermode}




Specifies the rendering mode of the control. See <a href="global.html#RenderMode">RenderMode</a>


#### Default Value



* auto




#### Example


{% highlight html %} 
// Set the renderMode property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-rendermode="auto"/> {% endhighlight %}


{% highlight html %} 
// Set the renderMode property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", renderMode:ej.mobile.RenderMode.Auto});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel rendermode, after initialization:
<script>
// Get the renderMode API value.                
 $("#scrollpanel").ejmScrollPanel("option", "renderMode");                      
// Set the renderMode API
$("#scrollpanel").ejmScrollPanel("option", "renderMode", ej.mobile.RenderMode.Auto);            
</script> {% endhighlight %}




### scrollHeight`int`
{:#members:scrollheight}




Specifies the scroll height of the content.


#### Default Value



* null




#### Example


{% highlight html %} 
// Set the scrollHeight property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-scrollheight="300"/>        {% endhighlight %}


{% highlight html %}// Set the scrollHeight property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", scrollHeight:300});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel content scrollheight, after initialization:
<script>
// Get the scrollHeight API value.              
 $("#scrollpanel").ejmScrollPanel("option", "scrollHeight");                    
// Set the scrollHeight API
$("#scrollpanel").ejmScrollPanel("option", "scrollHeight", "300");            
</script>{% endhighlight %}




### scrollWidth`int`
{:#members:scrollwidth}




Specifies the scroll width of the content.


#### Default Value



* null




#### Example


{% highlight html %} 
// Set the scrollWidth property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-scrollwidth="200"/> {% endhighlight %}


{% highlight html %}// Set the scrolWidth property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", scrollWidth:"200"});            
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel content scrollwidth, after initialization:
<script>
// Get the scrollWidth API value.               
 $("#scrollpanel").ejmScrollPanel("option", "scrollwidth");                     
// Set the scrollWidth API
$("#scrollpanel").ejmScrollPanel("option", "scrollwidth", "200");            
</script>{% endhighlight %}




### showScrollbars`boolean`
{:#members:showscrollbars}




Specifies whether need to show the scroll bars.


#### Default Value



* true




#### Example


{% highlight html %} 
// Set the showScrollbars property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-showscrollbars="true" />{% endhighlight %}


{% highlight html %}// Set the showScrollbars property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", showScrollbars:true});          
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel showScrollbars property, after initialization:
<script>
// Get the showScrollbars API value.            
 $("#scrollpanel").ejmScrollpanel("option", "showScrollbars");                  
// Set the showScrollbars API
$("#scrollpanel").ejmScrollpanel("option", "showScrollbars", true);            
</script>{% endhighlight %}




### startX`int`
{:#members:startx}




Specifies the x position on intialize.


#### Default Value



* 0




#### Example


{% highlight html %} 
// Set the startX property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-startx=0/>{% endhighlight %}


{% highlight html %}// Set the startX property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", startX:0});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel startX property, after initialization:
<script>
// Get the startX API value.
 $("#scrollpanel").ejmScrollPanel("option", "startX");
// Set the startX API
$("#scrollpanel").ejmScrollPanel("option", "startX", 0);
</script>{% endhighlight %}




### startY`int`
{:#members:starty}




Specifies the y position on intialize.


#### Default Value



* 0




#### Example


{% highlight html %} 
// Set the startY property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-starty=30/>{% endhighlight %}


{% highlight html %}// Set the startY property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", startY:0});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel startY property, after initialization:
<script>
// Get the startY API value.            
 $("#scrollpanel").ejmScrollPanel("option", "startY");                  
// Set the startY API
$("#scrollpanel").ejmScrollPanel("option", "startY", 30);            
</script>{% endhighlight %}




### startZoom`int`
{:#members:startzoom}




Specifies the initial zooming value.


#### Default Value



* 1




#### Example


{% highlight html %} 
// Set the startZoom property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablezoom="true" data-ej-startzoom=2/>{% endhighlight %}


{% highlight html %}// Set the startZoom property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", enableZoom:true, startZoom:2});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel startZoom property, after initialization:
<script>
// Get the startZoom API value.         
 $("#scrollpanel").ejmScrollPanel("option", "startZoom");                       
// Set the startZoom API
$("#scrollpanel").ejmScrollPanel("option", "startZoom", 2);            
</script>{% endhighlight %}




### target`string`
{:#members:target}




Specifies the target element.


#### Default Value



* null




#### Example


{% highlight html %} 
// Set the target property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" />{% endhighlight %}


{% highlight html %}// Set the target property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent"});               
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel target property, after initialization:
<script>
// Get the target API value.            
 $("#scrollpanel").ejmScrollpanel("option", "target");                  
// Set the target API
$("#scrollpanel").ejmScrollpanel("option", "target", "maincontent");            
</script>{% endhighlight %}




### targetHeight`int`
{:#members:targetheight}




Specifies the target element height.


#### Default Value



* null




#### Example


{% highlight html %} 
// Set the targetHeight property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-targetheight="300"/>                {% endhighlight %}


{% highlight html %}// Set the targetHeight property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", targetHeight:300});             
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel targetHeight, after initialization:
<script>
// Get the targetHeight API value.              
 $("#scrollpanel").ejmScrollpanel("option", "targetHeight");                    
// Set the targetHeight API
$("#scrollpanel").ejmScrollpanel("option", "targetHeight", "300");            
</script>{% endhighlight %}




### targetWidth`int`
{:#members:targetwidth}




Specifies the target element width.


#### Default Value



* null




#### Example


{% highlight html %} 
// Set the targetWidth property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-targetwidth="200"/>         {% endhighlight %}


{% highlight html %}// Set the targetWidth property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", targetWidth:200});              
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel targetWidth, after initialization:
<script>
// Get the targetWidth API value.               
 $("#scrollpanel").ejmScrollpanel("option", "targetWidth");                     
// Set the targetWidth API
$("#scrollpanel").ejmScrollpanel("option", "targetWidth", "200");            
</script>{% endhighlight %}




### theme`enum`
{:#members:theme}




Specifies the theme. See <a href="global.html#Theme">Theme</a>


#### Default Value



* auto




#### Example


{% highlight html %} 
// Set the theme property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-theme="auto"/>{% endhighlight %}


{% highlight html %}// Set the theme property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", theme:ej.mobile.Theme.Auto});           
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel theme, after initialization:
<script>
// Get the theme API value.             
 $("#scrollpanel").ejmScrollPanel("option", "theme");                   
// Set the theme API
$("#scrollpanel").ejmScrollPanel("option", "theme", ej.mobile.Theme.Auto);            
</script>{% endhighlight %}




### wheelSpeed`int`
{:#members:wheelspeed}




Specifies the wheel speed.


#### Default Value



* 16




#### Example


{% highlight html %} 
// Set the wheelSpeed property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-wheelspeed=20/>             {% endhighlight %}


{% highlight html %}// Set the wheelSpeed property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", wheelSpeed:20});                
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel wheelSpeed property, after initialization:
<script>
// Get the wheelSpeed API value.                
 $("#scrollpanel").ejmScrollPanel("option", "wheelSpeed");                      
// Set the wheelSpeed API
$("#scrollpanel").ejmScrollPanel("option", "wheelSpeed", 20);            
</script>{% endhighlight %}




### zoomMax`int`
{:#members:zoommax}




Specifies the maximum zoom value.


#### Default Value



* 6




#### Example


{% highlight html %} 
// Set the zoomMax property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-zoom="true" data-ej-zoommax=10/>            {% endhighlight %}


{% highlight html %}// Set the zoomMax property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", zoom:true, zoomMax:10});                
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel zoomMax property, after initialization:
<script>
// Get the zoomMax API value.           
 $("#scrollpanel").ejmScrollPanel("option", "zoomMax");                 
// Set the zoomMax API
$("#scrollpanel").ejmScrollPanel("option", "zoomMax", 10);            
</script>{% endhighlight %}




### zoomMin`int`
{:#members:zoommin}




Specifies the minimum zoom value.


#### Default Value



* 1




#### Example


{% highlight html %} 
// Set the zoomMin property in unobtrusive way.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-zoom="true" data-ej-zoommin=2/>             {% endhighlight %}


{% highlight html %}// Set the zoomMin property on initilization.
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>
<script>
$(function(){
$("#scrollpanel").ejmScrollPanel({target:"maincontent", zoom:true, zoomMin:2});         
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the scrollpanel zoomMin property, after initialization:
<script>
// Get the zoomMin API value.           
 $("#scrollpanel").ejmScrollPanel("option", "zoomMin");                 
// Set the zoomMin API
$("#scrollpanel").ejmScrollPanel("option", "zoomMin", 2);            
</script>{% endhighlight %}



## Methods




### disable`()`
{:#methods:disable}




To disable the scrollpanel.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Disable the scroll panel
$("#scrollpanel").ejmScrollPanel('disable');    
</script>{% endhighlight %}




### enable`()`
{:#methods:enable}




To enable the scrollpanel.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Enable the scroll panel
$("#scrollpanel").ejmScrollPanel('enable');     
</script>{% endhighlight %}




### getComputedPosition`()`
{:#methods:getcomputedposition}




To get the computed position.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Refresh the scroll panel
$("#scrollpanel").ejmScrollPanel('getComputedPosition');        
</script>{% endhighlight %}




### getScrollPosition`()`
{:#methods:getscrollposition}




To get the scroll position.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Refresh the scroll panel
$("#scrollpanel").ejmScrollPanel('getScrollPosition');  
</script>{% endhighlight %}




### refresh`()`
{:#methods:refresh}




To refresh the scrollpanel.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Refresh the scroll panel
$("#scrollpanel").ejmScrollPanel('refresh');    
</script>{% endhighlight %}




### scrollBy`()`
{:#methods:scrollby}




To make the content scroll with time and easing given.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>        
$(function (){
var scroll= $("#scrollpanel").data("ejmScrollPanel");
$( "#maincontent" ).click(function() {
scroll.scrollBy(100,1000,5,10);
});     
});
</script>{% endhighlight %}




### scrollTo`()`
{:#methods:scrollto}




To make the content scroll to the position given.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>        
$(function (){
var scroll= $("#scrollpanel").data("ejmScrollPanel");
$( "#maincontent" ).click(function() {
scroll.scrollTo(10,10);
});     
});
</script>{% endhighlight %}




### stop`()`
{:#methods:stop}




To stop the scrolling.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Refresh the scroll panel
$("#scrollpanel").ejmScrollPanel('stop');       
</script>{% endhighlight %}




### zoom`()`
{:#methods:zoom}




To zoom the scroll content.



#### Example


{% highlight html %}<div id="maincontent">
<div>
Scroll content here
</div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent"/>
<script>
// Refresh the scroll panel
$(function (){
var scroll= $("#scrollpanel").data("ejmScrollPanel");
$( "#maincontent" ).click(function() {
scroll.zoom(10,1,1,1);
 });
 });
</script>{% endhighlight %}



## Events




### scroll
{:#events:scroll}




Event triggers when scroll move happens on the control.

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
<td class="description last">Event parameters from scrollpanel.
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
<td class="name">{% highlight html %}x{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the x position.</td>
</tr>
<tr>
<td class="name">{% highlight html %}y{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the y position.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-scroll="scroll"/>           
<script> 
// scroll event for scrollpanel
function scroll(args){ //handle the event 
}
</script>{% endhighlight %}


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>   
<script> 
// scroll event for scrollpanel
$("#scrollpanel").ejmScrollPanel({
  target: "maincontent",
  scroll: function (args) { //handle the event
}
});           
</script> {% endhighlight %}




### scrollEnd
{:#events:scrollend}




Event triggers when scroll end happens on the control.

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
<td class="description last">Event parameters from scrollpanel.
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
<td class="name">{% highlight html %}x{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the x position.</td>
</tr>
<tr>
<td class="name">{% highlight html %}y{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the y position.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-scrollend="scrollEnd"/>             
<script> 
// scrollEnd event for scrollpanel
function scrollEnd(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>   
<script> 
// scrollEnd event for scrollpanel
$("#scrollpanel").ejmScrollPanel({
  target: "maincontent",
  scrollEnd: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}




### scrollStart
{:#events:scrollstart}




Event triggers when scroll start happens on the control.

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
<td class="description last">Event parameters from scrollpanel.
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
<td class="name">{% highlight html %}x{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the x position.</td>
</tr>
<tr>
<td class="name">{% highlight html %}y{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the y position.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-scrollstart="scrollStart"/>         
<script> 
// scrollStart event for scrollpanel
function scrollStart(args){ //handle the event 
}
</script>{% endhighlight %}


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>   
<script> 
// scrollStart event for scrollpanel
$("#scrollpanel").ejmScrollPanel({
  target: "maincontent",
  scrollStart: function (args) { //handle the event
}
});           
</script> {% endhighlight %}




### zoomEnd
{:#events:zoomend}




Event triggers when zoom end happens on the control.

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
<td class="description last">Event parameters from scrollpanel.
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
<td class="name">{% highlight html %}x{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the x position.</td>
</tr>
<tr>
<td class="name">{% highlight html %}y{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the y position.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-zoomend="zoomEnd"/>         
<script> 
// zoomEnd event for scrollpanel
function zoomEnd(args){ //handle the event 
}
</script>{% endhighlight %}


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>   
<script> 
// zoomEnd event for scrollpanel
$("#scrollpanel").ejmScrollPanel({
  target: "maincontent",
  zoomEnd: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}




### zoomStart
{:#events:zoomstart}




Event triggers when zoom start happens on the control.

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
<td class="description last">Event parameters from scrollpanel.
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
<td class="name">{% highlight html %}x{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the x position.</td>
</tr>
<tr>
<td class="name">{% highlight html %}y{% endhighlight %}</td>
<td class="type"><span class="param-type">int</span></td>
<td class="description last">returns the y position.</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


#### Example


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-zoomstart="zoomStart"/>             
<script> 
// zoomStart event for scrollpanel
function zoomStart(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
// Create Scrollpanel control
<div id="maincontent">
  <div>
      Scroll content here
  </div>
</div>
<div id="scrollpanel"/>   
<script> 
// zoomStart event for scrollpanel
$("#scrollpanel").ejmScrollPanel({
  target: "maincontent",
  zoomStart: function (args) { //handle the event
}
});           
</script> {% endhighlight %}



