---
layout: post
title: Title
description: title
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

# Title

The data-ej-title attribute is used to set the title text of the Dialog box. 

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome to Syncfusion"

        data-ej-leftbuttoncaption="Cancel">

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

![](Title_images/Title_img1.png)



