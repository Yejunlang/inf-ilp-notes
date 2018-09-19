# ilp on [learn](http://course.inf.ed.ac.uk/ilp)
###### Informatics Large Practical 2018-2019

###### _Lecture 1: 2018-09-19_

Design and implementation projects.

Submitted only by `submit`, we have two pieces of coursework:

1. Set up a source code repo, write a short (five page) project plan. It documents design decisions and presents a plan for completing the work of the project by the deadline.
    - 25% out of 25 marks
    - 4pm, Fri 12th Oct
2. Longer 15 page coursework. Imlementation and write-up (..)
    - 75% out of 75 marks
    - 4pm, Fri 14th Dec

## The Task

Mobile phone game for Android, using Android Studio.

> **Coinz**: a collaborative location based game
>
> A prototype of a multiplayer collaborative location-based game to collect & exchange virtual coins, scattered at random
> around the University of Edinburgh's Central Area.
>

- Coins are specified on a map
- Coins are collected by visiting their location on the map (physically)
    - Within 25 metres (...)
- New maps released everyday
- Aim is to get the most coins
    
**Maps**:

- [Geo-JSON](https://geojson.io)

## Understanding exchange rates

Rates are relative to currency `GOLD`

## Banking and _spare change_

You can only bank up to 25 picked up coins a day. If you collect 40 coins one day, you can bank 25 and this leaves you with 15 
spare change.

You can send these to other people.
They can cash that into their bank (this isn't affected by the limit of cashing 25 picked-up coins).

## Banking?! Sending stuff? SERVERS??!!!

> Use Firebase

## Underspecification and bonus features

This occurs quite often. Be creative.

Add some other cool bonus features :)

## Programming Language

Kotlin or Java?? Your choice.

Lets do Kotlin:

- Learn X in Y where [X=kotlin](https://learnxinyminutes.com/docs/kotlin/)
- [Kotlin By Example](http://kotlinbyexample.org/)
