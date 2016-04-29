layout: post
title: ejmRotator | API Reference | Mobile JS | Syncfusion
description:  Methods, members, events available in ejmRotator
platform: Mobilejs
control: ejmRotator
documentation: API
keywords: ejmRotator, API, Essential Studio JS Rotator (Mobile) 

# ejmRotator

The Essential Mobile JavaScript Rotator control displays a set of slides. Each slide may contain images or images with content, or content with user-defined transition between them.

Custom Design for Html Rotator control.

$(element).ejmRotator();

####Example
    <!-- Unbtrusive way of rendering -->
 
 <div id="rotatorcontent">
        <div data-ej-imageurl="bird.jpg">
        </div>
        <div data-ej-imageurl="wheat.jpg">
        </div>
        <div data-ej-imageurl="card.jpg">
        </div>
        <div data-ej-imageurl="rose.jpg">
        </div>
        <div data-ej-imageurl="snowfall.jpg">
        </div>
        <div data-ej-imageurl="bird.jpg">
        </div>
    </div>
    <div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent">
    </div>

    <!-- Obtrusive way of rendering -->
 
 <div id="rotatorcontent">
        <div data-ej-imageurl="bird.jpg">
        </div>
        <div data-ej-imageurl="wheat.jpg">
        </div>
        <div data-ej-imageurl="card.jpg">
        </div>
        <div data-ej-imageurl="rose.jpg">
        </div>
        <div data-ej-imageurl="snowfall.jpg">
        </div>
        <div data-ej-imageurl="bird.jpg">
        </div>
    </div>
    <div id="rotator">
    </div>
    <script>
        $(function(){
            $("#rotator").ejmRotator({ targetId: "rotatorcontent" });
        })
    </script>

####Requires
* module:jQuery

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch

## Members

### currentItemIndex `Int`
{:#members:currentitemindex}

Specifies the currentItemIndex for select the particular item based on the specified index.

#### Default Value:

* 0

#### Example  

//Set the currentItemIndex property in unobtrusive way.



 &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-currentitemindex="2"&gt;

    &lt;/div&gt;



// Set currentItemIndex on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set currentItemIndex API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", currentItemIndex: 2 });

        })

    &lt;/script&gt;



### dataSource
{:#members:datasource}

Specifies the dataSource for items.

#### Default Value:

* null

#### Example  

//Set the dataSource property in unobtrusive way.



  &lt;style&gt;

        .image-bird {

            background-image: url("bird.jpg");

        }



        .image-wheat {

            background-image: url("wheat.jpg");

        }



        .image-card {

            background-image: url("card.jpg");

        }



        .image-rose {

            background-image: url("rose.jpg");

        }



        .image-snowfall {

            background-image: url("snowfall.jpg");

        }

    &lt;/style&gt;



    &lt;script type="text/javascript"&gt;

        window.dataSource = [{ imageUrl: 'image-bird' }, { imageUrl: 'image-wheat' }, { imageUrl: 'image-card' }, { imageUrl: 'image-rose' }, { imageUrl: 'image-snowfall' }];

    &lt;/script&gt;

    &lt;div id="rotatorcontent"&gt;

        &lt;div class="e-m-rotator-image {{:imageUrl}}"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-datasource="window.dataSource"&gt;

    &lt;/div&gt;



// Set dataSource on initialization.



&lt;style&gt;

        .image-bird {

            background-image: url("bird.jpg");

        }



        .image-wheat {

            background-image: url("wheat.jpg");

        }



        .image-card {

            background-image: url("card.jpg");

        }



        .image-rose {

            background-image: url("rose.jpg");

        }



        .image-snowfall {

            background-image: url("snowfall.jpg");

        }

    &lt;/style&gt;

    &lt;div id="rotatorcontent"&gt;



        &lt;div class="e-m-rotator-image {{:imageUrl}}"&gt;

        &lt;/div&gt;



    &lt;/div&gt;



    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set dataSource API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", dataSource: [{ imageUrl: 'image-bird' }, { imageUrl: 'image-wheat' }, { imageUrl: 'image-card' }, { imageUrl: 'image-rose' }, { imageUrl: 'image-snowfall' }] });

        })

    &lt;/script&gt;



### cssClass `String`
{:#members:cssclass}

Specify the CSS class to Rotator to achieve custom theme.

#### Default Value:

*“ ”

#### Example  



//Set the cssClass property in unobtrusive way.

&lt;style&gt;

        .customize-rotator .e-m-rotator-image{

            background-size:200px 200px;

        }

    &lt;/style&gt;

    &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;



    &lt;div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-cssclass="customize-rotator"&gt;

    &lt;/div&gt;



// Set cssClass on initialization.

&lt;style&gt;

        .customize-rotator .e-m-rotator-image {

            background-size: 200px 200px;

        }

    &lt;/style&gt;



    &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set cssClass API value

            $("#rotator").ejmRotator({ targetId: "rotatorcontent", cssClass: "customize-rotator" });

        })

    &lt;/script&gt;



