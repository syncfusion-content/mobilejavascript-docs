---
layout: post
title: Button-Customization
description: button customization
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

## Button Customization

### LeftButtonCaption

The data-ej-leftbuttoncaption attribute is used to specify the text of the Left Button. The default value is cancel.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Cellular Data is Turned  off"

          data-ej-mode="confirm" data-ej-leftbuttoncaption="Ok" data-ej-enableautoopen="true">

      <div>

       Turn on cellular data or use Wi-Fi to access data

     </div>

</div>



{% endhighlight %}



The following screenshot displays the output.

{ ![](Button-Customization_images/Button-Customization_img1.png) | markdownify }
{:.image }


### RightButtonCaption

The data-ej-rightbuttoncaption attribute specifies the text of the Right Button. The default value is continue.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Cellular Data is Turned  off"

          data-ej-mode="confirm" data-ej-rightbuttoncaption="Continue" data-ej-enableautoopen="true">

      <div>

       Turn on cellular data or use Wi-Fi to access data

     </div>

</div>



{% endhighlight %}



The following screenshot displays the output.

{ ![](Button-Customization_images/Button-Customization_img2.png) | markdownify }
{:.image }


### ShowButtons

The data-ej-showbuttons attribute is used to show the buttons in the Dialog box. The default value is true.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome to Syncfusion"

          data-ej-mode="confirm" data-ej-rightbuttoncaption="Continue" data-ej-enableautoopen="true" data-ej-showbuttons="false">

      <div>

        Syncfusion provides software components and tools for the Microsoft .NET  

         platform



     </div>

</div>



{% endhighlight %}



The following screenshot displays the output.

{ ![](Button-Customization_images/Button-Customization_img3.png) | markdownify }
{:.image }


