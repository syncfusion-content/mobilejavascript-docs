---
layout: post
title: Getting-Started
description: getting started
platform: Mobilejs
control: MaskEdit (Mobile)
documentation: ug
---

# Getting Started

Essential JavaScript Mobile MaskEdit control allows you to enter input with standard format. From the following guidelines, you can learn how to create a MaskEdit control for adding a contact.

{ ![C:/Users/Vignesh Kumar/Desktop/screen.png](Getting-Started_images/Getting-Started_img1.png) | markdownify }
{:.image }


Create the layout

Create an HTML file and add the following template to it.

{% highlight html %}

<!DOCTYPE html>

<html>

<head>

    <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" />

    <title>Mask Edit</title>

    <link href="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css)" rel="stylesheet" />

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js)"></script>

    <script src="[http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)"></script>

</head>

<body>

    <!--Header Control-->

    <div id="header" data-role="ejmheader" data-ej-title="Contact" data-ej-position="normal"></div>

    <div class="sample" style="padding:10px">

        <div class="frame">

            <div class="control">

                <table class="editors">

                    <tbody>

                        <tr>

                            <td>

                                <label>

                                    Name

                                </label>

                            </td>

                            <td>

                                <!--Textbox control-->

                                <input id="textbox_sample" data-role="ejmtextbox" data-ej-watermarktext="Name" />

                            </td>

                        </tr>

                        <tr>

                            <td>

                                <label>

                                    Phone No

                                </label>

                            </td>

                            <td>

                                <!--Add MaskEdit Control-->                                

                            </td>

                        </tr>

                    </tbody>

                </table>

                <center>

                    <div class="button">

                        <!--Button Control-->

                        <input type="button" data-role="ejmbutton" data-ej-text="Save" />

                    </div>

                </center>

            </div>

        </div>

    </div>

</body>

</html>





{% endhighlight %}



Add MaskEdit Control

{% highlight html %}

<input id="maskedit_sample" data-role="ejmmaskedit" data-ej-watermarktext="Maskedit" data-ej-mask="+1 (999) 999-9999" />



{% endhighlight %}



Run the code and get the following output.

{ ![C:/Users/Vignesh Kumar/Desktop/screen.png](Getting-Started_images/Getting-Started_img2.png) | markdownify }
{:.image }


