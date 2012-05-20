# VCC Virtual Class Container
###### by MasterOne17
----------
The Virtual Class Container lets you create a virtual OOP-Class in PHP.

To Create a VCC, do this:
```javascript
include "vcc.class.php"; // include the library
$VCC = new VCC; // create a reference to the class
```

In addition to add functions to the class, do:
```javascript
$VCC->addRealFunction("Function-Name", "Virtual Name in Class"); // add a REAL existing function
$VCC->addFunction(Closure, "Virtual Name in Class"); // adds an Closure to the Container.
```