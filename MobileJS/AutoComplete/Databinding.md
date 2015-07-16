---
layout: post
title: Databinding
description: databinding
platform: Mobilejs
control: AutoComplete (Mobile) 
documentation: ug
---

## Databinding

### Local Databinding

The data-ej-datasource attribute is used to provide the suggestion list to the AutoComplete. The list of items are passed as an array and by using the data-ej-datasource attribute, AutoComplete retrieves the suggestion list. The data-ej-fields-text attribute is used to map the specific field name of the given DataSource to render the suggestion list when user type is in the textbox. You can refer to the following code example. Here “window.datasrc” refers to JSON data.

{% highlight html %}

<input id="autocomplete_sample" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-fields-text="name" />



{% endhighlight %}



Add the Following script.

{% highlight js %}

        window.datasrc = [

{ 'name': 'Audi S6' },

{ 'name': 'BMW 7' },

{ 'name': 'Chevrolet Camaro' },

{ 'name': 'Duesenberg J' },

{ 'name': 'Elantra' }

];



{% endhighlight %}



The following screenshot displays the DataSource:

{ ![C:/Users/apoorvah.ramanathan/Desktop/1.png](Databinding_images/Databinding_img1.png) | markdownify }
{:.image }


### Remote Databinding

The data-ej-mapper attribute is used to specify the remote URL of the DataSource for the suggestion list. 

{% highlight html %}

<input id="autocomplete_sample" data-role="ejmautocomplete" data-ej-fields-text="ContactName" data-ej-mapper="http://mvc.syncfusion.com/Services/Northwnd.svc/Suppliers" />



{% endhighlight %}



The following screenshot displays remote data binding:

{ ![](Databinding_images/Databinding_img2.png) | markdownify }
{:.image }


