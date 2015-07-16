---
layout: post
title: CDN
description: cdn
platform: Mobilejs
control: Introduction
documentation: ug
---

## CDN

The [CDN](http://en.wikipedia.org/wiki/Content_delivery_network) links are provided individually for all the Scripts and Stylesheets that provide easier access to Syncfusion JavaScript components. 

{% highlight text %}

> _Note: All the provided cdn links can be accessed either through_ _http_ _or_ _https__._



{% endhighlight %}

### CDN Script links

#### External dependency libraries

The first three common script libraries listed in the following table are more essential and mandatory to render any of the Syncfusion widgets on the application module. The basic syntax is as follows,

{% highlight text %}



http://cdn.syncfusion.com/js/assets/external/[file name]



Example:

http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js





{% endhighlight %}

_Property Table_

<table>
<tr>
<td>
Name</td><td>
Details</td><td>
CDN link</td></tr>
<tr>
<td>
jquery 1.10.2</td><td>
Common jquery script to render any of the Syncfusion widgets.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js](http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js) | markdownify }</td></tr>
<tr>
<td>
jsrender</td><td>
Supports template rendering.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/jsrender.min.js](http://cdn.syncfusion.com/js/assets/external/jsrender.min.js) | markdownify }</td></tr>
<tr>
<td>
Jquery.Globalize</td><td>
Supports Globalization.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js) | markdownify }</td></tr>
<tr>
<td>
Angular JS</td><td>
Minified angular file to support custom directives.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/angular.min.js](http://cdn.syncfusion.com/js/assets/external/angular.min.js) | markdownify }</td></tr>
<tr>
<td>
excanvas</td><td>
To support canvas element rendering in IE8 browser.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/excanvas.min.js](http://cdn.syncfusion.com/js/assets/external/excanvas.min.js) | markdownify }</td></tr>
<tr>
<td>
Knockout JS</td><td>
Minified knockout file to support the observable binding. </td><td>
{ [http://cdn.syncfusion.com/js/assets/external/knockout.min.js](http://cdn.syncfusion.com/js/assets/external/knockout.min.js) | markdownify }</td></tr>
<tr>
<td>
requireJS</td><td>
Supports loading of required dependencies.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/require.min.js](http://cdn.syncfusion.com/js/assets/external/require.min.js) | markdownify }</td></tr>
<tr>
<td>
jquery.validate</td><td>
Supports client-side validation.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.validate.min.js) | markdownify }</td></tr>
<tr>
<td>
Jquery.validate.unobtrusive</td><td>
To enable unobtrusive validation options in data-* attributes.</td><td>
{ [http://cdn.syncfusion.com/js/assets/external/jquery.validate.unobtrusive.min.js](http://cdn.syncfusion.com/js/assets/external/jquery.validate.unobtrusive.min.js) | markdownify }</td></tr>
</table>
#### Syncfusion Dependency Libraries - Based on latest build version

The CDN script files are maintained for each version of the Essential Studio individually. Refer to the following syntax.



http://cdn.syncfusion.com/[version]/js/mobile/[file name]



For example, to access the ej.mobile.all.min.js file in 13.1.0.21 version– 

[https://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](https://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js)



_Property Table_

<table>
<tr>
<td>
Name</td><td>
Details</td><td>
CDN link</td></tr>
<tr>
<td>
ej.mobile.all.min</td><td>
Combined script file that includes the script of all the Syncfusion UI mobile widgets. </td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js) | markdownify }</td></tr>
<tr>
<td>
ej.unobtrusive.min</td><td>
Supports Syncfusion widgets to render in HTML5 format.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/web/ej.unobtrusive.min.js](http://cdn.syncfusion.com/13.1.0.21/js/web/ej.unobtrusive.min.js) | markdownify }</td></tr>
<tr>
<td>
ej.widget.angular.min</td><td>
Provides complete support for Angular JS.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/ej.widget.angular.min.js](http://cdn.syncfusion.com/13.1.0.21/js/ej.widget.angular.min.js) | markdownify }</td></tr>
<tr>
<td>
ej.widget.ko.min</td><td>
Provides complete support for Knockout JS.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/ej.widget.ko.min.js](http://cdn.syncfusion.com/13.1.0.21/js/ej.widget.ko.min.js) | markdownify }</td></tr>
</table>
The Knockout and angular dependencies can be accessed through the following syntax,



http://cdn.syncfusion.com/[version]/js/[file name]



For example, to access the ej.widget.angular.min.js file in 13.1.0.21 version– 

[https://cdn.syncfusion.com/13.1.0.21/js/ej.widget.angular.min.js](https://cdn.syncfusion.com/13.1.0.21/js/ej.widget.angular.min.js)



### CDN Stylesheet links

The CDN links for all the css files (both core & theme related) are depicted together in the following table. Refer to the following syntax:



http://cdn.syncfusion.com/[version]/js/mobile/[file name]

_Property Table_

<table>
<tr>
<td>
Name</td><td>
Details</td><td colspan = "2">
CDN link</td></tr>
<tr>
<td>
ej.mobile.all.min.css</td><td colspan = "2">
Includes the CSS of all the themes combined in a single css file.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css) | markdownify }</td></tr>
<tr>
<td>
Android Dark</td><td colspan = "2">
To apply the Android dark theme specifically, refer to both core and theme css files related to it. </td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-dark.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-dark.min.css) | markdownify }</td></tr>
<tr>
<td>
Android Light</td><td colspan = "2">
To apply the Android light theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-light.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.android-light.min.css) | markdownify }</td></tr>
<tr>
<td>
iOS7 Dark</td><td colspan = "2">
To apply the iOS7 dark theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-dark.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-dark.min.css) | markdownify }</td></tr>
<tr>
<td>
iOS7 Light</td><td colspan = "2">
To apply the iOS7 light theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-light.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.ios7-light.min.css) | markdownify }</td></tr>
<tr>
<td>
Windows Dark</td><td colspan = "2">
To apply the Windows Dark theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-dark.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-dark.min.css) | markdownify }</td></tr>
<tr>
<td>
Windows Light</td><td colspan = "2">
To apply the Windows Dark theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-light.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-light.min.css) | markdownify }</td></tr>
<tr>
<td>
Windows Default</td><td colspan = "2">
To apply the Windows Default theme specifically, refer to both core and theme css files related to it.</td><td>
{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-core.min.css) | markdownify }{ [http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-default.min.css](http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.windows-default.min.css) | markdownify }</td></tr>
</table>
### Referring local Scripts & CSS, when CDN fails

