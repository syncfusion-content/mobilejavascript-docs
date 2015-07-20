---
layout: post
title: Customize-Label
description: customize label
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Customize Label

The data-ej-text attribute lets you set labels for the RadioButton. To set the text for the RadioButton, you can refer the following code example.

{% highlight html %}



    <div align="center">

        <br />

        <div>

            <div>

                <b>Marital Status</b>

            </div>

        </div>

        <br />

        <table border="0" cellpadding="5">

            <tr>

                <td width="100px">

                    <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Single"/>

                </td>

                <td>

                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Married" />

                </td>



            </tr>

            <tr>

                <td>

                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Divorced" />

                </td>



                <td>

                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Widowed" />

                </td>



            </tr>

        </table>

        <div>

        </div>

    </div>





{% endhighlight %}



The following screenshot displays customized labels.

{{ '![C:/Users/deepal/AppData/Local/Temp/SNAGHTML201e992b.PNG](Customize-Label_images/Customize-Label_img1.png)' | markdownify }}
{:.image }


