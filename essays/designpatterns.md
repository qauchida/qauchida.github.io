---
layout: essay
type: essay
title: Gotta Design Them All!
# All dates must be YYYY-MM-DD format!
date: 2019-04-27
labels:
  - Design Patterns
  - Java
---	

When I was young I was obsessed with Pokemon. No not the fancy augmented reality Pokemon that all the kids are playing today, I’m talking about the classic style role playing game. As a 90’s kid (barely I was born in 1996), I was raised on the original 150 Pokemon and I even stole my sister’s Gameboy color to play her Yellow version even though I couldn’t read. When I finally could read, (which I only learned how to do for the sake of playing Pokemon) I played Pokemon during my hour long morning commute to school everyday for 6 years. By the time I was in middle school the game’s illustrious hold on me weakend, but it soon came back when I took ICS 211 in college. 

At Kapiolani Community College, a miracle worker named Lisa Miller, teaches ICS 111, 141, 211, 212 and 241. For her ICS 111 and 211 classes, most of the assignments are based on Pokemon. At first I thought it was childish, but soon realized that the original Pokemon games are built upon a foundation of Object Oriented Programming. Later on in life, I learned about design patterns. I was racking my brain trying to recall if I have ever used these in my code before when it dawned on me that half of the semester in my ICS 211 class was spent programming using a Factory Method Design Pattern.

For a specific part of ICS 211, we were required to implement a class called “Pokemon”, where the specific pokemon (i.e. bulbasaur, ivysaur, etc.) would inherit that “Pokemon” class. We also had to make an interface, which were types (i.e. grass, poison, fire) and the Pokemon, based on those interfaces, were given a specific set of moves that only Pokemon of that type could do. Unfortunately, the code is really long so [click here to be taken to the Github repository containing all the Pokemon files](https://github.com/qauchida/s18-a3-pokemon-hierarchy-qauchida/tree/develop), which I have made public for the time being. I will have to take it down in the future (so that other students taking ICS 211 cannot see it and copy). What makes me believe that the Pokemon Inheritance project is an example of the Factory Design Pattern is that our super class, named Pokemon, was essentially our factory that made generic Pokemon objects, but those objects were made into specific pokemon based on their subclasses. I found the definitions at [this site](https://sourcemaking.com/design_patterns/creational_patterns) were the most helpful in understanding design patterns. 


