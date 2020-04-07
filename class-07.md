# Domain Modeling
"Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model."

When modeling many things, build self-contained objects with the same attributes and behaviors. When you need to change the algorithm, the changes will be small and targeted.  To do this, define a constructor function and initialize objects.

Constructor functions are defined using function expressions.  A variable is declared and then assigned a function with parameters.  When the function is called, the data inside these parameters are stored inside this.x properties.  Storeing data within properties ensures new objects can access that data later.

After this, objects are instantized with the "new" keyword and properties are initialised by calling the constructor function, and then stored in their own variables.  

This is object oriented programming.  The "new" keyword instantized (i.e. creates) and object.  The constructor function initializes properties inside that object using the "this." variable, and the object is stored for later use.

Methods can be added to a constructor function's protype.  

IN list form:
1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

## HTML Chapter 6: “Tables” (pp.126-145)

### JS Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

