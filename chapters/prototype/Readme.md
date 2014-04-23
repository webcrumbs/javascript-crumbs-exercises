# Prototype

## `exercise01`

fill in the blanks to make the program work:

```js
(function() {
  var larger = function(o1, o2) {
    if ( o1.size > o2.size ) {
        console.log('o1 is larger');
    } else {
        console.log('o2 is larger');
    }
  };
  
  var x = // write code here
  var y = // write code here
  
  larger(x, y);    
}());
```
## `exercise02`

fill in the blanks to make the program work:

    (function() {
      var favorite_album = function( collection ) {
        // do nothing if got an empty collection
        if ( collection.length === 0 ) {
          return;
        }

        // define two variables and initialize them
        var max_played = collection[0].played,
          max_index  = 0;

        for ( var i=0, len = collection.length; i < len; i++ ) {
          if ( collection[i].played > max_played ) {
            max_played = collection[i].played;
            max_index  = i;
          }
        }

        return { play: max_played, index: max_index };
      };

      var music = // write code here

      var fav = favorite_album( music );

      console.log( "Your favorite album was played " + fav.play + " times" );

      // Bonus: Write code here to make the following line print the above line
      console.log( fav );
    }());

## `exercise03`

implement a `Summer` objects with two methods: `getCurrentSum()`and `add(number)`. Run the following main code to make sure everything works:

    (function () {
      // write your code here to make the program work 

      var s1 = Summer();
      var s2 = Summer();
     
      s1.add(10);
      s1.add(20);
     
      s2.add(30);
     
      s2.add(5);
     
      // prints 30
      console.log(s1.getCurrentSum());
     
      // prints 35
      console.log(s2.getCurrentSum());
     
    }());


## `exercise04`

fill in the blanks to make the program work:
    
    (function () {
      var person = {
        // fill code here
      };

      var  car = {
        // fill code here
      };

      // print Vrum Vrum
      car.drive();
     
      // print I'm rich
      if ( car.price > 1000 ) {
        person.buy(car);
      }
    }());



    (function () {
      var employees = // fill code here;

      for (var i=0; i < employees.length; ++i ) {
        // print I work at IBM
        employees[i].hello();
      }
    }());

## `exercise05`

implement the following `Bingo` object. The `Bingo` object should randomize a number between 1 and 10 on creation and provide a single method `guess(number)`. That method should return `true` if the argument was the secret number. Test your class.

## `exercise06`

implement a `MusicBox` object that should make the following code work well:

    (function() {
    // Write your code here  

      var box = MusicBox();
      var a1 = Album("The Who", "Tommy");
      var a2 = Album("Tom Waits", "Closing Time");
      var a3 = Album("John Cale", "Paris 1919");
      var favorite;
     
      box.addAlbum(a1);
      box.addAlbum(a2);
      box.addAlbum(a3);
     
      a1.play() ; // prints "Playing The Who - Tommy"
      a2.play(); // prints "Playing Tom Waits - Closing Time"  
      a1.play(); // prints "Playing The Who - Tommy"
     
      favorite = box.favoriteAlbum(); 
     
      // prints "favorite album is The Who - Tommy"
      console.log("favorite album is " + favorite); 
    }());

### `exercise06a`

can you also write it so that box.addAlbum(a1, a2, a3) will work ? how ?

## `exercise07`

write the functions that will make the following code work:

    (function () {
      // Code goes here

      var album = PhotoAlbum();
      var p;
     
      p = Photo("Paris Trip 1");
      p.tag("Jimmy");
      p.tag("Jane");
      p.tag("Jeff");
     
      album.addPicture(p);
     
      p = Photo("Look the Eiffel");
      p.tag("Jimmy");
      p.tag("Max");
      album.addPicture(p);
     
      p = Photo("OMG it's so high");
      p.tag("Jimmy");
      p.tag("Jane");
     
      // prints "Jimmy, Jane"
      p.showTags();
     
      album.addPicture(p);
     
      // prints "Paris Trip 1, Look the Eiffel, OMG it's so high"
      album.showPictures("Jimmy");
     
      // prints "Paris Trip 1, OMG it's so high"
      album.showPictures("Jane");    
    }());

## `exercise08`

write a constructor function `Point2D`  
that create a 2D point given its `x` and `y` coordinates.

### `exercise08a`

write a contructor function `Edge`  
that create an edge given its two vertices (i.e. two points).

### `exercise08b`

write a method `length` for `Edge`  
that compute the length of the edge.

## `exercise09`

write a constructor function `Trinagle`  
that create a triangle given its three edges.

### `exercise09a`

write a method `perimeter` for `Triangle`  
that compute the perimeter of the triangle.

### `exercise09b`

write a method `area` for `Triangle`  
that compute the area of the triangle  
(Do you remeber the Erone's formula?).



