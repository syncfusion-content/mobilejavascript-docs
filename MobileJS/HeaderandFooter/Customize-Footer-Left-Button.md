---
layout: post
title: Customize-Footer-Left-Button
description: customize footer left button
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

## Customize Footer Left Button

### ShowLeftButton

In Footer control, you can view the previous page by using the data-ej-showleftbutton. You can manually enable/disable the button by setting the true/false using data-ej-showleftbutton attribute.

{% highlight html %}

<div id="footer_sample" data-role="ejmfooter" data-ej-showleftbutton=true ></div>



{% endhighlight %}

The following screenshot displays the output.

{{ '![](Customize-Footer-Left-Button_images/Customize-Footer-Left-Button_img1.png)' | markdownify }}
{:.image }




### LeftButtonCaption

To specify the caption (text) for Footer left button, set data-ej-leftbuttoncaption attribute. 

{% highlight html %}



<div id="footer_sample" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttoncaption="Home" ></div>    



{% endhighlight %}



The following screenshot displays the output.

{{ '![](Customize-Footer-Left-Button_images/Customize-Footer-Left-Button_img2.png)' | markdownify }}
{:.image }




### LeftButtonNavigationURL

Specifies the navigation URL to go to the page when the Left Button is clicked. 

{% highlight html %}



<div id="footer_sample" data-role="ejmfooter" data-ej-showleftbutton="true" data-ej-leftbuttonnavigationurl="" ></div>      



{% endhighlight %}



