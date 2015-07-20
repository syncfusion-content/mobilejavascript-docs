---
layout: post
title: Persist
description: persist 
platform: Mobilejs
control: Grid (Mobile)
documentation: ug
---

## Persist 

This section explains you on how to maintain Grid state. Refer to the following code example.

{% highlight html %}


    <div id="MobileGrid">

    </div>





{% endhighlight %}



Refer to the following script section.

{% highlight js %}

            $(function () {// Document is ready. 

        var data =    
           ej.DataManager("http://mvc.syncfusion.com/Services/Northwnd.svc/Orders");

            $("#MobileGrid").ejmGrid({

                dataSource: data, 

                enablePersistence: true,

                columns: [

                         { field: "OrderID", headerText: "Order ID" },

                         { field: "CustomerID", headerText: "Customer ID" },

                         { field: "Freight", headerText: "Freight" }

                ]

            });

        });



{% endhighlight %}



Run the above code to render the following output.

{{ '![C:/Users/ARAVIND/AppData/Local/Microsoft/Windows/INetCache/Content.Word/26.png](Persist_images/Persist_img1.png)' | markdownify }}
{:.image }


