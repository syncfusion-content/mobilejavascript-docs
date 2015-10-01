---
layout: post
title: Pane-Settings | SplitPane | Mobilejs | Syncfusion
description: pane settings
platform: Mobilejs
control: SplitPane (Mobile)
documentation: ug
---

# Pane Settings

The “data-ej-overlayleftpane” attribute is used to enable or disable the left pane in lower resolutions. Its default value is true. You can specify the direction of left pane to get slide over the rightpane by using this “data-ej-over;aydirection” attribute. The possible directions are,

* left - Left overlay pane gets transition from left side.
* right - Left overlay pane gets transition from right side.

The “data-ej-enableswipe” attribute is used to display the leftpane while swiping the screen. When this property is set to false, then you cannot swipe the left pane.

{% highlight html %}

<div id="splitpane" data-role="ejmsplitpane" data-ej-overlayleftpane="true" data-ej-enableswipe="true" data-ej-overlaydirection ="right">

	<div data-ej-layout="pane">

		<!--Left pane content-->

		<div id="listview" data-role="ejmlistview" data-ej-showheader=false data-ej-touchend="loadContent">

			<ul>

				<li data-ej-text="Item1"></li>

				<li data-ej-text="Item2"></li>

				<li data-ej-text="Item3"></li>

				<li data-ej-text="Item4"></li>

				<li data-ej-text="Item5"></li>

				<li data-ej-text="Item6"></li>

			</ul>

		</div>

	</div>

</div>

{% endhighlight %}

Refer to the script section and page content section to load the right pane content of appropriate page created.