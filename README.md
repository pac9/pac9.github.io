# Background 
I've recently completed an intensive [full-time 19 week professional software development course](https://codeclan.com/courses/16-week-course/) at the digital skills and coding academy Codeclan in Edinburgh, UK. Course ended on 27th July 2018 after 3 weeks of pre-course work then 16 weeks in the classroom in Edinburgh. My class was collectively referred to as E21. 

More information on the course I completed can be found in the [syllabus.](https://pac9.github.io/codeclan_syllabus/)

# Main projects

I contributed to 65 projects during the course, all of which can be found on my [github account](https://github.com/pac9). 

This page is a summary of week long projects undertaken and the skills learnt.

## Stock inventory system - CRUD Web Application

[Project github file](https://github.com/pac9/sweet_shop) and [project brief](https://pac9.github.io/sweet_shop/) 

This project involved combining Ruby, PostgreSQL, Sinatra, HTML and CSS to create a stock inventory system. 

<img src ="https://pac9.github.io/SweetsLikeChocolate.png" alt="stock inventory page" height= "400">
 
This was a solo project built in Ruby using Sinatra and PostgresSQL to interact with the database. We were given one week to build this project with a presentation provided to the class at the end of the week. This project was undertaken in Week 5 for the course. 

During the making of the project I demonstrated that:
- the app had been built to fit the needs of the end user 
- the online app could read, updated, and delete items in the database
- the principle of OOP and clean code were being practised
- test driven development was being undertaken 
- regular git commits were being made

## Fruit Machine(Slot Machine) - Native application

[Project github file](https://github.com/pac9/FruitMachineJavaProject) and [project brief](https://pac9.github.io/FruitMachineJavaProject/)

This project involved writing code in Java to create a fruit machine(slot machine).
 
<img src ="https://pac9.github.io/FruitMachineHouseWins.png" alt="House always wins slot machine" height="500" width="400"> <img src ="https://pac9.github.io/FruitMachineSuckers.png" alt="Suckers slot machine" height="500" width="400">

This was a solo project built in Java and run in the IntelliJ IDE.

We were given one week to build this project with a presentation provided to the class at the end of the week. This project was undertaken in Week 9 of the course.

I created two games through utilising an abstract class for the fruit machine and utilising enums for the content of the wheels. A runner file was used to pull together the code and run the game.  

During the making of the project I demonstrated that:
- test driven development was being undertaken 
- regular git commits were being made
- SOLID principles where being adhered to where relevant (in this case the single responsibility principle, open/closed principle and Liskov substitution principle were in point)
- consider the 4 pillars of OOP (here abstraction and encapsulation were used, polymorphism and inheritance were not used)

## A full stack JavaScript web application

[Project file](https://github.com/pac9/Planet_Nine) and [project brief](https://pac9.github.io/Planet_Nine/)

This project involved vanilla Javascript, Express, MongoDB and interacting with APIs.

This was a week long group project undertaken in Week 14. At the end of the week we gave a presentation to which all students and staff at Codeclan were invited.

Although the brief indicated that the BBC should be considered as the user, the actual remit was less strict therefore we chose to create an educational app for use at a science festival or museum. Our vision was that our app would be shown on screens and tablets whereby the user would be drawn by visually stimulating images to explore and learn about our solar system and space through interacting with the app. 

Our app is designed to:
-	education you on the solar system, 
-	allows you to learn how the Hubble telescope is helping scientists understand how planets and galaxies form, 
-	be intriguing with the astronomy picture of the day, and 
-	provides insight into the location of and views from the international space station (ISS).

Solar system screen example
<img src="https://pac9.github.io/SolarSystemMercuryhome.png" alt="Mercury page on Solar System app">

ISS - screenshot of ISS tracker part of page
<img src="https://pac9.github.io/ISStracker.png" alt="Tracking the International Space Station">

ISS - screenshot of live video from ISS
<img src="https://pac9.github.io/viewfromiss.png" alt="View from International Space Station">

Hubble telescope picture exampke
<img src="https://pac9.github.io/hubblepage.png" alt="Image taken by Hubble telescope">

The solar system information and images are contained within a database seeds file which we created and ran using MongoDB. All code was written in Javascript and we used the pub/sub model for transmitting the data. 

The images from the Hubble telescope, the ISS tracker, and the astronomy picture of the day are all powered by NASA APIs.  The ISS tracker is render on a map using an open source library on [Leaflet.](https://leafletjs.com/)

During the making of the project we demonstrated that:
- we were using agile methodologies through daily stand ups, use of Trello board, regular communication on status of build
- we could utilise solo programming, paired programming and group programming as required by the task in hand
- with git we were regularly creating branches and later merging them 

## Final Project - open brief

[Project file](https://github.com/pac9/creative_coding)

For our final week we were permitted to do a coding project entirely of our choice. I chose go back to the reason I started to write code and that was to draw things. 

I created sketches(programs) which run in the [Processing](https://processing.org/) development environment with the code written in Java.

<img src="https://pac9.github.io/countdownclock.png" alt="Random colour circles" height="350" width="400">    <img src="https://pac9.github.io/randomcircles.jpg" alt="Random colour circles" height="350" width="400"> 

I wrote/adapted four sketches which showed:
- a starfield whereby over the course of the program the message written on the screen changed (ie started as E21, then     showed "The Final Frontier", then "boldly going .." etc)
- the fade in of the pixels of an image until the whole image was revealed 
- creating circles and using the framerate to give illusion of movement
- a take on the countdown clock

The aim was really just to have fun and bring together some of common data structures and algorithms used throughout the course such as arrays, loops, and conditionals.

At the end of the week a brief presentation was provided to the class before running the four sketches three of which had background music to add to the effect of the drawings. 
