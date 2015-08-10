---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: TimePicker (Mobile)
documentation: ug
---

# Getting Started

The Essential Mobile JavaScript TimePicker provides support to display the TimePicker element within your web page and allows you to pick the time. The following section explains you on how to customize two TimePickers for a real time hotel reservation scenario.

The following screenshot illustrates the functionality of TimePicker.

![C:/Users/Bharathi/Desktop/Untitled.png](Getting-Started_images/Getting-Started_img1.png)

## Create the necessary layout

You can create Essential JavaScript Mobile TimePicker widget easily by using simple input element.

Create an HTML file and add the following code example to it.

{% highlight html %}

 <!DOCTYPE html>

<html>

<head>

<title> TimePicker </title>

<link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)"rel="stylesheet" />

<script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>                

<script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

<script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

<script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"> </script>

</head>

<body>

    <div data-role="appview">

        <!-- header control -->

        <div data-role="ejmheader" id="menuitems" data-ej-theme="light" data-ej-position="normal"

            data-ej-title="Hotel Reservation">

        </div>

        <div align="center" >

            <table>

            <tr>

                <td class="tdclass">Date</td>

                <td class="innerclass">

                    <span class="innerdp">

         <!-- create datepicker to select booking date -->

                        <input id="entryDate" data-role="ejmdatepicker" />

                    </span>

                </td>

             </tr>

             <tr>

                <td class="tdclass">In Time</td>

                <td class="innerclass">

                    <span class="innerdp">

        <!-- Add InTime Timepicker element here -->

                    </span>

                </td>

             </tr>

             <tr>

                <td class="tdclass">Out Time </td>

                <td class="innerclass">

                    <span class="innerdp">

        <!-- Add OutTime Timepicker element here -->

                    </span>

                </td>

             </tr>

        </table>

         <!-- button to confirm the reservation -->

        <input type="button" data-role="ejmbutton" data-ej-text="Book Now" data-ej-rendermode="auto" id="btnbook" data-ej-touchend="displayConfirmation"/>

         </div>

    </div>

</body>

</html>

{% endhighlight %}

Add the following styles to display the TimePicker’s input element.

{% highlight css %}

        .tdclass {

            width: 100px;       

                 }

                   td      {

            padding: 8px;       

                 }



        Table   {

            margin: 10px;

                }

        .innerclass {

            width: 300px;       

                 } 

{% endhighlight %}

Execute the above code to render the following output.

![C:/Users/Bharathi/Desktop/timepickerscreensecond.png](Getting-Started_images/Getting-Started_img2.png)

## Create TimePicker

To render the TimePicker control set data-role attribute to ejmtimepicker to the specific input element as follows.

{% highlight html %}

  <!-- InTime Timepicker element -->

         <input id="startTime" data-role="ejmtimepicker" />

  <!-- OutTime Timepicker element -->

         <input id="endTime" data-role="ejmtimepicker" />

{% endhighlight %}

Execute the above code example and focus on InTime or OutTime TimePicker element to render the following output.

![C:/Users/Bharathi/Desktop/Untitled.png](Getting-Started_images/Getting-Started_img3.png)

## Set the hour format

The TimePicker widget supports both 12 hour and 24 hour time format. The default value is 24 hour format. In this application, the booking table opens for all time throughout the day. Refer to the following code example to set 24 hour format by using the data-ej-hourformat attribute. 

{% highlight html %}

 <!-- InTime Timepicker element -->

         <input id="startTime" data-ej-hourformat="twentyfour" data-role="ejmtimepicker"/>

  <!-- OutTime Timepicker element -->

         <input id="endTime" data-ej-hourformat="twentyfour" data-role="ejmtimepicker"/>

{% endhighlight %}

Execute the above code example and focus on InTime or OutTime TimePicker element to render the following output.

![C:/Users/Bharathi/Desktop/Untitled.png](Getting-Started_images/Getting-Started_img4.png)

Refer to the following code example to display a conformation message on clicking the book button handled by the button touch end event.

{% highlight html %}

<div id="alertdlg" data-role="ejmdialog" data-ej-title="Booking Confirmation" data-ej-mode="alert" data-ej-leftbuttoncaption="OK" data-ej-enablemodal=true data-ej-enableautoopen=false data-ej-buttontap="alertClose">

            <div>Hotel reserved for specified time</div>

        </div>
		
{% endhighlight %}

Add the following code example

{% highlight js %}

            function alertClose() {

                $("#alertdlg").ejmDialog("close");    //to close dialog

            }

            function displayConfirmation(args) {

                App.activePage.find("#alertdlg").ejmDialog("open");  //to open dialog

            }

{% endhighlight %}

Execute the above code and click the Book Now button to render the conformation message as illustrated in the following screenshot.

![C:/Users/Bharathi/Desktop/timepickerscreen2.png](Getting-Started_images/Getting-Started_img5.png)