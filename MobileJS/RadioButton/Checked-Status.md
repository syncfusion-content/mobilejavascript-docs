---
layout: post
title: Checked-Status
description: checked status
platform: Mobilejs
control: RadioButton (Mobile)
documentation: ug
---

## Checked Status

You have options to set the state of the RadioButton either as checked or unchecked. When you select any one option, a dot mark appears inside the circle. This is called the checkedstate. RadioButtons selected earlier are unselected that is they are in unchecked state. The checked property is used to set the state of the RadioButton.

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

                        <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Single" data-ej-checked="true" />

                    </td>



                    <td>

                        <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Married" />

                    </td>



                </tr>

                <tr>

                    <td>

                        <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Divorced" />

                    </td>



                    <td>

                        <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Widowed" />

                    </td>



                </tr>

            </table>

            <div>

            </div>

        </div>





{% endhighlight %}

The following screenshot displays the checkedstatus:

{{ '![](Checked-Status_images/Checked-Status_img1.png)' | markdownify }}
{:.image }


