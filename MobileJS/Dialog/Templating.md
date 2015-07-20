---
layout: post
title: Templating
description: templating
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

## Templating

The data-ej-templateid attribute is used to define the ID of the template element where you can specify the content to render in the Dialog.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome to Syncfusion"

      data-ej-leftbuttoncaption="Cancel" data-ej-templateid="temp">

   <div>

       Syncfusion provides software components and tools for the Microsoft .NET 

       platform

   </div>

   <div id="temp">

       Syncfusion Software

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

{{ '![](Templating_images/Templating_img1.png)' | markdownify }}
{:.image }


