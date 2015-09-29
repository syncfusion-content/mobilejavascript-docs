---
layout: post
title: Windows Specific Customization | Menu | Mobilejs | Syncfusion
description: windows specific customization
platform: Mobilejs
control: Menu (Mobile)
documentation: ug
---

# Windows Specific Customization

You can set the windows specific properties to the control by accessing Windows property.

## Type	

When you click a button or target element, the Menu appears in contextual or popup mode. The appearance of the Menu is defined by the data-ej-type attribute. 

The possible values are,

1. Contextual 
2. Popup


{% highlight html %}

<div style="text-align: center;">

	<input id="menuitem" type="button" data-role="ejmbutton" data-ej-text="Menu" data-ej-rendermode="windows" />

</div>

<div id="menu_sample" data-role="ejmmenu" data-ej-target="menuitem" data-ej-rendermode="windows" data-ej-windows-type="contextual">

	<ul>

		<li data-ej-text="Get info"></li>

		<li data-ej-text="Show in folder"></li>

		<li data-ej-text="Delete"></li>

	</ul>

</div>

{% endhighlight %}

The following screenshot displays the Windows-specific Type:

![](Windows-Specific-Customization_images/Windows-Specific-Customization_img1.png)