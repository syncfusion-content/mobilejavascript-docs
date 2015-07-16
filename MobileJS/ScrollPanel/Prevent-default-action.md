---
layout: post
title: Prevent-default-action
description: prevent default action
platform: Mobilejs
control: Scroll Panel (Mobile)
documentation: ug
---

## Prevent default action

The default action of mouse while dragging over the page is text selection. While using ScrollPanel, you can prevent the default action by using “data-ej-preventdefault” attribute.  By default, this property is set to true.

{% highlight html %}



    <div data-role="ejmheader" data-ej-title="ScrollPanel"></div>

    <div id="maincontent" style="padding:10px">

        <div>

            Founded by industry experts in 2001, Syncfusion, Inc. provides the broadest range of enterprise-class software components and tools for the Microsoft .NET platform. With Syncfusion, developers can move beyond simply coding applications to delivering real business innovation—the elegant user interfaces, business intelligence dashboards, and sophisticated reporting that today's business users need, in the formats they demand. Our award-winning .NET components and controls are designed to meet your evolving development needs, whether you're working in Windows Forms, WPF, ASP.NET, ASP.NET MVC, or Silverlight. At Syncfusion, we uncompromisingly strive for excellence in order to offer the very best value to our customers—from small ISVs to Fortune 100 companies. Our most successful product is Essential Studio.

        </div>

    </div>



    <div id="sample_scrollpanel" data-role="ejmscrollpanel" data-ej-target="maincontent" data-ej-preventdefault="true" data-ej-enablenativescrolling="false" />



{% endhighlight %}



