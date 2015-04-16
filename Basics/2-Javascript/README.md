## Topics
* JavaScript Basics: [Code Academy](http://www.codecademy.com/tracks/javascript)
* jQuery Basics: [Code Academy](http://www.codecademy.com/tracks/jquery)
  * DOM selectors
  * ajax
  * Difference between generic $.ajax and $.get and $.post
* Chrome Console
  * Scripts
  * Resources
  * Network

### Further Reading - Will be covered in more detail in the Web Section
* Callbacks: http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/
* Prototypes: Need to find a good link
* Closures: [Robert Nyman’s Blog - Mozilla](http://robertnyman.com/2008/10/09/explaining-javascript-scope-and-closures/)  

## Practice Task

### JavaScript Basics
####1 - Data Generation

* Create an array of 20 user objects

```
  users = [
   {
    name: name1
    dob: some random date between 1970-2000
    address: {
     street: line1
     landmark: line2
     city: city1
    }
   },{
    name: name2
    dob: some random date between 1970-2000
    address: {
     street: line3
     landmark: line4
     city: city1
    } and so on
  ]
```
* Keep the same city for 5 consecutive users.
* Similar to Array of user objects, create Array of 8 branch objects with branch name and address.
* Each city should have 2 branches - city1 has branch1, branch2. city2 has branch3, branch4 and so on...
* Assign a branch to every user in their own city

####2 - Computations
* Find all users who are less than 30 years of age - print these usernames.
  * User Javascript Data Object to start with
  * In the 2nd iteration use [moment.js](http://momentjs.com/)
* Flip the object Model - Print all cities and all the branches in each city and users in each branch
```
Example
[
  {
    city: city1,
    branches: [
     {
      branch: b1,
      users: [u1, u2, u3]
     },
     {
      branch: b2,
      users: [u5, u6, u7]
     }
    ]
  },
  {
   city: city2,
   branches: [....]
   and so on....
  }
]
```

#### Notes
* All data is to be created programmatically
* Don't use any external libraries in the initial phase
* Make use of OOP style - [Introduction to Object-Oriented JavaScript - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* Write the code in Sublime Text
* Run this in the Chrome Browser Console
* Make this is a simple Node.js project which can be run from the command line
* Save the data and output in different files

### Prototype
* Create class structure and associated instances for Artoo's team the way you see it. e.g geeks, rainmakers, firefighters, etc and add some fun functions for individuals and teams.

### jQuery Basics
* Go to ```gl.artoo.in/login```
  * Populate the username and password using jQuery. If you can do that, then you should be able to login programatically too!
  * Print out a table of all the tags and their counts in the HTML page e.g. ```<meta> = 1```

