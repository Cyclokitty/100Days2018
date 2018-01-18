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

## Day 4 ##
### January 4, 2018 ###

Prepping for an internship interview. Nervous as heck. But I do have a nicely ironed shirt for the occasion.

More Salesforce class. So far, it's straight forward. We dabbled in creating custom fields. It's a double course: admin and developer.

More Scrum Master exam studying.

Good news! I have another interview scheduled for next week for mob dev!

Finally, worked on React Native. Decided to concentrate on getting from one page to another. Did some mild styling. It looks alright but more importantly it works!

## Day 5 ##
### January 5, 2018 ###

More Salesforce. We now have a pdf text book chock full of info. Even homework.

Had a very internship placement interview. They sent me a quick React Native assignment -- send a photo to an api. Looks fun!

## Day 6 ##
### January 6, 2018 ###

Worked on the RN assignment. Need to remember:

```

source $HOME/.bash_profile
```

Before setting up the android emulator on a new project.
Also, make sure the emulator is up and ready before running it.

And I set a background image. yay me!

Tomorrow I'll work on the button and the post and fetch to send the image to a server.

## Day 7 ##
### January 7, 2018 ###

Practicing android for the ATC exam.

Fiddled some more with the image posting project.

Really don't like the ATC book. They need an editor on staff for all of the ridiculous errors. Worked on chapter 8 -- async. The lab is coding a fortune telling app.

## Day 8 ##
### January 8, 2018 ###

Finished the project and it works! Sent it in for a look over.

Next, need to complete the Scrum exam.

Ok, have to do some more work on the project. Display the images from the returned json. Had a momentary brain bubble when I had difficulty reaching into the json. But I go it!

Will display the images tomorrow.

## Day 9 ##
### January 9, 2018 ###

Ok, still need to display the images. Had a long, busy day.

And still need to do the Scrum exam. See above. Will wake up at 5am to complete it *pinky swear*.

The job interview went well and I was given an assignment to complete by Monday. It's for android dev so sending a string and info about the sender phone to a recipient phone by ble.

Only 3 days until Grad!! Hooray!

## Day 10 ##
### January 10, 2018 ###

Some more Salesforce.

An interesting speaker in class who discussed effective communication. Active listening. Thinking before you speak. Lots of interesting techniques to build on as time rolls.

Worked some more on my image getter. Still need to display the images but now the View is better set up to do that.

## Day 11 ##
### January 11, 2018 ###

FIRST DAY AS AN INTERN!!

Spent some time setting up my laptop. I still need to do a clean install and then I'll finally have xcode.

## Day 12 ##
### January 12, 2018 ###

GRAD DAY!!

And started a clean install on my laptop. Oi, what a long process that was! The high sierra OS bootable version took most of the evening downloading and processing.

## Day 13 ##
### January 13, 2018 ###

Spent all day setting up Android Studio, java, Xcode. And reinstalling Atom, iTerm2, oh-my-zsh and a dozen different things. Only to seriously mess it all up when I realized my name was spelled incorrectly. I changed it and .... had to start all over again.

*SIGH*

At least the redo wasn't mysterious or complicated. Just another few hours of clean install and re-downloading Android Studio. That thing is huge! But the emulator works from the cli and I finally have Xcode.

## Day 14 ##
### January 14, 2018 ##

Finally, my laptop is fresh as the mountain dew. Even a couple of hours ago, I was still loading components (I'm looking at you, Xcode).

Tried out some React Native tutorials. I'm enjoying the Stephen Grider React Native and Redux course.

## Day 15 ##
### January 15, 2018 ##

First full day as an intern!

Ugh. All the configuring.

## Day 16 ##
### January 16, 2018 ##

More configuring...

## Day 17 ##
### January 17, 2018 ##

Some more configuring...


## Day 18 ##
### January 18, 2018 ##

And turns out we were on the wrong branch. *Sigh*

Back to the start.

Configuring...
