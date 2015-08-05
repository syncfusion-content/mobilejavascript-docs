---
layout: post
title: enabled
description: enabled
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Enabled

The **data-ej-enabled** is a **boolean** attribute that lets you enable or disable the options. When set to **false**, this prevents you from selecting that particular choice. By default, this attribute is set to **true**.

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
                    <input type="radio" name="radbtn" data-role="ejmradiobutton" data-ej-text="Single" />
                </td>

                <td width="100px">
                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Married" **data-ej-enabled="false"** />
                </td>

            </tr>
            <tr>
                <td width="100px">
                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Divorced" />
                </td>

                <td width="100px">
                    <input name="radbtn" type="radio" data-role="ejmradiobutton" data-ej-text="Widowed" />
                </td>
            </tr>
        </table>
        <div>
        </div>
    </div>


{% endhighlight %}



The following screenshot displays **enabled** option.

{% include image.html url="enabled_images/enabled_img1.png" Caption="RadioButton-Enabled"%}

