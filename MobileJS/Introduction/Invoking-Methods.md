---
layout: post
title: Invoking Methods | Introduction | Mobilejs | Syncfusion
description: invoking methods
platform: Mobilejs
control: Introduction
documentation: ug
---

# Invoking Methods

The functions can be invoked the same way the properties are accessed. The following syntaxes define the ways to invoke the public methods of the widgets.

{% highlight js %}

1. var obj = $(“jquery-selector”).data(“<ejm-plugin-name>”); [Recommended method]

obj.methodName(param1, param2, param3, ...)

Example:  var gaugeObject = $("#gauge").data("ejCircularGauge");

         gaugeObject.setPointerValue(0, 0, 50);

2. $(“jquery-selector”).<ejm-plugin-name>(“functionName”);

Example:  $("#myDate").ejmDatePicker("getValue");

3. $(“jquery-selector”).<ejm-plugin-name>(“functionName”, “param1”, “param2”, …);

Example:  $("#gauge").ejCircularGauge("setPointerValue", "0", "0", "30");

{% endhighlight %}