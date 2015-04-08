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
* Randomly assign some some username and some branchId to each user - but contained within the same city
* Find all users who are less than 30 years of age - print these usernames.
* All branches need to have atleast one user assigned. Each branch should not have more than 
* Find all users who are assigned the same branch with area same as their home_address area

### Notes
* All data is to be created programmatically
* Don't use any external libraries in the initial phase
* Make use of Object Oriented style of Programming - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript
* Write the code in sublime text
* Run this in the Browser Console
* Make this is a simple node project which can be run from the command line - save output in a file

