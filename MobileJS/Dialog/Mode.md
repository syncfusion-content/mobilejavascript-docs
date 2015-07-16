---
layout: post
title: Mode
description: mode
platform: Mobilejs
control: Dialog (Mobile)
documentation: ug
---

## Mode

The data-ej-mode attribute specifies the different types of dialog modes. The possible values are, 

1. Alert mode. 
2. Confirm mode.
3. Normal mode.
4. Full view mode.
### Alert Mode


The Alert Dialog mode is used to communicate an Alert message.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-mode="alert">

     <div>

        5% of battery remaining

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

{ ![](Mode_images/Mode_img1.png) | markdownify }
{:.image }


### Confirm Mode

The Confirm Dialog box attribute is mostly used to take the user's consent on any option. It displays a Dialog box with two buttons, Ok and Cancel. Ok button returns true and Cancel button returns false.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Cellular Data is Turned          

        off" data-ej-mode="confirm">

    <div>

       Turn on cellular data or use Wi-Fi to access data

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

{ ![](Mode_images/Mode_img2.png) | markdownify }
{:.image }


### Normal Mode

The Normal Mode Dialog box attribute is used to display the message in sub screen area on a whole screen. It displays a Dialog box with two buttons, Continue and Cancel. Continue button returns true and Cancel button returns false. It is suitable for tablet devices.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome"

        data-ej-mode="normal">

   <div>

         Syncfusion provides software components and tools for the Microsoft .NET 

         platform.

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

{ ![](Mode_images/Mode_img3.png) | markdownify }
{:.image }


### Full View Mode

The FullView Dialog box attribute is used to display messages on full screen and it is suitable for mobile devices.

{% highlight html %}



<div id="alertdlg" data-role="ejmdialog" data-ej-title="Welcome"

        data-ej-mode="fullview">

     <div>

       Syncfusion provides software components and tools for the Microsoft .NET 

       platform.

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

{ ![](Mode_images/Mode_img4.png) | markdownify }
{:.image }


