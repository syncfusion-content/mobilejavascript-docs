---
layout: post
title: ImageClass
description: imageclass
platform: Mobilejs
control: AutoComplete (Mobile) 
documentation: ug
---

# ImageClass

The data-ej-imageclass attribute is used to map the specific field name of the given DataSource to render the icons/images for each suggestion list. The mapped field should contain the CSS class names that define the icons/images for each suggestion list. You can customize the CSS class definitions for icons of each suggestion list based on the need.

{% highlight html %}

<input id="autocomplete_sample" data-role="ejmautocomplete" data-ej-datasource="window.datacont" data-ej-fields-text="country" data-ej-imageclass="flag" />



{% endhighlight %}



Add the following script

{% highlight js %}

        var datacont = [

{

"country": "Afghanistan",

"flag": "afghan"

},



{

"country": "Argentina",

"flag": "argen"

},

{

"country": "Australia",

"flag": "aust"

}];



{% endhighlight %}



Add the following style.

{% highlight css %}

        .afghan {

        background-image: url("../themes/sample/autocomplete/afghanistan.png");

        background-position: center center;

        background-size: 30px 30px;

        }

        .argen {

        background-image: url("../themes/sample/autocomplete/argentina.png");

        background-position: center center;

       background-size: 30px 30px;

        }

        .aust {

        background-image: url("../themes/sample/autocomplete/australia.png") ;

        background-position: center center;

        background-size: 30px 30px;

        }



{% endhighlight %}



The following screenshot displays ImageClass:

![C:/Users/apoorvah.ramanathan/Desktop/1.png](Image-customization_images/Image-customization_img2.png)


