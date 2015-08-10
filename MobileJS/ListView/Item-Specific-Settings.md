---
layout: post
title: Item-Specific-Settings
description: item specific settings
platform: Mobilejs
control: ListView (Mobile)
documentation: ug
---

# Item Specific Settings

In the ListView widget, the following numbered settings are available for easy customization of Items as per user demand. In JS, you can set this to the Li Item with ‘data-ej’ as prefix. Following are the detailed explanation.

_Item specific settings_
{% highlight html %}
<table>
<tr>
<th>
Settings</th><th>
Properties</th></tr>
<tr>
<td>
Ajax Post</td><td>
1. data-ej-href-This attribute can hold either the ID of an element or the name of the HTML page.* Option 1 - ID: The value should start with ‘#<ID>’* Option 2 - HTML: The value should be like ‘<HTML>.html’ or ‘<HTML>.htm’.2. data-ej-enableajax-This attribute must be set to true when the second option for href attribute is provided as mentioned above. </td></tr>
<tr>
<td>
<br>Selection</td><td>
1. MultiSelection* data-ej-enablecheckmark-This attribute is used to make the ListView as check list for multiple selection of items.* data-ej-checked-This attribute is used to make any item in checked state in the initial loading itself.2. data-ej-preventselection-This attribute is used to prevent selection while clicking on the list item.3. data-ej-persistselection-This attribute is used to persist the selection in the list item even after touch end. (By default, the active state is removed once touch end happens)</td></tr>
<tr>
<td>
<br>Item Customization</td><td>
data-ej-text-This attribute is used to set the text for the list item.</td></tr>
<tr>
<td>
Key Value</td><td>
data-ej-primarykey-This attribute is used to relate parent child and also to expose that the list item has inner page navigation.</td></tr>
<tr>
<td>
Image Customization</td><td>
1. data-ej-imageclass-This attribute is used to define the class name of the image that is to be rendered along with the list item.2. data-ej-imageurl-This attribute is used to define the URL of the image that is to be rendered along with the list item.</td></tr>
<tr>
<td>
<br>Child Customization</td><td>
1. Header Settings* data-ej-childheadertitle-This attribute is used to set the title of the header rendered in the child page.* data-ej-childheaderbackbuttontext-This attribute is used to set the text for the button available in the header that is rendered in the child page.2. data-ej-childId-This attribute is used to set the ID for the child item.</td></tr>
<tr>
<td>
<br>Templating</td><td>
1. data-ej-rendertemplate-This attribute is used to decide whether to render the list item with template or with default UI.2. data-ej-templateid-This attribute is used to define the ID of the template element.</td></tr>
<tr>
<td>
<br>Events</td><td>
1. data-ej-touchstart-This attribute is used to define the handler when touch start happens on a particular list item.2. data-ej-touchend-This attribute is used to define the handler when touch end happens on a particular list item.</td></tr>
</table>
{% endhighlight %}