### enablePersistence `Boolean`
{:#members:enablepersistence}

Current model value to browser cookies for state maintains. While refresh the Rotator control page retains the model value apply from browser cookies.

#### Default Value:

* false

#### Example  

//Set the enabledPersistence property in unobtrusive way.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-enablepersistence=true&gt;

    &lt;/div&gt;



// Set enablePersistence on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set enablePersistence API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", enablePersistence: true });

        })

    &lt;/script&gt;



### items `Array`
{:#members:items}

Specifies the rotator items.

#### Default Value:

* null

#### Example  

    //Set the items property in unobtrusive way.



    &lt;div id="rotatordefault" data-role="ejmrotator"  data-ej-items="[{imageUrl:'bird.jpg'},{imageUrl:'wheat.jpg'},{imageUrl:'card.jpg'},{imageUrl:'rose.jpg'},{imageUrl:'snowfall.jpg'}]"&gt;

    &lt;/div&gt;





// Set items on initialization.



&lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set items API value



            $("#rotator").ejmRotator({ items: [{ imageUrl: 'bird.jpg' }, { imageUrl: 'wheat.jpg' }, { imageUrl: 'card.jpg' }, { imageUrl: 'rose.jpg' }, { imageUrl: 'snowfall.jpg' }] });

        })

    &lt;/script&gt;



### orientation `Enum`
{:#members:orientation}

Specifies the rotator orientation to the horizontal or vertical. See below to know available orientation options. 

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
Horizontal</td><td>
To swipe the rotator content images in horizontal</td></tr>
<tr>
<td>
Vertical</td><td>
To swipe the rotator content images in vertical</td></tr>
</table>
#### Default Value:

* “horizontal”

#### Example  

    //Set the orientation property in unobtrusive way.

    &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-orientation="vertical"&gt;

    &lt;/div&gt;





// Set orientation on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set orientation API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", orientation: "vertical" });

        })

    &lt;/script&gt;



### pagerPosition `Enum`
{:#members:pagerposition}

Specifies the pager position relevant to orientation. See the below to know available pagerPosition options.



<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
Top</td><td>
To display the pager position on top side.</td></tr>
<tr>
<td>
Bottom</td><td>
To display the pager position on bottom side.</td></tr>
<tr>
<td>
Left</td><td>
To display the pager position on left side.</td></tr>
<tr>
<td>
Right</td><td>
To display the pager position on right side.</td></tr>
</table>


#### Default Value:

* “bottom”

#### Example  

    //Set the pagerPosition property in unobtrusive way.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-pagerposition="top"&gt;

    &lt;/div&gt;



// Set pagerPosition on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                       //To set pagerPosition API value

            $("#rotator").ejmRotator({ targetId: "rotatorcontent", pagerPosition: "top" });

        })

    &lt;/script&gt;



### showPager `Boolean`
{:#members:showpager}

Specifies whether to show the Pager on initialization.

#### Default Value:

* true

#### Example  

//Set the showPager property in unobtrusive way.



 &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-showpager="false"&gt;

    &lt;/div&gt;



// Set showPager on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                   //To set showPager API value

            $("#rotator").ejmRotator({ targetId: "rotatorcontent", showPager: false });

        })

    &lt;/script&gt;


### renderMode `Enum`
{:#members:rendermode}

Specifies the rendering mode of the control. See[RenderMode](http://help.syncfusion.com/mobilejs/api/global#members:rendermode)

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Default</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
Auto</td><td>
string</td><td>
auto</td><td>
Auto RenderMode</td></tr>
<tr>
<td>
IOS7</td><td>
string</td><td>
ios7</td><td>
IOS7 RenderMode</td></tr>
<tr>
<td>
Android</td><td>
string</td><td>
android</td><td>
Android RenderMode</td></tr>
<tr>
<td>
Windows</td><td>
string</td><td>
windows</td><td>
Windows RenderMode</td></tr>
</table>


#### Default Value:

* auto



#### Example  

//Set the renderMode property in unobtrusive way.



  &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-rendermode="android"&gt;

    &lt;/div&gt;



// Set renderMode on initialization.



 &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                   //To set renderMode API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", renderMode: "android" });

        })

    &lt;/script&gt;



### targetHeight `String`
{:#members:targetheight}

Specifies the targetHeight on initialization.

#### Default Value:

* auto

#### Example  

//Set the targetHeight property in unobtrusive way.



  &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-targetheight="300px"&gt;

    &lt;/div&gt;



// Set targetHeight on initialization.

&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                   //To set targetHeight API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", targetHeight: "300px" });

        })

    &lt;/script&gt;



