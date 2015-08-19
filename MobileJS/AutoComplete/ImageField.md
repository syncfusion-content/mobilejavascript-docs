---
layout: post
title: ImageField
description: imagefield
platform: Mobilejs
control: AutoComplete (Mobile) 
documentation: ug
---

# ImageField

The data-ej-imagefield attribute is used to map the specific field name of the given DataSource to render the icons/images for each suggestion list. The mapped field should contain the icon/image URL for each suggestion list.

{% highlight html %}

<input id="autocomplete_sample" data-role="ejmautocomplete" data-ej-datasource="window.datacont" data-ej-fields-text="country" data-ej-imagefield="flag" />



{% endhighlight %}



Add the following script.

{% highlight js %}

        var datacont = [

{

"country": "Afghanistan",

"flag": "../themes/sample/autocomplete/afghanistan.png"

},

{

"country": "Argentina",

"flag": "../themes/sample/autocomplete/argentina.png"

},

{

"country": "Australia",

"flag": "../themes/sample/autocomplete/Australia.png"

}

];



{% endhighlight %}



The following screenshot displays the ImageField:

![](Image-customization_images/Image-customization_img1.png)