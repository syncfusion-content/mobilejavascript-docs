---
layout: post
title: Templating
description: templating
platform: Mobilejs
control: Menu (Mobile)
documentation: ug
---

## Templating

### RenderTemplate	

By using the template support, you can customize the appearance of an individual Menu item or the whole Menu is rendered with a single template. Setting the data-ej-rendertemplate to true and specifying the template inside the li item render Menu with template item. Refer to the following code example.

{% highlight html %}

     <div style="text-align: center;">

            <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" />

        </div>

      <div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-rendertemplate="true">

        <div style="text-align:center;">

           <div><img class="image" src="message.gif" /><span class="text">Message</span></div>

           <div><img class="image" src="mail.gif" /><span class="text">Mail</span></div>

           <div><img class="image" src="twitter.gif" /><span class="text">Twitter</span></div>

           <div><img class="image" src="facebook.gif" /><span class="text">Facebook</span></div>

        </div>

      </div>



{% endhighlight %}

The following screenshot displays the RenderTemplate of Menu.

{ ![1](Templating_images/Templating_img1.png) | markdownify }
{:.image }


### TemplateID

This attribute is used to define the Template ID for the Menu item. Template is defined outside and can be rendered by using its ID for Menu items. The template’s ID is set to the data-ej-templateid attribute for the Menu control so that the template renders along with the Menu. To use data-ej-templateid attribute, enable the data-ej-rendertemplate attribute.

{% highlight html %}

<div style="text-align: center;">

       <input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" /> </div>

<div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem">

      <ul>

           <li data-ej-text="Get info" data-ej-rendertemplate="true" data-ej-templateid="template1" ></li>

           <li data-ej-text="Show in folder" data-ej-rendertemplate="true" data-ej-templateid="template2"></li>

           <li data-ej-text="Delete" data-ej-rendertemplate="true" data-ej-templateid="template3"></li>

      </ul>

</div>

<div id="template1">

     <span class="text">Insurance</span>

</div>

<div id="template2">

     <span class="text">Premium</span>

</div>

<div id="template3">

     <span class="text">Benefits</span>

</div>



{% endhighlight %}



