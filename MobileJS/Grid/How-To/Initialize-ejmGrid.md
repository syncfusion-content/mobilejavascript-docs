---
layout: post
title: Initialize-ejmGrid
description: initialize ejmgrid
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

### Initialize ejmGrid

In this section, you can learn the Mobile Grid’s mandatory attribute to render a simple Grid. To initialize Grid, it needs two important properties. They are columns and its inner attribute field. Columns are used to define schema of grid and field is mapping name to data source.

{% highlight js %}

$("#MobileGrid").ejmGrid({

     columns: [

        { field: "OrderID" },

        { field: "CustomerID" },

        { field: "EmployeeID" }

     ]

});





{% endhighlight %}

Run the above code to render the following output.

{{ '![1](Initialize-ejmGrid_images/Initialize-ejmGrid_img1.png)' | markdownify }}



