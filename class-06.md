# Class 6 Notes
Notes taken from John Duckets Javascript/Jquery

## Object Literals
  - Objects main use is to group together variables and functions to create a model that can be used later. 
    - Object variables are known as properties
    - Object functions are known as methods
   
   -Object properties are used in key/value pairs: 
    ```
    var person = {
      name: Peter,
      age: 29,
      family: ['Caitlin', 'Harper', 'Scarlett', 'Theodore', 'Jasper'],
      //This is a method example
      height: function(){
        return height;
      }
      }```
   
   -Accessing object names: 
    - `var user = person.name`;
    
    
## DOM
  - DOM stands for Document Object Model
  - Accessing Elements: 
    Returns Single Element:
      - getElementById('id')
      - querySelector('css selector')
    Returns more than one element: 
      - getElementsByClassName('class')
      - getElemementsByTagName('tagName')
      - querySelectorAll('css selector')
    
