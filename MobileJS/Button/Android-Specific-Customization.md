---
layout: post
title: Android Specific Customization | Button | Mobilejs | Syncfusion
description: android specific customization
platform: Mobilejs
control: Button (Mobile)
documentation: ug
---

# Android Specific Customization

By using data-ej-android-style attribute, you can customize the style of the button.

The possible values are

1. Normal
2. Small
3. Dialog

You can refer to the following code examples

{% highlight html %}

<div align="center" style="margin:10px">

	<input type="button" id="sample_button" data-role="ejmbutton" data-ej-text="Normal" data-ej-rendermode="android" data-ej-android-style="normal" /><br /><br />

	<input type="button" id="sample_button1" data-role="ejmbutton" data-ej-text="Small" data-ej-rendermode="android" data-ej-android-style="small" />

	<input type="button" id="sample_button2" data-role="ejmactionlink" data-ej-text="Dialog" data-ej-rendermode="android" data-ej-android-style="dialog" />

</div>

{% endhighlight %}