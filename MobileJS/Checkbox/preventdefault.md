---
layout: post
title: preventdefault  | Checkbox | Mobilejs | Syncfusion
description: preventdefault 
platform: Mobilejs
control: Checkbox (Mobile)
documentation: ug
---

# PreventDefault 

In CheckBox control, there are default actions to check or uncheck the control. You can prevent this default action by setting data-ej-preventdefault attribute to true. By default, this attribute is set to false.

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
				<input id="apple" name="chkbox" data-role="ejmcheckbox" data-ej-text="Apple" data-ej-preventdefault="true" />
			</td>

			<td width="100px">
				<input id="android" name="chkbox" data-role="ejmcheckbox" data-ej-text="Android" />
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