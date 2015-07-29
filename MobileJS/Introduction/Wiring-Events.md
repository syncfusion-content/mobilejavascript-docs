---
layout: post
title: Wiring-Events
description: wiring events
platform: Mobilejs
control: Introduction
documentation: ug
---

# Wiring Events

Whenever the control undergoes some changes or action, it should be notified to the users properly. To notify such actions, the appropriate events should be bound to the control. Events are wired the same way as jQuery events are bound, either during or after control initialization.

### During Initialization

{% highlight text %}



1. $(“jquery-selector”).<ejm-plugin-name>({ eventName : <eventhandler> });

Example:  $("#myDate").ejmDatePicker({ select: function () { // event handler }  });


{% endhighlight %}

## After initialization

{% highlight text %}

1. $(“jquery-selector”).<ejm-plugin-name>(“model.eventName”, <eventhandler>);

Example:  $("#myDate").ejmDatePicker("model.destroy" , function () {

            // Event handler

         });

2. $(“jquery-selector”).on(“ejm-plugin-nameeventName”, <eventhandler>);

Example:  $("#myDate").on("ejmDatePickerdestroy", function () {

            // Event handler

         }); 

{% endhighlight %}



