---
layout: post
title: ejmGrid
documentation: API
platform: js
metaname: 
metacontent: 
---

The grid can be easily configured to the DOM element, such as div. you can create a grid with a highly customizable look and feel.










$(element).ejmGrid<span class="signature">(options)</span>







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
<td class="name"><code>options</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">settings for grid</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script> 
// Create Grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));   
$("#mobilegrid").ejmGrid({ dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 }); 
</script></code>
</pre>






Requires
{:.require}




* module:jQuery


* module:jsrender


* module:jquery.globalize


* module:ej.mobile.application


* module:ej.core


* module:ej.unobtrusive


* module:ej.mobile.core


* module:ej.data


* module:ej.touch


* module:ej.mobile.scrollbar


* module:ej.mobile.scrollpanel


* module:ej.mobile.header


* module:ej.mobile.button


* module:ej.mobile.dialog


* module:ej.mobile.listbox


* module:ej.mobile.checkbox




## Members








### allowFiltering<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the filtering for the columns . It helps to filter the desired records in Grid columns.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ allowFiltering: false,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                                </code>
</pre>






### allowPaging<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the Grid pager feature




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>  
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));                   
$("#mobilegrid").ejmGrid ({ allowPaging: true,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });                
</script>                                         </code>
</pre>






### allowScrolling<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the scrolling feature in Grid.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ allowScrolling: false,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>            </code>
</pre>






### allowSelection<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the grid row selection.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ allowSelection: false,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                                 </code>
</pre>






### allowSorting<span class="type-signature type boolean">boolean</span>








Enable or disable the sorting behavior for the Grid and we can able to sort the Grid columns in Ascending or Decending Order.





Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ allowSorting: false,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });
</script>                                </code>
</pre>






### caption<span class="type-signature type string">string</span>








Set the caption for the grid




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ caption: "caption", showCaption: true,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                             </code>
</pre>






### columns<span class="type-signature type array">array</span>








It is used to define which columns can be bound to grid




Default Value:
{:.param}






* []








Example
{:.example}

<pre class="prettyprint">
<code><div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejGrid({ dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });                   
</script> </code>
</pre>






### cssClass<span class="type-signature type string">string</span>








Specifies the CSS class to grid to achieve custom theme.




Default Value:
{:.param}






* ""








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script> 
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ cssClass: "Customclass",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                                       </code>
</pre>






### dataSource<span class="type-signature type data">data</span>








Specifies the data source for the grid




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                                 </code>
</pre>






### enablePersistence<span class="type-signature type boolean">boolean</span>








Specifies whether to enable the state maintenance in grid.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ enablePersistence: false,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                     </code>
</pre>






### filterSettings








This property is used to customize the filtering behavior of the grid.











### filterSettings.filterBarMode<span class="type-signature type enum">enum</span>








Set the filter bar mode option in the grid. Accepted filterBarModes are "immediate" and "onenter". See <a href="global.html#FilterBarMode">FilterBarMode</a>




Default Value:
{:.param}






* ej.mobile.Grid.FilterBarMode.OnEnter








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowFiltering:true,
                filterSettings: { filterBarMode: ej.mobile.Grid.FilterBarMode.OnEnter },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });           
</script>                                        </code>
</pre>






### filterSettings.filteredColumns<span class="type-signature type object">object</span>








Get filtered columns details programmatically after filtering.




Default Value:
{:.param}






* []








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowFiltering:true,
                filterSettings: { interval: 1500 },filteredColumns:[],dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });            
</script></code>
</pre>






### filterSettings.interval<span class="type-signature type number">number</span>








Specifies the filter interval (in milliseconds) when filterbar mode is set to Immediate.




Default Value:
{:.param}






* 1500








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowFiltering:true,
                filterSettings: { interval: 1500 },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });            
</script>                                        </code>
</pre>






### pageSettings








This property is used to modify pager default configuration.











### pageSettings.currentPage<span class="type-signature type number">number</span>








This is used to define which page to display currently.




