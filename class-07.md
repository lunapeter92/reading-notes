# Class 7 Notes
Notes taken from John Duckets Javascript/Jquery

## Functions, Methods, Objects

  - Creating an Object: 
    `const hotel = {
      //properties
      name = 'Quay',
      rooms = 40
    }`
    
  - Updated an Object: 
    `hotel.name = 'Park';`
    
  - Creating an constructor function: 
    `function Hotel(name, rooms, booked){
      this.name = name;
      this.rooms = rooms;
      this.booked = booked; 
    }`
    
   - Creating a new object using constructor function: 
    - `const newHotel = new Hotel('Peter', '2', 77);`
