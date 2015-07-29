---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: RadioButton (Mobile)
documentation: ug
---

# Getting Started

The following guidelines show you how to use the RadioButton to select the answers in the application and get the selected items. The following screenshot displays a sample Quiz application.

![](Getting-Started_images/Getting-Started_img1.png)



## Create the necessary layout

Create an HTML file and paste the following template to the HTML file for the RadioButton creation.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

    <meta name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

    <title>RadioButton</title>

    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>



    <script src="http://js.syncfusion.com/UG/Mobile/Content/contacts.min.js"></script>

</head>



<body>

    <div align="center">

        <!-- Header control here-->

        <div id="Div1" data-role="ejmheader" data-ej-title="Quiz Application" data-ej-position="normal"></div>

        <div id="Div2">

            <div>



                <!--RadioButton content here-->

            </div>

        </div>



<!-- ScrollPanel control here-->

    <div id="Div3" data-role="ejmscrollpanel" data-ej-target="scroller"></div>

   </div>



</body>

</html>



{% endhighlight %}



## Create RadioButton

To render the RadioButton control, set data-role attribute to ejmradiobutton to an input element and type attribute as radio.

Add the following code example to render the RadioButton in the quiz application.

{% highlight html %}

<!--RadioButton content-->



<table border="0" cellpadding="5">

    <tr>

        <td>1. What is the Expansion for MVC?

        </td>

     </tr>

      <tr>

         <td class="align">

              <input id="Radio1" name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Model View Controller" />

          </td>

       </tr>

        <tr>

            <td class="align">

                 <input id="Radio2" name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Model Virtual Container" />

             </td>

         </tr>

          <tr>

             <td class="align">

                  <input id="Radio3" name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Model Visual Controller" />

             </td>

          </tr>

            <tr>

               <td>2. What is the Expansion for USB?

                </td>

            </tr>

             <tr>

                 <td class="align">

                      <input id="Radio4" name="USB" type="radio" data-role="ejmradiobutton" data-ej-text="Universal serialized Buffer" />

                  </td>

             </tr>

              <tr>

                 <td class="align">

                       <input id="Radio5" name="USB" type="radio" data-role="ejmradiobutton" data-ej-text="Universal Serial Buffer" />

                      </td>

                  </tr>

                   <tr>

                       <td class="align">

                           <input id="Radio6" name="USB" type="radio" data-role="ejmradiobutton" data-ej-text="Universal Serial Bus" />

                        </td>

                    </tr>

                </table>



{% endhighlight %}



Now, add the following style to align the RadioButton and contents properly in the quiz application

{% highlight css %}



        td {

            padding: 5px;

        }



            td.align {

                padding-left: 20px;

            }





{% endhighlight %}



The following screenshot is the output for the above code examples.

![](Getting-Started_images/Getting-Started_img2.png)



