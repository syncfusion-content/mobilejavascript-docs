---
layout: post
title: getting-started
description: getting started
platform: Mobilejs
control: Form Controls
documentation: ug
---

# Getting Started

In this section you can learn how to create Form Controls in mobile app.

## Create your first Form in JavaScript

The **Essential JavaScript** provides a way to create a **Form** with the following EJ mobile widgets.

1. Textbox 

2. Numeric Textbox

3. Radiobutton 

4. Checkbox 

5. Button

In the following guidelines, you are creating a Bill Payment App through that you can learn about the features in the above mentioned widgets.

{% include image.html url="getting-started_images/getting-started_img1.png" Caption="Bill Payment App"%}{% include image.html url="getting-started_images/getting-started_img2.png" Caption="Bill Payment App"%}

### Create the necessary layout 

In the Bill Payment App, you can use the **Textbox** control to get the Name of the Person, Email, and Remarks, **Numeric Textbox** control for Amount field, **Radio button** for Payment options, **Checkbox** for the terms and conditions, and **Button** control to submit the **Form**.

1. Create an **HTML** file and paste the following template to it to create a Form.

{% highlight html %}

<!DOCTYPE html>
<html>
<head>
<title>Form Elements</title>
<link href="http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css" rel="stylesheet" />
<scriptsrc="[http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js)"></script>
<scriptsrc="[http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js)"></script>
<script src="http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js"></script>
</head>
<body>
<div id="page" data-role="appview">
        <div id="header" data-ej-title="Bill Payment" data-role="ejmheader"></div>
        <div id="form_sample" class="sample">
            <div>
                <!--Add Form Element Here-->
                <form id="form1">
                    <br />
                    <label>
                        Name of the Person:
                    </label>
                    <div>
                        <!--Add user name Text box Here-->

                    </div>
                    <br />
                    <label>
                        Amount:
                    </label>
                    <div>
                        <!--Add numeric text box for amount here-->

                    </div>
                    <br />
                    <div>
                        <label>
                            Payment Option:
                        </label>
                    </div>
                    <div>
                        <table class="radio">
                            <tr>
                                <td>
                                    <!--radio button for credit -->
                                </td>
                                <td>
                                    <!--radio button for debit-->

                                </td>
                            </tr>
                        </table>
                    </div>
                    <br />
                    <div>
                        <label>
                            Email:
                        </label>
                        <div>
                            <!--Add email text box here-->
                        </div>
                        <br />
                    </div>
                    <div>
                        <label>
                            Remarks (Optional):
                        </label>
                        <div>
                            <!--Add remark text box here-->
                        </div>
                        <br />
                    </div>
                    <div>
                        <table class="check">
                            <tr>
                                <td>
                                    <!--Add check box here-->

                                </td>
                            </tr>
                        </table>
                    </div>
                    <br />
                    <div align="center" class="submitbutton">
                        <!--Add submit button here-->

                    </div>
                </form>
            </div>
        </div>
                <!--Add dialog control here-->
        <div id="info_msg" data-role="ejmdialog" data-ej-title="Alert"
             data-ej-leftbuttoncaption="Ok" data-ej-buttontap="exit"
             data-ej-enablemodal="true">
            <div id="dlgcontent"></div>
        </div>
<div id="ScrollPanel" data-role="ejmscrollpanel" data-ej-target="form_sample"></div>
 </body>
</html>


{% endhighlight %}



2. Add the following styles.

{% highlight css %}

   <style>
        .appview .submitbutton {
            text-align: center;
        }

        .appview .chksample {
            display: inline-block;
        }

        .appview #form_sample label.error {
            color: #FF0000;
        }

        .check td, .radio td {
            min-width: 150px;
        }

        .e-m-ios7 label, .e-m-ios7 .check, .e-m-ios7 .radio {
            padding-left: 10px;
        }

        .e-m-windows label, .e-m-windows .check {
            padding-left: 20px;
        }

        .e-m-windows .radio {
            padding-left: 20px;
        }

        .radio {
            padding-top: 5px;
        }

        .e-m-android #form_sample, .e-m-ios7 #form_sample {
            padding: 10px;
        }

        .e-m-android #form1 {
            padding: 0px 10px;
        }

        .e-m-windows #form_sample {
            padding: 3px;
        }
    </style>


{% endhighlight %}

### Add Textbox Control

To render the **Textbox** control, you need to set **“data-role”** attribute to **“ejmtextbox”** to an “input” element.

{% highlight html %}

**<!--Textbox-->**
<input id="user_name" data-role="ejmtextbox" required/>
<label for="user_name" class="error" generated="true" />


{% endhighlight %}



Run this code and you can see the following output.

{% include image.html url="getting-started_images/getting-started_img3.png" Caption="Form with Essential JS Mobile Textbox"%}

### Set Watermark text

The watermark text specifies a short hint that describes the expected value of the input field. This can be achieved by using the “**data-ej-watermarktext**” attribute.

{% highlight html %}

<!--Textbox-->
<input id="user_name" data-role="ejmtextbox" **data-ej-watermarktext="Name"** required />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img4.png" Caption="Form with Essential JS Mobile Textbox control"%}

### Add Numeric Textbox Control

To render the **Numeric****Textbox** control, you need to set **“data-role”** attribute to **“ejmnumeric”** to an “input” element and set its **type** attribute to **number**. Also watermark text can be specified by using the “**data-ej-watermarktext**” attribute.

{% highlight html %}

