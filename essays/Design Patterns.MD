---
layout: essay
type: essay
title: Don't freak out, it's just a design pattern! 
# All dates must be YYYY-MM-DD format!
date: 2018-05-01
labels:
  - Software Engineering
  - HTML
  - CSS
  - design pattern
  - Singleton
  - Factory
---

<div class="ui segment centered large image">
  <img class="ui image" src="../images/DP.jpg ">
</div>

  Introduction
=================

When trying to wrap your head around design patterns for the coding world, it helps to take a virtual step back, and remove all thoughts of C, C++, Java, or [insert your favorite coding language here that for some reason is better than all the others because YOU use it] from your mind. The simplicity of the concept is in the words themselves. When you hear the words “design patterns” break the meaning of each word up separately, and then combine. The word “design” according to Webster’s Dictionary is: to create, fashion, execute, or construct according to plan. The word “patterns” according to Webster’s Dictionary is: a form or model proposed for imitation. 

Combining the meanings we get a construction of an idea that follows a model proposed for imitation. Continuing to keep coding out of our minds, we see this idea of design patterns applied in everyday life. Look at any major company within the world and look at their products design from year to year, for example, the Apple iPhone. You will understand the design patterns that are at work for every new model they roll out. Apple has a design that is similar from the years before, they follow an established pattern for their product because it is a model that works for their products for that year. Apple’s design patterns work for their recurring problems they face each year to roll out another product. Now, allow yourself to apply the design patterns definition to the coding world. If you have a recurring problem, you can design patterns that will be solutions to those very general problems, thus making your code more efficient and effective. It is important to note, design patterns are guidelines on how to attempt to solve your problems in general situation, not everything will take your design pattern and work.

  Two Basic Patterns and Some Personal Application
=================

1. Singleton

<div class="ui medium rounded images">
  <img class="ui image" src="../images/singleton.png ">
</div>

A real world example
>At any given time, there can only be one president of the United States, and that same president is required to be brought to action, whenever he is called.  

What going on
>Provide a “global variable” in an object-oriented language that does not support global variables, and/or provide complex global state.

>Ensures that only one object instance of a class is ever created.

Wikipedia states
>In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one object. This is useful when exactly one object is needed to coordinate actions across the system.

Personal Application
>Currently I am apart of a team designing an app that allows students to sigh up for tutoring sessions for classes they need help in. A problem arose where my team needed to ensure there was exactly one instance of our internal Tutors class. We used the design pattern singleton to solve this issue and make sure that one instance was accessible to our clients from a global access point. 

2. Model View Controller (MVC)

<div class="ui medium rounded images">
  <img class="ui image" src="../images/MVC.png ">
</div>

Real world example
>In a restaurant you never see just one employee take your order, go to the back and cook your food, arrange your food nicely on the plate, then come back out and serve you your food. In a restaurant there are specialties at each step of the process to ensure there is a system to the whole process. I encourage you to watch the <a href="https://youtu.be/f46WEeM8HTA">video link</a> provided so get a more detailed understanding on this real world MVC example. 

What going on
>When implementing a user interface, it is desirable to decouple the internal represintation of information from the way it is presented to and accepted from the user.

Wikipedia states
>Model–view–controller is commonly used for developing software that divides an application into three interconnected parts. This is done to separate internal representations of information from the ways information is presented to and accepted from the user.[1][2] The MVC design pattern decouples these major components allowing for efficient code reuse and parallel development. Traditionally used for desktop graphical user interfaces (GUIs), this architecture has become popular for designing web applications and even mobile, desktop and other clients.

Personal Application
>When my team first sat down and drafted up the bare bones of our app Study Hall, we did not know a whole lot about what we wanted and what we should have in our app. What we did know however was that we needed to implement a MVC design with whatever direction we took our Study Hall app. We knew that we needed to have a model database to store tutor, user, and class data/information. We knew we needed to have a basic view and layout of our app through HTML and CSS, or no one would be able to access our app. We also knew that we needed to have a controller to mediate and decide what the user would see; weather they were logged in as a tutor, user, or admin. Changing the view based on their login credentials.


