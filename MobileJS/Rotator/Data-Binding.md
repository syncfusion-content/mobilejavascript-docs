---
layout: post
title: Data-Binding
description: data binding
platform: Mobilejs
control: Rotator (Mobile)
documentation: ug
---

# Data Binding

The Essential JavaScript Mobile Rotator provides support for data binding. Data binding provides a simple and consistent way for applications to present and interact with data. Elements can be bound to data from a variety of data sources.

Using data-ej-databinding attribute you can enable the databinding and data-ej-datasource is used to get the datasource that holds the Rotator items. Refer to the following code example.

{% highlight html %}

       <div id="page" data-role="appview">

        <!-- header control -->

        <div data-role="ejmheader" id="header" data-ej-title="Rotator">

        </div>   

        <div id="rotatordefault" data-role="ejmrotator" data-ej-    

                 targetid="rotatorcontentdefault" data-ej-datasource="window.imgdata"  

                  data-ej-databinding="true">

        </div>

    </div>

    <div id="rotatorcontentdefault">

        <div>

            <div class="photo {{:imageurl}}">

            </div>

        </div>

    </div>

    </div>


{% endhighlight %}


Refer the following code examples for script section.

{% highlight css %}





        window.imgdata = [

  {

      "imageurl": "photo1",

  },

  {

      "imageurl": "photo2",

  },

  {

      "imageurl": "photo3",

  },

  {

      "imageurl": "photo4",

  },

  {

      "imageurl": "photo5",

  }

        ];

{% endhighlight %}



![](Data-Binding_images/Data-Binding_img1.png)



