---
layout: post
title: ejmTab
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Tab control.










$(element).ejmTab<span class="signature">()</span>











Example
{:.example}

<pre class="prettyprint">
<code> 
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


* module:ej.mobile.listbox


* module:ej.mobile.scrollbar


* module:ej.mobile.scrollpanel




## Members








### ajaxSettings
{:#members:ajaxsettings}








Section for ajaxSettings specific functionalities.











### ajaxSettings.async<span class="type-signature type boolean">boolean</span>
{:#members:ajaxsettings-async}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { async: true });            </code>
</pre>






### ajaxSettings.cache<span class="type-signature type boolean">boolean</span>
{:#members:ajaxsettings-cache}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { cache: false });            </code>
</pre>






### ajaxSettings.contentType<span class="type-signature type string">string</span>
{:#members:ajaxsettings-contenttype}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { contentType: "html" });            </code>
</pre>






### ajaxSettings.data<span class="type-signature type jsonobject">JSONObject</span>
{:#members:ajaxsettings-data}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", {data: {}});            </code>
</pre>






### ajaxSettings.dataType<span class="type-signature type string">string</span>
{:#members:ajaxsettings-datatype}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { dataType: "html" });            </code>
</pre>






### ajaxSettings.type<span class="type-signature type jsonobject">JSONObject</span>
{:#members:ajaxsettings-type}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { type: 'GET'});            </code>
</pre>






### ajaxSettings.url<span class="type-signature type string">string</span>
{:#members:ajaxsettings-url}








Specifies the tab ajaxOptions.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the ajaxSettings, after initialization:
// Get the ajaxSetttings API value.
 $("#tab").ejmTab ("option", "ajaxSettings");                   
// Set the ajaxSettings API
$("#tab").ejmTab ("option", "ajaxSettings", { url: "" });            </code>
</pre>






### allowScrolling<span class="type-signature type boolean">boolean</span>
{:#members:allowscrolling}








Specifies whether enable tab content's scrolling or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the allowScrolling, after initialization:
// Get the allowScrolling API value.
 $("#tab").ejmTab ("option", "allowScrolling");                 
// Set the allowScrolling API
$("#tab").ejmTab ("option", "allowScrolling", "true");            </code>
</pre>






### android
{:#members:android}








Section for android rendermode specific functionalities.











### android.contentType<span class="type-signature type enum">enum</span>
{:#members:android-contenttype}








Specifies android tab content type tab content.




Default Value:
{:.param}






* both








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode contentType API, after initialization:
// Get the android mode contentType value  
$("#tab").ejmTab("option", "android.ContentType");   
// Set the android mode contentType value 
$("#tab").ejmTab("option", "android.ContentType", "ej.mobile.Tab.Android.ContentType.Text"); </code>
</pre>






### android.imageClass<span class="type-signature type string">string</span>
{:#members:android-imageclass}








Specifies class name for image to display in android mode.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>                            </code>
</pre>






### android.position<span class="type-signature type enum">enum</span>
{:#members:android-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




Default Value:
{:.param}






* fixed








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>        </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>    </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the android mode position API, after initialization:
// Get the android mode position value  
$("#tab").ejmTab("option", "android.position");   
// Set the android mode position value 
$("#tab").ejmTab("option", "android.position",  ej.mobile.Tab.Android.Position.Fixed); </code>
</pre>






### badge
{:#members:badge}








Section for badge specific functionalities.











### badge.enabled<span class="type-signature type boolean">boolean</span>
{:#members:badge-enabled}








Specifies whether to enable Badge or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enabled, after initialization:
// Get the enabled API value.
 $("#tab").ejmTab ("option", "badge.enabled");                  
// Set the showBadge API
$("#tab").ejmTab ("option", "badge.enabled", "true");            </code>
</pre>






### badge.maxValue<span class="type-signature type number">number</span>
{:#members:badge-maxvalue}








Specifies the maximum value allowed for a badge.




Default Value:
{:.param}






* 100








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the maxValue, after initialization:
// Get the maxValue API.
 $("#tab").ejmTab ("option", "badge.maxValue");                 
// Set the maxValue API
$("#tab").ejmTab ("option", "badge.maxValue", "100");            </code>
</pre>






### badge.minValue<span class="type-signature type number">number</span>
{:#members:badge-minvalue}








Specifies the minimum value allowed for a badge.




Default Value:
{:.param}






* 1








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the minValue, after initialization:
// Get the minValue API.
 $("#tab").ejmTab ("option", "badge.minValue");                 
// Set the minValue API
$("#tab").ejmTab ("option", "badge.minValue", "10");            </code>
</pre>






### badge.value<span class="type-signature type number">number</span>
{:#members:badge-value}








Specifies the badge Value.




Default Value:
{:.param}






* 0








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>           </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the badge value, after initialization:
// Get the badge value API.
 $("#tab").ejmTab ("option", "badge.value");                    
// Set the badge value API
$("#tab").ejmTab ("option", "badge.value", "2");            </code>
</pre>






### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}








Sets the root class for Tab theme. This cssClass API helps to use custom skinning option for Tab control. By defining the root class using this API, we need to include this root class in CSS.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
 Favourites contents here</code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.
 $("#tab").ejmTab ("option", "cssClass");                       
// Set the cssClass API
$("#tab").ejmTab ("option", "cssClass", "customclass");            </code>
</pre>






### enableAjax<span class="type-signature type boolean">boolean</span>
{:#members:enableajax}








Specifies whether Ajax content will be used to load the tab contents.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enableAjax, after initialization:
// Get the enableAjax API value.
 $("#tab").ejmTab ("option", "enableAjax");                     
// Set the enableAjax API
$("#tab").ejmTab ("option", "enableAjax", "true");            </code>
</pre>






### enableCache<span class="type-signature type boolean">boolean</span>
{:#members:enablecache}








Specifies whether to enable Caching or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
 Favourites contents here</code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enableCache, after initialization:
// Get the enableCache API value.
 $("#tab").ejmTab ("option", "enableCache");                    
// Set the enableCache API
$("#tab").ejmTab ("option", "enableCache", "true");            </code>
</pre>






### enableNativeScrolling<span class="type-signature type boolean">boolean</span>
{:#members:enablenativescrolling}








Specifies whether enable native scrolling or not.




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enableNativeScrolling, after initialization:
// Get the allowScrolling API value.
 $("#tab").ejmTab ("option", "enableNativeScrolling");                  
// Set the allowScrolling API
$("#tab").ejmTab ("option", "enableNativeScrolling", "true");            </code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}








Saves current model value to browser cookies for state maintains. While refreshing the page retains the model value applies from browser cookies.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set enablePersistence on initialization. 
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
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.
 $("#tab").ejmTab ("option", "enablePersistence");                      
// Set the enablePersistence API
$("#tab").ejmTab ("option", "enablePersistence", true);            </code>
</pre>






### flat
{:#members:flat}








Section for flat rendermode specific functionalities.











### flat.position<span class="type-signature type enum">enum</span>
{:#members:flat-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




Default Value:
{:.param}






* fixed








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>           </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the flat mode position API, after initialization:
// Get the flat mode position value  
$("#tab").ejmTab("option", "flat.position");   
// Set the flat mode position value 
$("#tab").ejmTab("option", "flat.position",  ej.mobile.Tab.Flat.Fixed); </code>
</pre>






### ios7
{:#members:ios7}








Section for ios7 rendermode specific functionalities.











### ios7.imageClass<span class="type-signature type string">string</span>
{:#members:ios7-imageclass}








Specifies the class for image to display in ios7 mode.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>                    </code>
</pre>






### ios7.overflowBadge
{:#members:ios7-overflowbadge}








Section for overflow badge specific functionalities.











### ios7.overflowBadge.enabled<span class="type-signature type boolean">boolean</span>
{:#members:ios7-overflowbadge-enabled}








Specifies whether to enable badge for overflow tab or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>           </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 overflowBadge mode enabled API, after initialization:
// Get the ios7 mode enabled value  
$("#tab").ejmTab("option", "ios7.overflowBadge.enabled");   
// Set the ios7 overflowBadge mode enabled value 
$("#tab").ejmTab("option", "ios7.overflowBadge.enabled", true); </code>
</pre>






### ios7.overflowBadge.maxValue<span class="type-signature type number">number</span>
{:#members:ios7-overflowbadge-maxvalue}








Specifies the maximum value for overflow batch in ios7 mode.




Default Value:
{:.param}






* 100








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>    </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 overflowBadge mode maxValue API, after initialization:
// Get the ios7 overflowBadge mode maxValue value  
$("#tab").ejmTab("option", "ios7.overflowBadge.maxValue");   
// Set the ios7 overflowBadge mode maxValue value 
$("#tab").ejmTab("option", "ios7.overflowBadge.maxValue",100); </code>
</pre>






### ios7.overflowBadge.minValue<span class="type-signature type number">number</span>
{:#members:ios7-overflowbadge-minvalue}








Specifies the minimum value for overflow batch in ios7 mode.




Default Value:
{:.param}






* 100








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>    </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 overflowBadge mode minValue API, after initialization:
// Get the ios7 overflowBadge mode minValue value  
$("#tab").ejmTab("option", "ios7.overflowBadge.minValue");   
// Set the ios7 overflowBadge mode minValue value 
$("#tab").ejmTab("option", "ios7.overflowBadge.minValue",10); </code>
</pre>






### ios7.overflowBadge.value<span class="type-signature type number">number</span>
{:#members:ios7-overflowbadge-value}








Specifies the value for overflow badge in ios7 mode.




Default Value:
{:.param}






* 0








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>          </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the ios7 overflowbadge mode value API, after initialization:
// Get the ios7 overflowBadge mode value  
$("#tab").ejmTab("option", "ios7.overflowBadge.value");   
// Set the ios7 overflowBadge mode value 
$("#tab").ejmTab("option", "ios7.overflowBadge.value",2); </code>
</pre>






### prefetchAjaxContent<span class="type-signature type boolean">boolean</span>
{:#members:prefetchajaxcontent}








Specifies whether need to prefetch the ajax content or not




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
 Favourites contents here</code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the prefetchAjaxContent, after initialization:
// Get the prefetchAjaxContent API value.
 $("#tab").ejmTab ("option", "prefetchAjaxContent");                    
// Set the enableCache API
$("#tab").ejmTab ("option", "prefetchAjaxContent", "true");            </code>
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.
 $("#tab").ejmTab ("option", "renderMode");                     
// Set the renderMode API
$("#tab").ejmTab ("option", "renderMode", ej.mobile.RenderMode.Android);            </code>
</pre>






### selectedItemIndex<span class="type-signature type number">number</span>
{:#members:selecteditemindex}








Specifies the Item Index which is selected.




Default Value:
{:.param}






* 0








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set selectedItemIndex on initialization. 
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
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the selectedItemIndex, after initialization:
// Get the selectedItemIndex API value.
 $("#tab").ejmTab ("option", "selectedItemIndex");                      
// Set the selectedItemIndex API
$("#tab").ejmTab ("option", "selectedItemIndex", "1");            </code>
</pre>






### showAjaxPopup<span class="type-signature type boolean">boolean</span>
{:#members:showajaxpopup}








Specifies whether show waiting popup in Ajax content loading or not.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
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
 Favourites contents here</code>
</pre>
<pre class="prettyprint">
<code> 
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showAjaxPopup, after initialization:
// Get the showAjaxPopup API value.
 $("#tab").ejmTab ("option", "showAjaxPopup");                  
// Set the showAjaxPopup API
$("#tab").ejmTab ("option", "showAjaxPopup", "false");            </code>
</pre>






### showScrollbars<span class="type-signature type boolean">boolean</span>
{:#members:showscrollbars}








Specifies whether show the scrollbars or not




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>                 </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showScrollbars property, after initialization:
// Get the showScrollbars API value.
 $("#tab").ejmTab ("option", "showScrollbars");                 
// Set the showScrollbars API
$("#tab").ejmTab ("option", "showScrollbars", "false");            </code>
</pre>






### theme<span class="type-signature type enum">enum</span>
{:#members:theme}








Changes the theme. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>         </code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.
 $("#tab").ejmTab ("option", "theme");                  
// Set the theme API
$("#tab").ejmTab ("option", "theme", ej.mobile.Theme.Dark);            </code>
</pre>






### windows
{:#members:windows}








Section for windows rendermode specific functionalities.











### windows.enableCustomText<span class="type-signature type boolean">boolean</span>
{:#members:windows-enablecustomtext}








Specifies whether to enable custom text for windows mode or not.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode enableCustomText API, after initialization:
// Get the windows mode enableCustomText value  
$("#tab").ejmTab("option", "windows.enableCustomText");   
// Set the windows mode enableCustomText value 
$("#tab").ejmTab("option", "windows.enableCustomText", "true"); </code>
</pre>






### windows.enableTouchMove
{:#members:windows-enabletouchmove}








Specifies whether enable to move the content while swipe move.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode enableTouchMove API, after initialization:
// Get the windows mode enableTouchMove value  
$("#tab").ejmTab("option", "windows.enableTouchMove");   
// Set the windows mode enableTouchMove value 
$("#tab").ejmTab("option", "windows.enableTouchMove", "true"); </code>
</pre>






### windows.position<span class="type-signature type enum">enum</span>
{:#members:windows-position}








Specifies whether to position the tabs in fixed or relative position in the page. See <a href="global.html#Position">Position</a>.




Default Value:
{:.param}






* fixed








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>           </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode position API, after initialization:
// Get the windows mode position value  
$("#tab").ejmTab("option", "windows.position");   
// Set the windows mode position value 
$("#tab").ejmTab("option", "windows.position",  ej.mobile.Tab.Windows.Position.Fixed); </code>
</pre>






### windows.preventContentSwipe<span class="type-signature type boolean">boolean</span>
{:#members:windows-preventcontentswipe}








Specifies whether to prevent swiping geture or not in windows mode.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>            </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode preventContentSwipe API, after initialization:
// Get the windows mode preventContentSwipe value  
$("#tab").ejmTab("option", "windows.preventContentSwipe");   
// Set the windows mode preventContentSwipe value 
$("#tab").ejmTab("option", "windows.preventContentSwipe", "true"); </code>
</pre>






### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}








Specifies whether to render based on the windowsphone's current accent color and device theme




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
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
</div>         </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#tab").ejmTab("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#tab").ejmTab("option", "windows.renderDefault", "false"); </code>
</pre>




## Methods








### addItem<span class="signature">()</span>
{:#methods:additem}








To add a tab item





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### addOverflowItem<span class="signature">()</span>
{:#methods:addoverflowitem}








To add tab item in more option





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### disableContent<span class="signature">()</span>
{:#methods:disablecontent}








To disable the tab item content





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### disableItem<span class="signature">()</span>
{:#methods:disableitem}








To disable the tab item





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### enableContent<span class="signature">()</span>
{:#methods:enablecontent}








To enable the tab item content





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### enableItem<span class="signature">()</span>
{:#methods:enableitem}








To enable the tab item





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### getActiveItem<span class="signature">()</span>
{:#methods:getactiveitem}








Get the current active item





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### getActiveItemText<span class="signature">()</span>
{:#methods:getactiveitemtext}








Get the current active item text





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### getItemsCount<span class="signature">()</span>
{:#methods:getitemscount}








To return the tab item count





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### getOverflowItemCount<span class="signature">()</span>
{:#methods:getoverflowitemcount}








Get the overflow tab item count





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### hideBadge<span class="signature">()</span>
{:#methods:hidebadge}








To hide a badge





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### removeItem<span class="signature">()</span>
{:#methods:removeitem}








To remove tab item





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### removeOverflowItem<span class="signature">()</span>
{:#methods:removeoverflowitem}








To remove tab item in overflow option





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### selectItem<span class="signature">()</span>
{:#methods:selectitem}








To make the tab item to be active





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### showBadge<span class="signature">()</span>
{:#methods:showbadge}








To show the tab's badge.





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>






### updateBadgeValue<span class="signature">()</span>
{:#methods:updatebadgevalue}








To update the badge value





Example
{:.example}

<pre class="prettyprint">
<code> 
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
</script></code>
</pre>




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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.item</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax element.</td>
</tr>
<tr>
<td class="name"><code>argument.content</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content.</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.error</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax error content.</td>
</tr>
<tr>
<td class="name"><code>argument.status</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">return the tab state</td>
</tr>
<tr>
<td class="name"><code>argument.item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name"><code>argument.index</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name"><code>argument.content</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name"><code>argument.index</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script>                        </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script></code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns the cancel option value</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.element</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab element</td>
</tr>
<tr>
<td class="name"><code>argument.id</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the id</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script>  </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.item</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the curent tab item</td>
</tr>
<tr>
<td class="name"><code>argument.content</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the ajax current content</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name"><code>argument.url</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item's url</td>
</tr>
<tr>
<td class="name"><code>argument.index</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current item index</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script>                        </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the text of the Tab</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script> </code>
</pre>
<pre class="prettyprint">
<code>             
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
</script> </code>
</pre>






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
<td class="name"><code>argument.cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>argument.model</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the Tab model</td>
</tr>
<tr>
<td class="name"><code>argument.type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>argument.text</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the text of the Tab</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code>             
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
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
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
</script> </code>
</pre>



