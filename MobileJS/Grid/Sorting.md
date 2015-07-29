---
layout: post
title: Sorting
description: sorting 
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

# Sorting 

## Default

Sorting is a basic technique in ejmGrid. It helps you in viewing grid records through ascending or descending based on particular column. If you want to enable sorting in Grid, use allowSorting attribute at Grid initialize. By default, sorting operation can perform through user interaction (UI) on Grid header.

{% highlight html %}


<div id="MobileGrid">

    </div>






{% endhighlight %}



{% highlight js %}

        $(function () {

            var data = ej.DataManager({

                url: "http://mvc.syncfusion.com/Services/Northwnd.svc/Orders/"

            });

            $("#MobileGrid").ejmGrid({

                dataSource: data,

                allowSorting: true,

                columns: [

                         { field: "OrderID", headerText: "Order ID" },

                         { field: "CustomerID", headerText: "Customer ID" },

                         { field: "ShipCity", headerText: "Ship City" }

                ]

            });

        });



{% endhighlight %}



Result of the above code example:

![16](Sorting_images/Sorting_img1.png)



### Multi Sorting

ejmGrid also has support to sort more than one column known as Multi sorting. To enable this behavior in Grid you can use allowMultiSorting in Mobile Grid. 

{% highlight html %}


<div id="MobileGrid">

    </div>





{% endhighlight %}



Refer to the following code example.

{% highlight js %}

        $(function () {

            var data = ej.DataManager({

                url: "http://mvc.syncfusion.com/Services/Northwnd.svc/Orders/"

            });

            $("#MobileGrid").ejmGrid({

                dataSource: data,

                allowSorting: true, 

                sortSettings:{allowMultiSorting:true},

                columns: [

                         { field: "OrderID", headerText: "Order ID" },

                         { field: "CustomerID", headerText: "Customer ID" },

                         { field: "ShipCity", headerText: "Ship City" }

                ]

            });

        });




{% endhighlight %}



Run the above code to render the following output.

![C:/Users/apoorvah.ramanathan/Desktop/1.png](Sorting_images/Sorting_img2.png)



