---
layout: post
title: ejmAutocomplete
documentation: API
platform: Mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html Autocomplete control.





$(element).ejmAutocomplete<span class="signature">()</span>






Example
{:.example}


{% highlight html %} 
// Create the autocomplete control in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Create autocomplete on initialization.
<input id="autocomplete" />
<script> 
// Create autocomplete  
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" }); 
</script>{% endhighlight %}




Requires
{:.require}


* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.mobile.listview

* module:ej.mobile.scrollpanel

* module:ej.mobile.menu

* module:ej.data

* module:ej.touch


## Members




### allowScrolling<span class="type-signature type boolean">boolean</span>
{:#members:allowscrolling}




Specifies whether to be allow the scrolling in suggestion list.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the allowScrolling property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-allowscrolling=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the allowScrolling on initialization. 
<input id="autocomplete" />
<script> 
//To set allowscrolling API value 
$("#autocomplete").ejmAutocomplete ({ allowScrolling:true, dataSource:"window.datasrc", field:"name" });                        
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the  allowScrolling, after initialization:
// Get the allowScrolling API value.            
 $("#autocomplete").ejmAutocomplete ("option", "allowScrolling");                       
// Set the allowScrolling API
$("#autocomplete").ejmAutocomplete ("option", "allowScrolling", true);            {% endhighlight %}




### allowSorting<span class="type-signature type boolean">boolean</span>
{:#members:allowsorting}




Specifies the whether allowSorting to be allowed or not in suggestion list on initialization


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the allowSorting property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-allowsorting=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the allowSorting on initialization. 
<input id="autocomplete" />
<script> 
//To set the allowSorting API value 
$("#autocomplete").ejmAutocomplete ({ allowSorting:true, dataSource:"window.datasrc", field:"name" });                  
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the allowSorting, after initialization:
// Get the allowSorting API value.              
 $("#autocomplete").ejmAutocomplete ("option", "allowSorting");                 
// Set the allowSorting API
$("#autocomplete").ejmAutocomplete ("option", "allowSorting", true);            {% endhighlight %}




### caseSensitiveSearch<span class="type-signature type boolean">boolean</span>
{:#members:casesensitivesearch}




Specifies whether to search key is case sensitive or not on initialization.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the caseSensitiveSearch property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-casesensitivesearch=false data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the caseSensitiveSearch on initialization. 
<input id="autocomplete" />
<script> 
//To set the caseSensitiveSearch API value 
$("#autocomplete").ejmAutocomplete ({ caseSensitiveSearch:false, dataSource:"window.datasrc", field:"name" });                  
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the caseSensitiveSearch, after initialization:
// Get the caseSensitiveSearch API value.               
 $("#autocomplete").ejmAutocomplete ("option", "caseSensitiveSearch");                  
// Set the caseSensitiveSearch API
$("#autocomplete").ejmAutocomplete ("option", "caseSensitiveSearch", false);            {% endhighlight %}




### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for AutoComplete theme. This cssClass API helps to use custom skinning option for AutoComplete control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}


{% highlight html %} 
//Set the cssClass property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-cssclass="customclass" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the cssClass on initialization. 
<input id="autocomplete" />
<script> 
//To set the cssClass API value 
$("#autocomplete").ejmAutocomplete ({ cssClass:"customclass", dataSource:"window.datasrc", field:"name" });                     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
$("#autocomplete").ejmAutocomplete ("option", "cssClass");                      
// Set the cssClass API
$("#autocomplete").ejmAutocomplete ("option", "cssClass", "customclass");            {% endhighlight %}




### dataSource<span class="type-signature type data">data</span>
{:#members:datasource}




Specifies the datasource for items.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the dataSource property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the dataSource on initialization. 
<input id="autocomplete" />
<script> 
//To set the dataSource API value 
$("#autocomplete").ejmAutocomplete ({ dataSource:"window.datasrc", field:"name" });                     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the dataSource, after initialization:
// Get the dataSource API value.                
 $("#autocomplete").ejmAutocomplete ("option", "dataSource");                   
// Set the dataSource API
$("#autocomplete").ejmAutocomplete ("option", "dataSource", "window.datasrc");            {% endhighlight %}




### delimiterChar<span class="type-signature type string">string</span>
{:#members:delimiterchar}




Specifies the delimiterChar string for Multivalue mode that separates two items.


Default Value:
{:.param}



* ","




Example
{:.example}


{% highlight html %} 
//Set the delimiterChar property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enablemultiselect="true" data-ej-delimiterchar="," data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the delimiterChar on initialization. 
<input id="autocomplete" />
<script> 
//To set the delimiterChar API value 
$("#autocomplete").ejmAutocomplete ({ enableMultiSelect:true, delimiterChar:",", dataSource:"window.datasrc", field:"name"  });                 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the delimiterChar, after initialization:
// Get the delimiterChar API value.             
 $("#autocomplete").ejmAutocomplete ("option", "delimiterChar");                        
// Set the delimiterChar API
$("#autocomplete").ejmAutocomplete ("option", "delimiterChar", ",");            {% endhighlight %}




### emptyResultText<span class="type-signature type string">string</span>
{:#members:emptyresulttext}




Specifies the text that to be displayed while there is no suggestion for AutoComplete search key


Default Value:
{:.param}



* "No suggestions"




Example
{:.example}


{% highlight html %} 
//Set the emptyResultText property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-emptyresulttext="No suggestions" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the emptyResultText on initialization. 
<input id="autocomplete" />
<script> 
//To set the emptyResultText API value 
$("#autocomplete").ejmAutocomplete ({ emptyResultText:"No suggestions", dataSource:"window.datasrc", field:"name" });                   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the  emptyResultText, after initialization:
// Get the emptyResultText API value.           
 $("#autocomplete").ejmAutocomplete ("option", "emptyResultText");                      
// Set the emptyResultText API
$("#autocomplete").ejmAutocomplete ("option", "emptyResultText", "No suggestions");            {% endhighlight %}




### enableAutoFill<span class="type-signature type boolean">boolean</span>
{:#members:enableautofill}




Specifies whether to auto fill option by which we can select and show up the first search result in textbox on initialization.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableAutoFill property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enableautofill=false data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enableAutoFill on initialization. 
<input id="autocomplete" />
<script> 
//To set the enableAutoFill API value 
$("#autocomplete").ejmAutocomplete ({ enableAutoFill:false, dataSource:"window.datasrc", field:"name" });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enableAutoFill, after initialization:
// Get the enableAutoFill API value.            
 $("#autocomplete").ejmAutocomplete ("option", "enableAutoFill");                       
// Set the enableAutoFill API
$("#autocomplete").ejmAutocomplete ("option", "enableAutoFill", false);            {% endhighlight %}




### enableCheckbox<span class="type-signature type boolean">boolean</span>
{:#members:enablecheckbox}




Specifies whether to show checkbox in suggestion item list in Multivalue mode.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the enableCheckbox property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-multivalue=true data-ej-enablecheckbox=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enableCheckbox on initialization. 
<input id="autocomplete" />
<script> 
//To set the enableCheckbox API value 
$("#autocomplete").ejmAutocomplete ({ enableCheckbox:true, dataSource:"window.datasrc", field:"name" });                        
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the autocomplete enableCheckbox, after initialization:
// Get the enableCheckbox API value.            
 $("#autocomplete").ejmAutocomplete ("option", "enableCheckbox");                       
// Set the enableCheckbox API
$("#autocomplete").ejmAutocomplete ("option", "enableCheckbox", true);            {% endhighlight %}




### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}




Specifies whether to enable the autoComplete on initialization.


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the enabled property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enabled=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enabled on initialization. 
<input id="autocomplete" />
<script> 
//To set the enabled API value 
$("#autocomplete").ejmAutocomplete ({ enabled:true, dataSource:"window.datasrc", field:"name" });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the  enabled, after initialization:
// Get the enabled API value.           
 $("#autocomplete").ejmAutocomplete ("option", "enabled");                      
// Set the enabled API
$("#autocomplete").ejmAutocomplete ("option", "enabled", true);            {% endhighlight %}




### enableDistinct<span class="type-signature type boolean">boolean</span>
{:#members:enabledistinct}




Specifies whether the duplicate results to be shown or not in search results


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableDistinct property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enabledistinct=false data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enableDistinct on initialization. 
<input id="autocomplete" />
<script> 
//To set the enableDistinct API value 
$("#autocomplete").ejmAutocomplete ({ enableDistinct:false, dataSource:"window.datasrc", field:"name" });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enableDistinct, after initialization:
// Get the enableDistinct API value.            
 $("#autocomplete").ejmAutocomplete ("option", "enableDistinct");                       
// Set the enableDistinct API
$("#autocomplete").ejmAutocomplete ("option", "enableDistinct", false);            {% endhighlight %}




### enableMultiSelect<span class="type-signature type boolean">boolean</span>
{:#members:enablemultiselect}




Specifies whether to accept multiple values or not.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enableMultiSelect property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enablemultiselect=false data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enableMultiSelect on initialization. 
<input id="autocomplete" />
<script> 
//To set the enableMultiSelect API value 
$("#autocomplete").ejmAutocomplete ({ enableMultiSelect:false, dataSource:"window.datasrc", field:"name" });                    
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enableMultiSelect, after initialization:
// Get the enableMultiSelect API value.         
 $("#autocomplete").ejmAutocomplete ("option", "enableMultiSelect");                    
// Set the enableMultiSelect API
$("#autocomplete").ejmAutocomplete ("option", "enableMultiSelect", false);            {% endhighlight %}




### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}




Current model value to browser cookies for state maintains. While refresh the Autocomplete control page retains the model value apply from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
//Set the enablePersistence property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-enablepersistence=false data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the enablePersistence on initialization. 
<input id="autocomplete" />
<script> 
//To set the enablePersistence API value 
$("#autocomplete").ejmAutocomplete ({ enablePersistence:false, dataSource:"window.datasrc", field:"name" });                    
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the enablePersistence, after initialization:
// Get the persist API value.           
 $("#autocomplete").ejmAutocomplete ("option", "enablePersistence");                    
// Set the persist API
$("#autocomplete").ejmAutocomplete ("option", "enablePersistence", false);            {% endhighlight %}




### field<span class="type-signature type string">string</span>
{:#members:field}




Specifies the datasource text field that to be queried by search key on initialization.


Default Value:
{:.param}



* "text"




Example
{:.example}


{% highlight html %} 
//Set the field property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the field on initialization. 
<input id="autocomplete" />
<script> 
//To set the field API value 
$("#autocomplete").ejmAutocomplete ({ dataSource:"window.datasrc", field:"name" });                     
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the field, after initialization:
// Get the field API value.             
 $("#autocomplete").ejmAutocomplete ("option", "field");                        
// Set the field API
$("#autocomplete").ejmAutocomplete ("option", "field", "name");            {% endhighlight %}




### filterType<span class="type-signature type enum">enum</span>
{:#members:filtertype}




Specifies the type of the filter by which the filtering occurs.See <a href="global.html#FilterType">FilterType</a>


Default Value:
{:.param}



* contains




Example
{:.example}


{% highlight html %} 
//Set the filterType property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-filtertype="contains" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the filterType on initialization. 
<input id="autocomplete" />
<script> 
//To set the filterType API value 
$("#autocomplete").ejmAutocomplete ({ filterType:"ej.mobile.Autocomplete.FilterType.Contains", dataSource:"window.datasrc", field:"name" });                    
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the filterType, after initialization:
// Get the filterType API value.                
 $("#autocomplete").ejmAutocomplete ("option", "filterType");                   
// Set the filterType API
$("#autocomplete").ejmAutocomplete ("option", "filterType", ej.mobile.Autocomplete.FilterType.Contains);            {% endhighlight %}




### imageClass<span class="type-signature type string">string</span>
{:#members:imageclass}




Specifies the autocomplete image field of the datasource as Class


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the imageClass property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-imageclass="image" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the imageClass on initialization. 
<input id="autocomplete" />
<script> 
//To set the imageClass API value 
$("#autocomplete").ejmAutocomplete ({ imageClass:"image", dataSource:"window.datasrc", field:"name" });                 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the imageClass, after initialization:
// Get the imageClass API value.                
 $("#autocomplete").ejmAutocomplete ("option", "imageClass");                   
// Set the imageClass API
$("#autocomplete").ejmAutocomplete ("option", "imageClass", "image");            {% endhighlight %}




### imageField<span class="type-signature type string">string</span>
{:#members:imagefield}




Specifies the datasource image field as URL.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the imageField property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-imagefield="image" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the imageField on initialization. 
<input id="autocomplete" />
<script> 
//To set the imageField API value 
$("#autocomplete").ejmAutocomplete ({ imageField:"image", dataSource:"window.datasrc", field:"name" });                 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the imageField, after initialization:
// Get the imageField API value.                
 $("#autocomplete").ejmAutocomplete ("option", "imageField");                   
// Set the imageField API
$("#autocomplete").ejmAutocomplete ("option", "imageField", "image");            {% endhighlight %}




### itemsCount<span class="type-signature type number">number</span>
{:#members:itemscount}




Specifies the number of items shown in the suggestion list.


Default Value:
{:.param}



* 5




Example
{:.example}


{% highlight html %} 
//Set the itemsCount property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-itemscount=5 data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the itemsCount on initialization. 
<input id="autocomplete" />
<script> 
//To set the itemsCount API value 
$("#autocomplete").ejmAutocomplete ({ itemsCount:5, dataSource:"window.datasrc", field:"name" });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the itemsCount, after initialization:
// Get the itemsCount API value.                
 $("#autocomplete").ejmAutocomplete ("option", "itemsCount");                   
// Set the itemsCount API
$("#autocomplete").ejmAutocomplete ("option", "itemsCount", 5);            {% endhighlight %}




### mapper<span class="type-signature type string">string</span>
{:#members:mapper}




Specifies the remote url that to be used as a datasource for autocomplete


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the mapper property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-mapper="http://mvc.syncfusion.com/Services/Northwnd.svc/Suppliers" data-ej-datasource="window.datasrc" data-ej-field="ContactName" />
{% endhighlight %}


{% highlight html %} 
// Set the mapper on initialization. 
<input id="autocomplete" />
<script> 
//To set the mapper API value 
$("#autocomplete").ejmAutocomplete ({ mapper: "http://mvc.syncfusion.com/Services/Northwnd.svc/Suppliers", dataSource:"window.datasrc", field:"ContactName" });                 
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the mapper, after initialization:
// Get the mapper API value.            
 $("#autocomplete").ejmAutocomplete ("option", "mapper");                       
// Set the mapper API
$("#autocomplete").ejmAutocomplete ("option", "mapper", "http://mvc.syncfusion.com/Services/Northwnd.svc/Suppliers");            {% endhighlight %}




### minCharacter<span class="type-signature type number">number</span>
{:#members:mincharacter}




Specifies the minimum search key length after which only autocomplete querying the datasource


Default Value:
{:.param}



* 1




Example
{:.example}


{% highlight html %} 
//Set the minCharacter property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-mincharacter=1 data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the minCharacter on initialization. 
<input id="autocomplete" />
<script> 
//To set the minCharacter API value 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",minCharacter:2 });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the minCharacter, after initialization:
// Get the minCharacter API value.              
 $("#autocomplete").ejmAutocomplete ("option", "minCharacter");                 
// Set the minCharacter API
$("#autocomplete").ejmAutocomplete ("option", "minCharacter", 1);            {% endhighlight %}




### mode<span class="type-signature type enum">enum</span>
{:#members:mode}




Specifies the AutoComplete mode. See <a href="global.html#Mode">Mode</a>


Default Value:
{:.param}



* default




Example
{:.example}


{% highlight html %} 
//Set the mode property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-mode="default" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the mode on initialization. 
<input id="autocomplete" />
<script> 
//To set the mode API value 
$("#autocomplete").ejmAutocomplete ({ mode:ej.mobile.Autocomplete.Mode.Default, dataSource:"window.datasrc", field:"name" });                   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the mode, after initialization:
// Get the mode API value.              
 $("#autocomplete").ejmAutocomplete ("option", "mode");                 
// Set the mode API
$("#autocomplete").ejmAutocomplete ("option", "mode", ej.mobile.Autocomplete.Mode.Default);            {% endhighlight %}




### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Changes the rendering mode of the autocomplete . See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}


{% highlight html %} 
//Set the renderMode property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-rendermode="auto" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the renderMode on initialization. 
<input id="autocomplete" />
<script> 
//To set the renderMode API value 
$("#autocomplete").ejmAutocomplete ({ renderMode: ej.mobile.RenderMode.Auto, dataSource:"window.datasrc", field:"name" });                      
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the  renderMode, after initialization:
// Get the renderMode API value.                
 $("#autocomplete").ejmAutocomplete ("option", "renderMode");                   
// Set the renderMode API
$("#autocomplete").ejmAutocomplete ("option", "renderMode", ej.mobile.RenderMode.Auto);            {% endhighlight %}




### showEmptyResultText<span class="type-signature type boolean">boolean</span>
{:#members:showemptyresulttext}




Specifies the search result to be shown or not while there is no suggestion for AutoComplete search key


Default Value:
{:.param}



* true




Example
{:.example}


{% highlight html %} 
//Set the showEmptyResultText property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-showemptyresulttext=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the showEmptyResultText on initialization. 
<input id="autocomplete" />
<script> 
//To set the showEmptyResultText API value 
$("#autocomplete").ejmAutocomplete ({ showEmptyResultText:true, dataSource:"window.datasrc", field:"name" });                   
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the showEmptyResultText, after initialization:
// Get the showEmptyResultText API value.               
 $("#autocomplete").ejmAutocomplete ("option", "showEmptyResultText");                  
// Set the showEmptyResultText API
$("#autocomplete").ejmAutocomplete ("option", "showEmptyResultText", true);            {% endhighlight %}




### sortOrder<span class="type-signature type enum">enum</span>
{:#members:sortorder}




Specifies the suggestion list sorting order. See <a href="global.html#SortOrder">SortOrder</a>


Default Value:
{:.param}



* ascending




Example
{:.example}


{% highlight html %} 
//Set the sortOrder property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-sortorder="ascending" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the sortOrder on initialization. 
<input id="autocomplete" />
<script> 
//To set the sortOrder API value 
$("#autocomplete").ejmAutocomplete ({ sortOrder:ej.mobile.SortOrder.Ascending, dataSource:"window.datasrc", field:"name" });                    
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the sortOrder, after initialization:
// Get the sortOrder API value.         
 $("#autocomplete").ejmAutocomplete ("option", "sortOrder");                    
// Set the sortOrder API
$("#autocomplete").ejmAutocomplete ("option", "sortOrder", ej.mobile.SortOrder.Ascending);            {% endhighlight %}




### templateId<span class="type-signature type string">string</span>
{:#members:templateid}




Specifies the template id for items.


Default Value:
{:.param}



* null




Example
{:.example}


{% highlight html %} 
//Set the templateId property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-templateId="template" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the templateId on initialization. 
<input id="autocomplete" />
<script> 
//To set the templateId API value 
$("#autocomplete").ejmAutocomplete ({ templateId:"template", dataSource:"window.datasrc", field:"name" });                      
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the templateId, after initialization:
// Get the templateId API value.                
 $("#autocomplete").ejmAutocomplete ("option", "templateId");                   
// Set the templateId API
$("#autocomplete").ejmAutocomplete ("option", "templateId", "template");            {% endhighlight %}




### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Changes the theme of the autocomplete . See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}


{% highlight html %} 
//Set the theme property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-theme="auto" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the theme on initialization. 
<input id="autocomplete" />
<script> 
//To set the theme API value 
$("#autocomplete").ejmAutocomplete ({ theme: ej.mobile.Theme.Auto, dataSource:"window.datasrc", field:"name" });                        
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the autocomplete theme, after initialization:
// Get the theme API value.             
 $("#autocomplete").ejmAutocomplete ("option", "theme");                        
// Set the theme API
$("#autocomplete").ejmAutocomplete ("option", "theme", ej.mobile.Theme.Auto);            {% endhighlight %}




### value<span class="type-signature type string">string</span>
{:#members:value}




Specifies the textbox value on initialization


Default Value:
{:.param}



* ""




Example
{:.example}


{% highlight html %} 
//Set the value property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-value="Text" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the value on initialization. 
<input id="autocomplete" />
<script> 
//To set the value API value 
$("#autocomplete").ejmAutocomplete ({ value:"Text", dataSource:"window.datasrc", field:"name" });                       
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the value, after initialization:
// Get the value API value.             
 $("#autocomplete").ejmAutocomplete ("option", "value");                        
// Set the value API
$("#autocomplete").ejmAutocomplete ("option", "value", "Text");            {% endhighlight %}




### watermarkText<span class="type-signature type string">string</span>
{:#members:watermarktext}




Specifies the autocomplete watermark text that to be shown on autocomplete text box when it is empty


Default Value:
{:.param}



* "Search"




Example
{:.example}


{% highlight html %} 
//Set the watermarkText property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-watermarktext="Search" data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// Set the watermarkText on initialization. 
<input id="autocomplete" />
<script> 
//To set the watermarkText API value 
$("#autocomplete").ejmAutocomplete ({ watermarkText: "Search", dataSource:"window.datasrc", field:"name" });                    
</script>{% endhighlight %}


{% highlight html %} 
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.             
 $("#autocomplete").ejmAutocomplete ("option", "watermarkText");                        
// Set the watermarkText API
$("#autocomplete").ejmAutocomplete ("option", "watermarkText", "Search");            {% endhighlight %}




### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}




Specifies whether to render the autocomplete based on the windowsphone's current accent color and device theme


Default Value:
{:.param}



* false




Example
{:.example}


{% highlight html %} 
// Set the windows mode renderDefault property in unobtrusive way.
<input id="autocomplete" data-role="ejmautocomplete" data-ej-rendermode="windows" data-ej-windows-renderdefault=true data-ej-datasource="window.datasrc" data-ej-field="name" />
{% endhighlight %}


{% highlight html %} 
// To set the windows mode renderDefault property API value 
<input id="autocomplete" />
<script> 
//To set the windows mode renderDefault API value 
$("#autocomplete").ejmAutocomplete({renderMode:"windows", windows:{ renderDefault: true }, dataSource:"window.datasrc", field:"name" });   
</script>{% endhighlight %}


{% highlight html %} 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
$("#autocomplete").ejmAutocomplete("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#autocomplete").ejmAutocomplete("option", "renderMode", "windows"); 
$("#autocomplete").ejmAutocomplete("option", "windows.renderDefault", true); {% endhighlight %}



## Methods




### clearText<span class="signature">()</span>
{:#methods:cleartext}




Clears the selected items in AutoComplete



Example
{:.example}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Create the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
var auto = $("#autocomplete").data("ejmAutocomplete");
auto.clearText(); // Get the value of autocomplete
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Clears text of autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
$("#autocomplete").ejmAutocomplete("clearText");
});
</script>{% endhighlight %}




### disable<span class="signature">()</span>
{:#methods:disable}




To disable AutoComplete



Example
{:.example}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Create the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
var auto = $("#autocomplete").data("ejmAutocomplete");
auto.disable(); // Disables the autocomplete
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Disable autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
$("#autocomplete").ejmAutocomplete("disable");
});
</script>{% endhighlight %}




### enable<span class="signature">()</span>
{:#methods:enable}




To enable AutoComplete



Example
{:.example}


{% highlight html %} 
<input id="autocomplete"/>
<script>
$(function(){
// Create the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
var auto = $("#autocomplete").data("ejmAutocomplete");
auto.enable(); // Enables the autocomplete
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="autocomplete"/>
<script>
$(function(){
// Enable the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
$("#autocomplete").ejmAutocomplete("enable");
});
</script>{% endhighlight %}




### getSelectedItems<span class="signature">()</span>
{:#methods:getselecteditems}




To get the list of items selected in AutoComplete



Example
{:.example}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Create the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
var auto = $("#autocomplete").data("ejmAutocomplete");
auto.getSelectedItems(); // Get the value of autocomplete
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// GetSelectedItems of  autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
$("#autocomplete").ejmAutocomplete("getSelectedItems");
});
</script>{% endhighlight %}




### getValue<span class="signature">()</span>
{:#methods:getvalue}




To get the value of AutoComplete



Example
{:.example}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Create the autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
var auto = $("#autocomplete").data("ejmAutocomplete");
auto.getValue(); // Get the value of autocomplete
});
</script>{% endhighlight %}


{% highlight html %} 
<input id="autocomplete" />
<script>
$(function(){
// Getvalue of  autocomplete
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name" });
$("#autocomplete").ejmAutocomplete("getValue");
});
</script>{% endhighlight %}



## Events




### change
{:#events:change}




Event triggers when the AutoComplete text box content changed.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}currentText{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns whether the current item is checked or not</td>
</tr>
<tr>
<td class="name">{% highlight html %}checkedItemsText{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns all checked item's text</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-change="onChange" />
<script> 
// change event for autocomplete  
function onChange(args){ 
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//change event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  change: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}




### focusIn
{:#events:focusin}




Event triggers when focused in to the Autocomplete text box

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-focusin="onfocusIn" />
<script> 
// focusIn event for autocomplete  
function onfocusIn(args){ 
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//focusIn event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  focusIn: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}




### focusOut
{:#events:focusout}




Event triggers when focused out from the Autocomplete text box

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-focusout="onfocusOut" />
<script> 
// focusOut event for autocomplete  
function onfocusOut(args){ 
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//focusOut event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  focusOut: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}




### keyPress
{:#events:keypress}




Event triggers when pressed a key

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-keypress="onkeyPress" />
<script> 
// keyPress event for autocomplete  
function onkeyPress(args){ 
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//keyPress event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  keyPress: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}




### select
{:#events:select}




Event triggers when we select a element from AutoComplete suggestion list.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}currentText{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns whether the current item is checked or not</td>
</tr>
<tr>
<td class="name">{% highlight html %}checkedItemsText{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns all checked item's text</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-select="onSelect" />
<script> 
// select event for autocomplete  
function onSelect(args){ 
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//select event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  select: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}




### touchEnd
{:#events:touchend}




Event triggers when the touch end happens in the AutoComplete suggestion list.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}argument{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from autocomplete
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">{% highlight html %}cancel{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">{% highlight html %}model{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the autocomplete model</td>
</tr>
<tr>
<td class="name">{% highlight html %}type{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name">{% highlight html %}element{% endhighlight %}</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name">{% highlight html %}currentText{% endhighlight %}</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the current item text</td>
</tr>
<tr>
<td class="name">{% highlight html %}isChecked{% endhighlight %}</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">returns whether the current item is checked or not</td>
</tr>
<tr>
<td class="name">{% highlight html %}checkedItemsText{% endhighlight %}</td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns all checked item's text</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>


Example
{:.example}


{% highlight html %} 
<input id="autocomplete" data-role="ejmautocomplete" data-ej-datasource="window.datasrc" data-ej-field="name" data-ej-touchend="onTouchEnd" />
<script> 
// touchEnd event for autocomplete  
function onTouchEnd(args){
//handle the event
}
</script>{% endhighlight %}


{% highlight html %} 
//touchEnd event for autocomplete
<input id="autocomplete" />
<script> 
$("#autocomplete").ejmAutocomplete({ dataSource:"window.datasrc", field:"name",
  touchEnd: function (args) { 
//handle the event 
}
});           
</script>{% endhighlight %}



