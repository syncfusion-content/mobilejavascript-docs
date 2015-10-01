---
layout: post
title: Customize header | Rotator | Mobilejs | Syncfusion
description: customize header
platform: Mobilejs
control: Rotator (Mobile)
documentation: ug
---

# Customize header

In Rotator you can enable the built-in header support.

To show or hide the header in Rotator, you can use data-ej-showheader attribute. You can set the title for header using data-ej-headerTitle attribute. Refer to the following code example.

{% highlight html %}

<div id="page" data-role="appview">

   <div id="rotatordefault" data-role="ejmrotator" data-ej-

		  targetid="rotatorcontentdefault" data-ej-showheader="true" data-ej-headertitle="Photo Gallery">

	</div>

</div>

<div id="rotatorcontentdefault">

	<div>

		<div class="photo photo1">

		</div>

	</div>

	<div>

		<div class="photo photo2">

		</div>

	</div>

	<div>

		<div class="photo photo3">

		</div>

	</div>

	<div>

		<div class="photo photo4">

		</div>

	</div>

	<div>

		<div class="photo photo5">

		</div>

	</div>

</div>

{% endhighlight %}

![](Customize-header_images/Customize-header_img1.png)