Default Value:
{:.param}






* 1








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowPaging:true,
                pageSettings: { currentPage: 1 },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });               
</script>                                 </code>
</pre>






### pageSettings.display<span class="type-signature type enum">enum</span>








Used to define the pager position which can be fixed or normal. See <a href="global.html#PagerDisplay">PagerDisplay</a>




Default Value:
{:.param}






* ej.mobile.Grid.PagerDisplay.Normal








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowPaging:true,
                pageSettings: { display: ej.mobile.Grid.PagerDisplay.Normal },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });              
</script>                                        </code>
</pre>






### pageSettings.pageSize<span class="type-signature type number">number</span>








This is used to define the number of records displayed per page.




Default Value:
{:.param}






* 5








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowPaging:true,
                pageSettings:{ pageSize: 5 },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });               
</script>                                 </code>
</pre>






### pageSettings.totalRecordsCount<span class="type-signature type number">number</span>








It holds the total records count available in the grid.




Default Value:
{:.param}






* null








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
$("#mobilegrid").ejmGrid({
    dataSource:  window.gridData,
    allowPaging: true
});
});
var value = $("#mobilegrid").ejmGrid("option", "pageSettings.totalRecordsCount");
$("#print").text("TotalRecordsCount: " + value);             
</script>                                        </code>
</pre>






### pageSettings.type<span class="type-signature type enum">enum</span>








Used to define the pager type which can be scrollable or normal. See <a href="global.html#PagerType">PagerType</a>




Default Value:
{:.param}






* ej.mobile.Grid.PagerType.Scrollable








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowPaging:true,
                pageSettings:{ type: ej.mobile.Grid.PagerType.Scrollable },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });              
</script>                                         </code>
</pre>






### renderMode<span class="type-signature type enum">enum</span>








Changes the rendering mode of the grid. It can be auto, ios7, android, windows or flat. See <a href="global.html#RenderMode">RenderMode</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ renderMode: ej.mobile.RenderMode.Auto,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script> </code>
</pre>






### scrollSettings








Used to enable grid column and row scrolling











### scrollSettings.enableColumnScrolling<span class="type-signature type boolean">boolean</span>








Used to enable or disable column scrolling.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowScrolling:true,
                scrollSettings:{ enableColumnScrolling: false },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });             
</script>                                  </code>
</pre>






### scrollSettings.enableNativeScrolling<span class="type-signature type boolean">boolean</span>








Used to enable or disable native scrolling.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script> 
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowScrolling:true,
                scrollSettings: { enableNativeScrolling: true },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });               
</script>                                </code>
</pre>






### scrollSettings.enableRowScrolling<span class="type-signature type boolean">boolean</span>








Used to enable or disable row scrolling.




Default Value:
{:.param}






* true








Example
{:.example}

<pre class="prettyprint">
<code>  
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowScrolling:true,
                scrollSettings: { enableRowScrolling: true },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });               
</script>                                          </code>
</pre>






### scrollSettings.height<span class="type-signature type string">string</span>








Specifies the height for the Grid content.




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowScrolling:true,
                scrollSettings: { height: "auto" },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });             
</script>                                 </code>
</pre>






### scrollSettings.width<span class="type-signature type string">string</span>








Specifies the width for the Grid content.




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowScrolling:true,
                scrollSettings: { width: "auto" },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });               
</script>                                         </code>
</pre>






### selectedRowIndex<span class="type-signature type number">number</span>








To apply row selection based on your row index value.




Default Value:
{:.param}






* -1








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
// Set grid selectedRowIndex on initialization. 
//To set selectedRowIndex API value 
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ selectedRowIndex: 1,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                                       </code>
</pre>






### sortSettings








This property is used to modify sorting default configuration.











### sortSettings.allowMultiSorting<span class="type-signature type boolean">boolean</span>








Enable or disable the multi sorting behavior of grid.




Default Value:
{:.param}






* false








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowSorting: true,
                sortSettings: { allowMultiSorting: false },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });   
                 });              
