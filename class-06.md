## JavaScript Chapter 3 *(Object Literals)*

Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables become properties and functions become methods. 
- Properties tell us about the object, such name, age, gender, etc. 
- Methods represent tasks that are associated with the object. For example you can check how many rooms are available in a hotel. 

#### Literal Notation:
var hotel = {
    <dd>name: 'Hilton", <br>
    rooms: 40, <br>
    booked: 25, <br>
    checkAvailability: function() { <br>
      return this.rooms - this.booked; <br>
    } 
  <dt>};


#### DOT Notation
You access the properties or methods of an oject using the dot notation. 
> var hotelName = hotel.name;

> var roomsFree = hotel.checkAvailability();


## JavaScript Chapter 5 *(Document Object Model)*

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

Methods that select individual elements:
- getElementById( ) - document.getElementById('one')
- querySelector( )

Selecting an element fron a nodelist:
- item( ) 
- array syntax

Adding or Removing HTML content:
- innerHtML
- DOM Manipulation

## Understanding the problem domain is the hardest part of programming

The other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. 
>"It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it"

Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.  It is much more expensive and time consuming to do things over than it is to do them right the first time.  I learn this lesson the hard way time and time again.
