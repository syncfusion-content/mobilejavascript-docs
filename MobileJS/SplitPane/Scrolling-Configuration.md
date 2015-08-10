---
layout: post
title: Scrolling-Configuration
description: scrolling configuration
platform: Mobilejs
control: SplitPane (Mobile)
documentation: ug
---

# Scrolling Configuration

## RightPane Scroll Settings

The “data-ej-allowrightpanescrolling” attribute is used to enable/disable the right pane content scrolling. By default the property is set to true. You can customize the right pane scrolling behavior by using this “data-ej-rightpanescrollsettings” attribute. 

{% highlight html %}

<div id="splitpane" data-role="ejmsplitpane" data-ej-rightpanescrollsettings-targetwidth="200">

        <div data-ej-layout="pane">

            <!--Left pane content-->

            <div id="listview" data-role="ejmlistview" data-ej-touchend="loadContent" data-ej-showheader=false>

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

Likewise, you can customize all other properties of scrollpanel using this property. Refer to the complete UG of scrollpanel to know its properties.



## LeftPane Scroll Settings

The “data-ej-allowleftpanescrolling” attribute is used to enable/disable the left pane content scrolling. By default the property is set to true. You can customize the left pane scrolling behavior by using this “data-ej-leftpanescrollsettings” attribute. 

{% highlight html %}

<div id="splitpane" data-role="ejmsplitpane"data-ej-leftpanescrollsettings-targetwidth=320>

        <div data-ej-layout="pane">

            <!--Left pane content-->

            <div id="listview" data-role="ejmlistview" data-ej-touchend="loadContent" data-ej-showheader=false>

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

Likewise, you can customize all other properties of scrollpanel using this property. Refer to the complete UG of scrollpanel to know its properties.





