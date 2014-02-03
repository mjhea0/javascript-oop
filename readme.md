## OOP in JavaScript

Quick example:

```javascript
Car = {
  createNew: function() {
    var car = {};
    car.drive = function(){ alert("driving!"); }
    return animal;
  };
};
  
Sedan = {
  createNew: function() {
    var sedan = Car.createNew(); // Inherits
    var wheels = "four";
    sedan.numWheels= function(){
        alert( wheels );
    };
    return sedan;
    };
};
  
var sedan = Sedan.createNew();
sedan.makeSound();
sedan.eat();
