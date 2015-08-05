---
layout: post
title: enabled-
description: enabled 
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Enabled 

The **data-ej-enabled** attribute enables you to **disable** or **enable** the control. By default, this attribute is set to **true**.

Refer to the following code example.

{% highlight html %}


    <div data-role="ejmheader" data-ej-title="CheckBox"></div>
    <div align="center" style="padding-top:100px">
        <div>
            <b> Favorite Mobile</b>
        </div>
        <br />
        <table border="0" cellpadding="6">
            <tr>
                <td width="100px">
                    <input id="apple" name="chkbox" data-role="ejmcheckbox" data-ej-text="Apple" **data-ej-enabled="false"**/>
                </td>

                <td width="100px">
                    <input id="android" name="chkbox" data-role="ejmcheckbox" data-ej-text="Android" **data-ej-enabled="false"** />
                </td>
            </tr>
            <tr>
                <td width="100px">
                    <input id="windows" name="chkbox" data-role="ejmcheckbox" data-ej-text="Windows" />
                </td>

                <td width="100px">
                    <input id="Bberry" name="chkbox" data-role="ejmcheckbox" data-ej-text="BlackBerry" />
                </td>
            </tr>
        </table>
    </div>



{% endhighlight %}



Execute the above code examples to render the following output.

{% include image.html url="//Mobilejs//JSFormControls(Mobile)//concepts-and-features-of-checkbox//enabled-_images//enabled-_img1.png" Caption="CheckBox with Enable and Disable state"%}