### targetId `String`
{:#members:targetid}

Specifies the targetId to the content.

#### Default Value:

* null

#### Example  

//Set the targetId property in unobtrusive way.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent"&gt;

    &lt;/div&gt;



// Set targetId on initialization.



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                   //To set targetId API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent" });

        })

    &lt;/script&gt;





### targetWidth `String`
{:#members:targetwidth}


Specifies the targetWidth on initialization.

#### Default Value:

* auto

#### Example  

//Set the targetWidth property in unobtrusive way.   

 &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-targetwidth="300px"&gt;

    &lt;/div&gt;



// Set targetWidth on initialization.

&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotator"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        $(function () {

                   //To set targetWidth API value



            $("#rotator").ejmRotator({ targetId: "rotatorcontent", targetWidth: "300px" });

        })

    &lt;/script&gt;



## Methods



### renderDatasource()
{:#methods:renderdatasource}

To handle the rotator datasource.

#### Example  

&lt;div id="rotator" data-role="ejmrotator" data-ej-targetid="rotatorcontent"&gt;

    &lt;/div&gt;

    &lt;div id="rotatorcontent"&gt;

        &lt;div class="background-image:{{:imageUrl}};height:350px;width:630px"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    //To set the dataSource API value

    &lt;script&gt;

        $(function () {

            var imgdata = [{ imageUrl: 'bird.jpg' }, { imageUrl: 'wheat.jpg' }, { imageUrl: 'card.jpg' }, { imageUrl: 'rose.jpg' }, { imageUrl: 'snowfall.jpg' }];

            // To get the instance of the rotator control



            var rotObj = $("#rotator").data("ejmRotator");

            rotObj.renderDatasource(imgdata); 

        });

    &lt;/script&gt;



## Events

### change
{:#events:change}

Event triggers when the rotator changes from one slide to another slide

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
returns the targetElement of the rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
returns the current slide index.</td></tr>
</table>




#### Example  

&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-change="change"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        function change(args) {

            //handle the event

        }

    &lt;/script&gt;





### pagerSelect
{:#events:pagerselect}

Event triggers when the rotator’s pager clicked

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
returns the targetElement of the rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
returns the current slide index.</td></tr>
</table>


#### Example  

&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-pagerselect="pagerSelect"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        function pagerSelect(args) {

            //handle the event

        }

    &lt;/script&gt;





### swipeDown
{:#events:swipedown}

Event triggers when the swipeDown happens in the Rotator

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
returns the targetElement of the rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
returns the current slide index.</td></tr>
</table>


#### Example  



&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipedown="swipeDown"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        function swipeDown(args) {

            //handle the event

        }

    &lt;/script&gt;




### swipeLeft
{:#events:swipeleft}

Event triggers when the swipeLeft happens.

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
Returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
Returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
Returns the targetElement of the Rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
Returns the current slide index.</td></tr>
</table>


#### Example  

  &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipeleft="swipeLeft"&gt;

    &lt;/div&gt;

    &lt;script&gt;

    function swipeLeft(args) {

        //handle the event

    }

    &lt;/script&gt;



### swipeRight
{:#events:swiperight}

Event triggers when the swipeRight happens in the Rotator

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
returns the targetElement of the rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
returns the current slide index.</td></tr>
</table>


#### Example  

  &lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swiperight="swipeRight"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        function swipeRight(args) {

            //handle the event

        }

    &lt;/script&gt;



### swipeUp
{:#events:swipeup}

Event triggers when the swipeUp happens in the Rotator

<table>
<tr>
<th>
<b>Name</b></th><th>
<b>Type</b></th><th>
<b>Description</b></th></tr>
<tr>
<td>
argument.cancel</td><td>
boolean</td><td>
returns the cancel option value</td></tr>
<tr>
<td>
argument.model</td><td>
object</td><td>
returns the Rotator model</td></tr>
<tr>
<td>
argument.type</td><td>
string</td><td>
returns the name of the event</td></tr>
<tr>
<td>
argument.targetElement</td><td>
string</td><td>
returns the targetElement of the rotator</td></tr>
<tr>
<td>
argument.value</td><td>
number</td><td>
returns the current slide index.</td></tr>
</table>


#### Example  

&lt;div id="rotatorcontent"&gt;

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="wheat.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="card.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="rose.jpg"&gt;

        &lt;/div&gt;

        &lt;div data-ej-imageurl="snowfall.jpg"&gt;

        </div>s

        &lt;div data-ej-imageurl="bird.jpg"&gt;

        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div id="rotatordefault" data-role="ejmrotator" data-ej-targetid="rotatorcontent" data-ej-swipeup="swipeUp"&gt;

    &lt;/div&gt;

    &lt;script&gt;

        function swipeUp(args) {

            //handle the event

        }

    &lt;/script&gt;