</script>                                          </code>
</pre>






### sortSettings.sortedColumns<span class="type-signature type object">object</span>








To define which column can be sorted and also to define the sort direction




Default Value:
{:.param}






* []








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ 
                allowSorting: true,
                sortSettings: { sortedColumns:[] },dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });  
                 });             
</script>                                          </code>
</pre>






### theme<span class="type-signature type enum">enum</span>








Specifies the theme of the Grid. See <a href="global.html#Theme">Theme</a>




Default Value:
{:.param}






* auto








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ theme: ej.mobile.Theme.Auto,dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });    
</script>                               </code>
</pre>






### transition<span class="type-signature type string">string</span>








Specifies the transition type when navigation happens while interacting with grid.




Default Value:
{:.param}






* For Android, "pop". For Windows, "turn". For IOS, "slide".








Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
// Set grid transition on initialization. 
//To set transition API value 
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid ({ transition: "slide",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });
</script>                              </code>
</pre>




## Methods








### getColumnByField<span class="signature">()</span>








To get column by field





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Create grid object.
var gridObj = $("#mobilegrid").data("ejGrid");
gridObj.getColumnByField("OrderID"); // Get the column details based on the given field name
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Get the column details based on the given field name
$("#mobilegrid").ejGrid("getColumnByField", "OrderID");        
</script></code>
</pre>






### getColumnByHeaderText<span class="signature">()</span>








To get column by header text





Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>  
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.getColumnByHeaderText("Order ID"); // Get column by header text
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>  
<script>
// Get column by header text
$("#mobilegrid").ejmGrid("getColumnByHeaderText", "Order ID");  
</script></code>
</pre>






### getColumnByIndex<span class="signature">()</span>








To get column by index





Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>        
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.getColumnByIndex(1); // Get column by index
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>  
<script>
// Get column by index
$("#mobilegrid").ejmGrid("getColumnByIndex",1); 
</script></code>
</pre>






### getColumnFieldNames<span class="signature">()</span>








To get column field names





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.getColumnFieldNames(); // Get column field names
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Get column field names
$("#mobilegrid").ejmGrid("getColumnFieldNames");        
</script></code>
</pre>






### getColumnIndexByField<span class="signature">()</span>








To get column index by field





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.getColumnIndexByField("OrderID"); // Get column index by field
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Get column index by field
$("#mobilegrid").ejmGrid("getColumnIndexByField","OrderID");    
</script></code>
</pre>






### getColumnMemberByIndex<span class="signature">()</span>








To get column member by index





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.getColumnMemberByIndex(1); // Get column member by index
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Get column member by index
$("#mobilegrid").ejmGrid("getColumnMemberByIndex",1);   
</script></code>
</pre>






### hideColumns<span class="signature">()</span>








To hide the specified column





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.hideColumns("Order ID"); // Hides column based on the given header text of the column
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Hides column based on the given header text of the column
$("#mobilegrid").ejmGrid("hideColumns","Order ID"); 
</script></code>
</pre>






### refreshContent<span class="signature">()</span>








