## Basics
* Code Academy: http://www.codecademy.com/tracks/javascript
* Chrome Console
  * Scripts
  * Resources
  * Network
* Prototype
* jQuery
  * DOM selectors
  * ajax
  * Difference between generic $.ajax and $.get and $.post

## Practice Task
* Create an array of 100 usernames - [user1, user2, user3 and so on...]
* Create an array of 100 user objects

```
  users = [
   {
    name: name1
    dob: some random date between 1970-2000
    address: {
     street: line1
     landmark: line2
     area: area1
     city: city1
    }
   },{
    name: name2
    dob: some random date between 1970-2000
    address: {
     street: line3
     landmark: line4
     area: area2
     city: city1
    } and so on
  ]
```

* Keep the same city for 10 consicutive users.
* Each city has only 3 areas - area1, area2 or area3 only
* Create an array of 30 branchesIds - [b1, b2, b3 and so on...]
* Similar to Array of user objects, create Array of branch objects with name and address.
* Keep the city same for 3 consecutive branches - city 1 has [branch1 in area1, branch2 in area2, branch3 in area3]
* Assign some some username and randomly some branchId to each user - but contained within the same city
  * Every user should get one branch, every branch should get atleast one user
* Find all users who are less than 30 years of age - print these usernames.
  * User Javascript Data Object to start with. In the 2nd iteration use [moment.js](http://momentjs.com/)
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

### Notes
* All data is to be created programmatically
* Don't use any external libraries in the initial phase
* Make use of OOP style - [Introduction to Object-Oriented JavaScript - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* Write the code in Sublime Text
* Run this in the Chrome Browser Console
* Make this is a simple Node.js project which can be run from the command line
* Save the data and output in different files

