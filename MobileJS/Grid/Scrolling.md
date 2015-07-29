---
layout: post
title: Scrolling
description: scrolling
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

# Scrolling

## Default

Scrolling is an important feature in Mobile Grid. It makes Grid more compatible with layout. You can enable scrolling in Grid by using allowScrolling attribute in grid at grid initializes. In this following example, scrolling properties is used to adjust grid width and height of grid. Use the following code to enable scrolling feature in Mobile Grid. 

{% highlight html %}


<div id="MobileGrid"></div>





{% endhighlight %}



Refer to the following script section.

{% highlight js %}

        $(function () { // Document is ready.

            $("#MobileGrid").ejmGrid({

                // The datasource "window.gridData" is referred from jsondata.min.js

                dataSource: window.gridData,

                allowScrolling: true,

                scrollSettings: { height: 352 },

                columns:

            [

                { field: "OrderID", headerText: "Order ID" },

                { field: "CustomerID", headerText: "Customer ID" },

                { field: "Freight", headerText: "Freight" }

            ]

            });

        });




{% endhighlight %}

Result of above code example.


![22](Scrolling_images/Scrolling_img1.png)



### Column Scrolling

Column scrolling is powerful technique in ejmGrid. It makes Grid more compatible with layout. It is very useful feature for Mobile Grid with more columns. By enabling “enableColumnScrolling” attribute you can achieve column scrolling. 

{% highlight html %}


<div id="MobileGrid"></div>





{% endhighlight %}



Refer to the following script section.

{% highlight js %}

        $(function () { // Document is ready.

            $("#MobileGrid").ejmGrid({

                // The datasource "window.gridData" is referred from jsondata.min.js

                dataSource: window.gridData,

                allowScrolling: true,

                scrollSettings: { enableColumnScrolling: true, height: 352 },

                columns:

            [



                         { field: "OrderID", headerText: "Order ID", width: 100 },

                         { field: "CustomerID", headerText: "Customer ID", width: 140 },

                         { field: "EmployeeID", headerText: "Employee ID", width: 140 },

                         { field: "Freight", headerText: "Freight", width: 100 }

            ]

            });

        });




{% endhighlight %}



Run the above code to render the following output.

![23](Scrolling_images/Scrolling_img2.png)



