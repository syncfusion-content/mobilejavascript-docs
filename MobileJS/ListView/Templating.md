---
layout: post
title: Templating
description: templating
platform: Mobilejs
control: ListView (Mobile)
documentation: ug
---

## Templating

### Internal Template

By using template support, you can customize the appearance of the individual list item or render the whole ListView by using a single template. Setting the data-ej-rendertemplate to true and specifying the template inside the li item renders the ListView with template item.

{% highlight html %}



        <div data-role="ejmListView" id="templatelist" data-ej-allowscrolling="false" data-ej-datasource="window.dbitem" data-ej-databinding="true" data-ej-rendertemplate="true">

            <div class="cont-bg">

                <div class="{{>Class}}">

                </div>

                <div class="listrightdiv">

                    <span class="templatetext">{{>Name}}</span> <span class="designationstyle">{{>Designation}}</span>

                    <div class="aboutstyle">

                        {{>About}}</div>

                </div>

            </div>

        </div> 



{% endhighlight %}



### External template

The data-ej-templateid attribute is used to define the template ID for the list item. Template is defined outside and is rendered by using its ID for list items. The Template ID is set to the data-ej-templatid attribute for the ListView control so that the template renders along with the ListView. To use data-ej-templateid attribute, enable the data-ej-rendertemplate attribute.

{% highlight html %}



        <div id="lb" data-role="ejmListView" data-ej-headertitle="Inbox">

        <ul>

            <li data-ej-rendertemplate=true data-ej-templateid="target1"></li>

            <li data-ej-rendertemplate=true data-ej-templateid="target2"></li>

            <li data-ej-rendertemplate=true data-ej-templateid="target3"></li>

        </ul>

    </div>



    <div id="target1">

        <div class="content-panel">

            <div class="name-panel">

                John Linden<div class="time-panel">

                    5th Jan

                </div>

            </div>

            <div class="message-title">

                Fw:Training

            </div>

            <p class="text-panel">

                All WinRT controls are optimized for touch, supporting common gestures: zooming, panning, selecting, double-tapping, rotating, resizing.

            </p>

            <div class="border-panel">

            </div>

        </div>

    </div>

    <div id="target2">

        <div class="content-panel">

            <div class="name-panel" style="padding-top: 10px;">

                David<div class="time-panel">

                    6th Jan

                </div>

            </div>

            <div class="message-title">

                Re:Training

            </div>

            <p class="text-panel">

                All the components in the ASP. NET MVC Essential Studio have been built from the ground up with performance in mind and are extremely lightweight.

            </p>

        </div>

    </div>

    <div id="target3">

        <div class="content-panel">

            <div class="name-panel" style="padding-top: 10px;">

                James Mario<div class="time-panel">

                    6th Jan

                </div>

            </div>

            <div class="message-title">

                Re:Training

            </div>

            <p class="text-panel">

                Syncfusion Metro Studio is a collection of over 2500 Metro-style icon templates that can be easily customized to create thousands of unique Metro icons.

            </p>

        </div>

    </div>



{% endhighlight %}



You can add the following styles for better appearance.

{% highlight css %}



        .appview .e-m-android .name-panel, .appview .e-m-android .time-panel {

            color: #4DA6C4;

        }



        .appview .e-m-flat .name-panel, .appview .e-m-flat .time-panel {

            color: #F48B22;

        }



        .appview .time-panel {

            float: right;

            color: #007AFF;

            font-weight: bold;

        }



        .appview .content-panel {

            font-size: 14px;

        }



        .appview .name-panel {

            font-size: 15px;

            font-weight: bold;

            color: #007AFF;

            padding-bottom: 5px;

        }



        .appview .message-title {

            font-weight: bold;

            padding-bottom: 5px;

        }



        .appview .text-panel {

            padding-bottom: 5px;

            padding-top: 5px;

        }





{% endhighlight %}



The following screenshot displays the Template:

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_18.png](Templating_images/Templating_img1.png)' | markdownify }}
{:.image }


