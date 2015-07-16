---
layout: post
title: Overlay
description: overlay
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

## Overlay

The data-ej-enablemodal attribute enables the Modal Dialog that blocks you from interacting with the rest of the page until it is closed. The default value is false.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome to Syncfusion"

          data-ej-leftbuttoncaption="Cancel" data-ej-enablemodal="true">

       <div>

         Syncfusion provides software components and tools for the Microsoft .NET  

         platform

       </div>

</div>

<div style="text-align: center">

         <input data-role="ejmbutton" data-ej-text="Click here to open dialog"

         type="button" data-ej-touchend="openAlertDialog" />

</div>



{% endhighlight %}



Add the following script to the code

{% highlight js %}



function openAlertDialog(args)

        {

            App.activePage.find("#alertdlg").ejmDialog("open");

        }





{% endhighlight %}



The following screenshot displays the output.

{ ![](Overlay_images/Overlay_img1.png) | markdownify }
{:.image }


