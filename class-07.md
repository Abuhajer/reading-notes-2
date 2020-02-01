## HTML Chapter 6 *(Tables)*

Tables represent information in a grid format. To create a table we use the \<table> element. The contents of the table are written row byy row using the \<tr> element. Each cell of a table is represented with the \<td> element. To write the headings of a table, we use the \<th> element. 

If you are working with long tables, you can use the \<thead>, \<tbody>, \<tfooter> elements. This will help distinguish between the main content and the fisrt and last rows. 


## JavaScript Chapter 3 *(Functions, Methods and Objects)*

- Functions allow you to group a set of related statements together that represent a single task.
- Functions can take parameters.
- An Object is a series of variables and functions that represent something from the world around you.
- In an Object, variables are known as properties and functions as methods. 
- Web browsers implement onjects that represent both thr browser windows and the document loaded into the browser window.
- JavaScript has several built-in objects suchs as String, Number, Math, and Date.
Arrays and objects can be used to create complex data sets. 

Literal Notation:

```
var hotel = { 
  name: 'Quay', 
  rooms: 40, 
  booked: 25, 
  checkAvailability: function() { 
    return this.rooms - this.booked; 
  } 
} 
```

Object Constructor Notation: 
```
function Hotel(name, rooms, booked) { 
  this.name = name; 
  this.rooms = rooms; 
  this.booked = booked; 
  this.checkAvailability = function() 
    return this.rooms - this.booked; 
}; 
var quayHotel = new Hotel('Quay', 40, 25); 
var parkHotel =new Hotel('Park', 120, 77); 
```

## Domain Modeling

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Tips to follow when building your own domain models:

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.

