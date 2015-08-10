---
layout: post
title: Type
description: type
platform: Mobilejs
control: Group Button (Mobile)
documentation: ug
---

# Type

The Group Button is rendered via button and input tag elements. Group Button rendering is classified into three types: Button type, radio input type, and checkbox input type.

## Button

{% highlight html %}

<!-- Group Button rendering via button tag -->

    <div id="groupbutton_sample" data-role="ejmgroupbutton">

        <button>ipad</button>

        <button>ipod</button>

        <button>iphone</button>

    </div>



{% endhighlight %}

## Radio Button

{% highlight html %}

<!-- Group Button rendering via radiobutton -->

    <div id="groupbutton_sample" data-role="ejmgroupbutton">

        <label>

            <input type="radio" />ipad

        </label>

        <label>

            <input type="radio" />ipod

        </label>

        <label>

            <input type="radio" />iphone

        </label>

    </div>



{% endhighlight %}

## Checkbox

{% highlight html %}

<!-- Group Button rendering via checkbox-->

    <div id="groupbutton_sample" data-role="ejmgroupbutton">

        <label>

            <input type="checkbox" />ipad

        </label>

        <label>

            <input type="checkbox" />ipod

        </label>

        <label>

            <input type="checkbox" />iphone

        </label>

    </div>



{% endhighlight %}

The following screenshot displays the Group Button.

![](Type_images/Type_img1.png)



