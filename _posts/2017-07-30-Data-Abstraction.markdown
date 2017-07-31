---
layout: post
title: "Data Abstraction"
date:  2017-07-30 20:27:48 +0530
categories: First Blog
---

What's an Abstraction?

Abstraction is a technique for managing complexity of computer systems. So programmer implements abstraction by dividing the complex problems into sub-problems i.e creating fine line between between sub-problems which will be more easy to implement,less complex for the programmer to implement and help in making a system less prone to error.So due to abstraction a team can be more efficient and can solve more complex problems.It works by establishing a level of complexity on which a person interacts with the system, suppressing the more complex details below the current level.So if we write a code for adding  numbers we don't have to worry about  how numbers are represented and how addition is happening at lower level, so those details have been suppressed ,it can be said that they were abstracted away, leaving simply numbers and addition with which we can work upon.

Abstraction can be done in two ways :

1- Procedural Abstraction

2- Data Abstraction

We'll talk more about Data Abstraction- particularly why we do this,what will be the advantage of doing it.

So the first question which arise in our mind is why Data Abstraction - so basic mantra of abstraction is to create fine line between parts of problem to make system less complex to implement and to be more efficient. So for example if we have to represent rational number , we can simply have two integer one denoting numerator and another one denominator , now we have to add two rational numbers we can have a procedure add-rat which would implemented by two procedure (one producing numerator and another one producing denominator) ,but we have to explicitly keep track of which numerator corresponds to which denominator, so for the system intended to perform many operations on rational will become more complex , more prone to error and more unstable.So it would be much better if we are able to isolate the representation from  implementation and user see rational number as one enitity he doesn't have to worry about how it is represented , he only knows a procedure add with two arguments i.e add(a,b) but a and b could be anything from simple numbers to rational numbers so we have created a line between how data is represented and how it is being handle making easier for a programmer doing more complex operation on rational numbers.

So biggest advantage of such methodology is we have made the problem less complex and we could tackle complex problem at a faster pace.Data abstraction is a methodology that enables us to isolate how a compound data object is used from the details of how it is constructed from more primitive data objects.

So to summarise we understood why data abastraction is important and what will be the advatange of doing it in creating a less complex system.

We'll learn more about how data abstraction should be done in future blogs.