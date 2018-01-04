# 100 Days of Code for 2018! #

## Day 1 ##
### January 1, 2018 ###
For the last 4 months I've been extremely busy completing an intense Mobile Applications Developer program with Seneca College and the Toronto YWCA. 

It was a heck of a program! I learned Java, OOP, iOS app making, Objective-C, Swift, and Android app making. As well as taking a weekend long Scrum Master course (exam will be completed in the next day or so), and later this week I'm starting a 2.5 week Salesforce course.

My longterm plans for the next 100 days include building more Android and iOS apps, learning React Native, getting back into Node.js web development, and checking out ReasonML that all the cool kids at FCC's gitter chat are cooing over these days. As well as getting accepted as an intern in either web development or mobile development. 

## Day 2 ##
### January 2, 2018 ###

Began Salesforce training today.

More Scrum Master exam studying. I really need to complete. Let's give that a go today!

Did some set up work yesterday to learn React Native. Had a bit of trouble setting up the android studio emulator. I can't get the thing to load from the cli. Worse comes to worse, I'll have to run Android Studio to use the emulator but that is such a drag on cpu and memory. I did find some good online tuts about React Native.

YES! I finally sorted out how to run a React Native app on the android studio emulator from the command line!!!

in first terminal tab:
* emulator -avd <name of emulator>

in second terminal tab:
* react-native run-android

Onwards towards tearing apart the sample app and building something really cool!!

As well, I did a warm up algo: take a number and reduce it by adding the digits together until you have only 1 digit:

```javascript
  // possible number by adding each digit in the number.
  // Hint: the returned number should be in the range of 0 - 9

  function oneDigitPlease(num) {
    var numArr;
    while (num > 9 ) {
      numArr = num.toString().split("").map(Number);
      num = reduceIt(numArr);
    } 
    return num;
  }

  function reduceIt(numArr) {
    while (numArr.length > 0) {
      return  numArr.reduce((accum, item) => {
        return accum + item;
      });
    }
  }

  oneDigitPlease(999);

```

## Day 3 ##
### January 3, 2018 ###

Began Salesforce.

Worked on my resume.

Note: work on Android Studio and ATC textbook -- I have the ATC exam soon!

Also: just complete the Scrum Master Exam already!

