---
layout: post
title: ejmTab | API Reference | Mobile JS | Syncfusion
description:
documentation: API
platform: Mobilejs
keywords: ejmTab, API, Essential Studio JS Autocomplete (Mobile) 
---

# ejmTab

Custom Design for Html Tab control.

$(element).ejmTab<span class="signature">()</span>


#### Example

{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script> 
// Create tab  
$("#tab").ejmTab(); 
</script>{% endhighlight %}







#### Requires




* module:jQuery


* module:ej.mobile.application


* module:ej.core


* module:ej.unobtrusive


* module:ej.mobile.core


* module:ej.data


* module:ej.touch


* module:ej.mobile.listbox


* module:ej.mobile.scrollbar


* module:ej.mobile.scrollpanel




## Members








### ajaxSettings
{:#members:ajaxsettings}








Section for ajaxSettings specific functionalities.











### ajaxSettings.async`boolean`
{:#members:ajaxsettings-async}








Specifies the tab ajaxOptions.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: {                 
  async: true,                                                                
  } });                 
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { async: true });            {% endhighlight %}







### ajaxSettings.cache`boolean`
{:#members:ajaxsettings-cache}








Specifies the tab ajaxOptions.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: { 
  cache: false,                
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { cache: false });            {% endhighlight %}







### ajaxSettings.contentType`string`
{:#members:ajaxsettings-contenttype}








Specifies the tab ajaxOptions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: { 
  contentType: "html",                                
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { contentType: "html" });            {% endhighlight %}







### ajaxSettings.data`JSONObject`
{:#members:ajaxsettings-data}








Specifies the tab ajaxOptions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: { 
  data: {}
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", {data: {}});            {% endhighlight %}







### ajaxSettings.dataType`string`
{:#members:ajaxsettings-datatype}








Specifies the tab ajaxOptions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: {                                 
  dataType: "html",                                                
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { dataType: "html" });            {% endhighlight %}







### ajaxSettings.type`JSONObject`
{:#members:ajaxsettings-type}








Specifies the tab ajaxOptions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: { type: 'GET',                
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { type: 'GET'});            {% endhighlight %}







### ajaxSettings.url`string`
{:#members:ajaxsettings-url}








Specifies the tab ajaxOptions.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the ajaxSettings property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableAjax="true">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
// Set ajaxSettings on initialization. 
// To set ajaxSettings API value 
<script> 
$("#tab").ejmTab({ ajaxSettings: { 
  url: "",                
  } });                 
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { url: "" });            {% endhighlight %}







### allowScrolling`boolean`
{:#members:allowscrolling}








Specifies whether enable tab content's scrolling or not.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the allowScrolling property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-allowscrolling="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set allowScrolling on initialization. 
//To set allowScrolling API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
$("#tab").ejmTab({allowScrolling:true});        
});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the allowScrolling, after initialization:
// Get the allowScrolling API value.
 $("#tab").ejmTab ("option", "allowScrolling");                 
// Set the allowScrolling API
$("#tab").ejmTab ("option", "allowScrolling", "true");            {% endhighlight %}







### android
{:#members:android}








Section for android rendermode specific functionalities.











### android.contentType`enum`
{:#members:android-contenttype}








Specifies android tab content type tab content.




#### Default Value






* both








#### Example


{% highlight html %} 
// Set the android mode contentType property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="android" data-ej-android-contenttype="text" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-android-imageClass="icn-Movies" >
</li >
<li data-ej-href="#default2" data-ej-text='Music' data-ej-android-imageClass="icn-Music" >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-android-imageClass="icn-Favourites" >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set android mode contentType on initialization. 
//To android mode contentType API value 
<div id="tab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-android-imageClass="icn-Movies" >
</li >
<li data-ej-href="#default2" data-ej-text='Music' data-ej-android-imageClass="icn-Music" >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-android-imageClass="icn-Favourites" >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"android", android:{contentType:"ej.mobile.Tab.Android.ContentType.Text"}});       
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the android mode contentType API, after initialization:
// Get the android mode contentType value  
$("#tab").ejmTab("option", "android.ContentType");   
// Set the android mode contentType value 
$("#tab").ejmTab("option", "android.ContentType", "ej.mobile.Tab.Android.ContentType.Text"); {% endhighlight %}







### android.imageClass`string`
{:#members:android-imageclass}








Specifies class name for image to display in android mode.




#### Default Value






* ""








#### Example


{% highlight html %} 
// Set the android mode imageClass property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="android">
<ul >
<li data-ej-android-imageClass="icn-Movies" data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-android-imageClass="icn-Music" data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-android-imageClass="icn-Favourites" data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>                            {% endhighlight %}







### android.position`enum`
{:#members:android-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




#### Default Value






* fixed








#### Example


{% highlight html %} 
// Set the android mode position property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="android" data-ej-android-position="fixed" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>        {% endhighlight %}


{% highlight html %} 
// Set position on initialization. 
//To set position API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"android", android:{position: ej.mobile.Tab.Android.Position.Fixed}});     
});
</script>    {% endhighlight %}


{% highlight html %} 
// Get or set the android mode position API, after initialization:
// Get the android mode position value  
$("#tab").ejmTab("option", "android.position");   
// Set the android mode position value 
$("#tab").ejmTab("option", "android.position",  ej.mobile.Tab.Android.Position.Fixed); {% endhighlight %}







### badge
{:#members:badge}








Section for badge specific functionalities.











### badge.enabled`boolean`
{:#members:badge-enabled}








Specifies whether to enable Badge or not.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="false" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set enabled on initialization. 
// To enabled API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script>
$(function(){
$("#tab").ejmTab({badge:{enabled:true}});       
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the enabled, after initialization:
// Get the enabled API value.
 $("#tab").ejmTab ("option", "badge.enabled");                  
// Set the showBadge API
$("#tab").ejmTab ("option", "badge.enabled", "true");            {% endhighlight %}







### badge.maxValue`number`
{:#members:badge-maxvalue}








Specifies the maximum value allowed for a badge.




#### Default Value






* 100








#### Example


{% highlight html %} 
//Set the maximum Badge Value property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="true" data-ej-badge-maxvalue="100" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-badge-value="120" >
</li >
<li data-ej-href="#default2" data-ej-text='Music'data-ej-badge-value="80" >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-badge-value="64" >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set maxValue on initialization. 
// To maxValue API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-badge-value="120">
</li >
<li data-ej-href="#default2" data-ej-text='Music' data-ej-badge-value="80">
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-badge-value="64">
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script>
$(function(){
$("#tab").ejmTab({badge:{maxValue:100}});       
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the maxValue, after initialization:
// Get the maxValue API.
 $("#tab").ejmTab ("option", "badge.maxValue");                 
// Set the maxValue API
$("#tab").ejmTab ("option", "badge.maxValue", "100");            {% endhighlight %}







### badge.minValue`number`
{:#members:badge-minvalue}








Specifies the minimum value allowed for a badge.




#### Default Value






* 1








#### Example


{% highlight html %} 
//Set the minimum Badge Value property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="true" data-ej-badge-minvalue="10" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-badge-value="120" >
</li >
<li data-ej-href="#default2" data-ej-text='Music'data-ej-badge-value="80" >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-badge-value="64" >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set minValue on initialization. 
// To minValue API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' data-ej-badge-value="120">
</li >
<li data-ej-href="#default2" data-ej-text='Music' data-ej-badge-value="80">
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' data-ej-badge-value="64">
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script>
$(function(){
$("#tab").ejmTab({badge:{minValue:10}});        
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the minValue, after initialization:
// Get the minValue API.
 $("#tab").ejmTab ("option", "badge.minValue");                 
// Set the minValue API
$("#tab").ejmTab ("option", "badge.minValue", "10");            {% endhighlight %}







### badge.value`number`
{:#members:badge-value}








Specifies the badge Value.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the Badge Value property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="true" data-ej-badge-value="2" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>           {% endhighlight %}


{% highlight html %} 
// Set badge value on initialization. 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script>
$(function(){
$("#tab").ejmTab({badge:{value:2}});    
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the badge value, after initialization:
// Get the badge value API.
 $("#tab").ejmTab ("option", "badge.value");                    
// Set the badge value API
$("#tab").ejmTab ("option", "badge.value", "2");            {% endhighlight %}







### cssClass`string`
{:#members:cssclass}








Sets the root class for Tab theme. This cssClass API helps to use custom skinning option for Tab control. By defining the root class using this API, we need to include this root class in CSS.




#### Default Value






* ""








#### Example


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-cssclass="customclass" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 
//Create the music.html file with following content.
 Music contents here 
//Create the favourites.html file with following content.
 Favourites contents here{% endhighlight %}


{% highlight html %} 
// Set prefetchAjaxContent on initialization. 
//To set prefetchAjaxContent API value 
<div id="tab">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
<script>
$(function(){
$("#tab").ejmTab({cssClass:"customclass"});     
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.
 $("#tab").ejmTab ("option", "cssClass");                       
// Set the cssClass API
$("#tab").ejmTab ("option", "cssClass", "customclass");            {% endhighlight %}







### enableAjax`boolean`
{:#members:enableajax}








Specifies whether Ajax content will be used to load the tab contents.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enableAjax property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableajax="true" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 
//Create the music.html file with following content.
 Music contents here 
//Create the favourites.html file with following content.
 Favourites contents here            
// Set enableAjax on initialization. 
//To set enableAjax API value 
<div id="tab">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
<script>            
$(function(){
$("#tab").ejmTab({enableAjax: true});   
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the enableAjax, after initialization:
// Get the enableAjax API value.
 $("#tab").ejmTab ("option", "enableAjax");                     
// Set the enableAjax API
$("#tab").ejmTab ("option", "enableAjax", "true");            {% endhighlight %}







### enableCache`boolean`
{:#members:enablecache}








Specifies whether to enable Caching or not.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enableCache property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableajax="true" data-ej-enablecache="true" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 
//Create the music.html file with following content.
 Music contents here 
//Create the favourites.html file with following content.
 Favourites contents here{% endhighlight %}


{% highlight html %} 
// Set enableCache on initialization. 
//To set enableCache API value 
<div id="tab">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
<script>
$(function(){
$("#tab").ejmTab({enableAjax: true, enableCache: true });       
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enableCache, after initialization:
// Get the enableCache API value.
 $("#tab").ejmTab ("option", "enableCache");                    
// Set the enableCache API
$("#tab").ejmTab ("option", "enableCache", "true");            {% endhighlight %}







### enableNativeScrolling`boolean`
{:#members:enablenativescrolling}








Specifies whether enable native scrolling or not.




#### Default Value






* null








#### Example


{% highlight html %} 
//Set the enableNativeScrolling property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-allowscrolling="true" data-ej-enablenativescrolling="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set enableNativeScrolling on initialization. 
//To set enableNativeScrolling API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
$("#tab").ejmTab({allowScrolling:true, enableNativeScrolling:true});    
});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the enableNativeScrolling, after initialization:
// Get the allowScrolling API value.
 $("#tab").ejmTab ("option", "enableNativeScrolling");                  
// Set the allowScrolling API
$("#tab").ejmTab ("option", "enableNativeScrolling", "true");            {% endhighlight %}







### enablePersistence`boolean`
{:#members:enablepersistence}








Saves current model value to browser cookies for state maintains. While refreshing the page retains the model value applies from browser cookies.




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enablepersistence=true >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %}// Set enablePersistence on initialization. 
//To set enablePersistence API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({enablePersistence:true});     
});
</script> {% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.
 $("#tab").ejmTab ("option", "enablePersistence");                      
// Set the enablePersistence API
$("#tab").ejmTab ("option", "enablePersistence", true);            {% endhighlight %}







### flat
{:#members:flat}








Section for flat rendermode specific functionalities.











### flat.position`enum`
{:#members:flat-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




#### Default Value






* fixed








#### Example


{% highlight html %} 
// Set the flat mode position property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="flat" data-ej-flat-position="fixed" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>           {% endhighlight %}


{% highlight html %} 
// Set flat mode position on initialization. 
//To set flat mode position API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>  
<div id="default3" >
Favourites content here
</div>
<script>
$(function(){
$("#tab").ejmTab({renderMode:"flat", flat:{position: ej.mobile.Tab.Flat.Fixed}});       
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the flat mode position API, after initialization:
// Get the flat mode position value  
$("#tab").ejmTab("option", "flat.position");   
// Set the flat mode position value 
$("#tab").ejmTab("option", "flat.position",  ej.mobile.Tab.Flat.Fixed); {% endhighlight %}







### ios7
{:#members:ios7}








Section for ios7 rendermode specific functionalities.











### ios7.imageClass`string`
{:#members:ios7-imageclass}








Specifies the class for image to display in ios7 mode.




#### Default Value






* ""








#### Example


{% highlight html %} 
// Set the ios7 mode imageClass property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="ios7">
<ul >
<li data-ej-ios7-imageclass="icn-Movies" data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-ios7-imageclass="icn-Music" data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-ios7-imageclass="icn-Favourites" data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>                    {% endhighlight %}







### ios7.overflowBadge
{:#members:ios7-overflowbadge}








Section for overflow badge specific functionalities.











### ios7.overflowBadge.enabled`boolean`
{:#members:ios7-overflowbadge-enabled}








Specifies whether to enable badge for overflow tab or not.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the ios7 overflowBadge mode enabled property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="ios7" data-ej-ios7-overflowbadge-enabled="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>           {% endhighlight %}


{% highlight html %} 
// Set ios7 mode overflowbadge enabled badge on initialization. 
//To set ios7 mode overflowbadge enabled badge customText API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"ios7", ios7:{overflowBadge:{enabled:true}}});     
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the ios7 overflowBadge mode enabled API, after initialization:
// Get the ios7 mode enabled value  
$("#tab").ejmTab("option", "ios7.overflowBadge.enabled");   
// Set the ios7 overflowBadge mode enabled value 
$("#tab").ejmTab("option", "ios7.overflowBadge.enabled", true); {% endhighlight %}







### ios7.overflowBadge.maxValue`number`
{:#members:ios7-overflowbadge-maxvalue}








Specifies the maximum value for overflow batch in ios7 mode.




#### Default Value






* 100








#### Example


{% highlight html %} 
// Set the ios7 mode overflowBadge maxValue property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="ios7" data-ej-ios7-overflowbadge-enabled="true" data-ej-ios7-overflowbadge-maxvalue="100" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set ios7 mode overflowbadge maxvalue on initialization. 
//To set ios7 mode overflowbadge maxvalue  API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"ios7",ios7:{overflowBadge:{enabled:true,maxValue:100}}}); 
});
</script>    {% endhighlight %}


{% highlight html %} 
// Get or set the ios7 overflowBadge mode maxValue API, after initialization:
// Get the ios7 overflowBadge mode maxValue value  
$("#tab").ejmTab("option", "ios7.overflowBadge.maxValue");   
// Set the ios7 overflowBadge mode maxValue value 
$("#tab").ejmTab("option", "ios7.overflowBadge.maxValue",100); {% endhighlight %}







### ios7.overflowBadge.minValue`number`
{:#members:ios7-overflowbadge-minvalue}








Specifies the minimum value for overflow batch in ios7 mode.




#### Default Value






* 100








#### Example


{% highlight html %} 
// Set the ios7 mode overflowBadge minValue property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="ios7" data-ej-ios7-overflowbadge-enabled="true" data-ej-ios7-overflowbadge-minvalue="10" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set ios7 mode overflowbadge minvalue on initialization. 
//To set ios7 mode overflowbadge minvalue  API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"ios7",ios7:{overflowBadge:{enabled:true,minValue:10}}});  
});
</script>    {% endhighlight %}


{% highlight html %} 
// Get or set the ios7 overflowBadge mode minValue API, after initialization:
// Get the ios7 overflowBadge mode minValue value  
$("#tab").ejmTab("option", "ios7.overflowBadge.minValue");   
// Set the ios7 overflowBadge mode minValue value 
$("#tab").ejmTab("option", "ios7.overflowBadge.minValue",10); {% endhighlight %}







### ios7.overflowBadge.value`number`
{:#members:ios7-overflowbadge-value}








Specifies the value for overflow badge in ios7 mode.




#### Default Value






* 0








#### Example


{% highlight html %} 
// Set the ios7 overflowBadge mode value property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="ios7" data-ej-ios7-overflowbadge-enabled="true" data-ej-ios7-overflowbadge-value="2" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>          {% endhighlight %}


{% highlight html %} 
// Set ios7 mode overflowbadge value on initialization. 
//To set ios7 mode overflowbadge value API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"ios7",ios7:{overflowBadge:{enabled:true,value:2}}});      
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the ios7 overflowbadge mode value API, after initialization:
// Get the ios7 overflowBadge mode value  
$("#tab").ejmTab("option", "ios7.overflowBadge.value");   
// Set the ios7 overflowBadge mode value 
$("#tab").ejmTab("option", "ios7.overflowBadge.value",2); {% endhighlight %}







### prefetchAjaxContent`boolean`
{:#members:prefetchajaxcontent}








Specifies whether need to prefetch the ajax content or not




#### Default Value






* false








#### Example


{% highlight html %} 
//Set the prefetchAjaxContent property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-prefetchajaxcontent="true" data-ej-enableajax="true" data-ej-enablecache="true" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 
//Create the music.html file with following content.
 Music contents here 
//Create the favourites.html file with following content.
 Favourites contents here{% endhighlight %}


{% highlight html %} 
// Set prefetchAjaxContent on initialization. 
//To set prefetchAjaxContent API value 
<div id="tab">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
<script>
$(function(){
$("#tab").ejmTab({enableAjax: true, enableCache: true, prefetchAjaxContent:true});      
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the prefetchAjaxContent, after initialization:
// Get the prefetchAjaxContent API value.
 $("#tab").ejmTab ("option", "prefetchAjaxContent");                    
// Set the enableCache API
$("#tab").ejmTab ("option", "prefetchAjaxContent", "true");            {% endhighlight %}







### renderMode`enum`
{:#members:rendermode}








Changes the rendering mode. See <a href="global.html#RenderMode">RenderMode</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="auto" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// To hideBadge Tab Control
$("#tab").ejmTab({renderMode:ej.mobile.RenderMode.Android});    
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.
 $("#tab").ejmTab ("option", "renderMode");                     
// Set the renderMode API
$("#tab").ejmTab ("option", "renderMode", ej.mobile.RenderMode.Android);            {% endhighlight %}







### selectedItemIndex`number`
{:#members:selecteditemindex}








Specifies the Item Index which is selected.




#### Default Value






* 0








#### Example


{% highlight html %} 
//Set the selectedItemIndex property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-selecteditemindex="1" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %}// Set selectedItemIndex on initialization. 
//To set selectedItemIndex API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({selectedItemIndex:1});        
});
</script> {% endhighlight %}


{% highlight html %} 
//Get or set the selectedItemIndex, after initialization:
// Get the selectedItemIndex API value.
 $("#tab").ejmTab ("option", "selectedItemIndex");                      
// Set the selectedItemIndex API
$("#tab").ejmTab ("option", "selectedItemIndex", "1");            {% endhighlight %}







### showAjaxPopup`boolean`
{:#members:showajaxpopup}








Specifies whether show waiting popup in Ajax content loading or not.




#### Default Value






* true








#### Example


{% highlight html %} 
//Set the showAjaxPopup property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-enableajax="true" data-ej-showajaxpopup="true" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 
//Create the music.html file with following content.
 Music contents here 
//Create the favourites.html file with following content.
 Favourites contents here{% endhighlight %}


{% highlight html %} 
// Set showAjaxPopup on initialization. 
//To set showAjaxPopup API value 
<div id="tab">
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div> 
<script>
$(function(){
$("#tab").ejmTab({enableAjax: true, showAjaxPopup: false });    
});
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showAjaxPopup, after initialization:
// Get the showAjaxPopup API value.
 $("#tab").ejmTab ("option", "showAjaxPopup");                  
// Set the showAjaxPopup API
$("#tab").ejmTab ("option", "showAjaxPopup", "false");            {% endhighlight %}







### showScrollbars`boolean`
{:#members:showscrollbars}








Specifies whether show the scrollbars or not




#### Default Value






* null








#### Example


{% highlight html %} 
//Set the showScrollbars property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-allowscrolling="true" data-ej-showscrollbars="false" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
// Set showScrollbars property on initialization. 
//To set showScrollbars API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
$("#tab").ejmTab({allowScrolling:true,showScrollbars:false});   
});
</script>                 {% endhighlight %}


{% highlight html %} 
//Get or set the showScrollbars property, after initialization:
// Get the showScrollbars API value.
 $("#tab").ejmTab ("option", "showScrollbars");                 
// Set the showScrollbars API
$("#tab").ejmTab ("option", "showScrollbars", "false");            {% endhighlight %}







### theme`enum`
{:#members:theme}








Changes the theme. See <a href="global.html#Theme">Theme</a>




#### Default Value






* auto








#### Example


{% highlight html %} 
//Set the theme property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-theme="auto" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>{% endhighlight %}


{% highlight html %} 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
// Set theme on initialization. 
//To set theme API value 
<script>
$(function(){
// To enable tab Control
$("#tab").ejmTab({theme:ej.mobile.Theme.Dark}); 
});
</script>         {% endhighlight %}


{% highlight html %} 
//Get or set the theme, after initialization:
// Get the theme API value.
 $("#tab").ejmTab ("option", "theme");                  
// Set the theme API
$("#tab").ejmTab ("option", "theme", ej.mobile.Theme.Dark);            {% endhighlight %}







### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.enableCustomText`boolean`
{:#members:windows-enablecustomtext}








Specifies whether to enable custom text for windows mode or not.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode enableCustomText property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="windows" data-ej-windows-enablecustomtext="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set windows mode enableCustomText on initialization. 
//To set windows mode enableCustomText API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"windows", windows:{enableCustomText:true}});      
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode enableCustomText API, after initialization:
// Get the windows mode enableCustomText value  
$("#tab").ejmTab("option", "windows.enableCustomText");   
// Set the windows mode enableCustomText value 
$("#tab").ejmTab("option", "windows.enableCustomText", "true"); {% endhighlight %}







### windows.enableTouchMove
{:#members:windows-enabletouchmove}








Specifies whether enable to move the content while swipe move.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode enableTouchMove property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="windows" data-ej-windows-enabletouchmove="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set windows mode enableTouchMove on initialization. 
//To set windows mode enableTouchMove API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"windows", windows:{enableTouchMove:true}});       
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode enableTouchMove API, after initialization:
// Get the windows mode enableTouchMove value  
$("#tab").ejmTab("option", "windows.enableTouchMove");   
// Set the windows mode enableTouchMove value 
$("#tab").ejmTab("option", "windows.enableTouchMove", "true"); {% endhighlight %}







### windows.position`enum`
{:#members:windows-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




#### Default Value






* fixed








#### Example


{% highlight html %} 
// Set the windows mode position property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="windows" data-ej-windows-position="fixed" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>           {% endhighlight %}


{% highlight html %} 
// Set windows mode position on initialization. 
//To set windows mode position API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"windows", windows:{position: ej.mobile.Tab.Windows.Position.Fixed}});     
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode position API, after initialization:
// Get the windows mode position value  
$("#tab").ejmTab("option", "windows.position");   
// Set the windows mode position value 
$("#tab").ejmTab("option", "windows.position",  ej.mobile.Tab.Windows.Position.Fixed); {% endhighlight %}







### windows.preventContentSwipe`boolean`
{:#members:windows-preventcontentswipe}








Specifies whether to prevent swiping geture or not in windows mode.




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode preventContentSwipe property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="windows" data-ej-windows-preventcontentswipe="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            {% endhighlight %}


{% highlight html %} 
// Set windows mode preventContentSwipe on initialization. 
//To set windows mode preventContentSwipe API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"windows", windows:{preventContentSwipe:true}});   
});
</script>  {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode preventContentSwipe API, after initialization:
// Get the windows mode preventContentSwipe value  
$("#tab").ejmTab("option", "windows.preventContentSwipe");   
// Set the windows mode preventContentSwipe value 
$("#tab").ejmTab("option", "windows.preventContentSwipe", "true"); {% endhighlight %}







### windows.renderDefault`boolean`
{:#members:windows-renderdefault}








Specifies whether to render based on the windowsphone's current accent color and device theme




#### Default Value






* false








#### Example


{% highlight html %} 
// Set the windows mode renderDefault property in unobtrusive way.
<div id="tab" data-role="ejmtab" data-ej-rendermode="windows" data-ej-windows-renderdefault="false" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>         {% endhighlight %}


{% highlight html %} 
// Set windows mode renderDefault on initialization. 
//To set windows mode renderDefault API value 
<div id="tab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div> 
<script>
$(function(){
$("#tab").ejmTab({renderMode:"windows", windows:{renderDefault:true}}); 
});
</script> {% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#tab").ejmTab("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#tab").ejmTab("option", "windows.renderDefault", "false"); {% endhighlight %}





## Methods








### addItem`()`
{:#methods:additem}








To add a tab item





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call addItem method
$("#tab").ejmTab("addItem","addTab",3); 
});
</script>{% endhighlight %}







### addOverflowItem`()`
{:#methods:addoverflowitem}








To add tab item in more option





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// To addOverflowItem Tab Control
$("#tab").ejmTab("addOverflowItem","addMoreTab",3);
});
</script>{% endhighlight %}







### disableContent`()`
{:#methods:disablecontent}








To disable the tab item content





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call disableContent method
$("#tab").ejmTab("disableContent",1);   
});
</script>{% endhighlight %}







### disableItem`()`
{:#methods:disableitem}








To disable the tab item





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call disableItem method
$("#tab").ejmTab("disableItem",1);      
});
</script>{% endhighlight %}







### enableContent`()`
{:#methods:enablecontent}








To enable the tab item content





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call enableContent method
$("#tab").ejmTab("enableContent",1);    
});
</script>{% endhighlight %}







### enableItem`()`
{:#methods:enableitem}








To enable the tab item





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call enableItem method
$("#tab").ejmTab("enableItem",1);       
});
</script>{% endhighlight %}







### getActiveItem`()`
{:#methods:getactiveitem}








Get the current active item





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call getActiveItem method
$("#tab").ejmTab("getActiveItem");      
});
</script>{% endhighlight %}







### getActiveItemText`()`
{:#methods:getactiveitemtext}








Get the current active item text





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call getActiveItem method
$("#tab").ejmTab("getActiveItemText");  
});
</script>{% endhighlight %}







### getItemsCount`()`
{:#methods:getitemscount}








To return the tab item count





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call getItemsCount method
$("#tab").ejmTab("getItemsCount");      
});
</script>{% endhighlight %}







### getOverflowItemCount`()`
{:#methods:getoverflowitemcount}








Get the overflow tab item count





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call getOverflowItemCount method
$("#tab").ejmTab("getOverflowItemCount");       
});
</script>{% endhighlight %}







### hideBadge`()`
{:#methods:hidebadge}








To hide a badge





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="true">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call hideBadge method
$("#tab").ejmTab("hideBadge",1);        
});
</script>{% endhighlight %}







### removeItem`()`
{:#methods:removeitem}








To remove tab item





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call removeItem method
$("#tab").ejmTab("removeItem",1);       
});
</script>{% endhighlight %}







### removeOverflowItem`()`
{:#methods:removeoverflowitem}








To remove tab item in overflow option





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call removeOverflowItem method
$("#tab").ejmTab("removeOverflowItem",1);       
});
</script>{% endhighlight %}







### selectItem`()`
{:#methods:selectitem}








To make the tab item to be active





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
// Call selectTabItem method
$("#tab").ejmTab("selectItem",1);       
});
</script>{% endhighlight %}







### showBadge`()`
{:#methods:showbadge}








To show the tab's badge.





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
// To showBadge Tab Control
$(function(){
$("#tab").ejmTab("showBadge",1);        
});
</script>{% endhighlight %}







### updateBadgeValue`()`
{:#methods:updatebadgevalue}








To update the badge value





#### Example


{% highlight html %} 
<div id="tab" data-role="ejmtab" data-ej-badge-enabled="true" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>  
<script>
$(function(){
//Call updateBadgeValue method
$("#tab").ejmTab("updateBadgeValue",1,"Music Collection");      
});
</script>{% endhighlight %}





## Events








### ajaxBeforeLoad
{:#events:ajaxbeforeload}








Event triggers when the ajaxBeforeLoad happens in the Tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.item{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax element.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.content{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content.</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-ajaxbeforeload="beforeLoad" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
<script> 
// ajaxbeforeload event 
function beforeLoad(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here            
//ajaxBeforeLoad event
<script> 
$("#tab").ejmTab({
  ajaxBeforeLoad: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### ajaxComplete
{:#events:ajaxcomplete}








Event triggers when the ajaxComplete happens in the tab.

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-ajaxcomplete="complete" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
<script> 
// ajaxComplete event 
function complete(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here            
<script> 
//ajaxComplete event 
$("#tab").ejmTab({
  ajaxComplete: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### ajaxError
{:#events:ajaxerror}








Event triggers when the ajaxError happens in the tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.error{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax error content.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.status{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the tab state</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.item{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.index{% endhighlight %}</td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-ajaxerror="error" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
<script> 
// ajaxError event 
function error(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here 
<script> 
//ajaxError event 
$("#tab").ejmTab({
  ajaxError: function (args) { //handle the event 
}
});   
</script> {% endhighlight %}







### ajaxSuccess
{:#events:ajaxsuccess}








Event triggers when the ajaxSuccess happens in the tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.item{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.content{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.index{% endhighlight %}</td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-ajaxsuccess="success" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
<script> 
// ajaxSuccess event 
function success(args){ //handle the event
}
</script>                        {% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here            
<script> 
//ajaxSuccess event 
$("#tab").ejmTab({
  ajaxSuccess: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### load
{:#events:load}








Event triggers when the load happens in the Tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-load="onLoad" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
<script> 
// complete event 
function onLoad(args){ //handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>   
<script> 
//load event 
$("#tab").ejmTab({
  load: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### loadComplete
{:#events:loadcomplete}








Event triggers when the loadComplete happens in the Tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.element{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab element</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.id{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the id</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-loadcomplete="onComplete" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
<script> 
// loadcomplete event 
function onComplete(args){ //handle the event
}
</script>  {% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>
<script> 
//loadComplete event 
$("#tab").ejmTab({
  loadComplete: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### prefetchContentLoaded
{:#events:prefetchcontentloaded}








Event triggered after ajax contents are prefetched.

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.item{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.content{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.url{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item's url</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.index{% endhighlight %}</td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-prefetchContentLoaded="onPrefetch" data-ej-prefetchajaxcontent="true" data-ej-enableajax="true" data-ej-enablecache="true" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here
<script> 
// prefetchContentLoaded event 
function onPrefetch(args){ //handle the event
}
</script>                        {% endhighlight %}


{% highlight html %} 
//prefetchContentLoaded event for Tab
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="movies.html" data-ej-text='Movies' >
</li >
<li data-ej-href="music.html" data-ej-text='Music' >
</li >
<li data-ej-href="favourites.html" data-ej-text='Favourites' >
</li >
</ul >
</div>             
//Create the movies.html file with following content.
 Movies contents here 

//Create the music.html file with following content.
 Music contents here 

//Create the favourites.html file with following content.
 Favourites contents here            
<script> 
//prefetchContentLoaded event 
$("#tab").ejmTab({enableAjax: true, enableCache: true, prefetchAjaxContent:true},ajaxSuccess: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### touchEnd
{:#events:touchend}








Event triggers when the touchEnd happens in the Tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the text of the Tab</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-touchend="end" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            
<script> 
// touchEnd event 
function end(args){ //handle the event
}
</script> {% endhighlight %}


{% highlight html %}             
<div id="tab" data-role="ejmtab" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>    
<script> 
//touchEnd event
$("#tab").ejmTab({
  touchEnd: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}







### touchStart
{:#events:touchstart}








Event triggers when the touchStart happens in the Tab

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
<td class="name">{% highlight html %}argument.cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.model{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}argument.text{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the text of the Tab</td>
</tr>
</tbody>
</table>




#### Example


{% highlight html %}             
<div id="tab" data-role="ejmtab" data-ej-touchstart="start" >
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>            
<script> 
// touchStart event 
function start(args){ //handle the event
}
</script> {% endhighlight %}


{% highlight html %} 
//open event for Tab
<div id="tab" data-role="ejmtab">
<ul >
<li data-ej-href="#default1" data-ej-text='Movies' >
</li >
<li data-ej-href="#default2" data-ej-text='Music' >
</li >
<li data-ej-href="#default3" data-ej-text='Favourites' >
</li >
</ul >
</div>  
<div id="default1" >
Movies content here
</div>    
<div id="default2" >
Music content here
</div>
<div id="default3" >
Favourites content here
</div>    
<script> 
//touchStart event 
$("#tab").ejmTab({
  touchStart: function (args) { //handle the event 
}
});           
</script> {% endhighlight %}




