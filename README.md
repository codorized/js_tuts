#JS Cheatsheet

### Difference between Classes and IDs?

IDs | CLASSES
------------ | -------------
```<div id="my_first_id"></div>``` | ```<div class="my_first_classes"></div>```
IDs have higher specificity than classes.  | The only way for classes to outmatch IDs is to use the keyword **!important** in CSS
You can only have ONE id of the same name within the same html page.   | You can create multiple classes of the same name with the same html page

### How to get/set element style properties in the DOM using IDs and Classes in Javascript?

IDs | CLASSES
------------ | -------------
```document.getElementById('my_first_id').style.<property_name>;``` | ```document.getElementsByClassname('my_first_id')[<index_number>].style.<property_name>;```

### Functions and Variables

User-defined functions:
1. FORMAT: 
``` function myFunction() { ... } ```
2. INVOKE:
``` <button onclick="myFunction()">Try it</button> ```

Variables:
1. FORMAT:
``` var x = 5 ```
2. INVOKE: 
``` x += x + 6 ```  <br />
NOTE: JS variables are loosely typed which means the info to be stored inside it does not need to be specific.
&nbsp;It can contain of the following: 
&nbsp;&nbsp;* Strings
&nbsp;&nbsp;* Numbers
&nbsp;&nbsp;* Booleans
&nbsp;&nbsp;* Arrays
&nbsp;&nbsp;* Objects 
&nbsp;&nbsp;* Undefined
&nbsp;&nbsp;* Empty
&nbsp;&nbsp;* Null
&nbsp;&nbsp;* Function



