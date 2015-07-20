---
layout: post
title: Collapse-content
description: collapse content
platform: Mobilejs
control: Accordion (Mobile)
documentation: ug
---

## Collapse content

In some cases, you may want to collapse the Accordion content dynamically due to limited space available in the screen. You can enable this feature by setting “data-ej-collapsible” attribute to true. By clicking the Accordion header, you can collapse or expand the content.

{% highlight html %}



<div id="accordion_sample" data-role="ejmaccordion" data-ej-collapsible="true">

     <ul>

         <li data-ej-text="MVC">

            <div>

             Model-view-controller (MVC) is a software architecture pattern which separates the representation of information from the user's interaction with it. The model consists of application data, business rules, logic, and functions



             </div>

         </li>

         <li data-ej-text="WPF" >

            <div>

             Developed by Microsoft, the Windows Presentation Foundation (or WPF) is a computer-software graphical subsystem for rendering user interfaces in Windows-based applications.

            </div>

         </li>              

         <li data-ej-text="WCF" >

            <div>

            WCF is a tool often used to implement and deploy a service-oriented architecture (SOA). It is designed using service-oriented architecture principles to support distributed computing where services have remote consumers.

             </div>

         </li>  

    </ul>

</div>



{% endhighlight %}



The following screenshot displays the collapse content:



{{ '![C:/Users/isuriyar/AppData/Local/Temp/SNAGHTML8593e48f.PNG](Collapse-content_images/Collapse-content_img1.png)' | markdownify }}
{:.image }


