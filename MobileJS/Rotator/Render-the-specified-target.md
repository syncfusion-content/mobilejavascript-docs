---
layout: post
title: Render the specified target | Rotator | Mobilejs | Syncfusion
description: render the specified target
platform: Mobilejs
control: Rotator (Mobile)
documentation: ug
---

# Render the specified target

You can render the contents for the Rotator by specifying the particular target element. The target element should maintain the HTML structure as mentioned in the following code example.

The data-ej-targetid attribute is used to define the Id of the target element where you can specify the content to render in the control. The data-ej-targetheight and data-ej-targetwidth attributes are used to specify the Rotator height and width respectively on initialization. Refer to the following code example.

{% highlight html %}

<div id="page" data-role="appview">

	<!-- header control -->

	<div data-role="ejmheader" id="header" data-ej-title="Rotator">

	</div>   

	<div id="rotatordefault" data-role="ejmrotator" data-ej-

		 targetid="rotatorcontentdefault">

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

</div>

{% endhighlight %}

![](Render-the-specified-target_images/Render-the-specified-target_img1.png)