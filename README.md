# Study

Node "Require" needs 5 stages to complete:
    Resolving
    Loading
    Wrapping - Wrapping of module and the require objects so they are available locally to every field.
    Evaluating
    Caching
   
DEEP COPY   
  Object.assign({},src)
  Iterating of keys(Fails in to much nesting)
  Stringyfy and Parse The Object Again

Window Object
  window is the browser container like module in node js
  
Method Overloading
  It is used when client side is restricted to Get and Post request Only
  We can use this to make request more extensive like DELETE and PUT
  
MONGOOSE
  $sum can only be used in $project and $group same goes with $add
  $map is same as javascript map returns an array {$map : {input:[],as:"",in:"$$"}}

Updating Nesting Arrays
  We use $ as filed in to update nested arrays
  arr[{score:80},{score:70}]
  so we will use arr.$.sscore and find condition above that.