It is used to refresh the grid contents

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
<td class="name"><code>[requestType].</code></td>
<td class="type"><span class="param-type">enum</span></td>
<td class="description last">The request type can be refresh, paging, sorting, filtering. If no parameter is passed, the request type will be refresh</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.refreshContent(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
$("#mobilegrid").ejmGrid("refreshContent");     
</script></code>
</pre>






### scrollRefresh<span class="signature">()</span>








To refersh grid scrollpanel





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.scrollRefresh(); // To Refresh grid scrollpanel
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div> 
<script>
// To Refresh grid scrollpanel
$("#mobilegrid").ejmGrid("scrollRefresh"); 
</script></code>
</pre>






### showColumns<span class="signature">()</span>








To show the specified column





Example
{:.example}

<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Create Grid
var grid = $("#mobilegrid").data("ejmGrid");
grid.showColumns("Order ID"); // Shows column based on the given header text of the column
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<div id="mobilegrid"></div>
<script>
// Shows column based on the given header text of the column
$("#mobilegrid").ejmGrid("showColumns","Order ID");     
</script></code>
</pre>




## Events








### actionBegin








Triggered for every grid action before its starts.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>requestType</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Returns request type</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//actionBegin event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ actionBegin:"actionBegin",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });            
function actionBegin(args) { //handle the event }                       
</script>                 </code>
</pre>






### actionComplete








Event triggers when grid data loading action succeeds.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>requestType</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Returns request type</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//actionComplete event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ actionComplete:"actionComplete",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });
function actionComplete(args) { //handle the event }            
</script>                 </code>
</pre>






### actionFailure








Event triggers when grid data loading action fails.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>requestType</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Returns request type</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ actionFailure:"actionFailure",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });
function actionFailure(args) { //handle the event }            
</script>                 </code>
</pre>






### actionSuccess








Triggered for every grid action success.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>requestType</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Returns request type</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//actionSuccess event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ actionSuccess:"actionSuccess",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });
function actionSuccess(args) { //handle the event }          
</script>                 </code>
</pre>






### load








Triggered for every grid load.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>requestType</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Returns request type</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ load:"load",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });
function load(args) { //handle the event }            
</script>                 </code>
</pre>






### modelChange








Triggered every time while a model value changed.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current grid row</td>
</tr>
<tr>
<td class="name"><code>options</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the changed model values</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//modelChange event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ modelChange:"modelChange",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 }); 
function modelChange(args) { //handle the event }            
</script>                 </code>
</pre>






### queryCellInfo








Triggered every time a request is made to access particular cell information, element and data.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current cell</td>
</tr>
<tr>
<td class="name"><code>data</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current data</td>
</tr>
<tr>
<td class="name"><code>text</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current cell Html content</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//queryCellInfo event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ queryCellInfo:"queryCellInfo",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] }); 
                 });
function queryCellInfo(args) { //handle the event }   
</script>                         </code>
</pre>






### rowDataBound








Triggered every time a request is made to access row information, element and data.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current grid row</td>
</tr>
<tr>
<td class="name"><code>data</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current data</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
//rowDataBound event for grid
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ rowDataBound:"rowDataBound",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 }); 
function rowDataBound(args) { //handle the event }              
</script>                         </code>
</pre>






### rowSelected








Triggered after the row is selected.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>rowIndex</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current row index</td>
</tr>
<tr>
<td class="name"><code>row</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current row</td>
</tr>
<tr>
<td class="name"><code>cell</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current data cell</td>
</tr>
<tr>
<td class="name"><code>data</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current data record</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));
$("#mobilegrid").ejmGrid({ rowSelected:"rowSelected",dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ] });
                 });                     
function rowSelected(args) { //handle the event }
</script>                 </code>
</pre>






### rowSelecting








Triggered before the row is going to be selected.

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
<td class="name"><code>argument</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">Event parameters from grid
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
<td class="name"><code>cancel</code></td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description last">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name"><code>model</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the grid model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>rowIndex</code></td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">returns the current row index</td>
</tr>
<tr>
<td class="name"><code>row</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current row</td>
</tr>
<tr>
<td class="name"><code>cell</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current data cell</td>
</tr>
<tr>
<td class="name"><code>data</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current data record</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




Example
{:.example}

<pre class="prettyprint">
<code> 
<div  id="mobilegrid" ></div>
<script>       
$(document).ready(function(){
var data = ej.DataManager(window.gridData).executeLocal(ej.Query().take(50));                   
$("#mobilegrid").ejmGrid ({ dataSource:data,columns: [
                         { field: "OrderID", headerText: "Order ID" },
                         { field: "CustomerID", headerText: "Customer ID" },
                         { field: "Freight", headerText: "Freight" }
                 ],rowSelecting:"rowSelecting" });
                 });    
function rowSelecting(args) { //handle the event }      
</script>                         </code>
</pre>



