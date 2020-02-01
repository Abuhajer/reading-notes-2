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

