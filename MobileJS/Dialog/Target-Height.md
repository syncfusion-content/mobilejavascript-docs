---
layout: post
title: Target-Height
description: target height
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

# Target Height

 The data-ej-targetheight attribute specifies the target height of the Dialog.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome to Syncfusion"

         data-ej-leftbuttoncaption="Cancel" data-ej-targetheight="500">

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

![](Target-Height_images/Target-Height_img1.png)



