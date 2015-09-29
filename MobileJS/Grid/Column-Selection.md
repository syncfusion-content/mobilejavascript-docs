---
layout: post
title: Column Selection | Grid | Mobilejs | Syncfusion
description: column selection
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

# Column Selection

By enabling “allowColumnSelector”, you can hide the columns dynamically whenever needed. This feature is mostly useful when the available device width is not enough to display all the necessary columns. 

{% highlight html %}

<div id="MobileGrid"> </div>

{% endhighlight %}

Refer to the following script section.

{% highlight js %}

$(function () {

	var data = ej.DataManager({

		url: "http://mvc.syncfusion.com/Services/Northwnd.svc/Orders/"

	});

	$("#MobileGrid").ejmGrid({

		allowColumnSelector: true,

		dataSource: data,

		allowPaging: true,

		columns: [

				 { field: "OrderID", headerText: "Order ID" },

				 { field: "CustomerID", headerText: "Customer ID" },

				 { field: "ShipCity", headerText: "Ship City" }

		]

	});

});

{% endhighlight %}

Run the above code to render the following output.

![](Columns_images/Columns_img4.png)

![](Columns_images/Columns_img5.png)

![](Columns_images/Columns_img6.png)