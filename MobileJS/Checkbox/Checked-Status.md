---
layout: post
title: Checked Status | Checkbox | Mobilejs | Syncfusion
description: checked status
platform: Mobilejs
control: Checkbox (Mobile)
documentation: ug
---

# Checked Status

By using data-ej-checked attribute, you can set the state of Checkbox. When data-ej-checked is true, the Checkbox is in checked state. When false, Checkbox is in unchecked state. When you want to use this data-ej-checked attribute, then checkbox should be in non Tri-state and data-ej-enabletristate attribute should be false.

The following code explains you the details about rendering the Checkbox with above mentioned checked options, when the checkbox is in non tri-state.

In the HTML page, add the following input elements to configure Checkbox widget.                                     

{% highlight html %}

<table id="main">

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox1" data-ej-text="Google" data-ej-checked="true" />

		</td>

	</tr>

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox2" data-ej-text="Yahoo" data-ej-checked="true" />

		</td>

	<tr />

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox3" data-ej-text="Bing" data-ej-checked="false" />

		</td>

	<tr />

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox4" data-ej-text="Wikipedia" data-ej-checked="true" />

		</td>

	<tr />

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox5" data-ej-text="Amazon" />

		</td>

	<tr />

	<tr>

		<td>

		  <input data-role="ejmcheckbox" type="checkbox" id="Checkbox6" data-ej-text="Twitter" />

		</td>

	<tr />

</table>

{% endhighlight %}