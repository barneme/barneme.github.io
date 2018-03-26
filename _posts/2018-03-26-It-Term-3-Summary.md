---
title: It Term 3 Summary
layout: post
author: barney.mepham
permalink: /it-term-3-summary/
source-id: 1rkhFg3uxC-G7JGkhgGMR5j0yFD8_YGp_XBLBOtdPm8U
published: true
---
IT Term 3 Summary

This term we have been working with python 3 on repl.it. We started off by using turtle to draw simple shapes such as squares and triangles and we changed the shape, speed and size of the turtle in the first lesson so that instead of appearing like a triangle it actually looked like a turtle.  In lesson 2 we were taught how to add colour and making a distance between the shapes using penup.

We used code such as this;

import turtle

turtle.shape("turtle")

turtle.speed(5)

turtle.color("magenta")

sides=7

length=92

for number in range(sides):

  turtle.forward(length)

  turtle.left(360/sides)

  

sides=4

length=90

for number in range(sides):

  turtle.forward(length)

  turtle.left(360/sides)

  

turtle.shape("turtle")

turtle.speed(5)

turtle.color("red")

turtle.penup()

turtle.forward(200)

turtle.pendown()

This code creates a turtle that makes a heptagon, a square and a triangle.

In lesson 3 we learnt how to make our initials by moving the turtle and rotating it to make letters.

In lesson 4 we started a new project which was a quiz. It was multiple choice or answering questions, for example you would be asked for your name and then it would say hello your_name, you could also make multiple choice questions saying, what do you like more, apples or pears and you would get an individual answer for each. Below is the code for the quiz that I made.

print("Please type in your name")

my_name = input ()

print("Nice to meet you " + my_name)

print("What is your favourite colour?")

my_colour = input ()

print("Interesting colour choice, " + my_name + " , " + my_colour)

if my_colour == ("Blue"):

 print("What an amazing colour, " + my_colour)

elif my_colour == ("Yellow"):

 print("What an awful colour," + my_colour)

elif my_colour == ("Turtle"): 

 print ("Correct answer")

else:

 print("That is a generic colour, personally I prefer turtles")

 

if my_colour == ("Turtle"):

 print ("Restart")

 

else:

 print ("What is your favourite food?")

 my_food = input ()

 print("Hmm " + my_food)

 

if my_food == ("Turtle"):

  print ("You disgust me")

  print ("Restart")

if my_food == ("Salmon"):

   print("Very healthy choice")

if my_food == ("Pizza"):

   print("My favourite, " + my_food)

else:

  print("Interesting choice, " + my_food)

