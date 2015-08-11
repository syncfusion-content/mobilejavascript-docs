---
layout: post
title: ejmTextBox
documentation: API
platform: mobilejs
metaname: 
metacontent: 
---

# Custom Design for Html TextBox control.





$(element).ejmTextBox<span class="signature">()</span>






Example
{:.example}

<pre class="prettyprint">
<code>//To create the textbox 
<input id="textbox" />
<script> 
//Create the textbox  
$("#textbox").ejmTextBox(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox" data-role="ejmtextbox" />
</code>
</pre>
<pre class="prettyprint">
<code> 
//To create the password
<input id="password" />
<script> 
//Create the password  
$("#password").ejmPassword(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password" data-role="ejmpassword" />
</code>
</pre>
<pre class="prettyprint">
<code> 
//To create the maskedit
<input id="maskedit" />
<script> 
//Create the maskedit  
$("#maskedit").ejmMaskEdit(); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit" data-role="ejmmaskedit" />
</code>
</pre>
<pre class="prettyprint">
<code> 
//To create the textarea
<textarea id="textarea" ></textarea>
<script> 
//Create the textarea  
$("#textarea").ejmTextArea();
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea" data-role="ejmtextarea" ></textarea>
</code>
</pre>



Requires
{:.require}


* module:jQuery

* module:ej.mobile.application

* module:ej.core

* module:ej.unobtrusive

* module:ej.mobile.core

* module:ej.data

* module:ej.touch


## Members




### cssClass<span class="type-signature type string">string</span>
{:#members:cssclass}




Sets the root class for Textbox theme. This cssClass API helps to use custom skinning option for Textbox control. By defining the root class using this API, we need to include this root class in CSS.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code>// For TextBox 
//Set the cssClass property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-cssclass="customclass" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the cssClass on initialization. 
//To set the cssClass API value 
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ value: "" });               
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the TextBox cssClass, after initialization:
// Get the cssClass API value.          
<script>
 $("#textbox").ejmTextBox ("option", "cssClass");                       
// Set the value API
$("#textbox").ejmTextBox ("option", "cssClass", "customclass");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the cssClass property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-cssclass="customclass" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set Password cssClass on initialization. 
//To set the value API value 
<input id="password"/>
<script>
$("#password").ejmPassword ({ cssClass: "customclass" });       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Password cssClass, after initialization:
// Get the cssClass API value.          
<script>
 $("#password").ejmPassword ("option", "cssClass");                     
// Set the cssClass API
$("#password").ejmPassword ("option", "cssClass", "customclass");
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the cssClass property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-cssclass="customclass" data-ej-mask="+1 (999) 999-9999"/>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the cssClass on initialization. 
//To set the cssClass API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ cssClass: "customclass",mask:"+1 (999) 999-9999" });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
<script>
 $("#maskedit").ejmMaskEdit ("option", "cssClass");                     
// Set the cssClass API
$("#maskedit").ejmMaskEdit ("option", "cssClass", "customclass");
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the cssClass property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-cssclass="customclass" ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the cssClass on initialization. 
//To set the cssClass API value 
<textarea id="textarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ cssClass: "customclass" });               
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the cssClass, after initialization:
// Get the cssClass API value.          
<script>
$("#textarea").ejmTextArea ("option", "cssClass");                      
// Set the cssClass API
$("#textarea").ejmTextArea ("option", "cssClass", "customclass");    
</script></code>
</pre>



### enabled<span class="type-signature type boolean">boolean</span>
{:#members:enabled}




Specifies whether to be enable on initialization.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code> 
// For TextBox
//Set the enabled property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-enabled=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enabled on initialization. 
//To set the enabled API value
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ enabled: true });           
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  enabled, after initialization:
// Get the enabled API value.           
<script>
 $("#textbox").ejmTextBox ("option", "enabled");                        
// Set the enabled API
$("#textbox").ejmTextBox ("option", "enabled", true);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the enabled property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-enabled=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enabled on initialization. 
//To set enabled API value 
<input id="password" />
<script>
$("#password").ejmPassword ({ enabled: true });         
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
<script>
 $("#password").ejmPassword ("option", "enabled");                      
