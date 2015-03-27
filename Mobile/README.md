
The idea is to introduce one aspect of android every week, look at the Artoo codebase to see how it is used, then do a small patch and release to UAT. **Every Week**

## Week 1
### Day 1, 2:
 Activities and Fragments are one of the core aspects of Android. You will need a implement a simple app following the android tutorial.
 The developer site provides a basic introduction http://developer.android.com/training/basics/firstapp/index.html

### Day 3, 4:
 Get together with one of the Android devs on the team. Look at the source code of `Loan mobile application`. Create a branch, write code to fix one issue or code one new functionality in the UAT environment. Send in a pull request for your changes.

### Day 5:
 Pester the dev to get your pull request reviewed, push it to Travis and onto UAT. Showcase your work and head with the team to a sumptuous lunch to celebrate.

## Week 2
### Day 1, 2:
  Services and Intents are another set of core aspects of Android. You need to implement a simple service by following the android tutorial, http://developer.android.com/guide/components/services.html, http://developer.android.com/guide/components/intents-filters.html.

### Day 3, 4:
  Get together with one of the Android devs on the team. Look at the source code of `Data` service and `TouchDB` library. Create a branch, write code to fix one issue or code new functionality in the UAT environment. Send in a pull request with your changes.

### Day 5:
  Get your pull request reviewed, push it to Travis and onto UAT. Job done.

## Week 3
### Day 1, 2:
  Unit testing is an important aspect of any developer's toolbox, understand the frameworks available in Android for Unit Test. Write the dummy tests following the tutorial.
  Robolectric is a popular alternate 3rd party unit testing framework, write some dummy tests following the tutorial.

### Day 3, 4:
  Think about how you can go about writing test cases for the code you have written over the past 2 weeks. Go back to the 2 branches you have created over the past 2 weeks and add test cases to them.
  
  Ideally, you would write test cases along with or before writing your functional code. These test cases would be executed on Travis before the functionality or bug fix is let out into the wild. We wanted you to get excited by the power of functionality that is possible in android before introducing you to its responsibilities.

### Day 5:
  Discuss the pull request and the test cases with your Android mentor, push these to the travis build system. Now you are in charge.

## Week 4
  This is your week to have fun and explore android, provide us suggestions and alternate solutions in usability, performance, security. You can divide your week as you wish, remember, you were put in charge last week. Some questions to get you started:
- Do you remember your field visit, did you feel the field agent was at ease with our product, could be make it simpler, faster or more lovable?
- Is the way we store data secure? What happens if the user loses his mobile? Can he recover data after a crash?
- Can we make our sync more intuitive? Faster?

### Day 4, 5:
  You will need to build at least 2 experimental apps or make experimental modifications in our apps to demonstrate your ideas. Discuss with people around you if you need some help. Blow the team away showcasing your experiments.


