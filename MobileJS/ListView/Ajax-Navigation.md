---
layout: post
title: Ajax-Navigation
description: ajax navigation
platform: Mobilejs
control: ListView (Mobile)
documentation: ug
---

## Ajax Navigation

### EnableAjax

In the ListView widget, when all the items have navigation page to be loaded through Ajax content, then data-ej-enableajax attribute is set to true. 

Sample.html

{% highlight html %}



  <div id="ajaxListBox" data-role="ejmListView" data-ej-showheader="true" data-ej-headertitle="ListView" data-ej-enableajax="true">

      <ul>

          <li data-ej-text="Man of Steel" data-ej-href="load1.html"></li>

          <li data-ej-text="World War Z" data-ej-href="load2.html"></li>

          <li data-ej-text="Monsters University" data-ej-href="load3.html"></li>

      </ul>

  </div>





{% endhighlight %}



Add the following styles to the html

{% highlight css %}



        .listrightdiv

        {

            padding:20px;

        }





{% endhighlight %}



Load1.html

{% highlight html %}



<div class="listrightdiv">      

<span class="subtitlestyle"><b>Movie Info:</b></span>

      <div class="subtitlestyle">

      A young boy learns that he has extraordinary powers and is not of this Earth.

      </div>

</div>





{% endhighlight %}



Load2.html

{% highlight html %}



<div class="listrightdiv">

<span class="subtitlestyle"><b>Movie Info:</b></span>

      <div class="subtitlestyle">

      The story revolves around United Nations employee Gerry Lane (Pitt).

      </div>

</div>





{% endhighlight %}



Load3.html

{% highlight html %}



<div class="listrightdiv">

<span class="subtitlestyle"><b>Movie Info:</b></span>

      <div class="subtitlestyle">

      Mike Wazowski and James P. Sullivan are an inseparable pair, but that wasn't always the case.

      </div>

</div>



{% endhighlight %}



The following screenshot displays the Enable Ajax:

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_1e.png](Ajax-Navigation_images/Ajax-Navigation_img1.png)' | markdownify }}
{:.image }






{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_2.png](Ajax-Navigation_images/Ajax-Navigation_img2.png)' | markdownify }}
{:.image }


> _Note: When the Ajax navigation is only for a specific item, then use this atribute inside item specific configuration. (In JS, use this attribute “data-ej-enableajax” in specific “li” tag in html, while in MVC, set through EnableAjax)._

### AjaxSettings

In Ajax method, the ListView widget loads the content with default jQuery settings. You can customize it as in normal Ajax method through data-ej-ajaxsettings attribute. The following options are available.

1. Type
2. Cache
3. Async
4. DataType
5. ContentType
6. URL
7. Data



{% highlight html %}

<!--Sample.html -->



<div id="ajaxListBox" data-role="ejmListView" data-ej-showheader="true" data-ej-headertitle="ListView" data-ej-enableajax="true" data-ej-ajaxsettings-cache=true>

      <ul>

          <li data-ej-text="Man of Steel" data-ej-href="load1.html"></li>

          <li data-ej-text="World War Z" data-ej-href="load2.html"></li>

          <li data-ej-text="Monsters University" data-ej-href="load3.html"></li>

      </ul>

  </div>





{% endhighlight %}



The following screenshots display the Ajax Settings:

{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_1e.png](Ajax-Navigation_images/Ajax-Navigation_img3.png)' | markdownify }}
{:.image }


{{ '![C:/Users/vincentxavier/Desktop/Work/Documentation/Complete Doc/ListBox/images/ios7_2.png](Ajax-Navigation_images/Ajax-Navigation_img4.png)' | markdownify }}
{:.image }


### EnableCache

data-ej-enablecache attribute is used to prevent loading Ajax content every time. This is set to true only when the content is not updated for each request.

{% highlight html %}



<!--Sample.html -->



   <div id="ajaxListBox" data-role="ejmListView" data-ej-enablecache="true">

            <ul>

                <li data-ej-text="Man of Steel" data-ej-enableajax="true" data-ej-href="load1.html"></li>

                <li data-ej-text="World War Z" data-ej-enableajax="true" data-ej-href="load2.html"></li>

                <li data-ej-text="Monsters University" data-ej-enableajax="true" data-ej-href="load3.html"></li>

            </ul>

   </div>





{% endhighlight %}