// Set the enabled API
$("#password").ejmPassword ("option", "enabled", true);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the enabled property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-enabled=true data-ej-mask="+1 (999) 999-9999"  />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enabled on initialization. 
//To set the enabled API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ enabled: true,mask:"+1 (999) 999-9999" });        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
<script>
 $("#maskedit").ejmMaskEdit ("option", "enabled");                      
// Set the enabled API
$("#maskedit").ejmMaskEdit ("option", "enabled", true); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For textarea
//Set the enabled property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-enabled=true ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enabled on initialization. 
//To set the enabled API value 
<textarea id="textarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ enabled: true });                 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enabled, after initialization:
// Get the enabled API value.           
<script>
 $("#textarea").ejmTextArea ("option", "enabled");                      
// Set the enabled API
$("#textarea").ejmTextArea ("option", "enabled", true);  
</script></code>
</pre>



### enablePersistence<span class="type-signature type boolean">boolean</span>
{:#members:enablepersistence}




Specifies to maintain the current model value to browser cookies for state maintenance. While refresh the page, the model value will get apply to the control from browser cookies.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
// For TextBox
//Set the enablePersistence property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-enablepersistence=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
//To set the enablePersistence API value 
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ enablePersistence: false });        
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value. 
<script>
 $("#textbox").ejmTextBox ("option", "enablePersistence");                      
// Set the enablePersistence API
$("#textbox").ejmTextBox ("option", "enablePersistence", false);  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the enablePersistence property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-enablepersistence=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
//To set the enablePersistence API value 
<input id="password"/>
<script>
$("#password").ejmPassword ({ enablePersistence: false });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
<script>
 $("#password").ejmPassword ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#password").ejmPassword ("option", "enablePersistence", false);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the enablePersistence property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-enablepersistence=false data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
//To set the enablePersistence API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ enablePersistence: false,mask:"+1 (999) 999-9999" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
<script>
 $("#maskedit").ejmMaskEdit ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#maskedit").ejmMaskEdit ("option", "enablePersistence", false);  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the enablePersistence property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-enablepersistence=false ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the enablePersistence on initialization. 
//To set the enablePersistence API value 
<textarea id="textarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ enablePersistence: false });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the enablePersistence, after initialization:
// Get the enablePersistence API value.         
<script>
 $("#textarea").ejmTextArea ("option", "enablePersistence");                    
// Set the enablePersistence API
$("#textarea").ejmTextArea ("option", "enablePersistence", false); 
</script></code>
</pre>



### readOnly<span class="type-signature type boolean">boolean</span>
{:#members:readonly}




Specifies the TextBox, Password, Mask Edit, and Textarea readOnly.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
// For TextBox
//Set the readOnly property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-readonly=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the readOnly on initialization. 
//To set the readOnly API value
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ readOnly: false });         
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the readOnly, after initialization:
// Get the readOnly API value.          
<script>
 $("#textbox").ejmTextBox ("option", "readOnly");                       
// Set the readOnly API
$("#textbox").ejmTextBox ("option", "readOnly", false);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the readOnly property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-readonly=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the readOnly on initialization. 
//To set readOnly API value 
<input id="password"/>
<script>
$("#password").ejmPassword ({ readOnly: false });               
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  readOnly, after initialization:
// Get the readOnly API value.          
<script>
 $("#password").ejmPassword ("option", "readOnly");                     
// Set the readOnly API
$("#password").ejmPassword ("option", "readOnly", false);  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the readOnly property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-readonly=false data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the readOnly on initialization. 
//To set the readOnly API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ readOnly: false,mask:"+1 (999) 999-9999" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the readOnly, after initialization:
// Get the readOnly API value.          
<script>
 $("#maskedit").ejmMaskEdit ("option", "readOnly");                     
// Set the readOnly API
$("#maskedit").ejmMaskEdit ("option", "readOnly", false);   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the readOnly property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-readonly=false ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the readOnly on initialization. 
//To set the readOnly API value 
<textarea id="textarea"> </textarea>
<script>
$("#textarea").ejmTextArea ({ readOnly: false });                       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the readOnly, after initialization:
// Get the readOnly API value.          
<script>
 $("#textarea").ejmTextArea ("option", "readOnly");                     
// Set the readOnly API
$("#textarea").ejmTextArea ("option", "readOnly", false);          
</script></code>
</pre>