<!--Numeric Textbox-->
<input id="amt" data-role="ejmnumeric" type="number" data-ej-watermarktext="Amount" required />
<label for="amount" class="error" generated="true" />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img5.png" Caption="Form with Essential JS Mobile Numeric Textbox control"%}

### Disable Spin Button

By default, the spin button is visible. By using this, you can increment or decrement the values. In the Bill Payment app, you don’t require a spin button. To hide this, set **data-ej-showpinbutton** attribute to **false**.

{% highlight html %}

<!--Numeric Textbox-->
<input id="amt" data-role="ejmnumeric" type="number" data-ej-watermarktext="Amount" **data-ej-showspinbutton="false"** required />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img6.png" Caption="Form with Essential JS Mobile Numeric Textbox control without spin button"%}

### Set Decimal Point

By default, decimal numbers (floating point) are not allowed. In this use case, you need to allow the decimal values since it is an amount field. To achieve this, you need to set **data-ej-decimalplaces** attribute with a numeric value which specifies the number of decimals allowed.

{% highlight html %}

<!--Numeric Textbox-->
<input id="amt" data-role="ejmnumeric" type="number"****data-ej-enablespinbutton="false" data-ej-watermarktext="Amount" **data-ej-decimalplaces="2"** required />


{% endhighlight %}

### Add Radio Button Control

A **Radio****Button** control is required for the payment option (credit or debit). To render this control, set **data-role** attribute to **ejmradiobutton** to an **input** element and set its **type** attribute to **radio**. By using **data-ej-text** attribute you can set the test for **Radio****Button**.

{% highlight html %}

       <!--Radio Button for Credit-->
      <input id="credit" name="payoption" data-role="ejmradiobutton" data-ej-checked="true" type="radio" data-ej-text="Credit Card" />       
       <!--Radio Button for Debit-->
       <input id="debit" name="payoption" data-role="ejmradiobutton" type="radio" data-ej-text="Debit Card" />


{% endhighlight %}

### Add Textbox for E-mail

You can add Textbox for E-mail.

{% highlight html %}

<!-Add Email Textbox here>
<input id="mail" name="mail" data-role="ejmtextbox" data-ej-watermarktext="user@mail.com" type="email" required />
<label for="mail" class="error" generated="true" />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img7.png" Caption="Form with Essential JS Mobile Radio Button control"%}

### Add Textbox for Remarks.

You can add Textbox for Remarks.

{% highlight html %}

<!-Add Remarks Textbox here-->
<input name="remarks" data-role="ejmtextbox" data-ej-watermarktext="Remarks" />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img8.png" Caption="Form with Essential JS Mobile "%}

### Add Checkbox Control

You can use **Checkbox****Control** for “agree the terms and conditions” option. To render this, set **data-role** attribute to **ejmcheckbox** to an **input** element and set its **type** attribute to **checkbox**. By using **data-ej-text** you can set the text for the text box.

{% highlight html %}

    <!--Checkbox-->
    <input id="chkbox" data-role="ejmcheckbox" type="checkbox" data-ej-text="I accept the terms and conditions" />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img9.png" Caption="Form with Essential JS Mobile Checkbox"%}

### Add Button Control

You require a **Button****Control** to submit the **Form**. To render this control, set **data-role** attribute to **ejmbutton** to an “input” element. Add the **data-ej-text** attribute to specify the Button text. By using **data-ej-touchend** attribute, you can handle the form validation on button click.

{% highlight html %}

<!-Add Sumbit Button Here-->
<input id="btn" name="submit" data-role="ejmbutton" data-ej-text="Pay Bill" type="button" data-ej-touchend="formsubmit" />


{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img10.png" Caption="Form with Essential JS Mobile Button"%}

### Form Validation

The Bill payment is created with required controls and for validation, Essential **JavaScript Mobile Dialog** control is used to show the status of your payment.

{% highlight html %}

<script type="text/javascript">
        function formsubmit(event) {
            validation();
            $("#form1").submit();
            $("#ScrollPanel").ejmScrollPanel("refresh");
        }
        function exit() {
            var dialogObject = $("#info_msg").data("ejmDialog"); / creating instance for dialog
            dialogObject.close(); / close dialog
            $(".e-m-text-input").val("");
            $(".e-m-editor-input").val("");
            $("#chkbox").ejmCheckBox("model.checked", false);
        }

        function validation() {
            validator = $("#form1").validate({
                debug: true,
                messages: {
                    user_name: { required: "Please enter user name" },
                    amount: { required: "Please enter amount" },
                    mail: { required: "Please enter e-mail" }
                },
                submitHandler: function (form) {
                    var dialogObject = $("#info_msg").data("ejmDialog"); / creating instance for dialog
                    if (!$("#chkbox").ejmCheckBox("isChecked")) {
                        dialogObject.open(); / open dialog
                        $("#dlgcontent").text("Could you please agree our terms and conditions ?");
                    }
                    else {
                        dialogObject.open();
                        $("#dlgcontent").text("Your payment is received successfully");
                    }
                }
            });
        }
    </script>




{% endhighlight %}



{% include image.html url="getting-started_images/getting-started_img11.png" Caption="Figure 10: Form Validation"%}{% include image.html url="getting-started_images/getting-started_img12.png" Caption="Figure 10: Form Validation"%}

From the above steps, you have learnt how to create and customize Essential JS mobile Textbox, Numeric Textbox, Maskedit, Radiobutton, checkbox and Button widgets with use case samples. We have more customization properties other than the one used here. To know more about the properties in mentioned mobile widgets please refer the complete documentation page.

