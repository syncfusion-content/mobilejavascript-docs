---
layout: post
title: Customize threshold value | Scroll Panel | Mobilejs | Syncfusion
description: customize threshold value
platform: Mobilejs
control: Scroll Panel (Mobile)
documentation: ug
---

# Customize threshold value

The threshold value is used to initiate scrolling function, that is, the direction of scrolling based on the touch movement and at what distance (movement) the scrolling should be initiated. The “data-ej-directionlockthreshold” attribute specifies the threshold value where the x/y positions are to be controlled with the respect to z axis. By default, this property is set to 5.

{% highlight html %}

<div data-role="ejmheader" data-ej-title="ScrollPanel"></div>

<div id="maincontent" style="padding:10px">

	<div>

		<!--Scroll Content Here-->

		Founded by industry experts in 2001, Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform. With Syncfusion, developers can move beyond simply coding applications to delivering real business innovation—the elegant user interfaces, business intelligence dashboards, and sophisticated reporting that today's business users need, in the formats they demand. Our award-winning .NET components and controls are designed to meet your evolving development needs, whether you're working in Windows Forms, WPF, ASP.NET, ASP.NET MVC, or Silverlight. At Syncfusion, we uncompromisingly strive for excellence in order to offer the very best value to our customers—from small ISVs to Fortune 100 companies. Our most successful product is Essential Studio.

	</div>

</div>

<div id="sample_scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enablenativescrolling="false" data-ej-directionlockthreshold=90 />

{% endhighlight %}