### renderMode<span class="type-signature type enum">enum</span>
{:#members:rendermode}




Changes the rendering mode of the TextBox, Password, Mask Edit, and Textarea. See <a href="global.html#RenderMode">RenderMode</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code> 
// For textbox 
//Set the renderMode property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-rendermode="auto" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the renderMode on initialization. 
//To set the renderMode API value 
<input id="textbox" data-role="ejmtextbox"/>
<script>
$(function () {
$("#textbox").ejmTextBox ({ renderMode:ej.mobile.RenderMode.Auto });    
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  renderMode, after initialization:
// Get the renderMode API value.        
<script>
 $("#textbox").ejmTextBox ("option", "renderMode");                     
// Set the renderMode API
$("#textbox").ejmTextBox ("option", "renderMode", ej.mobile.RenderMode.Auto);
</script>
</code>
</pre>
<pre class="prettyprint">
<code>// For Password 
//Set the renderMode property in unobtrusive way.
<input id="password" data-role="ejmpassword"/>
</code>
</pre>
<pre class="prettyprint">
<code>// Set the renderMode on initialization. 
//To set the renderMode API value 
<input id="password" data-role="ejmpassword"/>
<script>
$(function () {
$("#password").ejmPassword ({ renderMode: ej.mobile.RenderMode.Auto});
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.        
<script>
 $("#password").ejmPassword ("option", "renderMode");                   
// Set the renderMode API
$("#password").ejmPassword ("option", "renderMode", ej.mobile.RenderMode.Auto); 
</script>
</code>
</pre>
<pre class="prettyprint">
<code>             
// For MaskEdit
//Set the renderMode property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-mask="+1 (999) 999-9999"/>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the renderMode on initialization. 
//To set the renderMode API value 
<input id="maskedit" data-role="ejmmaskedit" />
<script>
$(function () {
$("#maskedit").ejmMaskEdit ({ renderMode:ej.mobile.RenderMode.Auto,mask:"+1 (999) 999-9999" });         
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.        
<script>
 $("#maskedit").ejmMaskEdit ("option", "renderMode");                   
// Set the renderMode API
$("#maskedit").ejmMaskEdit ("option", "renderMode", ej.mobile.RenderMode.Auto);
</script>
</code>
</pre>
<pre class="prettyprint">
<code>    
// For TextArea
//Set the renderMode property in unobtrusive way. 
<textarea id="textarea" data-role="ejmtextarea" > </textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the renderMode on initialization. 
//To set the renderMode API value 
<textarea id="textarea" data-role="ejmtextarea" > </textarea>
<script>
$(function () {
$("#textarea").ejmTextArea ({ renderMode:ej.mobile.RenderMode.Auto });  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the renderMode, after initialization:
// Get the renderMode API value.                
<script>
 $("#textarea").ejmTextArea ("option", "renderMode");                   
// Set the renderMode API
$("#textarea").ejmTextArea ("option", "renderMode", ej.mobile.RenderMode.Auto);
</script></code>
</pre>



### showBorder<span class="type-signature type boolean">boolean</span>
{:#members:showborder}




Specifies whether to show the border on the TextBox, Password, Mask Edit, and Textarea.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code>// For TextBox 
//Set the showBorder property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-showborder=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showBorder on initialization. 
//To set the showBorder API value 
<input id="textbox" data-role="ejmtextbox"/>
<script>
$("#textbox").ejmTextBox ({ showBorder: true });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showBorder, after initialization:
// Get the showBorder API value.
<script>
 $("#textbox").ejmTextBox ("option", "showBorder");                     
// Set the showBorder API
$("#textbox").ejmTextBox ("option", "showBorder", true); 
</script>
</code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the showBorder property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-showborder=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showBorder on initialization. 
//To set the showBorder API value 
<input id="password" data-role="ejmpassword"/>
<script>
$("#password").ejmPassword ({ showBorder: true });      
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showBorder, after initialization:
// Get the showBorder API value.                
<script>
 $("#password").ejmPassword ("option", "showBorder");                   
// Set the showBorder API
$("#password").ejmPassword ("option", "showBorder", true); 
</script>
       </code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the showBorder property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-showborder=true data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showBorder on initialization. 
//To set the showBorder API value 
<input id="maskedit" data-role="ejmmaskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ showBorder: true,mask:"+1 (999) 999-9999" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the showBorder, after initialization:
// Get the showBorder API value.                
<script>
 $("#maskedit").ejmMaskEdit ("option", "showBorder");                   
// Set the showBorder API
$("#maskedit").ejmMaskEdit ("option", "showBorder", true); 
</script>
 </code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the showBorder property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-showborder=true > </textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the showBorder on initialization. 
//To set the showBorder API value 
<textarea id="textarea" data-role="ejmtextarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ showBorder: true });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the  showBorder, after initialization:
// Get the showBorder API value.
<script>
 $("#textarea").ejmTextArea ("option", "showBorder");                   
// Set the showBorder API
$("#textarea").ejmTextArea ("option", "showBorder", true);
</script></code>
</pre>



### theme<span class="type-signature type enum">enum</span>
{:#members:theme}




Changes the theme of the TextBox, Password, Mask Edit, and Textarea. See <a href="global.html#Theme">Theme</a>


Default Value:
{:.param}



* auto




Example
{:.example}

<pre class="prettyprint">
<code>// For TextBox  
//Set the theme property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-theme="auto" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
//To set the theme API value 
<input id="textbox" data-role="ejmtextbox" />
<script>
$(function () {
$("#textbox").ejmTextBox ({ theme: ej.mobile.Theme.Auto });     
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.             
<script>
 $("#textbox").ejmTextBox ("option", "theme");                  
// Set the theme API
$("#textbox").ejmTextBox ("option", "theme", ej.mobile.Theme.Auto);
</script> 
 </code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the theme property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-theme="auto" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
//To set the theme API value 
<input id="password" data-role="ejmpassword"/>
<script>
$(function () {
$("#password").ejmPassword ({ theme: ej.mobile.Theme.Auto });   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.     
<script>
 $("#password").ejmPassword ("option", "theme");                        
// Set the theme API
$("#password").ejmPassword ("option", "theme", ej.mobile.Theme.Auto); 
</script> 
 </code>
</pre>
<pre class="prettyprint">
<code>// For MaskEdit 
//Set the theme property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-theme="auto" data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
//To set the theme API value 
<input id="maskedit" data-role="ejmmaskedit"/>
<script>
$(function () {
$("#maskedit").ejmMaskEdit ({ theme: ej.mobile.Theme.Auto,mask:"+1 (999) 999-9999"  }); 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the theme, after initialization:
// Get the theme API value.     
<script>
 $("#maskedit").ejmMaskEdit ("option", "theme");                        
// Set the theme API
$("#maskedit").ejmMaskEdit ("option", "theme", ej.mobile.Theme.Auto); 
</script>
</code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the theme property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-theme="auto" ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the theme on initialization. 
//To set the theme API value 
<textarea id="textarea" data-role="ejmtextarea"></textarea>
<script>
$(function () {
$("#textarea").ejmTextArea ({ theme: ej.mobile.Theme.Auto });
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the textarea theme, after initialization:
// Get the theme API value.     
<script>
 $("#textarea").ejmTextArea ("option", "theme");                        
// Set the theme API
$("#textarea").ejmTextArea ("option", "theme", ej.mobile.Theme.Auto); 
</script></code>
</pre>



### value<span class="type-signature type string">string</span>
{:#members:value}




Specifies the value on initialization.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code>// For TextBox 
//Set the value property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-value="" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the value on initialization. 
//To set the value API value 
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ value: "" });               
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the TextBox value, after initialization:
// Get the value API value.             
<script>
 $("#textbox").ejmTextBox ("option", "value");                  
// Set the value API
$("#textbox").ejmTextBox ("option", "value", "");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the value property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-value="" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set Password value on initialization. 
//To set the value API value 
<input id="password"/>
<script>
$("#password").ejmPassword ({ value: "" });     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the Password value, after initialization:
// Get the value API value.             
<script>
 $("#password").ejmPassword ("option", "value");                        
// Set the value API
$("#password").ejmPassword ("option", "value", "");
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the value property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-value="" data-ej-mask="+1 (999) 999-9999"/>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the value on initialization. 
//To set the value API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ value: "",mask:"+1 (999) 999-9999" });    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the value, after initialization:
// Get the value API value.             
<script>
 $("#maskedit").ejmMaskEdit ("option", "value");                        
// Set the value API
$("#maskedit").ejmMaskEdit ("option", "value", "");
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the value property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-value="" ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the value on initialization. 
//To set the value API value 
<textarea id="textarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ value: "" });             
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the value, after initialization:
// Get the value API value.             
<script>
$("#textarea").ejmTextArea ("option", "value");                 
// Set the value API
$("#textarea").ejmTextArea ("option", "value", "");    
</script></code>
</pre>



### watermarkText<span class="type-signature type string">string</span>
{:#members:watermarktext}




Specifies the watermarkText on initialization.


Default Value:
{:.param}



* ""




Example
{:.example}

<pre class="prettyprint">
<code> 
// For TextBox
//Set the watermarkText property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-watermarktext="" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the watermarkText on initialization. 
//To set the watermarkText API value 
<input id="textbox"/>
<script>
$("#textbox").ejmTextBox ({ watermarkText: "" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.             
<script>
 $("#textbox").ejmTextBox ("option", "watermarkText");                  
// Set the watermarkText API
$("#textbox").ejmTextBox ("option", "watermarkText", "");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For Password
//Set the watermarkText property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-watermarktext="" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the watermarkText on initialization. 
//To set the watermarkText API value 
<input id="password"/>
<script>
$("#password").ejmPassword ({ watermarkText: "" });     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.             
<script>
 $("#password").ejmPassword ("option", "watermarkText");                        
// Set the watermarkText API
$("#password").ejmPassword ("option", "watermarkText", "");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For MaskEdit
//Set the watermarkText property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-watermarktext="" data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the watermarkText on initialization. 
//To set the watermarkText API value 
<input id="maskedit"/>
<script>
$("#maskedit").ejmMaskEdit ({ watermarkText: "",mask:"+1 (999) 999-9999" });
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.     
<script>
 $("#maskedit").ejmMaskEdit ("option", "watermarkText");                        
// Set the watermarkText API
$("#maskedit").ejmMaskEdit ("option", "watermarkText", ""); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// For TextArea
//Set the watermarkText property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-watermarktext="" ></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// Set the watermarkText on initialization. 
//To set the watermarkText API value 
<textarea id="textarea"></textarea>
<script>
$("#textarea").ejmTextArea ({ watermarkText: "" });             
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Get or set the watermarkText, after initialization:
// Get the watermarkText API value.             
<script>
 $("#textarea").ejmTextArea ("option", "watermarkText");                        
// Set the watermarkText API
$("#textarea").ejmTextArea ("option", "watermarkText", "");        
</script></code>
</pre>



### windows
{:#members:windows}




Section for windows rendermode specific functionalities.






### windows.allowReset<span class="type-signature type boolean">boolean</span>
{:#members:windows-allowreset}




Specifies whether to allow the reset button for the windows mode in TextBox, Password, MaskEdit, TextArea.


Default Value:
{:.param}



* true




Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox Control
// Set the windows mode allowReset property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-rendermode="windows" data-ej-windows-allowreset=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode allowReset property API value 
<input id="textbox"/>
<script>
$(function () {
$("#textbox").ejmTextBox({ windows:{allowReset: true},renderMode:ej.mobile.RenderMode.Windows});   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode allowReset API, after initialization:
// Get the windows mode allowReset value  
<script>
$("#textbox").ejmTextBox("option", "windows.allowReset");   
// Set the windows mode allowReset value 
$("#textbox").ejmTextBox("option", "windows.allowReset", true);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password Control
// Set the windows mode allowReset property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-rendermode="windows" data-ej-windows-allowreset=true />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode allowReset property API value 
<input id="password"/>
<script>
$(function () {
$("#password").ejmPassword({ windows:{allowReset: true},renderMode:ej.mobile.RenderMode.Windows});  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode allowReset API, after initialization:
// Get the windows mode allowReset value  
<script>
$("#password").ejmPassword("option", "windows.allowReset");   
// Set the windows mode allowReset value 
$("#password").ejmPassword("option", "windows.allowReset", true); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit Control
// Set the windows mode allowReset property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit"  data-ej-rendermode="windows" data-ej-windows-allowreset=true data-ej-mask="+1 (999) 999-9999" />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode allowReset property API value 
<input id="maskedit"/>
<script>
$(function () {
$("#maskedit").ejmMaskEdit({ windows:{allowReset: true},mask:"+1 (999) 999-9999",renderMode:ej.mobile.RenderMode.Windows});   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode allowReset API, after initialization:
// Get the windows mode allowReset value  
<script>
$("#maskedit").ejmMaskEdit("option", "windows.allowReset");   
// Set the windows mode allowReset value 
$("#maskedit").ejmMaskEdit("option", "windows.allowReset", true);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area Control
// Set the windows mode allowReset property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-rendermode="windows" data-ej-windows-allowreset=true > </textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode allowReset property API value 
<textarea id="textarea"></textarea>
<script>
$(function () {
$("#textarea").ejmTextArea({windows:{allowReset: true,renderMode:ej.mobile.RenderMode.Windows}});  
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode allowReset API, after initialization:
// Get the windows mode allowReset value  
<script>
$("#textarea").ejmTextArea("option", "windows.allowReset");   
// Set the windows mode allowReset value 
$("#textarea").ejmTextArea("option", "windows.allowReset", true); 
</script></code>
</pre>



### windows.renderDefault<span class="type-signature type boolean">boolean</span>
{:#members:windows-renderdefault}




Specifies whether to render control based on the windowsphone's current accent color and device theme.


Default Value:
{:.param}



* false




Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox Control
// Set the windows mode renderDefault property in unobtrusive way.
<input id="textbox" data-role="ejmtextbox" data-ej-rendermode="windows" data-ej-windows-renderDefault=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode renderDefault property API value 
<input id="textbox"/>
<script>
$(function () {
$("#textbox").ejmTextBox({ windows:{renderDefault: false},renderMode:ej.mobile.RenderMode.Windows});
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
<script>
$("#textbox").ejmTextBox("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#textbox").ejmTextBox("option", "windows.renderDefault", false);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password Control
// Set the windows mode renderDefault property in unobtrusive way.
<input id="password" data-role="ejmpassword" data-ej-rendermode="windows" data-ej-windows-renderDefault=false />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode renderDefault property API value 
<input id="password"/>
<script>
$(function () {
$("#password").ejmPassword({ windows:{renderDefault: false},renderMode:ej.mobile.RenderMode.Windows});   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
<script>
$("#password").ejmPassword("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#password").ejmPassword("option", "windows.renderDefault", false);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit Control
// Set the windows mode renderDefault property in unobtrusive way.
<input id="maskedit" data-role="ejmmaskedit" data-ej-rendermode="windows" data-ej-windows-renderDefault=false data-ej-mask="+1 (999) 999-9999"  />
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set the windows mode renderDefault property API value 
<input id="maskedit" />
<script>
$(function () {
$("#maskedit").ejmMaskEdit({ windows:{renderDefault: false},mask:"+1 (999) 999-9999"},renderMode:ej.mobile.RenderMode.Windows); 
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
<script>
$("#maskedit").ejmMaskEdit("option", "windows.renderDefault"); 
// Set the windows mode renderDefault value 
$("#maskedit").ejmMaskEdit("option", "windows.renderDefault", false);
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area Control
// Set the windows mode renderDefault property in unobtrusive way.
<textarea id="textarea" data-role="ejmtextarea" data-ej-rendermode="windows" data-ej-windows-renderDefault=false></textarea>
</code>
</pre>
<pre class="prettyprint">
<code> 
// To set windows mode renderDefault property API value 
<textarea id="textarea" ></textarea>
<script>
$(function () {
$("#textarea").ejmTextArea({windows:{renderDefault: false},renderMode:ej.mobile.RenderMode.Windows});   
});
</script></code>
</pre>
<pre class="prettyprint">
<code> 
// Get or set the windows mode renderDefault API, after initialization:
// Get the windows mode renderDefault value  
<script>
$("#textarea").ejmTextArea("option", "windows.renderDefault");   
// Set the windows mode renderDefault value 
$("#textarea").ejmTextArea("option", "windows.renderDefault", false); 
</script></code>
</pre>


## Methods




### disable<span class="signature">()</span>
{:#methods:disable}




To handle the TextBox, or Password or MaskEdit or TextArea to disable



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.disable(); // Returns the textbox to disable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
// Get the textbox to disable
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("disable");    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.disable(); // Returns the password to disable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to disable
$("#password").ejmPassword();
$("#password").ejmPassword("disable");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the MaskEdit
$("#maskedit").ejmMaskEdit({mask:"+1 (999) 999-9999"});
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.disable(); // returns the maskedit to disable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to disable
$("#maskedit").ejmMaskEdit({mask:"+1 (999) 999-9999"});
$("#maskedit").ejmMaskEdit("disable");  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area
<textarea id="textarea" > </textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.disable(); // Returns the textarea to disable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"></textarea>
<script>
// Get the textarea to disable
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("disable");  
</script></code>
</pre>



### enable<span class="signature">()</span>
{:#methods:enable}




To handle the TextBox, or Password or MaskEdit or TextArea to enable



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.enable(); // Returns the textbox to enable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
// Get the textbox to enable
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("enable");     
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.enable(); // Returns the password to enable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to enable
$("#password").ejmPassword();
$("#password").ejmPassword("enable");   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the maskedit
$("#maskedit").ejmMaskEdit();
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.enable(); // Returns the maskedit to enable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to enable
$("#maskedit").ejmMaskEdit();
$("#maskedit").ejmMaskEdit("enable");   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area
<textarea id="textarea" ></textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.enable(); // Returns the textarea to enable mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"></textarea>
<script>
// Get the textarea to enable
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("enable");   
</script></code>
</pre>



### getStrippedValue<span class="signature">()</span>
{:#methods:getstrippedvalue}




To handle the TextBox, or Password or MaskEdit or TextArea to getStrippedValue



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.getStrippedValue(); // Returns the textbox value with stripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
// Get the textbox to getStrippedValue
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("getStrippedValue");   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.getStrippedValue(); // Returns the password value with stripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to getStrippedValue
$("#password").ejmPassword();
$("#password").ejmPassword("getStrippedValue"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the MaskEdit
$("#maskedit").ejmMaskEdit();
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.getStrippedValue(); // Returns the maskedit Value with Stripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to getStrippedValue
$("#maskedit").ejmMaskEdit();
$("#maskedit").ejmMaskEdit("getStrippedValue"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area
<textarea id="textarea" > </textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.getStrippedValue(); // Returns the textarea value with stripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"></textarea>
<script>
// Get the textarea to getStrippedValue
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("getStrippedValue"); 
</script></code>
</pre>



### getUnstrippedValue<span class="signature">()</span>
{:#methods:getunstrippedvalue}




To handle the TextBox, or Password or MaskEdit or TextArea to getUnstrippedValue



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.getUnstrippedValue(); // Returns the textbox value with unstripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
// Get the textbox to getUnstrippedValue
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("getUnstrippedValue"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.getUnstrippedValue(); // Returns the password value with unstripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to getUnstrippedValue
$("#password").ejmPassword();
$("#password").ejmPassword("getUnstrippedValue");       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the MaskEdit
$("#maskedit").ejmMaskEdit();
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.getUnstrippedValue(); // Returns the maskedit value with unstripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to getUnstrippedValue
$("#maskedit").ejmMaskEdit();
$("#maskedit").ejmMaskEdit("getUnstrippedValue");       
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area
<textarea id="textarea" ></textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.getUnstrippedValue(); // Returns the textarea value with unstripped mode.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"> </textarea >
<script>
// Get the textarea to getUnstrippedValue
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("getUnstrippedValue");       
</script></code>
</pre>



### getValue<span class="signature">()</span>
{:#methods:getvalue}




To handle the TextBox, or Password or MaskEdit or TextArea to getValue



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.getValue(); // Returns the textbox value.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
// Get the textbox to getValue
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("getValue");   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.getValue(); // Returns the password value.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to getValue
$("#password").ejmPassword();
$("#password").ejmPassword("getValue"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the maskedit
$("#maskedit").ejmMaskEdit();
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.getValue(); // Returns the maskedit value.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to getValue
$("#maskedit").ejmMaskEdit();
$("#maskedit").ejmMaskEdit("getValue"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Text Area
<textarea id="textarea" ></textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.getValue(); // Returns the textarea value.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"></textarea>
<script>
// Get the textarea to getValue
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("getValue"); 
</script></code>
</pre>



### getWatermarkText<span class="signature">()</span>
{:#methods:getwatermarktext}




To handle the TextBox, or Password or MaskEdit or TextArea to getWatermarkText



Example
{:.example}

<pre class="prettyprint">
<code> 
//For TextBox
<input id="textbox" />
<script>
// Create the textbox
$("#textbox").ejmTextBox();
var textbox = $("#textbox").data("ejmTextBox");
textbox.getWatermarkText(); // Returns the textbox watermarkText.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="textbox"/>
<script>
//Get the textbox to getWatermarkText
$("#textbox").ejmTextBox();
$("#textbox").ejmTextBox("getWatermarkText");   
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" />
<script>
// Create the password
$("#password").ejmPassword();
var password = $("#password").data("ejmPassword");
password.getWatermarkText(); // Returns the password watermarkText.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="password"/>
<script>
// Get the password to getWatermarkText
$("#password").ejmPassword();
$("#password").ejmPassword("getWatermarkText"); 
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For MaskEdit
<input id="maskedit" />
<script>
// Create the maskedit
$("#maskedit").ejmMaskEdit();
var maskedit = $("#maskedit").data("ejmMaskEdit");
maskedit.getWatermarkText(); // Returns the maskedit watermarkText.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<input id="maskedit"/>
<script>
// Get the maskedit to getWatermarkText
$("#maskedit").ejmMaskEdit();
$("#maskedit").ejmMaskEdit("getWatermarkText"); 
</script></code>
</pre>
<pre class="prettyprint">
<code>//For Text Area 
<textarea id="textarea" ></textarea>
<script>
// Create the textarea
$("#textarea").ejmTextArea();
var textarea = $("#textarea").data("ejmTextArea");
textarea.getWatermarkText(); // Returns the textarea watermarkText.
</script></code>
</pre>
<pre class="prettyprint">
<code> 
<textarea id="textarea"> </textarea >
<script>
// Get the textarea to getWatermarkText
$("#textarea").ejmTextArea();
$("#textarea").ejmTextArea("getWatermarkText"); 
</script></code>
</pre>


## Events




### change
{:#events:change}




Event triggers when the Textbox or Password or Maskedit or textarea value changed

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
<td class="description last">Event parameters from Textbox or Password or Maskedit or textarea
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
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the Textbox or Password or Maskedit or textarea model</td>
</tr>
<tr>
<td class="name"><code>type</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the name of the event</td>
</tr>
<tr>
<td class="name"><code>element</code></td>
<td class="type"><span class="param-type">object</span></td>
<td class="description last">returns the current element</td>
</tr>
<tr>
<td class="name"><code>value</code></td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">returns the value of the control</td>
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
// For TextBox
<input id="textbox" data-role="ejmtextbox" data-ej-change="onChange"/>
<script> 
// Change event for textbox
function onChange(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Change event for textbox
<input id="textbox" data-role="ejmtextbox" data-ej-change="onChange"/>
<script>
$("#textbox").ejmTextBox({
  change: function (args) { 
//handle the event 
}
});  
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For Password
<input id="password" data-role="ejmpassword" data-ej-change="onChange"/>
<script> 
// Change event for password
function onChange(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Change event for password
<input id="password" data-role="ejmpassword" data-ej-change="onChange"/>
<script>
$("#password").ejmPassword({
  change: function (args) { 
//handle the event 
}
});    
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//For maskedit
<input id="maskedit" data-role="ejmmaskedit" data-ej-change="onChange" data-ej-mask="+1 (999) 999-9999" />
<script> 
// Change event for maskedit
function onChange(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Change event for maskedit
<input id="maskedit" data-role="ejmmaskedit" data-ej-change="onChange" data-ej-mask="+1 (999) 999-9999" />
<script> 
$("#maskedit").ejmMaskEdit({
  change: function (args) { 
//handle the event 
}
});     
</script> </code>
</pre>
<pre class="prettyprint">
<code> 
//For textarea
<textarea id="textarea" data-role="ejmtextarea" data-ej-change="onChange"></textarea>
<script> 
// Change event for textArea
function onChange(args) { 
//handle the event 
}
</script></code>
</pre>
<pre class="prettyprint">
<code> 
//Change event for textarea
<textarea id="textarea" data-role="ejmtextarea" data-ej-change="onChange"></textarea>
<script> 
$("#textarea").ejmTextArea({
  change: function (args) { 
//handle the event 
}
});           
</script> </code>
</pre>


