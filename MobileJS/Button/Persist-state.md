---
layout: post
title: Persist state | Button | Mobilejs | Syncfusion
description: persist state
platform: Mobilejs
control: Button (Mobile)
documentation: ug
---

# Persist state

EnablePersistence is a Boolean property that allows you to declare the persistence state of the Button control. This is basically to maintain the current model value to browser cookies for “state maintenance”. While refreshing the page, the model value is applied to the control from browser cookies.

By default, the EnablePersistence is set to ‘false’.

You can refer to the following code example.

{% highlight html %}

<input id="sample_button" type="button" data-role="ejmbutton" data-ej-text="button" data-ej-enablepersistence="true" />

{% endhighlight %}