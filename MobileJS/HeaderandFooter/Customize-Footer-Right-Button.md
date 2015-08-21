---
layout: post
title: Customize-Footer-Right-Button
description: customize footer right button
platform: Mobilejs
control: Header and Footer (Mobile)
documentation: ug
---

# Customize Footer Right Button

## ShowRightButton

In Footer control, you can view the next page by using the ShowRightButton. You can manually enable/disable the button by setting true/false using data-ej-showrightbutton attribute.

{% highlight html %}



    <div id="footer_sample" data-role="ejmfooter" data-ej-showrightbutton=true ></div>  



{% endhighlight %}

The following screenshot displays the output.

{{ '![](Customize-Footer-Right-Button_images/Customize-Footer-Right-Button_img1.png)' | markdownify }}





## RightButtonCaption

To specify the caption (text) for Footer Right Button, set data-ej-rightbuttoncaption attribute. 

{% highlight html %}



<div id="footer_sample" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttoncaption="Next" ></div>



{% endhighlight %}

The following screenshot displays the output.

![](Customize-Footer-Right-Button_images/Customize-Footer-Right-Button_img2.png)





## RightButtonNavigationURL

Specifies the URL to which the page should be navigated when the Right Button is clicked.

{% highlight html %}



<div id="footer_sample" data-role="ejmfooter" data-ej-showrightbutton="true" data-ej-rightbuttonnavigationurl="" ></div>



{% endhighlight %}



