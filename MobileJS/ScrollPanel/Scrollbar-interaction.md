---
layout: post
title: Scrollbar-interaction
description: scrollbar interaction
platform: Mobilejs
control: Scroll Panel (Mobile)
documentation: ug
---

# Scrollbar interaction

Normally, the content is scrolled by dragging (touch move action) over the scrollable content. The content can also be scrolled through scrollbars by dragging it. It can be enabled by using “data-ej-enableinteraction” attribute. By default, this property is set to true. Refer to the following code example.

{% highlight html %}

    <div data-role="ejmheader" data-ej-title="ScrollPanel"></div>

    <div id="maincontent" style="padding:10px">

        <div>

            <!--Scroll Content Here-->

            Founded by industry experts in 2001, Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform. With Syncfusion, developers can move beyond simply coding applications to delivering real business innovation—the elegant user interfaces, business intelligence dashboards, and sophisticated reporting that today's business users need, in the formats they demand. Our award-winning .NET components and controls are designed to meet your evolving development needs, whether you're working in Windows Forms, WPF, ASP.NET, ASP.NET MVC, or Silverlight. At Syncfusion, we uncompromisingly strive for excellence in order to offer the very best value to our customers—from small ISVs to Fortune 100 companies. Our most successful product is Essential Studio.

        </div>

    </div>

    <div id="sample_scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-enableinteraction=true data-ej-enablenativescrolling="false" />	

{% endhighlight %}



