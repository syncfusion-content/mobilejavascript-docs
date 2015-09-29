---
layout: post
title: Monitor DOM Changes | Scroll Panel | Mobilejs | Syncfusion
description: monitor dom changes
platform: Mobilejs
control: Scroll Panel (Mobile)
documentation: ug
---

# Monitor DOM Changes

The “data-ej-checkdomchanges” attribute lets you specify whether or not to refresh the Scrollpanel automatically when elements are added to the DOM tree dynamically. By default, this property is set to false. 

{% highlight html %}

<div data-role="ejmheader" data-ej-title="ScrollPanel"></div>

<div id="maincontent" style="padding:10px">

	<div id="content">

		Founded by industry experts in 2001, Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform. With Syncfusion, developers can move beyond simply coding applications to delivering real business innovation—the elegant user interfaces, business intelligence dashboards, and sophisticated reporting that today's business users need, in the formats they demand. Our award-winning .NET components and controls are designed to meet your evolving development needs, whether you're working in Windows Forms, WPF, ASP.NET, ASP.NET MVC, or Silverlight. At Syncfusion, we uncompromisingly strive for excellence in order to offer the very best value to our customers—from small ISVs to Fortune 100 companies. Our most successful product is Essential Studio.<br />

		<input type="button" data-role="ejmbutton" data-ej-touchstart="touchstart" data-ej-text="click me" /><br />

	</div>

</div>

<div id="sample_scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablenativescrolling="false" data-ej-checkdomchanges="true" />

{% endhighlight %}

Refer the following code examples for script section

{% highlight js %}

function touchstart() {

	$("#content").append("Dynamically added content<br/>");

}

{% endhighlight %}