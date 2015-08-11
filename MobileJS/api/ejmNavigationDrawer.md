---
layout: post
title: ejmNavigationDrawer
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Navigation Drawer control.





$(element).ejmNavigationDrawer<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code> 
//create Navigation Drawer in Unobtrusive way
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-type="overlay" data-ej-position="fixed">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
//create Navigation Drawer in Obtrusive way
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer();    
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

* module:ej.mobile.listview

* module:ej.mobile.scrollpanel

* module:ej.mobile.menu

* module:ej.navigationdrawerbase


## Members




### allowScrolling<span class="type-signature type boolean">boolean</span>
{:#members:allowscrolling}




While set as true, enables scrollpanel inside the element.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the allowscrolling property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-allowscrolling="true">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Navigation Drawer Scrolling on initialization. 
//To set scrolling API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("allowScrolling","true");     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the Navigation Drawer allowscrolling, after initialization:
$(function () {
// Gets the allowscrolling API value.           
$("#navpane").ejmNavigationDrawer("option", "allowScrolling");  
// Sets the allowscrolling API  
$("#navpane").ejmNavigationDrawer ("option", "allowScrolling", false);  
});
</script>  </code>
</pre>



### considerSubPage<span class="type-signature type boolean">boolean</span>
{:#members:considersubpage}




When set as true, the control will render inside the closest subpage.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the allowscrolling property in unobtrusive way.
//Set the allowscrolling property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-considersubpage="true">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer considersubpage on initialization. 
//To set scrolling API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("considerSubPage","true");    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the Navigation Drawer allowscrolling, after initialization:
$(function () {
// Gets the Considersubpage API value.          
$("#navpane").ejmNavigationDrawer("option", "considerSubPage"); 
// Sets the Considersubpage API 
$("#navpane").ejmNavigationDrawer ("option", "considerSubPage", false);  
});
</script>  </code>
</pre>



### contentId<span class="type-signature type string">string</span>
{:#members:contentid}




Specifies the contentId for navigation drawer, where the ajax content need to updated


Default Value:
{:.param}



* null




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the contentId property in unobtrusive way.
<div id="container"> </div>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-contentid="container" >
<ul>
                <li data-ej-text="Artwork"></li>
                <li data-ej-text="Abstract"></li>
                <li data-ej-text="2 Acrylic Mediums"></li>
                <li data-ej-text="Creative Acrylic"></li>
                <li data-ej-text="Modern Painting"></li>
</ul>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer contentId on initialization. 
//To set contentId API value 
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-contentid="container" >
<ul>
                <li data-ej-text="Artwork"></li>
                <li data-ej-text="Abstract"></li>
                <li data-ej-text="2 Acrylic Mediums"></li>
                <li data-ej-text="Creative Acrylic"></li>
                <li data-ej-text="Modern Painting"></li>
</ul>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("contentId","container");     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer contentId, after initialization:
<script>
// Gets the contentId API value.                
 $("#navpane").ejmNavigationDrawer ("option", "contentId");             
// Sets the contentId API
$("#navpane").ejmNavigationDrawer ("option", "contentId", "container");   
</script></code>
</pre>



### cssclass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for NavigationDrawer theme. This cssClass API helps to use custom skinning option for NavigationDrawer control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the direction property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
< input id="target" data-role="button" type="button" />
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-cssclass="customclass" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer direction on initialization. 
//To set direction API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
< input id="target" data-role="button" type="button" />
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("cssClass","customclass");    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer cssClass, after initialization:
<script>
// Gets the cssClass API value.         
 $("#navpane").ejmNavigationDrawer ("option", "cssClass");              
// Sets the cssClass API
$("#navpane").ejmNavigationDrawer ("option", "cssClass", "customclass");   
</script></code>
</pre>



### direction<span class="type-signature type enum">enum</span>
{:#members:direction}




Sets the Direction for the control. See Direction


Default Value:
{:.param}



* left




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the direction property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-direction="left" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer direction on initialization. 
//To set direction API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("direction","left");  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<script>
//Get or set the Navigation Drawer direction, after initialization:
$(function () {
// Gets the direction API value.                
$("#navpane").ejNavigationDrawer("option", "direction");        
// Sets the direction API       
$("#navpane").ejNavigationDrawer ("option", "direction", "left");  
});
</script>  </code>
</pre>



### enablelistview<span class="type-signature type boolean">boolean</span>
{:#members:enablelistview}




Sets the listview to be enabled or not


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the listview property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-enablelistview="false" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer listview on initialization. 
//To set listview API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("enableListView","false");    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer listview, after initialization:
<script>
// Gets the listview API value.         
 $("#navpane").ejmNavigationDrawer ("option", "enableListView");                
// Sets the listview API
$("#navpane").ejmNavigationDrawer ("option", "enableListView", false);   
</script></code>
</pre>



### items<span class="type-signature type array">array</span>
{:#members:items}




Specifies the listview items as an array of object.


Default Value:
{:.param}



* []




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the listView items property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-items=window.lvItems >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer listview items on initialization. 
//To set listview items API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer({enableListview:true,items:[{text:"Item1"},{text:"Item2"},{text:"Item3"}]});  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer listview item, after initialization:
<script>
// Gets the listview item API value.            
 $("#navpane").ejmNavigationDrawer ("option", "items"); 
// Sets the listview item API
$("#navpane").ejmNavigationDrawer ("option", "items", [{text:"Item1"},{text:"Item2"},{text:"Item3"}]);   
</script></code>
</pre>



### listviewsettings<span class="type-signature type object">object</span>
{:#members:listviewsettings}




Sets all the properties of listview to render in navigation drawer



Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the listView Settings property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-listviewsettings-width="200" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer listview settings on initialization. 
//To set listview settings API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer({model.listViewSettings{width:200});  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer listViewSettings, after initialization:
<script>
// Gets the listViewSettings API value.         
 $("#navpane").ejmNavigationDrawer ("option", "listViewSettings.width");        
// Sets the listViewSettings API
$("#navpane").ejmNavigationDrawer ("option", "listViewSettings.width", "200");   
</script></code>
</pre>



### position<span class="type-signature type enum">enum</span>
{:#members:position}




Specifies position whether it is in fixed or relative to the page. See <a href="global.html#Position">Position</a>


Default Value:
{:.param}



* normal




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the position property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-position="fixed" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer position on initialization. 
//To set position API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("position","fixed");  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer position, after initialization:
<script>
// Gets the position API value.         
 $("#navpane").ejmNavigationDrawer ("option", "position");              
// Sets the position API
$("#navpane").ejmNavigationDrawer ("option", "position", "fixed");   
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
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-rendermode="auto">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Navigation Drawer renderMode on initialization. 
//To set renderMode API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("renderMode","auto"); 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer renderMode, after initialization:
<script>
// Gets the renderMode API value.               
 $("#navpane").ejmNavigationDrawer ("option", "renderMode");                    
// Sets the renderMode API
$("#navpane").ejmNavigationDrawer ("option", "renderMode", ej.mobile.RenderMode.Auto);   
</script></code>
</pre>



### scrollSettings
{:#members:scrollsettings}




Used to set scrollpanel related properties to the navigation drawer






### targetid<span class="type-signature type string">string</span>
{:#members:targetid}




Specifies the targetId for navigation drawer


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the direction property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
< input id="target" data-role="button" type="button" />
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-targetid="target" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer direction on initialization. 
//To set direction API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
< input id="target" data-role="button" type="button" />
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("targetId","left");   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer targetId, after initialization:
<script>
// Gets the TargetId API value.         
 $("#navpane").ejmNavigationDrawer ("option", "targetId");              
// Sets the TargetId API
$("#navpane").ejmNavigationDrawer ("option", "targetId", "sample");   
</script></code>
</pre>



### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Changes the Theme of the control


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the Theme property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-theme="auto">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code> 
// Set Navigation Drawer renderMode on initialization. 
//To set Theme API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane">
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("theme","auto");      
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer Theme, after initialization:
<script>
// Gets the Theme API value.            
 $("#navpane").ejmNavigationDrawer ("option", "theme");                 
// Sets the Theme API
$("#navpane").ejmNavigationDrawer ("option", "theme", ej.mobile.Theme.Auto);   
</script></code>
</pre>



### type<span class="type-signature type enum">enum</span>
{:#members:type}




Sets the rendering type of the control. See <a href="global.html#Type">Type</a>


Default Value:
{:.param}



* overlay




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the type property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-type="overlay" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer type on initialization. 
//To set type API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("type","overlay");    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer type, after initialization:
<script>
// Gets the type API value.             
 $("#navpane").ejmNavigationDrawer ("option", "type");          
// Sets the type API
$("#navpane").ejmNavigationDrawer ("option", "type", "overlay");   
</script></code>
</pre>



### width<span class="type-signature type int">int</span>
{:#members:width}




Specifies the width of the control


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
//Set the width property in unobtrusive way.
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-width="200" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div></code>
</pre>
<pre class="prettyprint">
<code>// Set Navigation Drawer width on initialization. 
//To set width API value 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$(function () {
$("#navpane").ejmNavigationDrawer("width","200");       
});</code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Navigation Drawer width, after initialization:
<script>
// Gets the type API value.             
 $("#navpane").ejmNavigationDrawer ("option", "width");         
// Sets the type API
$("#navpane").ejmNavigationDrawer ("option", "width", "auto");   
</script></code>
</pre>


## Methods




### close<span class="signature">()</span>
{:#methods:close}




To close the navigation drawer control



Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
$(function()
{ 
var lsm = $("#navpane").data("ejmNavigationDrawer");
lsm.close();
});
</script ></code>
</pre>



### open<span class="signature">()</span>
{:#methods:open}




To open the navigation drawer control



Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
$(function()
{ 
var lsm = $("#navpane").data("ejmNavigationDrawer");
lsm.open();
});
</script ></code>
</pre>



### toggle<span class="signature">()</span>
{:#methods:toggle}




To Toggle the navigation drawer control



Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
$(function()
{ 
var lsm = $("#navpane").data("ejmNavigationDrawer");
lsm.toggle();
});
</script ></code>
</pre>


## Events




### beforeclose
{:#events:beforeclose}




Event triggers before the control gets closed.

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
<td class="description last">Event parameters from Navigation Drawer
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
<td class="description last">returns the Navigation Drawer model</td>
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
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-beforeclose="onBeforeClose" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
function onBeforeClose(args)
{ //handle the event
}
</script ></code>
</pre>
<pre class="prettyprint">
<code> 
//BeforeClose event for Navigation pane
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$("#navpane").ejmNavigationDrawer({
  beforeClose: function (args) { //handle the event
}
});   
$("#navpane").ejNavigationDrawer();   
</script></code>
</pre>



### open
{:#events:open}




Event triggers when the control open.

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
<td class="description last">Event parameters from Navigation Drawer
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
<td class="description last">returns the Navigation Drawer model</td>
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
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-open="onOpen" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
function onOpen(args)
{ //handle the event
}
</script ></code>
</pre>
<pre class="prettyprint">
<code> 
//Open event for Navigation pane
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$("#navpane").ejNavigationDrawer({
  open: function (args) { //handle the event
}
});   
$("#navpane").ejNavigationDrawer("open");
</script></code>
</pre>



### swipe
{:#events:swipe}




Event triggers when the Swipe happens.

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
<td class="description last">Event parameters from Navigation Drawer
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
<td class="description last">returns the Navigation Drawer model</td>
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
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div data-role="ejmnavigationdrawer" id="navpane" data-ej-swipe="onSwipe" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script >
function onSwipe(args)
{ //handle the event
}
</script ></code>
</pre>
<pre class="prettyprint">
<code> 
//Swipe event for Navigation pane
<div id="home" class="navsubpage">
<div align="center" class="content">
<h2 class="title">
Home</h2>
<p>
Founded by industry experts in 2001,Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform.
</p>
</div>
</div>
<style>
.list {
  border-bottom: 1px solid;
  line-height: 50px;
  text-align: center;
  width:200px;
  }
</style>
<div id="navpane" >
<div class="list"> Home </div>
<div class="list"> Communities </div>
</div>
<script>
$("#navpane").ejmNavigationDrawer({
  swipe: function (args) { //handle the event
}
});   
</script></code>
</pre>