Sometimes, CDN links may go down due to network or connection problems. On such scenarios, you can refer to the local scripts and css files dynamically in the application by checking if the scripts and css files loaded through CDN returns undefined. If it returns undefined, the local scripts gets referred, else the cdn links work fine as illustrated in the following code example.

&lt;!DOCTYPE html&gt;

&lt;html xmlns="http://www.w3.org/1999/xhtml"&gt;

&lt;head&gt;



&lt;meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0, user-scalable=no" /&gt;



    <title>My first HTML page</title>



    &lt;!-- CDN LINK references--&gt;  

    &lt;link href="http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.css" rel="stylesheet" /&gt;



    &lt;script src="http://cdn.syncfusion.com/js/assets/external/jquery-1.10.2.min.js"&gt;&lt;/script&gt;



    &lt;script src="http://cdn.syncfusion.com/js/assets/external/jquery.globalize.min.js"&gt;&lt;/script&gt;



    &lt;script src="http://cdn.syncfusion.com/js/assets/external/jsrender.min.js"&gt;&lt;/script&gt;



    &lt;script src="http://cdn.syncfusion.com/13.1.0.21/js/mobile/ej.mobile.all.min.js" &gt;&lt;/script&gt;



    &lt;script type="text/javascript"&gt;



        if (typeof jQuery == "undefined") { // If CDN fails, jQuery returns undefined

            // Referring local scripts - Specify the path where the following files are located in your machine

            document.write(decodeURIComponent('%3Cscript src="Scripts/jquery-1.10.2.min.js" %3E%3C/script%3E'));

            document.write(decodeURIComponent('%3Cscript src="Scripts/jquery.globalize.min.js" %3E%3C/script%3E'));

            document.write(decodeURIComponent('%3Cscript src="Scripts/jsrender.min.js" %3E%3C/script%3E'));

        }



        if (typeof ej == "undefined") { // If CDN fails, ej returns undefined.

            // So that, refer the Syncfusion stylesheets and scripts from the local path here



            // StyleSheet reference from the local system path

            document.write(decodeURIComponent('%3Clink rel="stylesheet" href="Content/ej/mobile/ej.mobile.all.min.css" %3C/%3E'));



            // Script reference from the local system path

            document.write(decodeURIComponent('%3Cscript src="Scripts/ej/ej.mobile.all.min.js" %3E%3C/script%3E'));

        }



    &lt;/script&gt; 

&lt;/head&gt;

&lt;body&gt; 



&lt;div data-role="appview"&gt;

&lt;!--Container for ejmDatePicker widget--&gt;

&lt;input id="startDate" data-role="ejmdatepicker" data-ej-value="01/01/2000" /&gt;



&lt;/div&gt;

&lt;/body&gt;

&lt;/html&gt;





