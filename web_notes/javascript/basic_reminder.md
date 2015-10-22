# JAVASCRIPT
##Basics

1. in <script></script> , every where in HTML file , however the place affect the web page and the order that the fuctions work;

       Place the scripts at the bottom of the <body> element --> not blocking the HTML display

	   External: <script src = "myScript.js"></script>

2. window.alert() document.write() innerHTML consolo.log();

3. seprated by semicolons, literals(fixed) and variables, use "var" to define  and  create variables

4. Case Sensitive, use // and /**/ to comment

5.  number string array object :

    object: var person = {firstname: "john", lastName: "Doe", age:50}

6. null is still an object, so weird and interesting! 

7. functions:

  () operater invokes the Function, accessing a function without () will return the function definitioni

  arguments are passed by value, objects are passed by reference

  1) Function declaration:   function myFunction(a, b){}  not common to end it with a semicolon for function declaration

  2) Functin expression : var x = function (a,b){return a * b} Defined using an expression,  anonymous funtion (a function without a name)

  3) self invoke: A self-invoking expression is invoked (started) automatically, without being called.

     can not invoke function declaration 

	 (function () {
	      var x = "Hello!!";      // I will invoke myself
		  })();
  
  4) missing arguments will be set to undefined, have build-in object called the arguments object which can be called: arguments.length  arguments[0]

  5) THIS!!!!!!!!!!!!!!!!!!!!!!

    this , is the object that 'owns' the current code

	global object is window for web browser



  @@) mFunction.toString()  
  
8. objects:

  have attributes and functions, objectName.propertyName or objectName["propertyName"] , objectName.functionName()

9.Scopes:

 globale and loacl , Automatically Globle --> assign a value to a variable that has not been declared!!


##Mediums



##Advanced



